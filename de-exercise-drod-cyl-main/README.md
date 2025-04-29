# data-engineering-exercise
## Cylinder Health Interview Exercise for the Role of Data Engineer

## Setup

### A local DB
A local PostgreSQL database is required to run this dbt project. The easiest way to get one running is likely:
1. Run `docker compose up` in the root directory
2. You should now be able to login to [pgAdmin](http://localhost:5050/) with the following:
    - username: `pgadmin@Cylinderhealth.interview`
    - password: `pw`
- And connect to the running PostresDB with the following:
    - hostname: `postgres-local`
    - username: `postgres`
    - password: `admin`

(or if you wanted to install PostgreSQL locally, read [this](./LocalPostgresDBInstallation.md))

### Run DBT:
1. Seed the database: `dbt seed`
   1. NOTE: This may take up to 5 minutes
2. Run dbt: `dbt run`
3. Test dbt: `dbt test`

## Exercise Instructions

Access to the exercise [instructions](https://docs.google.com/document/d/1-WJBcnAlx2qGb1ZyIVAi-uA7-luG5pSSHK3OsyQ10kE/edit) will be granted during the live interview.
