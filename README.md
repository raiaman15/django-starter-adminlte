## DJANGO-STARTER

### DEVELOPMENT SETUP
**Deleting Development Setup**
`docker-compose down -v`

**Creating Development Setup**
`docker-compose up -d --build`

### PRODUCTION SETUP
**Deleting Production Setup**
`docker-compose -f docker-compose.prod.yml down -v`

**Creating & Verify Prod Setup**
`docker-compose -f docker-compose.prod.yml up -d --build`

**Database (Postgres) Verification**
`docker-compose exec db psql --username=DB_USERNAME --dbname=DB_NAME`
`\l`
`\c DB_NAME`

### Reference URLs
- https://docs.docker.com/compose/django/
- https://testdriven.io/blog/dockerizing-django-with-postgres-gunicorn-and-nginx/

*NOTE: This is a starter template for django (version 2.2)*
