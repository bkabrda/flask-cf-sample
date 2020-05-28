Creating services:

```
cf create-service google-cloudsql-postgres postgres-db-f1-micro PG-slavek-flask-cf-sample-new
cf create-service p.rabbitmq single-node-3.7 RMQ-slavek-flask-cf-sample-new
cf cups JUST_TESTING_NEW -p '{"username":"admin","password":"pa55woRD"}' -t "tag1,tag2"
```
