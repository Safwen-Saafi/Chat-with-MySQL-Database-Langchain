# Introduction

A simple Python notebook file that allows you to chat with a MySQL database using Python and LangChain. I used the LangChain wrapper of sqlalchemy to interact with the database including also the langchain package to create a custom chain that will allow you to chat with the database using natural language.

***Note:*** I'm gonna say it from the beginning, this project requires a paid version of the ChatGPT subscription in order to generate the SQL Queries and the response, useless to use a free API Version. You'll get an error response "Quota exceeded".

---

<br/>

# Prerequisites

- Anaconda for virtual environment setup

- MySQL installed
  
---
<br/>

# Configuring DataBase

First download a database, you can use this [one](https://github.com/lerocha/chinook-database/releases/download/v1.4.5/Chinook_MySql.sql.).

Create a database inside your MySQL command line client, for example:

```
CREATE DATABASE chinook;
USE chinook;
SOURCE chinook.sql; #or just drop the database file inside the cli
```

---

<br/>

# Configuring Anaconda:

Activate your conda environment, if not available create one.

Install these dependencies :


```
 conda install langchain langchain-openai mysql-connector-python

```

---

<br/>

# Note:

Don't forget to put your `API-Key`, the `database name` and `password` when connecting to the database.

<br/><br/>


<p align="center">Developed with ❤️ by SafSaf</p>
