# migration-db2-iris
Sample repository to show how to migrate from MySQL to InterSystems IRIS


# to run
1. Build
```
docker-compose build
```
2. Run
```
docker-compose up -d
```
3. Use DBeaver to connect to the databases
    - **Connection to DB2**: 
        - Host: localhost
        - Port: 50000
        - Database: sample
        - Username: db2inst1
        - Password: password
    - **Connection to IRIS**: 
        - host: localhost 
        - database: user 
        - port: 1972 
        - username: _SYSTEM 
        - password: SYS