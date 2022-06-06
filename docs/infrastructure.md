## Udagram
## Infrastructure

![Structure](structure.png)

### AWS SERVICES
#### FRONTEND On S3 Bucket [udcfullstackdeploy]
The frontend application is deployed on AWS S3 Bucket which is publicly readable.

the application frontend is accessible from the bucket URL.

Bucket URL: `http://udcfullstackdeploy.s3-website-us-east-1.amazonaws.com`

#### RDS Postgres
The application server uses AWS RDS Postgres as database server.

Database URI: `postgresql://postgres:udc123456@udcfullstackdeploydb.c0gpxe9nwgsx.us-east-1.rds.amazonaws.com`

#### The application uses Elastic Beanstalk as web server
The application api server is built and deployed on AWS Elastic Beanstalk service and accessible through the following URI. 

EB URL: `http://udcfullstackdeploy-env-1.eba-xfmrpppw.us-east-1.elasticbeanstalk.com/`

