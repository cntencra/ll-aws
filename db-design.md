# Databases

Good book for info:
designing data intensive applications

## Criteria

- What Data
- How much
- write throughput
- Read throughput
- uptime

## Relational

Real time access for a months worth of data

## Big Data

Historical data for reporting


## Queues

For ingesting large amount of data into relational dbs

A queue stores the data you need to write

- SQS Simple Queue Service more populare, simpler, more expensive if there are lots of events
- Kinesis handles a large stream of incoming data, can also connect to other sources
- SNS Simple Notification Service pushes out a message email, https request,

## NOSQL

https://aws.amazon.com/nosql/   

data is object based and doesn't need reporting

## Using DBs

You could just spin up an ec2 instance running MYSQL

What is failover replication

You are responsible for managing lots of things

## RDS Relational Database Service

Manage everything for you. Supports Postgres etc

Start small and scale up. You cannot scale back down an rds instance

## In memory caches

### Elasticahce

Helps you manage and deploy the two of the most common types of in memory caches

- Redis
- meme cache

can install this on ec2 or use elasti cache


## Big Data Store


### data lake

- contains every bit of data ever collected for your application
- this is unstructured data maybe text csvs or web server logs

only charge for the queries

## Data warehouse

Redshift

- structured data
- optimised for very large data sets

more costly

