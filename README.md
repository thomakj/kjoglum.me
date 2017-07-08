# kjoglum.me

## Design

kjoglum.me -> VPC

--------  VPC           -------
(:* )West US
(:22 :80 :443) Elastic Load Balancing
(:22 :80 :443) Web Server (EC2 instance)
--------                -------

--------  Web Server    -------
(:80 :443) nginx
localhost:8080 Jenkins
--------                -------
