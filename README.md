Creating services:

```
cf create-service google-cloudsql-postgres postgres-db-f1-micro PG-slavek-flask-cf-sample
cf cups JUST_TESTING -p '{"username":"admin","password":"pa55woRD"}' -t "tag1,tag2"
```
