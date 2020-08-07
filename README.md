# DAVID GOODCHILD

## IN A NUTSHELL

I am a developer with 20 years of experience working for all
manner of organisations, from working as a single freelancer, through a number
of startups and consultancies, to large companies including [Sun Microsystems](http://sun.com) and [The Economist](http://economist.com).

## SKILLSET

- **JavaScript**: fully proficient in ES6 and have both worked directly on the Economist front end team and providing support from the Content Platform. Current project at Direct Line is almost all JS, front and back. Technologies include [React](https://reactjs.org/), [Redux](http://redux.js.org/) and [Vue](https://vuejs.org/), as well as working with [GraphQL](http://graphql.org/) and the [Apollo platform](https://www.apollographql.com/) and building AWS Lambda functions for event-driven systems.
- **Go**: working with Go for nearly 3 years now, building out an event-driven distributed content platform at The Economist. Instrumental in bringing the language to the organization, securing training with [Bill Kennedy](https://www.linkedin.com/in/william-kennedy-5b318778/) and mentoring new hires. Outside The Economist, contributed to numerous Go OSS projects and open sourced some libraries we built in house. Also work closely with [Todd McLeod](https://www.udemy.com/course/learn-how-to-code/#instructor-1), who created the best-selling Go courses on Udemy, on his [social education platform](https://greatercommons.com/). Bill was kind enough to say this about me:
  > "In the early days when I was learning and teaching Go, I had the pleasure of meeting Dave. Dave was writing Go and introducing it into his projects as an early adopter. Dave was there to help me as well since he had experience I didn't have yet. If you are looking for a top notch engineer with the ability to lead/manage teams and projects, Dave is someone you need to consider."
- Example OSS contributions to Go projects: [bluemonday](https://github.com/microcosm-cc/bluemonday/commits?author=buddhamagnet), [Docker](https://github.com/docker/docker/commit/6fd8e485c85c4f8ca62578d0840bdeddc4cba151), [caddy](https://github.com/caddyserver/caddy/commits?author=buddhamagnet) and [godep](https://github.com/tools/godep/commits?author=buddhamagnet). Example of libraries built by myself and open sourced from The Economist - [cloudcheck](https://github.com/EconomistDigitalSolutions/cloudcheck) and [ramlapi](https://github.com/EconomistDigitalSolutions/ramlapi).
- **Python**: conversant with Python 3, which is used for a fleet of Lambda functions at The Economist.
- **Ruby**: a passionate Rubyist, have worked with pure Ruby and Rails, including contributions to the [Rails framework itself](http://contributors.rubyonrails.org/contributors/dave-goodchild/commits). Involved in the maintenance and development of a set of Rails applications used internally at The Economist.
- **Back end**: extensive work on the back end using a large set of technologies inluding Varnish, [Openresty](https://openresty.org/en/) (including Lua), [Elasticsearch](https://www.elastic.co/), [Docker](https://www.docker.com/) to name a few. Pushed the envelope with many (writing test suites for Varnish using [varnishtest](https://varnish-cache.org/docs/trunk/reference/varnishtest.html), zero downtime deployments with Elasticsearch, using Lua to compose incoming requests into Elasticsearch filter searches via POST.)
- **Cloud**: The Content Platform at The Economist is an event-driven distributed architecture making heavy use of SQS, SNS (incuding message filtering), S3, Lambda, CodeBuild, AWS SAM, Cloudwatch, API Gateway, DynamoDB and many more. We hand-rolled our own CICD using SAM and CodeBuild and engineers are able to test and build Lambda locally using SAM. Other projects have also been making using of [Terraform](https://www.terraform.io)Also built numerous tools to make full use of the cloud stack, including tools to automate the build of new Go Lambdas, touch S3 files based on user-supplied criteria to effect event replay and tools to more deeply validate SAM templates above and beyond the standard offerings.
- **Logging and metrics**: Extensive use of a slew of technologies to gain maximum visibilty into our software, including [Datadog](https://www.datadoghq.com/), [Logz.io](https://logz.io), CloudWatch, AWS X-Ray, Kibana, [Grafana](https://grafana.com/) and [Prometheus](https://prometheus.io/).

I am also deep into [Elixir](https://elixir-lang.org/) and [Clojure](https://clojure.org/) right now as a big fan of functional programming. Currently porting a [node GraphQL server to Clojure](https://github.com/buddhamagnet/clj-graphql).

## MOST RECENT PROJECTS

### DIRECT LINE

Currently working as a consultant for Direct Line on a pioneer cloud team building a real time fraud detection engine. Working on all parts of the stack, from the React front end to the back end composed of a set of node Lambdas and associated AWS infrastructure. Advised and worked on all aspects of the project and team to hit several tight and budget-sensitive dealdines (code review process, rebuilding and streamlining CICD, infrastructure as code). Phase 1 of the project, the real time engine was delivered on time and under budget. Phase 2 involves batch processing of insurance claim data, making heavy use of ETL tools provided by AWS (specifically [Glue](https://aws.amazon.com/glue/) and [Athena](https://aws.amazon.com/athena/)). I was also responsible for building out the whole GraphQL layer which served as a conduit between the front end and back end claim data (relational data held in Postgres).

### THE ECONOMIST

Worked on the Content Platform as tech lead, migrating the initial fleet of worker services from Elastic Beanstalk worker environments to AWS Lambda and serverless. Worked on the entire stack, including the above mentioned workers (Go), a subset of workers written in ES6 JavaScript, the GraphQL layer that sits in front of our fleet, our gateway layer which comprises Nginx (Openresty), Varnish and Lua, and our Elasticsearch back end, including working out a way to reindex with zero downtime.

> "It is my pleasure to write a recommendation for Dave Goodchild whom I have had the fortune of working with at The Economist since I joined end of February 2015 as platform architect for the content and the data management platforms. Dave Goodchild was a senior engineer on the project to revamp the content platform into a micro-service based, message driven, reactive system. He played a key role to enable us to deliver the modernization of the core content stack of The Economist on time and on budget. It is rare to come across a standout talent like Dave Goodchild who is an amazing Golang developer and any other programming language he is asked to use, regardless if it is php, javascript, clojure or configuring nginx or varnish. He is able to quickly capture the entire end-to-end picture of a problem or a feature, devise a technical solution in record time, then implement & maintain it. His deep understanding of functional reactive programming concepts enabled to build up the new containerized system based on Docker with the back-end micro-services written in Golang and front-end based on GraphQL and ReactJS running completely optimized for Amazon Web Services (AWS), driven fully by a Continuous Delivery (CD) pipeline. It's a pity that he decided to leave after contracting about four years for The Economist. At least I've learnt a great deal working with him and I'm happy that he remains as a very good personal friend who I can deeply recommend as a colleague."

[Artur Ortega](https://www.linkedin.com/in/arturortega/?originalSubdomain=uk), Platform Architect, The Economist (previously Telegraph and Yahoo).

> "Dave is a level headed very highly skilled engineer. He has an uncanny ability to break down even the most complex task and simplify it to the point that everybody on the team can contribute. He cuts through the noise and encourages everybody to see the core value proposition. He takes ownership of any task given to him or tangential to him and ensures it gets done to the highest quality. It doesn't matter if it's greenfield or legacy, unfamiliar tech or a well trodden road; Dave will roll up his sleeves and get it done. He has deep knowledge of Golang and high scale AWS cloud architectures. He's a true polyglot engineer and will cut code in the appropriate tech to get the job done."

[Juhjar Singh](https://www.linkedin.com/in/jujhar/), Devops Practice Lead, The Economist.

### PEAK BI

Hired by the cloud computing consultancy that worked with The Economist on providing AWS services and training to build a data product using [React](https://facebook.github.io/react/) and [Redux](http://redux.js.org/) on the front end and [Serverless](https://facebook.github.io/react/) and AWS on the back. The system provides a dynamic UI on top of Peak's data management offering allowing clients to log in and navigate a series of data-driven dashboards.

### THE ECONOMIST

Built out several iterations of a distributed content platform at The Economist. Involved in all aspects of the project:

- Building microservices in [Go](http://golang.org), including building the microservice template, mentoring team members in Go and building key components, some of which are now open source.
- Working alongside web products team to deliver the front end (using [Node](https://nodejs.org/en/) and [GraphQL](http://graphql.org/)).
- Working as a devops resource on an API gateway and caching architecture, using a suite of tools including [Salt](http://saltstack.com), [Nginx](https://www.nginx.com), [Openresty](https://openresty.org/en/), and [Varnish](https://www.varnish-software.com). Initial gateway code was managed via Salt then ported to Docker.
- Working with a variety of AWS tools in a devops capacity, including S3, SNS, Lambda, CloudFormation, SQS, Elastic Beanstalk, EC2, EC2 Container Service and VPC.
- Builing a development environment using Docker Compose which integrated all services and the API gateway locally. Later work also involved a fair amount of [Lua](https://www.lua.org/) to turn the gateway into a true powerhouse.
- Assisting with implementing a continuous delivery pipeline with [Docker](https://www.docker.com/) and [Amazon ECS](https://aws.amazon.com/ecs/details/), initially using [GoCD](https://www.go.cd/) for the pipeline and transitioning to [AWS Code Pipeline](https://aws.amazon.com/codepipeline/).
- Assisting with ensuring the whole stack was fully tested using Go's built-in testing package and developing a set of contract and integration tests.
- Helping to build the service discovery layer, initially with [Consul](https://www.consul.io/) and transitioning to dynamic back ends in Nginx routing to AWS ELBs.
- Building Drupal modules for the back end to deliver content from the CMS to API consumers. Later iterations leveraged S3 events and SNS to trigger downstream Go workers which transformed and stored raw content in the appropriate format (modified JSON for API consumers, Apple News format for the Apple News service, and later all content consolidated in a canonical data model influenced by [schema.org](http://schema.org)).
- In later stages of the project, worked on mechanisms to ensure content could still be served even if all the services and Drupal back end went down using Varnish write behind cache and storage of responses and content on S3.
- Documenting it all!

Other projects at the Economist included:

- an ID forwarding service to allow services to refer to resources using canonical identifiers.
- a service that pushes Economist content to the Apple News service.
- [vendorgodeps - migrate from godeps to vendor folder](https://github.com/prisamuel/vendorgodeps)
- [goberry - microservice template](https://github.com/EconomistDigitalSolutions/goberry).
- [ramlapi - API plumbing](https://github.com/EconomistDigitalSolutions/ramlapi).
- [watchman - logging and metrics](https://github.com/EconomistDigitalSolutions/watchman)
- [tripper - circuitbreaker wrapper](https://github.com/buddhamagnet/tripper).
- [gq - worker queue package in go](https://github.com/buddhamagnet/gq)
- [goconsul - simple service registration](https://github.com/buddhamagnet/goconsul)

Recent open source contributions to Go projects:

- [bluemonday](https://github.com/microcosm-cc/bluemonday/commits?author=buddhamagnet)
- [silk](https://github.com/matryer/silk/pull/19)
- [gizmo (New York Times)](https://github.com/NYTimes/gizmo/commits?author=buddhamagnet)
- [godep](https://github.com/tools/godep/commits?author=buddhamagnet)
- [caddy](https://github.com/mholt/caddy/commits?author=buddhamagnet)
- [migrate](https://github.com/mattes/migrate/commits?author=buddhamagnet)
- [gobundle](https://github.com/alecthomas/gobundle/graphs/contributors)
- [consul](https://github.com/hashicorp/consul/commit/c34bcb45c670af076846826ea72c436fbd0e2c35)
- [docker - code](https://github.com/docker/docker/commit/6fd8e485c85c4f8ca62578d0840bdeddc4cba151)
- [docker - documentation](https://github.com/docker/docker/commit/5be5749d544702c5da37c8ab448b417daf13e297)
- [docker - documentation](https://github.com/docker/docker/commit/53edce79f16816a165b5be9cd4ee05501c103c6f)
- [godotenv](https://github.com/joho/godotenv/commit/443e926da0d793d3b3f32118b1e4ba52ada26503)
- [gods](https://github.com/emirpasic/gods/commit/4257bbbae30da5ae4fa1621734efb9ddd02d7fa4)

Open source contributions and projects outside Go:

- [gothimbl - go client for the thimbl network](https://github.com/buddhamagnet/gothimbl)
- [badaboom - rails export tool for extracting audio from audioboom](https://github.com/buddhamagnet/badaboom)
- [wildearth - refinery site for a remote production support company](https://github.com/buddhamagnet/wildearth)
- [cardshark - rails app built in 40 minutes as a technical test](https://github.com/buddhamagnet/cardshark)
- [quartz (ruby-go interface gem)](https://github.com/DavidHuie/quartz/graphs/contributors)
- [rails](http://contributors.rubyonrails.org/contributors/dave-goodchild/commits)
- [rails api](https://github.com/rails-api/rails-api/pull/145#issuecomment-52991509)
- [refinery CMS](https://github.com/refinery/refinerycms/pull/2649)
- [sass documentation site](https://github.com/sass/sass-site/issues/86)
- [ghost - js blogging engine](https://github.com/TryGhost/Ghost/commits?author=buddhamagnet)
- [varnish cache](https://github.com/varnishcache/varnish-cache/commits?author=buddhamagnet)
- [ruby](https://github.com/ruby/ruby/commit/71b6077a5354335f5f04b7e852a22b3290b9f528)
- [ruby](https://github.com/ruby/ruby/commit/5f55e23f9c2feb774aaffde8c9e20213c7b97497)
- [regularity - rb regex library](https://github.com/andrewberls/regularity/pull/2)
- [draper - rb presenter library](https://github.com/drapergem/draper/commits?author=buddhamagnet)
- [discourse - rails and ember forum](https://github.com/discourse/discourse)
- [jumpstartlabs](https://github.com/JumpstartLab/curriculum/commit/2f6a26e4f62b9cd12e51d6d68758777d87f3af3d)
- [railsgirls](https://github.com/railsgirlslondon/railsgirls-london/contributors)
- [adn (API wrapper for app.net)](https://github.com/adn-rb/adn/graphs/contributors)
- [adn-cli(command line client for same)](https://github.com/adn-rb/adn-cli/graphs/contributors)
- [split (ab testing gem)](https://github.com/andrew/split/graphs/contributors)
- [resque - rb redis-backed queue](https://github.com/defunkt/resque/graphs/contributors)
- [diaspora - decentralized social software](https://github.com/diaspora/diaspora/commits?author=buddhamagnet)
- [rstat.us - decentralizised social software](https://github.com/hotsh/rstat.us/graphs/contributors)

## COMMUNITY AND EDUCATION

I'm a big believer in sharing the love and have delivered training sessions at The Economist and am currently helping with the build and maintenance of [Greater Commons](https://greatercommons.com/), a course platform for developers. I am also working with Todd McLeod to build some Udemy courses on Go, and was intrumental in bringing Bill Kennedy in for training sessions. [Here's an example](https://www.youtube.com/watch?v=HdMmLQB8ZWE) of a session on Varnish testing I delivered for The Economist.

I was one of the original creators of [rubyinthepub](http://www.joannageary.com/2010/05/13/ruby-in-the-pub-3/), a meet-up
designed to put developers, journalists and writers in the same room to explore their
common space and collaborate on projects. This small event has since transformed into
the UK arm of [Hackshackers](http://meetuplondon.hackshackers.com/), an event originally
kicked off by the New York Times.

I am also now giving some of my time as a mentor on the Go track at [exercism][https://exercism.io].

## [WHERE HAVE I BEEN?](https://github.com/buddhamagnet/cv/blob/master/employment.md)

## [COULD YOU WORK WITH ME?](https://github.com/buddhamagnet/cv/blob/master/me.md)
