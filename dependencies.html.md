---
title: GitLab
---

# Dependencies
For the GitLab product to work, it has some dependencies which must be satisfied.

## MySQL
The product requires an external MySQL database in order to hold its state.

We recommend that you use a MySQL database that is Highly Available to remove any single points of failure from the product.

We have tested using the [MySQL for PCF](https://network.pivotal.io/products/p-mysql) tile as well the hosted [ClearDB](https://console.run.pivotal.io/marketplace/cleardb) offering on http://run.pivotal.io.

However any MySQL compatible database should work.

The required fields to be populated are:
* Database name - defaulted to `gitlabhq_production`
* Hostname - this can be a URL or IP address
* DB port
* DB username
* DB password

If the database does not exist it will be created upon installation. All database migrations are performed automatically during upgrades of the tile.

![Image of OpsManager MySQL Configuration](mysql.jpeg)

## Redis
The product requires an external Redis database in order to power its background processing queues.

We recommend that you use a Redis database that is Highly Available to remove any single points of failure from the product.

We have tested using the [Redis for PCF](https://network.pivotal.io/products/p-redis) tile as well as the hosted [Redis Labs](https://console.run.pivotal.io/marketplace/rediscloud) offering on http://run.pivotal.io.

However any Redis database should work.

The required fields to be populated are:
* Redis Hostname - this can be a URL or IP address
* Redis port - defaults to 6379
* Redis password

![Image of OpsManager Redis Configuration](redis.jpeg)

## NFS Storage
