# PostgresSQL

1. What is the default Port of Postgres database?
2. 
5432

3. What is the master process in Postgres?
   
Postmaster

5. Oracle to Postgres backgroud process comparison
   
Log writer -> WAL Writer
Databse writer -> Background writer
User process -> Backend Process

7. Postmaster in Postgress

Loads configuration files and initializes shared memory segments
Recovers database after crash recovery
similar to listener process in oracle, to accept incoming connections

9. Oracle to Postgres comparison
    
Redo log Buffer -> WAL buffer
sort_area_size -> work_mem
Buffer cache -> shared buffer

11. Postgres Database Cluster
    
It is a group of databases running out of a particular PGDATA







