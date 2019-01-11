# DAVID GOODCHILD

## IN A NUTSHELL

I am a developer with nearly 20 years of experience working for all
manner of organisations, from working as a single freelancer, through a number
of startups and consultancies, to large companies including [Sun Microsystems](http://sun.com) and [The Economist](http://economist.com).

Primarily a back end developer, I can read and debug C, have been working with [Go](https://golang.org) for around three years, and make heavy use of Python and bash in day to day development tasks. I did a fair amount of [Ruby] in previous
projects, and recent work has involved use of [Lua], primarily in [Openresty]. I am 
also comfortable, if less than happy, to write Javascript and have both worked on front end teams utilising [React](https://reactjs.org/) and [Redux](http://redux.js.org/), as well as developing in [GraphQL](http://graphql.org/).

I am deep into [Elixir](https://elixir-lang.org/) right now as a big fan of functional programming.

I am also a cloud native, primarily working with AWS and serverless with a large stack of technologies including ElasticSearch, Varnish, Nginx, Lambda, SQS, SNS, EC2, Docker, and S3.

## MOST RECENT PROJECTS

### THE ECONOMIST

Currently back on the Content Platform as tech lead, right now migrating the initial fleet of worker services from Elastic Beanstalk worker environments to AWS Lambda and serverless.

### PEAK BI

Hired by the cloud computing consultancy that worked with The Economist on providing AWS services and training to build a data product using [React](https://facebook.github.io/react/) and [Redux](http://redux.js.org/) on the front end and [Serverless](https://facebook.github.io/react/) and AWS on the back. The system provides a dynamic UI on top of Peak's data management offering allowing clients to log in and navigate a series of data-driven dashboards. 

### THE ECONOMIST

Built out several iterations of a distributed content platform at The Economist. Involved in all aspects of the project:

* Building microservices in [Go](http://golang.org), including building the microservice template, mentoring team members in Go and building key components, some of which are now open source.
* Working alongside web products team to deliver the front end (using [Node](https://nodejs.org/en/) and [GraphQL](http://graphql.org/)).
* Working as a devops resource on an API gateway and caching architecture, using a suite of tools including [Salt](http://saltstack.com), [Nginx](https://www.nginx.com), [Openresty](https://openresty.org/en/), and [Varnish](https://www.varnish-software.com). Initial gateway code was managed via Salt then ported to Docker. 
* Working with a variety of AWS tools in a devops capacity, including S3, SNS, Lambda, CloudFormation, SQS, Elastic Beanstalk, EC2, EC2 Container Service and VPC.
* Builing a development environment using Docker Compose which integrated all services and the API gateway locally. Later work also involved a fair amount of [Lua](https://www.lua.org/) to turn the gateway into a true powerhouse.
* Assisting with implementing a continuous delivery pipeline with [Docker](https://www.docker.com/) and [Amazon ECS](https://aws.amazon.com/ecs/details/), initially using [GoCD](https://www.go.cd/) for the pipeline and transitioning to [AWS Code Pipeline](https://aws.amazon.com/codepipeline/).
* Assisting with ensuring the whole stack was fully tested using Go's built-in testing package and developing a set of contract and integration tests.
* Helping to build the service discovery layer, initially with [Consul](https://www.consul.io/) and transitioning to dynamic back ends in Nginx routing to AWS ELBs.
* Building Drupal modules for the back end to deliver content from the CMS to API consumers. Later iterations leveraged S3 events and SNS to trigger downstream Go workers which transformed and stored raw content in the appropriate format (modified JSON for API consumers, Apple News format for the Apple News service, and later all content consolidated in a canonical data model influenced by [schema.org](http://schema.org)).
* In later stages of the project, worked on mechanisms to ensure content could still be served even if all the services and Drupal back end went down using Varnish write behind cache and storage of responses and content on S3.
* Documenting it all! 

Other projects at the Economist included:

* an ID forwarding service to allow services to refer to resources using canonical identifiers.
* a service that pushes Economist content to the Apple News service.
* [vendorgodeps - migrate from godeps to vendor folder](https://github.com/prisamuel/vendorgodeps)
* [goberry - microservice template](https://github.com/EconomistDigitalSolutions/goberry).
* [ramlapi - API plumbing](https://github.com/EconomistDigitalSolutions/ramlapi).
* [watchman - logging and metrics](https://github.com/EconomistDigitalSolutions/watchman)
* [tripper - circuitbreaker wrapper](https://github.com/buddhamagnet/tripper).
* [gq - worker queue package in go](https://github.com/buddhamagnet/gq)
* [goconsul - simple service registration](https://github.com/buddhamagnet/goconsul)

Recent open source contributions to Go projects:

* [silk](https://github.com/matryer/silk/pull/19)
* [gizmo (New York Times)](https://github.com/NYTimes/gizmo/commits?author=buddhamagnet)
* [godep](https://github.com/tools/godep/commits?author=buddhamagnet)
* [caddy](https://github.com/mholt/caddy/commits?author=buddhamagnet)
* [migrate](https://github.com/mattes/migrate/commits?author=buddhamagnet)
* [gobundle](https://github.com/alecthomas/gobundle/graphs/contributors)
* [consul](https://github.com/hashicorp/consul/commit/c34bcb45c670af076846826ea72c436fbd0e2c35)
* [docker - code](https://github.com/docker/docker/commit/6fd8e485c85c4f8ca62578d0840bdeddc4cba151)
* [docker - documentation](https://github.com/docker/docker/commit/5be5749d544702c5da37c8ab448b417daf13e297)
* [docker - documentation](https://github.com/docker/docker/commit/53edce79f16816a165b5be9cd4ee05501c103c6f)
* [godotenv](https://github.com/joho/godotenv/commit/443e926da0d793d3b3f32118b1e4ba52ada26503)
* [gods](https://github.com/emirpasic/gods/commit/4257bbbae30da5ae4fa1621734efb9ddd02d7fa4)

Open source contributions and projects outside Go:

* [gothimbl - go client for the thimbl network](https://github.com/buddhamagnet/gothimbl)
* [badaboom - rails export tool for extracting audio from audioboom](https://github.com/buddhamagnet/badaboom)
* [wildearth - refinery site for a remote production support company](https://github.com/buddhamagnet/wildearth)
* [cardshark - rails app built in 40 minutes as a technical test](https://github.com/buddhamagnet/cardshark)
* [quartz (ruby-go interface gem)](https://github.com/DavidHuie/quartz/graphs/contributors)
* [rails](http://contributors.rubyonrails.org/contributors/dave-goodchild/commits)
* [rails api](https://github.com/rails-api/rails-api/pull/145#issuecomment-52991509)
* [refinery CMS](https://github.com/refinery/refinerycms/pull/2649)
* [sass documentation site](https://github.com/sass/sass-site/issues/86)
* [ghost - js blogging engine](https://github.com/TryGhost/Ghost/commits?author=buddhamagnet)
* [varnish cache](https://github.com/varnishcache/varnish-cache/commits?author=buddhamagnet)
* [ruby](https://github.com/ruby/ruby/commit/71b6077a5354335f5f04b7e852a22b3290b9f528)
* [ruby](https://github.com/ruby/ruby/commit/5f55e23f9c2feb774aaffde8c9e20213c7b97497)
* [regularity - rb regex library](https://github.com/andrewberls/regularity/pull/2)
* [draper - rb presenter library](https://github.com/drapergem/draper/commits?author=buddhamagnet)
* [discourse - rails and ember forum](https://github.com/discourse/discourse)
* [jumpstartlabs](https://github.com/JumpstartLab/curriculum/commit/2f6a26e4f62b9cd12e51d6d68758777d87f3af3d)
* [railsgirls](https://github.com/railsgirlslondon/railsgirls-london/contributors)
* [adn (API wrapper for app.net)](https://github.com/adn-rb/adn/graphs/contributors)
* [adn-cli(command line client for same)](https://github.com/adn-rb/adn-cli/graphs/contributors)
* [split (ab testing gem)](https://github.com/andrew/split/graphs/contributors)
* [resque - rb redis-backed queue](https://github.com/defunkt/resque/graphs/contributors)
* [diaspora - decentralized social software](https://github.com/diaspora/diaspora/commits?author=buddhamagnet)
* [rstat.us - decentralizised social software](https://github.com/hotsh/rstat.us/graphs/contributors)

## COMMUNITY AND EDUCATION

I'm a big believer in sharing the love and have delivered training sessions at The Economist and am currently helping with the build and maintenance of [Greater Commons](https://greatercommons.com/), a course platform for developers. [Here's an example](https://www.youtube.com/watch?v=HdMmLQB8ZWE) of a session on Varnish testing I delivered for The Economist.

I was one of the original creators of [rubyinthepub](http://www.joannageary.com/2010/05/13/ruby-in-the-pub-3/), a meet-up
designed to put developers, journalists and writers in the same room to explore their
common space and collaborate on projects. This small event has since transformed into
the UK arm of [Hackshackers](http://meetuplondon.hackshackers.com/), an event originally
kicked off by the New York Times.

## [WHERE HAVE I BEEN?](https://github.com/buddhamagnet/cv/blob/master/employment.md)

## [COULD YOU WORK WITH ME?](https://github.com/buddhamagnet/cv/blob/master/me.md)
