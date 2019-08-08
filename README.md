## Requirement

- please forked this repo for practice
- use `MyBatis-Spring-Boot-Starter-Test` to implement `Repository` testing for follow test cases
- finish the implementation of test cases 

### test cases

We are building a employee management application, this application has `Employee` entity with fields `id`,`name`,`age`,`company_id` and `Company` entity with fields `id`,`name`,`address`. One `Company` can have many `Employee`

1. `Employee` can be fetched by `company_id`
2. `Company` can be fetched by `id` and include it owned `Employee` list 

##  Practice Output & Submit

- submit your git repo url to field `answer`

## Hint

- create `Entity` to present your data structure
- create `Repository` for MyBatis integration 
- create `Mapper` under resources package 
- write sql statements 
- use `Repository` for your business to access to database
- write `Repository` testing 

## How to use H2

- `schema.sql` will be loaded and init database when application is starting
- navigate to web console`http://localhost:8080/h2-console`
- put `jdbc:h2:mem:tws_persistence_db` in `JDBC URL` field

## Out of scope

- controller layer is not required
