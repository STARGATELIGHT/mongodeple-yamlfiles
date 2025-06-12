yaml files for mongoDB-deployment, service.yaml as well as secretes.yaml
Access Mongo Express on port 80 via mongo-express-service.

Auth is set to username admin, password admin123.

The MongoDB host is passed via a ConfigMap (mongodb-service must be the name of the MongoDB service).


Mongo Express connects to MongoDB using root credentials from the mongodb-secret.

The MongoDB hostname is pulled from the mongo-express-config ConfigMap.

Exposed internally via mongo-express-service on port 80.
