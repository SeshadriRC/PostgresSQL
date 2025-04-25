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

11. What is the purpose of  initdb in Postgres?

  Initialize the cluster and populate PGDATA

12. From where can I get instructions to install postgres for my OS?

  Follow instructions from postgresql.org/download

13. High Level comparison of Oracle and Postgresql

![image](https://github.com/user-attachments/assets/b0650c42-9ea3-4b96-bb1a-f70e738c536d)
![image](https://github.com/user-attachments/assets/4be98716-66f8-44d7-a2fc-9dfefa1cc3b0)
![image](https://github.com/user-attachments/assets/4b017f62-d871-4b62-a636-d0b4d554b6d5)

14. Database Cluster and Instance

![image](https://github.com/user-attachments/assets/8e3c6043-405d-4e7c-a531-09bdab4c3732)
![image](https://github.com/user-attachments/assets/f080a769-240d-4b7d-ab21-4192933c6d1a)
![image](https://github.com/user-attachments/assets/0a81450a-ce48-4aec-a7d6-a99927232e04)

15. Check the memory

    ipcs -a

16. Process comparison in postgresql

![image](https://github.com/user-attachments/assets/c116a713-236e-4a53-907f-cae48ebfb3fc)

17. Functions of Postmaster

![image](https://github.com/user-attachments/assets/f81c3be1-4ed5-4ddc-ab80-512ed57d83c9)

18. Background process and its functions

![image](https://github.com/user-attachments/assets/0de56dcc-ca72-4884-b724-2b16529e1592)

19. Listener in postgres

![image](https://github.com/user-attachments/assets/c0b91abe-d49e-4844-b408-38a96313f766)

20. Memory comparison

![image](https://github.com/user-attachments/assets/2831bab2-6b38-48b4-8a6d-7deb0c6bcfcc)





















