# Skupper demo

This demo shows some of the capabilities in [Skupper](https://skupper.io) and is split into three parts:

  - [Part1](./demo-scripts/part1-hybrid-cloud.md) shows a hybrid cloud setup and how you can set up an application with two services deployed in two different OpenShift clusters.
  
  - [Part2](./demo-scripts/part1-hybrid-cloud.md) builds on top of part 1 and shows resiliency and loadbalincing capabilities in Skupper. In this scenario we deploy identical copies of the application in the two separate clusters and show how Skupper can detect failure in the local backend service and start routing traffic to the backend service running in the second cluster.
  
  - [Part3](./demo-scripts/part3-private-database.md) shows how you can deploy an application in a public cluster that communicates with a MySQL database running in a RHEL instance on a private network. This part can be run standalone or be build on top of part 1 and 2.

