#  DevOps FAQ
A list of questions covering various topics in DevOps.


- [Mansion](#mansion)
    - [Database](#database)

## Database

*There are various types of databases; relational databases, non-relational databases.
Here are some questions pertaining to databases*

**1. Qns**:\
Is sql the default query language to write database?

**Ans**:\
To `write` to database.
SQL is the default language for SQL database.

--

**2. Qns**:\
Would it be more accessible for deployment if I
write sql database in container instead of maintaining
it in a sql cloud or local environment?

**Ans**:\
Only use container to solve the problem of different environment.

Database containerization provide scalability, and matched well with Devops process.
It is currently gaining popularity and becoming an on-demand utility as part of the shift toward microservices and
serverless architectures. However, there are some challenges to it. Do research it if you require more info.

--

**3. Qns**:\
Devops need to learn SQL as one of their operating languages?

**Ans**:\
It's good to know. Linux is an operating system, not a programming language
Python is the default programming language for DevOps to use for scripting.
SQL is the querying language to talk to SQL database.

--

**4. Qns**:\
For horizontal scaling of PostGreSql
Must all the servers be postgresql? or can be different?

**Ans**:\
Postgres is a type of SQL server. Yes, it must all be Postgres.
For simple setup, all database should be of the same type
If you are using different databases, it must be for specific reasons.
ie a particular feature in the entire app itself. like timeline

--

**5. Qns**:\
what is data cleansing?

**Ans**:\
Data cleansing is to clean up data to remove things like white spaces, weird symbol like `" %`,
make sure the data is in the right format and other things like change string to integer. `"$18"` is a string.
Change to `18` as integer

--

**6. Qns**:
