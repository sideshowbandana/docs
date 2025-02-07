Kyle Barton
===========
kyle.humberto@gmail.com | [Github](https://github.com/sideshowbandana) | [LinkedIn](https://www.linkedin.com/in/kyle-barton-586a39180/) | [Medium](https://medium.com/@kyle_26541) | [HackerRank](https://www.hackerrank.com/kyle_humberto) | [Atomic Machines](https://www.facebook.com/TheAtomicMachines/)

----

> Obtain a software engineering position where I can utilize my versatility and experience of scaling cloud-based systems.

----

## Software Languages / Frameworks / Services  / Tools / Buzzwords ##


|               |               |             |               |                |            |
| :------------ | :------------ | :---------- | :------------ | :------------- | :--------  |
| git           | redis         | python      | circleci      | Docker         | Atlantis   |
| BigQuery      | postgres      | memcached   | mysql         | Terraform      | Airflow    |
| GitHub        | ActiveAdmin   | hackerone   | pagerduty     | datadog        | Cloudflare |
| rails         | resque        | dmarcian    | Sentry        | Helm           | Emacs      |
| ruby          | AWS           | codeclimate | Kubernetes    | GoogleCloud    | NewRelic   |

## Communication ##

Thought leadership presenter. Responsible for presenting various pieces of on going work to larger groups in order to socialize new ideas and directions to the rest of the company

## Leadership ##

Server side consumer team lead. Responsible for a team of 4-5 people focused primarily on consumer facing features as well as analytics and data processing related to those feature to understand the impact on our users.

## Experience ##

### Principal Backend Engineer | Albert | 6/2024 - PRESENT
- Made library updates to configure cors headers across all services
- Implemented AWS REST API gateway that routes traffic through NLB to microservice ALBs inside the VPC using terraform. Including changes to a client binary to allow developers to deploy to their own feature environments
- Updated client tool to toggle postgres query logging, generate new services from scratch,
- Moved alert notification functionality from monolithic app intio a microservice
- Integrated codecov into github actions for each project
- Refactored django model bulk_update code to update based on partitions

### Server lead | FITBOD | 9/2018-06/2024

- Responsible for building the team through recruiting, interviewing and training
- Responsible for migrating legacy ParseServer (NodeJS/MongoDB) to new service oriented architecture
- Assist founder decisions on people, process and technology based on my previous experience in small companies
- Implement API for user workout data storage following the jsonapi spec
- Implement deployment pipeline to allow for continuous deployment of dev, staging, production and features using circleci.
- Implement authentication service and architecture for handling authenticating users across micro services
- Manage GCP and AWS infrastructure via terraform and atlantis
- Implement API for queuing long running jobs
- Implement migration job to transfer user data from MongoDB to Postgres

### Devops | OpsZero | 9/2017-9/2018 ###

- Assist companies in reducing monthly spend on AWS and GoogleCloud by placing existing software onto kubernetes
- Convert legacy Java app from using SQL Server to Postgres to increase performance and decrease spend.
- Deploy customized Jenkins instance for building and deploying multiple projects
- Assist companies in becoming HIPPA compliant
- Manage and implement Docker images
- Convert projects from CircleCI v1 to v2
- Implemented a system for configuring and deploying [feature branches](https://itnext.io/feature-deployments-in-kubernetes-c74bdcff0d8e) into kubernetes environment

### Lead Engineer | MasterClass | 2/2015-7/2016 ###

- Worked with a team of 2 other engineers to create production release of masterclass.com
- Split out admin/content management related functionality from the user facing site and added it to an admin portal using ActiveAdmin
- Added server side async job processing with Resque
- Set up development and deployment process using, git, gerrit, github, heroku, pivotal tracker and circleci.
- Integrated bug tracking (Raygun) and user reported issues (zendesk) with pivotal and slack
- Used AWS to handle resource retrieval with cloudfront and s3.
- Maintained domain records for masterclass.com
- Set up rotating schedule to handle on-call (pagerduty/release management), security (hackerone), tech debt(codeclimate), and bug triage (raygun/zendesk) using a simple round robin rails app.
- Set up DMARC and SPF using dmarcian
- Provisioned SSL certificates
- Advised team members on API design as well as system architecture and best practices.
- Helped the analytics team by consolidating production postgres/kiss metrics/google ads/ segment/google analytics into redshift using xplenty so that we could build dashboards using looker. Set up the preliminary dashboards showing revenue statistics.
- Ensured site uptime using new relic, pingdom, and pager duty.
- Upgraded the main application from Rails 3.2 to rails 4.2 and ruby 1.9 to ruby 2.2

### Sr. Software Engineer | Lookout Inc | 9/2008 –2/2015 ###

- Implemented original device to server communication protocol based on SyncML
- Designed and implemented a “one time tasks” framework to allow developers to run various tasks in the production environment safely and easily
- Added archival functionality for user related data
- Designed and implemented a features framework to allow customization of users feature sets based on device capability and company policy (free/premium/preload)
- Designed and implemented a “gratification” framework for tracking success metrics for various features
- Designed and implemented [signal flare](https://venturebeat.com/2012/10/09/lookout-redesign/) functionality in a hackathon project.
- Implemented original device ping functionality
- Designed and implemented premium upsell and billing functionality
- Designed and implemented database sharding functionality which allowed us to scale to 50 million users
- Investigated and fixed various security vulnerabilities
- Re-engineered communication protocol to follow REST

### Software Engineer | Ripple TV | 9/2007 – 9/2008 ###

- Developed and maintained administrative console for distributing advertising content to remote display units
- Maintained consumer-facing portal for uploading ad content and purchasing ad space.


## Education ##

### B.S. | 2006 | Loyola Marymount University ###

- Major: Computer Science
- Related coursework: Data structures and algorithms, database design, and programming languages
