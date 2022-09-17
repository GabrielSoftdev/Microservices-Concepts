
# Microservices with NodeJS and React and Typescript

Uma breve descrição sobre o que esse projeto faz e para quem ele é




## Data management between services
- Each database gets its own database (if it needs one)
- Services will never, ever reach into another services database


## Why Database-Per-Service
- We want each service to run independently of other services
- Database schema/structure might change unexpectedly
- Some services might function more efficiently with different types of DB's (SQL vs noSQL)

## Communication Strategies Between Services
- #### Sync: 
    - Services Communicate with each other using direct requests
- #### Async:
    - Services Communicate with each other using events


