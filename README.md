## Udacity Microservices Project

#### Overview

This is an Instagram-like application that consists of four micro-services: udagram-frontend, reverseproxy, udagram-api-feed, and udagram-api-user.

All the four micro-services are containerized, and can be deployed by docker-compose and kubectl.

#### Getting started (k8s)

1. Set up S3, Postgres, and EKS.
2. Create aws-secret.yaml and env-secret.yaml, which define the following environment variables:
- POSTGRES_USERNAME
- POSTGRES_PASSWORD
- POSTGRES_DB
- POSTGRES_HOST
- AWS_REGION
- AWS_PROFILE
- AWS_BUCKET
- JWT_SECRET
3. Apply all the files under k8s folder in order.
4. Portforward the reverseproxy and frontend services.
