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

7. How to find the pgdata location

   Type --> ps -ef|grep postgres, from there you can see ( /var/lib/pgsql/15/data )
   
   Here you can find the file pgsql.conf

   whenever you edit the file pgsql.conf, we need to restart the services using pg_ctrl restart

8. What is pg_ctl

   pg_ctl is a command-line utility used to control the PostgreSQL database server (postgres).

   pg_ctl restart

9. Which RPM contains Postgres extensions supported officially:

   postgresql5-contrib.x86_64

10. Which RPM is used for developing applications that interact with PostgreSQL.

   postgresql5-devel.x86_64





