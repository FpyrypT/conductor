# Community projects related to Conductor


## Microservices operations

* https://github.com/flaviostutz/schellar - Schellar is a scheduler tool for instantiating Conductor workflows from time to time, mostly like a cron job, but with transport of input/output variables between calls.

* https://github.com/flaviostutz/backtor - Backtor is a backup scheduler tool that uses Conductor workers to handle backup operations and decide when to expire backups (ex.: keep backup 3 days, 2 weeks, 2 months, 1 semester)

* https://github.com/cquon/conductor-tools - Conductor CLI for launching workflows, polling tasks, listing running tasks etc


## Conductor deployment

* https://github.com/flaviostutz/conductor-server - Docker container for running Conductor with  Prometheus metrics plugin installed and some tweaks to ease provisioning of workflows from json files embedded to the container

* https://github.com/flaviostutz/conductor-ui - Docker container for running Conductor UI so that you can easily scale UI independently

* https://github.com/flaviostutz/elasticblast - "Elasticsearch to Bleve" bridge tailored for running Conductor on top of Bleve indexer. The footprint of Elasticsearch may cost too much for small deployments on Cloud environment.

* https://github.com/mohelsaka/conductor-prometheus-metrics - Conductor plugin for exposing Prometheus metrics over path '/metrics'

## OAuth2.0 Security Configuration
Forked Repository - [Conductor (Secure)](https://github.com/maheshyaddanapudi/conductor/tree/oauth2)

[OAuth2.0 Role Based Security!](https://github.com/maheshyaddanapudi/conductor/blob/oauth2/SECURITY.md) - Spring Security with easy configuration to secure the Conductor server APIs.

Docker image published to [Docker Hub](https://hub.docker.com/repository/docker/conductorboot/server)

## Conductor Worker utilities

* https://github.com/ggrcha/conductor-go-client - Conductor Golang client for writing Workers in Golang

* https://github.com/courosh12/conductor-dotnet-client - Conductor DOTNET client for writing Workers in DOTNET
  * https://github.com/TwoUnderscorez/serilog-sinks-conductor-task-log - Serilog sink for sending worker log events to Netflix Conductor

* https://github.com/davidwadden/conductor-workers - Various ready made Conductor workers for common operations on some platforms (ex.: Jira, Github, Concourse)

## Conductor Web UI

* https://github.com/maheshyaddanapudi/conductor-ng-ui - Angular based - Conductor Workflow Management UI

## Conductor Persistence

### Mongo Persistence

* https://github.com/maheshyaddanapudi/conductor/tree/mongo_persistence - With option to use Mongo Database as persistence unit.
  * Mongo Persistence / Option to use Mongo Database as persistence unit.
  * Docker Compose example with MongoDB Container.
