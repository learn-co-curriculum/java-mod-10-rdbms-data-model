# RDBMS Data Model with PostgreSQL

## Learning Goals

- What data models and structures RDBMS use

## Introduction

When software developers hear the term Database, the systems most tend to think of are those classified as RDBMS(Relational DataBase Management System).
These have been the predominate type of Data storage and retrieval systems in use until recently. When new challenges were encountered with Cloud and massive Web scale applications,
development of newer type Data storage and retrieval systems took place to solve for these unique situations. These newer class of systems are colloquially know as NoSQL systems.

We will be exploring what makes Data storage systems Relational in this section, and will be utilizing the popular Database system PostgreSQL(also commonly seen as Postgres, PG, PSQL).
More importantly, we will be covering how to utilize these systems quickly and easily in you own code development practices using more recent DevOps toolsets and practices.

## What Data Models and Structures RDBMS Use

If you've developed for some time with any low-level programming language, or have ever taken any traditional Computer Science classes in Data Structures, you can
probably conceptualize to some degree the purpose of implementing Data Structures in any given computer program. At the most abstract, you can think of them as
ways to store and structure data, while optimizing some types of computation and retrieval for a given task. More common data structures you may have seen references to include linked lists, binary trees,
and hash trees.

While these all have their use cases when embedded directly into their respective applications, we need to start designing these data systems with different considerations
once we start migrating data out of the application for shared use. All of the abstract concepts still apply, however we now become just as concerned with interoperability,
stability, integrity, and compliance with well know and used standards.


For an overview of the core concepts we will be applying, you can read through the following documentation

- [Introduction to Relational Databases](https://mariadb.com/kb/en/introduction-to-relational-databases/)
- [Understanding Relational Models](https://mariadb.com/kb/en/understanding-the-relational-database-model/)
- [Basic RDBMS Terms](https://mariadb.com/kb/en/relational-databases-basic-terms/)
- [Table Keys](https://mariadb.com/kb/en/relational-databases-table-keys/)
- [Foreign Keys](https://mariadb.com/kb/en/relational-databases-foreign-keys/)
- [Normalization Overview](https://mariadb.com/kb/en/database-normalization-overview/)

- [Indexes Introduction](https://postgresql.org/docs/current/indexes-intro.html)
- [Index Types](https://postgresql.org/docs/current/indexes-types.html)


If you are already familiar with this content, or finish up early, continue browsing through these two documentation sites. The MariaDB documentation tends to be more
accessible and is mostly applicable with Postgres, while the Postgres documentation is a little more difficult to follow but is the authoritative source for the Postgres system.
