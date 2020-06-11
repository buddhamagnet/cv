import sys
from awsglue.transforms import *
from awsglue.utils import getResolvedOptions
from pyspark.context import SparkContext
from awsglue.context import GlueContext
from awsglue.job import Job

## @params: [JOB_NAME]
args = getResolvedOptions(sys.argv, ['JOB_NAME'])

sc = SparkContext()
glueContext = GlueContext(sc)
spark = glueContext.spark_session
job = Job(glueContext)
job.init(args['JOB_NAME'], args)
## @type: DataSource
## @args: [database = "claims", table_name = "claims_csv", transformation_ctx = "datasource0"]
## @return: datasource0
## @inputs: []
datasource0 = glueContext.create_dynamic_frame.from_catalog(database = "claims", table_name = "claims_csv", transformation_ctx = "datasource0")
## @type: ApplyMapping
## @args: [mapping = [("claimid", "double", "claimid", "double"), ("claimnumber", "long", "claimnumber", "long"), ("policyid", "double", "policyid", "double"), ("dateofloss", "string", "dateofloss", "string"), ("timeofloss", "string", "timeofloss", "string"), ("datereported", "string", "datereported", "string"), ("closedate", "string", "closedate", "string"), ("losslocationid", "double", "losslocationid", "double"), ("currentcircumstances", "string", "currentcircumstances", "string"), ("liabilitydenialcomments", "string", "liabilitydenialcomments", "string"), ("fnolcircumstances", "string", "fnolcircumstances", "string"), ("losstypedesc", "string", "losstypedesc", "string"), ("losscausedesc", "string", "losscausedesc", "string"), ("statedesc", "string", "statedesc", "string"), ("faultratingdesc", "string", "faultratingdesc", "string"), ("howreporteddesc", "string", "howreporteddesc", "string"), ("reportedbydesc", "string", "reportedbydesc", "string")], transformation_ctx = "applymapping1"]
## @return: applymapping1
## @inputs: [frame = datasource0]
applymapping1 = ApplyMapping.apply(frame = datasource0, mappings = [("claimid", "double", "claimid", "double"), ("claimnumber", "long", "claimnumber", "long"), ("policyid", "double", "policyid", "double"), ("dateofloss", "string", "dateofloss", "string"), ("timeofloss", "string", "timeofloss", "string"), ("datereported", "string", "datereported", "string"), ("closedate", "string", "closedate", "string"), ("losslocationid", "double", "losslocationid", "double"), ("currentcircumstances", "string", "currentcircumstances", "string"), ("liabilitydenialcomments", "string", "liabilitydenialcomments", "string"), ("fnolcircumstances", "string", "fnolcircumstances", "string"), ("losstypedesc", "string", "losstypedesc", "string"), ("losscausedesc", "string", "losscausedesc", "string"), ("statedesc", "string", "statedesc", "string"), ("faultratingdesc", "string", "faultratingdesc", "string"), ("howreporteddesc", "string", "howreporteddesc", "string"), ("reportedbydesc", "string", "reportedbydesc", "string")], transformation_ctx = "applymapping1")
## @type: ResolveChoice
## @args: [choice = "make_cols", transformation_ctx = "resolvechoice2"]
## @return: resolvechoice2
## @inputs: [frame = applymapping1]
resolvechoice2 = ResolveChoice.apply(frame = applymapping1, choice = "make_cols", transformation_ctx = "resolvechoice2")
## @type: DropNullFields
## @args: [transformation_ctx = "dropnullfields3"]
## @return: dropnullfields3
## @inputs: [frame = resolvechoice2]
dropnullfields3 = DropNullFields.apply(frame = resolvechoice2, transformation_ctx = "dropnullfields3")
## @type: DataSink
## @args: [catalog_connection = "claims", connection_options = {"dbtable": "claims_csv", "database": "deop"}, transformation_ctx = "datasink4"]
## @return: datasink4
## @inputs: [frame = dropnullfields3]
datasink4 = glueContext.write_dynamic_frame.from_jdbc_conf(frame = dropnullfields3, catalog_connection = "claims", connection_options = {"dbtable": "claims_csv", "database": "claims"}, transformation_ctx = "datasink4")
job.commit()