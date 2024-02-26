# kubernetes-wordpress
This repository is an attempt to create kubernetes clusters to deploy a wordpress site.
The contents of this repository is a part-fulfilment of the requirements for the day 3 assignment in the HNG Advanced - Docker and Kubernetes class.

There are few files that Kubernetes will need for this deployement to run:
- a secret file for the mariadb service that stores all the credentials for the mariadb service
- a secret file for the wordpress service that stores all the credentials that wordpress needs to connect to the mariadb database.