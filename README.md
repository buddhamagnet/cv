# DAVID GOODCHILD

## IN A NUTSHELL
![aws-certified-cloud-practitioner](https://github.com/buddhamagnet/cv/assets/35007/2044b400-c7d2-412a-af1b-2b6b4477cbcf) ![aws-certified-solutions-architect-associate](https://github.com/buddhamagnet/cv/assets/35007/bf92b67e-947e-43c9-ad62-6f5c4d086a47) ![aws-certified-developer-associate](https://github.com/buddhamagnet/cv/assets/35007/8ea4e60e-814d-4a62-871f-400a6a55f5ec) ![aws-certified-sysops-administrator-associate](https://github.com/buddhamagnet/cv/assets/35007/04ecd180-b2f9-4551-9609-836e2668ff2f) ![aws-certified-machine-learning-engineer-associate](https://github.com/user-attachments/assets/dc3e2c27-c229-4b31-a9be-1f9f9d977cb0)

I am a full stack engineer and architect with over 20 years of experience working for all manner of organisations, from working as a single freelancer, through a number of startups and consultancies, to large companies including [Sun Microsystems](http://sun.com) and [The Economist](http://economist.com). I am passionate about open source and past contributions can be found below the employment history below. As I started my career in the 90s I have a solid foundation in all the things we used to do by hand (SQL, server admin, C, perl, you know the score).

## MINDSET

I believe mindset trumps technology and have a passionate interest in collaboration, mentoring, upskilling and communication. I think shipped and working software is better than perfect software and am fully possessed of a devops mindset, encouraging ownership of all aspects of the development lifecycle. I have also worked across multiple teams in my time, picking up invaluable skills in cross-functional working, cross-team communication, dependency identification, cutting through static, unblocking team memmbers and data analysis.

## SKILLSET

- **Cloud**: Fully conversant with AWS and GCP, making heavy use of many services as detailed below and pushing the envelope in many cases. Also possessed of a devops mindset, instrumental in building CICD flows for teams and pushing ownership of the full software development lifeycle to engineers. Recent projects involved use of [Terraform](https://www.terraform.io/) as a replacement for Cloudformation as well as migrating older projects to CDK. AWS services used in anger across multiple projects include API Gateway, Step Functions, Athena, CloudFormation, CloudFront, CloudTrail, CloudWatch, Cognito, CodeBuild, CodePipeline, DynamoDB, EC2, ECS, ECR, EFS, Elasticache, Elastic Beanstalk, Event Bridge, Elasticsearch, ELB, Glue (building ETL pipelines), IAM, KMS, Lambda, RDS (Aurora/Postgres), Route 53, S3, SAM, Secrets Manager, SNS (including message filtering), VPC asssembly and X-Ray. GCP services used include BigQuery, Cloud Storage, Spanner, Cloud SQL, GKE, GCE, Stackdriver and PubSub.
- **JavaScript**: fully proficient in ES6. Technologies used include [Typescript](https://www.typescriptlang.org), [React](https://reactjs.org/), [Redux](http://redux.js.org/), [Node](https://nodejs.org/en/), [Vue](https://vuejs.org/), [GraphQL](http://graphql.org/) and the [Apollo platform](https://www.apollographql.com/) and building AWS Lambda functions for event-driven systems. Prefer to code in a functional style.
- **Go**: early adopter long before Go modules and generics landed, main project involved building out an event-driven distributed content platform at The Economist. Instrumental in bringing the language to the organization, securing training with [Bill Kennedy](https://www.linkedin.com/in/william-kennedy-5b318778/) and mentoring new hires. Outside The Economist, contributed to numerous Go OSS projects and open sourced some libraries we built in house. Also work closely with [Todd McLeod](https://www.udemy.com/course/learn-how-to-code/#instructor-1), who created the best-selling Go courses on Udemy, on his [social education platform](https://greatercommons.com/). Bill was kind enough to say this about me:
  > "In the early days when I was learning and teaching Go, I had the pleasure of meeting Dave. Dave was writing Go and introducing it into his projects as an early adopter. Dave was there to help me as well since he had experience I didn't have yet. If you are looking for a top notch engineer with the ability to lead/manage teams and projects, Dave is someone you need to consider."
- Example OSS contributions to Go projects: [bluemonday](https://github.com/microcosm-cc/bluemonday/commits?author=buddhamagnet), [Docker](https://github.com/docker/docker/commit/6fd8e485c85c4f8ca62578d0840bdeddc4cba151), [caddy](https://github.com/caddyserver/caddy/commits?author=buddhamagnet) and [godep](https://github.com/tools/godep/commits?author=buddhamagnet). Example of a core library built by myself for the first iteration of the platform and open sourced by The Economist - [ramlapi](https://github.com/EconomistDigitalSolutions/ramlapi).
- **Python**: fully conversant with Python 3, mainly from supporting a fleet of Lambdas at The Economist and through interaction with the data science team.
- **Ruby**: not so much these days, but was a passionate Rubyist in the 2000s. Have worked with both pure Ruby and Rails, including contributions to the [Rails framework itself](http://contributors.rubyonrails.org/contributors/dave-goodchild/commits) and substantial [commits](https://github.com/splitrb/split/commits?author=buddhamagnet) to the A/B testing library Split.
- **Back end**: extensive work on the back end using a large set of technologies inluding Varnish, [Openresty](https://openresty.org/en/) (including Lua), [Elasticsearch](https://www.elastic.co/), [Docker](https://www.docker.com/) to name a few. Pushed the envelope with many (writing test suites for Varnish using [varnishtest](https://varnish-cache.org/docs/trunk/reference/varnishtest.html), zero downtime deployments with Elasticsearch, using Lua to compose incoming requests into Elasticsearch filter searches via POST). Also SQL fluent.
- **Logging and metrics**: Extensive use of a slew of technologies to gain maximum visibilty into applications, including [New Relic](https://newrelic.com/), [Datadog](https://www.datadoghq.com/), [Logz.io](https://logz.io), CloudWatch, AWS X-Ray, Kibana, [Grafana](https://grafana.com/) and [Prometheus](https://prometheus.io/).

I am also deep into [Elixir](https://elixir-lang.org/) and [Clojure](https://clojure.org/) right now as a big fan of functional programming.

## MOST RECENT PROJECTS

### JUN 2022 - PRESENT: CONSULTANT TECH LEAD - THE ECONOMIST

Switched to team spun up to decommission the legacy content sources, APIs and cloud resources, alongside assisting in the build of a new content platform.

Main initiatives included:

* Creating and executing a migration plan for moving old content into the new Content Platform (Lambda, Apollo GraphQL).
* Working with the Editorial Tools team to build new features to allow publication of older content sources from the new CMS (CUE) to the old and new Content Platforms.
* Building out the new Economist podcast experience (easy wins in CP1, extra functionality built out in CP2).
* Building out the new Economist homepage.

Work also involved cross-team collaboration in building out the new Content Platform (Apollo/Prisma, Lambda, Postgres, Cloudflare Workers) including schema stitching to use both the new and old Content Platforms at the GraphQL level as we deprecated functionality and building end to end migration plan and execution of same to get all old content (stored in Drupal and surfaced in old Content Platform) into the new API and data store (migration workers listening to SNS containing content reprocessing events, assembling old content into the new structure and pushing to the new GraphQL mutations) and working with BA to target appropriate content slices using a phased approach.

Technologies used: TypeScript, Node, GraphQL (Apollo toolchain), AWS (Lambda, SNS, SQS, AWS CDK, API Gateway, Step Functions, CloudWatch Events), Drupal, CUE.

### OCT 2021 - JUN 2022: CONSULTANT ENGINEER - THE ECONOMIST

Worked on the Economist editorial tools team (team assembled to switch from Drupal as a content source to [CUE](http://docs.escenic.com/cue-user-guide/3.3/introduction.html)) in order to help the team move the weekly edition publishing flow from the older source systems. Instrumental in helping the team achieve their target on time and under budget. First weekly edition was published from CUE with zero errors.

Technologies used: TypeScript, Node, AWS (Lambda, SNS, SQS, AWS CDK, Step Functions, CloudWatch Events).

### JAN 2021 - OCT 2021: CONSULTANT ENGINEER - THE ECONOMIST

Back at The Economist again, this time on a contract to build out a syndication platform to consolidate and centralise various approaches adopted in-house to syndicate content to a range of internal, retail, wholesale and aggregation clients.

Techologies used: TypeScript with heavy functional flavour (mainly [Ramda](https://ramdajs.com/)), AWS (Lambda, SNS, SQS, AWS CDK, Step Functions, CloudWatch Events).

### OCT 2020 - JAN 2021: CONSULTANT ENGINEER - LUSH

Working as a back end engineer across a variety of products and teams. Remit included consolidating and documenting the microservice estate, hiring new engineers, building and maintaining services, acting as a conduit between back end and front end teams, collaborating as devops building CICD pipelines (ArgoCD, K8S) and working on cloud back end (GCP) with services written in Go, Python and Node. Used a variety of build and dev tools including [Mage](https://magefile.org), [Tusk](https://github.com/rliebz/tusk), [SOPS](https://github.com/mozilla/sops). GCP technologies used: BigQuery, Spanner, PubSub, Cloud Storage, Cloud SQL, Kubernetes, GCE.

### MAR 2020 - SEP 2020: CONSULTANT ENGINEER - DIRECT LINE

Worked as a consultant for Direct Line on a pioneer cloud team building a real time fraud detection engine. Worked on all parts of the stack, from the React front end to the back end composed of a set of Node Lambdas and associated AWS infrastructure. Advised and worked on all aspects of the project and team to hit several tight and budget-sensitive deadlines in a high governance environment (code review process, rebuilding and streamlining CICD, infrastructure as code). Main components included:

* Assisting on build of the in house real-time fraud detection system and building a router to forward requests to both in-house and third party decision engines. Technologies involved Docker, Node (sample packages used included commander, jest, husky, lerna, pg, pg-essential, webpack, aws-sdk, axios, lodash and xml2js) and AWS (AWS SAM, API Gateway, Cloudformation, CodeBuild, CodePipeline, DynamoDB, Lambda, S3, SQS, X-Ray).
* Single-handedly building a prioritization service designed to allow claim handlers to pull a claim to work on based on a set of nuanced criteria. Service was invoked on a regular schedule via AWS CloudWatch Event Rules. Technologies involved Node (primary package used was lodash for list processing and composition) and React (front end integration including wiring into Redux). Back end was Postgres (AWS Aurora).
* Single-handedly building a GraphQL layer to interface the front end with relational data contained in a Postgres database. Technologies used included Docker, Node (apollo-server, apollo-server-express, dataloader, dotenv, express, graphql, graphql-tools, pg, pg-format, sequelize) and AWS (Aurora).
* Building an ETL pipeline to process and transform large quantities of claim data in batch for storage in a relational database. Service was invoked by S3 event triggers on CSV upload. Technologies involved Node, Python, Apache Spark and AWS (Athena, Cloudformation, CloudWatch, CodeBuild, CodePipeline, S3 and Glue).

### OCT 2019 - FEB 2020: TECHNICAL LEAD, CONTENT PLATFORM, THE ECONOMIST 

Worked on the Content Platform as technical lead for a team of 8 distributed engineers (UK, New York and Slovakia), building on the foundational work completed in a previous project (detailed below) and migrating the initial fleet of worker services from Elastic Beanstalk worker environments to AWS Lambda and serverless. Worked on the entire stack, including the above mentioned workers (Go), a subset of workers written in ES6 JavaScript, the GraphQL layer that sat in front of the fleet, a gateway layer which comprised Nginx (Openresty), Varnish and Lua, and an Elasticsearch back end, including working out a way to re-index with zero downtime. Technologies used: Docker, Node, Varnish, Nginx, Lua, Elasticsearch, AWS (AWS SAM, Cloudformation, Cloudwatch, CodeBuild, CodePipeline, Elasticache, S3 SNS and SQS).

> "It is my pleasure to write a recommendation for Dave Goodchild whom I have had the fortune of working with at The Economist since I joined end of February 2015 as platform architect for the content and the data management platforms. Dave Goodchild was a senior engineer on the project to revamp the content platform into a micro-service based, message driven, reactive system. He played a key role to enable us to deliver the modernization of the core content stack of The Economist on time and on budget. It is rare to come across a standout talent like Dave Goodchild who is an amazing Golang developer and any other programming language he is asked to use, regardless if it is php, javascript, clojure or configuring nginx or varnish. He is able to quickly capture the entire end-to-end picture of a problem or a feature, devise a technical solution in record time, then implement & maintain it. His deep understanding of functional reactive programming concepts enabled to build up the new containerized system based on Docker with the back-end micro-services written in Golang and front-end based on GraphQL and ReactJS running completely optimized for Amazon Web Services (AWS), driven fully by a Continuous Delivery (CD) pipeline. It's a pity that he decided to leave after contracting about four years for The Economist. At least I've learnt a great deal working with him and I'm happy that he remains as a very good personal friend who I can deeply recommend as a colleague."

[Artur Ortega](https://www.linkedin.com/in/arturortega/?originalSubdomain=uk), Platform Architect, The Economist (previously Telegraph and Yahoo).

> "Dave is a level headed very highly skilled engineer. He has an uncanny ability to break down even the most complex task and simplify it to the point that everybody on the team can contribute. He cuts through the noise and encourages everybody to see the core value proposition. He takes ownership of any task given to him or tangential to him and ensures it gets done to the highest quality. It doesn't matter if it's greenfield or legacy, unfamiliar tech or a well trodden road; Dave will roll up his sleeves and get it done. He has deep knowledge of Golang and high scale AWS cloud architectures. He's a true polyglot engineer and will cut code in the appropriate tech to get the job done."

[Juhjar Singh](https://www.linkedin.com/in/jujhar/), Devops Practice Lead, The Economist.

### MAY 2017 - OCT 2019: PLATFORM ENGINEER, THE ECONOMIST

Built out several iterations of a distributed content platform at The Economist. Involved in all aspects of the project:

* Built a set of microservices in [Go](http://golang.org), including building the microservice template, mentoring team members in Go and building key components, some of which are now open source.
* Worked alongside the web products team to deliver the front end (using [Node](https://nodejs.org/en/) and [GraphQL](http://graphql.org/)).
* Worked as a devops resource on an API gateway and caching architecture, using a suite of tools including [Salt](http://saltstack.com), [Nginx](https://www.nginx.com), [Openresty](https://openresty.org/en/), and [Varnish](https://www.varnish-software.com). Initial gateway code was managed via Salt then ported to Docker.
* Worked with a variety of AWS tools in a devops capacity, including S3, SNS, Lambda, CloudFormation, SQS, Elastic Beanstalk, EC2, EC2 Container Service and VPC.
* Built a development environment using Docker Compose which integrated all services and the API gateway locally. Later work also involved a fair amount of [Lua](https://www.lua.org/) to turn the gateway into a true powerhouse.
* Assisted with implementing a continuous delivery pipeline with [Docker](https://www.docker.com/) and [Amazon ECS](https://aws.amazon.com/ecs/details/), initially using [GoCD](https://www.go.cd/) for the pipeline and transitioning to [AWS Code Pipeline](https://aws.amazon.com/codepipeline/).
* Assisted with ensuring the whole stack was fully tested using Go's built-in testing package and developing a set of contract and integration tests.
* Helped to build the service discovery layer, initially with [Consul](https://www.consul.io/) and transitioning to dynamic back ends in Nginx routing to AWS ELBs.
* Built Drupal modules for the back end to deliver content from the CMS to API consumers. Later iterations leveraged S3 events and SNS to trigger downstream Go workers which transformed and stored raw content in the appropriate format (modified JSON for API consumers, Apple News format for the Apple News service, and later all content consolidated in a canonical data model influenced by [schema.org](http://schema.org)).
* In later stages of the project, worked on mechanisms to ensure content could still be served even if all the services and Drupal back end went down using Varnish write behind cache and storage of responses and content on S3.

### JAN 2017 - MAY 2017: CONSULTANT ENGINEER, PEAK BI

Hired by the cloud computing consultancy that worked with The Economist on providing AWS services and training to build a data product using [React](https://facebook.github.io/react/) and [Redux](http://redux.js.org/) on the front end and [Serverless](https://www.serverless.com/) and AWS on the back. The system provideD a dynamic UI on top of Peak's data management offering allowing clients to log in and navigate a series of data-driven dashboards.

### JUL 2012 - DEC 2016: CONSULTANT ENGINEER, THE ECONOMIST

Initially hired as a Drupal developer, I had the good fortune to establish a great working relationship with The Economist and work on a number of digital transormation projects from inception to delivery, including: 

* Instrumental in assisting in the migration of The Economist stack onto AWS. Touched all parts of the migration process, from consulting on migrating our services and packing configurations into Salt, adjusting the deployment process to cater for auto-scaling, normalising HTTP headers across the whole stack through Incapsula, through the Amazon ELBs, Varnish, web servers and applications.
* Providing support for a Rails application owned by [Digital News Agency](digitalnewsagency.com) (part of the Economist Group), including advising on upgrading from Rails 2.3.8 to 3 and then 3.1, building a robust test harness around the application and supporting ongoing development. Also involved in building a set of tools in Ruby for use by the ops team.
* Heavily involved in an ongoing project to bring Javascript development at The Economist into the 21st century (toolset involved: Bower, Grunt, Yeoman, Jasmine, Qunit, Node and Express).
* Sole developer on a project to integrate subscription and reconciliation services into Google Play, built using a back end composed of Symfony components and exposing a JSON API. Involved working closely with the team of Java developers tasked with working on the Economist Android app.
* Helped to deliver service-oriented architecture for The Economist, which was
essentially a monolithic Drupal codebase. Work covered all aspects of this mammoth undertaking, from building of initial feature lists for potential vendors and working closely with all stakeholders to ensure the project was delivered with minimal risk and disruption. The system was broken down into several discrete components which could fail without bringing the rest of the system down and potentially be swapped out for other components if necessary. The in-house built components involved a large range of technologies - a data store, a series of user-facing components (for example a Manage My Account system which was built using a range of cutting-edge front end technologies including Yeoman, Jasmine, PhantomJs, Grunt and Angular) and a set of carefully designed APIs.
* Instrumental in delivering a project whose main remit was to ensure the site could handle the extra load that will be generated by the uptake in registrations and subscriptions generated by the new paywall. Heavy stuff, working on one stream to utilise Varnish to allow us to cache pages for authenticated users in parallel with a second stream to build the system that returned user data via JSON
to correctly populate the dynamic and user-specific subsystems (user navigation, analytics and ads). Involved close collaboration with ops to ensure the correct architectural decisions were made (and building tools to speed up the process, such as this [memcache client](https://github.com/buddhamagnet/memquery) I wrote to make querying the cache for user sessions easier).
* Worked on the first part of the Economist mobile project - driving the mobile wallpage implementation as well as working on some high profile mobile entry points (login and registration pages) as well as a larger initiative to start placing more diverse Economist content behind the paywall.
* Completed a project to decouple the Economist paywall from Drupal and help move The Economist towards a service-oriented archiecture. This project was pure JavaScript (with an admixture of Jquery and Underscore), tested using Jasmine and Phantom. The application also utilised local storage to store pre-compiled paywall templates.

### OCT 2011 - OCT 2012: CONSULTANT ENGINEER, [UNBOUND](http://unbound.co.uk)

Freelanced for a UK-based startup (Rails 3 platform) created by the QI research team. Unbound provides a crowd-funded publishing platform for writers, both published and unknown, and has garnered an impressive amount of press:

- [TechCrunch](http://techcrunch.com/2011/05/29/unbound-launches-its-kickstarter-byliner-hybrid-for-celebrity-authors/)
- [Mashable](http://mashable.com/2011/06/01/unbound/)
- [Wired](http://www.wired.co.uk/news/archive/2011-05/29/unbound-publishing-platform)
- [Telegraph](http://www.telegraph.co.uk/culture/hay-festival/8543961/Hay-Festival-2011-New-site-Unbound-gives-readers-the-power-of-publishing.html)

Roles previous to 2011 can be seen on my [LinkedIn profile](https://www.linkedin.com/in/dgoodchild/).

## OPEN SOURCE CONTRIBUTIONS

### DOCKER

* [docker - code](https://github.com/docker/docker/commit/6fd8e485c85c4f8ca62578d0840bdeddc4cba151)
* [docker - documentation](https://github.com/docker/docker/commit/5be5749d544702c5da37c8ab448b417daf13e297)

### GO

* [bluemonday](https://github.com/microcosm-cc/bluemonday/commits?author=buddhamagnet)
* [silk](https://github.com/matryer/silk/pull/19)
* [gizmo (New York Times)](https://github.com/NYTimes/gizmo/commits?author=buddhamagnet)
* [godep](https://github.com/tools/godep/commits?author=buddhamagnet)
* [migrate](https://github.com/mattes/migrate/commits?author=buddhamagnet)
* [gobundle](https://github.com/alecthomas/gobundle/graphs/contributors)
* [consul](https://github.com/hashicorp/consul/commit/c34bcb45c670af076846826ea72c436fbd0e2c35)
* [godotenv](https://github.com/joho/godotenv/commit/443e926da0d793d3b3f32118b1e4ba52ada26503)
* [gods](https://github.com/emirpasic/gods/commit/4257bbbae30da5ae4fa1621734efb9ddd02d7fa4)

### JS

* [ghost - js blogging engine](https://github.com/TryGhost/Ghost/commits?author=buddhamagnet)

### RUBY

* [ruby](https://github.com/ruby/ruby/commit/71b6077a5354335f5f04b7e852a22b3290b9f528)
* [ruby](https://github.com/ruby/ruby/commit/5f55e23f9c2feb774aaffde8c9e20213c7b97497)
* [rails](http://contributors.rubyonrails.org/contributors/dave-goodchild/commits)
* [rails api](https://github.com/rails-api/rails-api/pull/145#issuecomment-52991509)
* [regularity - rb regex library](https://github.com/andrewberls/regularity/pull/2)
* [draper - rb presenter library](https://github.com/drapergem/draper/commits?author=buddhamagnet)
* [discourse - rails and ember forum](https://github.com/discourse/discourse)
* [jumpstartlabs](https://github.com/JumpstartLab/curriculum/commit/2f6a26e4f62b9cd12e51d6d68758777d87f3af3d)
* [railsgirls](https://github.com/railsgirlslondon/railsgirls-london/contributors)
* [quartz (ruby-go interface gem)](https://github.com/DavidHuie/quartz/graphs/contributors)
* [refinery CMS](https://github.com/refinery/refinerycms/pull/2649)
contributors)
* [adn-cli(command line client for same)](https://github.com/adn-rb/adn-cli/graphs/contributors)
* [split (ab testing gem)](https://github.com/andrew/split/graphs/contributors)
* [resque - rb redis-backed queue](https://github.com/defunkt/resque/graphs/contributors)
* [adn (API wrapper for app.net)](https://github.com/adn-rb/adn/graphs/
* [diaspora - decentralized social software](https://github.com/diaspora/diaspora/commits?author=buddhamagnet)
* [rstat.us - decentralizised social software](https://github.com/hotsh/rstat.us/graphs/contributors)

### VARNISH

- [varnish cache](https://github.com/varnishcache/varnish-cache/commits?author=buddhamagnet)

## COMMUNITY AND EDUCATION

I'm a big believer in sharing the love and have delivered training sessions at The Economist and Direct Line and am currently helping with the build and maintenance of [Greater Commons](https://greatercommons.com/), a course platform for developers. I am also working with Todd McLeod to build some Udemy courses on Go, and was intrumental in bringing Bill Kennedy in for training sessions. [Here's an example](https://www.youtube.com/watch?v=HdMmLQB8ZWE) of a session on Varnish testing I delivered for The Economist.

I was one of the original creators of [rubyinthepub](http://www.joannageary.com/2010/05/13/ruby-in-the-pub-3/), a meet-up designed to put developers, journalists and writers in the same room to explore their common space and collaborate on projects. This small event has since transformed into the UK arm of [Hackshackers](http://meetuplondon.hackshackers.com/), an event originally
kicked off by the New York Times.
