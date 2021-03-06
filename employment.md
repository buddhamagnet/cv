## [BACK TO CV](https://github.com/buddhamagnet/cv/blob/master/README.md)

### [THE ECONOMIST] JAN 2021 - PRESENT

Back at The Economist again, this time on a contract to build out a syndication platform to consolidate and centralise various approaches adopted in-house to syndicate content to a range of internal, retail, wholesale and aggregation clients.

Techologies used: Typescript, AWS (Lambda, SNS, SQS, AWS CDK, Step Functions, CloudWatch Events).

### [LUSH](https://uk.lush.com) OCT 2020 - JAN 2021

Working as a back end engineer across a variety of products and teams. Remit included consolidating and documenting the microservice estate, hiring new engineers, building and maintaining services, acting as a conduit between back end and front end teams, collaborating as devops building CICD pipelines (ArgoCD, K8S) and working on cloud back end (GCP) with services written in Go, Python and Node. Used a variety of build and dev tools including [Mage](https://magefile.org), [Tusk](https://github.com/rliebz/tusk), [SOPS](https://github.com/mozilla/sops). GCP technologies used: BigQuery, Spanner, PubSub, Cloud Storage, Cloud SQL, Kubernetes, GCE.

### [DIRECT LINE](http://www.economist.com/) FEB 2020 - PRESENT

Senior engineer, fraud department.

### [THE ECONOMIST](http://www.economist.com/) OCT 2017 - JAN 2020

Technical lead, Content Platform. Heading up a distributed team of eight engineers.

### [THE ECONOMIST](http://www.economist.com/) MAY 2017 - OCT 2017

Back at The Economist, this time straddling both front and back end teams armed with experience building out the microservice architecture (primarily in Go) with the platform team and a recent project making heavy use of React and Redux. Main remit was to act as a conduit between front end and back end as the former moved to consumption of a canonical data model built by the latter. Main work involved adapting GraphQL to work with the new model and helping to refactor the front end (Relay) parts accordinly. As of October 2017 I will be re-joining the content platform team full-time once again to work on wider intiatives.

### [PEAK BI](http://www.peak.bi/) JANUARY 2016 - APRIL 2017

Hired by the cloud computing consultancy that worked with The Economist on providing AWS services and training to build a data product using [React](https://facebook.github.io/react/) on the front end and [Serverless](https://serverless.com/) and AWS on the back end.

### [WILD EARTH PRODUCTIONS](http://wildearth.productions) OCTOBER 2014 - FEBRUARY 2015

Project completed in parallel with other consulting gigs. Designed and built a fully responsive site backed by [Refinery CMS](http://refinerycms.com) for Wild Earth Productions, a new business specialising in remote location support for film, TV and advertising organisations. The brainchild of Jason Ingamells, owner of the [Woodland Ways](http://woodland-ways.co.uk) bushcraft and survival school and [Anders Brogaard](http://www.andersbrogaard.co.uk), globe-trotting commercial photographer. I am technical consultant on the digital side.

### [THE ECONOMIST](http://www.economist.com) JULY 2012 - DECEMBER 2016

Working with an varied and exciting technology stack (PHP for Drupal and Symfony, Ruby for Puppet, Capistrano, Compass/SASS and an internal Rails application), Varnish, git, memcached, you name it.

#### PROJECTS

#### MICROSERVICE ARCHITECTURE - SHIPPED!

Instrumental in selling Go to the business and in the process of building out a suite of microservices to run in conjunction with an Enterprise Service Bus (Mulesoft). Services in Go are now being written on both sides of the pond. The project, which is an ongoing evolution, comprised building out a reactive architecture using Go and AWS (S3, SQS, SNS, EC2, EC2 Container Service and Lambda).

#### RAILS APPLICATION - SHIPPED!

Providing support for a Rails application owned by [Digital News Agency](digitalnewsagency.com) (part of the Economist Group), including advising on upgrading from Rails 2.3.8 to 3 and then 3.1, building a robust test harness around the application and supporting ongoing development. Also involved in building a set of tools in Ruby for use by the ops team.

#### AWS MIGRATION - SHIPPED!

Instrumental in assisting in the migration of The Economist stack onto Amazon. Touched all parts of the migration process, from consulting on migrating our services and packing configurations into Salt, adjusting the deployment process to cater for
auto-scaling, normalising HTTP headers across the whole stack through Incapsula, through the Amazon ELBs, Varnish, web servers and applications.

#### THE JAVASCRIPT CAMPAIGN - SHIPPED!

Heavily involved in an ongoing project to bring Javascript development at The Economist into the 21st century (toolset involved:
Bower, Grunt, Yeoman, Jasmine, Qunit, Node and Express).

#### GOOGLE PLAY INTEGRATION - SHIPPED!

Sole developer on a project to integrate our subscription and reconciliation services into Google Play, built using a back end composed of Symfony components and exposing a JSON API. Involves working closely with the team of Java developers tasked with working on the Economist Android app.

#### DECOUPLING THE ECONOMIST - SHIPPED!

In the midst of a vast project the end goal of which is to deliver a service-oriented architecture for The Economist, which is
essentially a monolithic Drupal installation. Work covers all aspects of this mammoth undertaking, from building of initial feature lists
for potential vendors and working closely with all stakeholders to ensure the project is delivered with minimal risk and disruption.

The system is being broken down into several discrete components which can fail without bringing the rest of the system down and
potentially be swapped out for other components if necessary. The in-house built components involve a large range of technologies - a
data store (current options are Postgres, documented-oriented solutions such as Mongodb for certain sets of data), a series of user-facing components (for example
a Manage My Account system which is being built using a range of cutting-edge front end technologies including Yeoman, Jasmine, PhantomJs, Grunt and
Angular) and a set of carefull designed API.

#### CACHING AUTHENTICATED USERS - SHIPPED!

Intrumental (not my words) in delivering a project whose main remitwas to ensure the site can handle the extra load that will be generated by the uptake
in registrations and subscriptions generated by the new paywall. Heavy stuff, working on one stream to utilise Varnish to allow us
to cache pages for authenticated users in parallel with a second stream to build the system that returns user data via JSON
to correctly populate the dynamic and user-specific subsystems (user navigation, analytics and ads).

Involved close collaboration with sysadmin to ensure the correct architectural decisions were made (and building tools to speed up the process,
such as this [memcache client](https://github.com/buddhamagnet/memquery) I wrote to make querying the cache for user sessions easier).

Also assisted in setting up the new deployment process using Puppet and Capistrano.

#### THE ECONOMIST ON MOBILE - SHIPPED!

Worked on the first part of the Economist mobile project - driving the mobile wallpage implementation as well as working on some high
profile mobile entry points (login and registration pages) as well as a larger initiative to start placing more
diverse Economist content behind the paywall. Check out the following URLs on a smartphone:

- [Login](http://economist.com/user)
- [Registration](http://economist.com/user/register)
- [Sample article](http://economist.com/news/leaders/21576385-one-margaret-thatchers-legacies-has-grown-more-troubling-electoral-reform-and-devolution/)
- [Print edition](http://economist.com/printedition)

#### THE ECONOMIST PAYWALL - SHIPPED!

Completed a project to decouple the Economist paywall from Drupal and help move The Economist towards a service-oriented archiecture. This
project is pure JavaScript (with an admixture of Jquery and Underscore), tested using Jasmine and Phantom. The application also
utilises local storage to store pre-compiled paywall templates.

#### BITS AND PIECES

Also assisting with their migration to git (including developer training and working with sysadmin to modify deployment and CI process accordingly). Have also been made
a core committer which essentially makes me a final checkpoint on code going into the Economist codebase.

Have also made a couple of trips to the Tower (where the journalists live) to introduce the graphics and front end team to the joys
of selenium testing.

> “I worked with Dave Goodchild at the Economist. Dave is a fantastic person to work with. Not only does he hold to a high standard of excellence (even if that means spending great amounts of time cleaning up other people's messes), but he brings a charisma and enthusiasm into his work that is just contagious."
> Judah Anthony, lead developer, New York office.

> "I had the luck to work with Dave for almost a year. He is one of the hard worker colleagues who helps you first whenever you have a problem. It was surprising sometimes how quickly and precisely he can solve problems. His technical skills are really great - and also as a team member he is able to keep up a good spirit no matter how hard the pressure is. I would love to work with him again in the future."
> Peter Arato, Drupal developer.

### [UNBOUND](http://unbound.co.uk) JULY 2011 - JUNE 2012

Freelancing for a UK-based startup (Rails 3 platform) created by the QI research team. Unbound provides a crowd-funded publishing platform for
writers, both published and unknown, and has garnered an impressive amount of press over the last few months:

- [TechCrunch](http://techcrunch.com/2011/05/29/unbound-launches-its-kickstarter-byliner-hybrid-for-celebrity-authors/)
- [Mashable](http://mashable.com/2011/06/01/unbound/)
- [Wired](http://www.wired.co.uk/news/archive/2011-05/29/unbound-publishing-platform)
- [Telegraph](http://www.telegraph.co.uk/culture/hay-festival/8543961/Hay-Festival-2011-New-site-Unbound-gives-readers-the-power-of-publishing.html)

I was originally
brought in to assist in refactoring the original codebase but soon jumped in full-time. [Here's my contribution](https://github.com/buddhamagnet/cv/blob/master/unbound.md).

> “Dave has been an absolute pleasure to work with at Unbound, with his ability to see web development not simply from the coding perspective but from the users experience as well. Producing a site that is clear, works elegantly and doesn't fall over when people with 1.5 million Twitter followers tweet it, is a major achievement. Dave is also extremely affable, very easy to work with, highly conscientious and technically excellent. You couldn't ask for more.”
> [Justin Pollard](http://www.visualartefact.com), co-founder.

> “Dave produced creative, well structured and stable code for the Unbound site, rewriting and testing large sections of an existing code base to better suit the application's purpose, as well as building features and squashing major bugs. He was on time, on budget and very conscientious. It is great to be able to work with a developer who is not only highly skilled but who thinks things through to the point of user interaction before implementation as well as during the testing process. This allowed his skills as a developer to help augment product creation in a swiftly changing startup environment. He is an exemplary freelance developer and a pleasure to work with.”
> Xander Cansell, product owner.

### [LOVEFRESH](http://lovefre.sh) JUNE 2011 - JULY 2011

Worked as a freelancer for a UK-based startup on the build of a social food application. I pitched in on the Rails side (Rails 2.3.8, subsequently updated to 3), working on features, tests and refactoring.

> “Dave joined us at a key time in our development of Lovefre.sh, to build out our Ruby on Rails web app prior to launch. He was a pleasure to work with, skilled, had a very positive attitude and a thorough approach.”
> Mark Spofforth, CEO.

### [TURNER BROADCASTING](http://turner.com) JULY 2010 - JUNE 2011

Freelance developer in London-based digital team looking after [Cartoon Network](http://cartoonnetwork.co.uk), [Boomerang](http://boomerangtv.co.uk) and [Adult Swim](http://adultswim.co.uk) for 14 countries. Core remit was as a Drupal developer with time split between building custom modules and maintenance tasks. Was instrumental in introducing version control branching and merging to the development team as well as building common code libraries and improving the overall development process. Also patched and extended the Webistrano (Rails) app used for deployment.

> “Dave is basically a great bloke with an excellent sense of humour. He really knows his stuff when it comes to Drupal development and is a pleasure to work with. If there's a technical issue that you need help with, Dave is the first to offer assistance.”
> Mike King, web designer.

### [COMIC RELIEF](http://comicrelief.com) SEPTEMBER 2009 - JULY 2010

Worked on the [Sport Relief](http://sportrelief.com) 2010 campaign as well as the Comic Relief and [Red Nose Day](http://rednoseday.com) sites. Main remit was to build custom Drupal modules for the sites. Also rebuilt the existing web services back end for Sport Relief end using [Zend Framework](http://zend.com) and ported this to Comic Relief.

My work at Comic Relief was varied, touching on back end work (writing back end services for the Flash part of the Sport Relief site using AMF; refactoring the Mile Event registration and management system using a combination of Zend components and pure PHP; working on internal Rails application used to manage data flow between various databases) and front end (building fundraising hub pages for major donors; working on theme layer for all three sites).

> “I worked with David during Sport Relief 2010 and found him to be a consummate professional and technically proficient. His ability to understand the client's requirements and provide a swift and streamlined solution was commendable. As such I have no hesitation in recommending him as a proficient developer and an able communicator.”
> Paul Wood, senior designer.

### [JELLYFISH](http://jellyfish.co.uk) MAY 2004 - SEPTEMBER 2009

Worked as senior developer on a fast-moving PHP development team comprising 12 developers, three seniors, [one lead](http://blog.mikepearce.net), a DBA, QA tester and manager. I was been involved in a number of projects, starting with converting the existing campaign site templates to standards-compliant tableless design, to playing a large part in rebuilding the entire PHP4 platform from scratch and delivering a PHP5 platform – team used the scrum agile methodology, version control and daily standup meetings to adapt fast to changing requirements. My domain included building a centralized signup process for all campaign sites, re-engineering the fulfillment system and redesigning the product module as a web service.

> “It was a great pleasure to work with Dave. He is a dedicated and focussed developer as well as being keen to help steer the direction of any product he is working on. He takes ownership of his work and was known for this tenacity in creating good, solid code. Dave is also someone able to talk to clients and colleagues without baffling, scaring or belittling them, something not all developers are capable of. I would definitely work with Dave again.”
> Mike Pearce, lead developer.

> “Working alongside Dave at Jellyfish is an experience I will never forget! He is extremely skilled and still manages to fork out time to help guide younger developers when they need explanation / guidance. Dave has a great sense of humour but at the same time works hard when needed to achieve the set goals.”
> Bart Shelfhout, senior developer.

### [SUN MICROSYSTEMS](http://sun.com) NOVEMBER 1999 - MAY 2003

Part of a enterprise development team using a mixture of technologies (primarily java) to migrate over 40 European websites from a legacy platform to a new platform built on oracle and documentum. I was initially hired as a contractor to assist in the migration process and was offered a permanent position after six months, working in a variety of domains in the global tech department, including working on sun.com and building a series of applications to aid in site maintenance and content delivery.

## [BACK TO CV](https://github.com/buddhamagnet/cv/blob/master/README.md)
