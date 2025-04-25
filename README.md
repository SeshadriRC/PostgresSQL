# PostgresSQL

1. What is the default Port of Postgres database?

5432

2. What is the master process in Postgres?
   
Postmaster

3. Oracle to Postgres backgroud process comparison
   
Log writer -> WAL Writer

Databse writer -> Background writer

User process -> Backend Process

4. Postmaster in Postgress

Loads configuration files and initializes shared memory segments

Recovers database after crash recovery

similar to listener process in oracle, to accept incoming connections

5. Oracle to Postgres comparison
    
Redo log Buffer -> WAL buffer

sort_area_size -> work_mem

Buffer cache -> shared buffer

6. Postgres Database Cluster
    
It is a group of databases running out of a particular PGDATA







