# University Database Queries
Created: 09/15/2018<br>
Latest Update: 09/15/2018<br>
By: Can Bekleyici - bekleydata.com<br>

## Introduction
This project goes through the complete process of creating a database and performing SQL queries in Python using the SQLAlchemy package. In this example, a university database, that includes tables for <code>teacher</code>, <code>student</code>, <code>course</code>, and their relations <code>teaches</code> and <code>takes</code>, have been created using the Database Management System (DBMS) <code>PostgreSQL</code>. The database has then been filled with "dummy data" in order to perform different SQL queries on single and multiple tables.

SQLAlchemy is a SQL toolkit for Python, created by Mike Bayer (see the repository here: https://github.com/zzzeek/sqlalchemy ).

## Prerequisite
### Files that are included:
<ul><li><code>university_db_query.html</code> - the full report as an HTML file</li>
  <li><code>university_db_query.ipynb</code> - a JSON formatted notebook file for usage in Jupyter Notebook</li>
  <li><code>environment.yaml</code> - the developement environment containing package and version informations that has been used for this project</li>
  <li><code>requirements.txt</code> - all packages and their versions that has been used for this project, listed in a txt-file</li></ul>

### Installation:
In order to run the project on <code>Anaconda</code>, you will need to download the files <code>university_db_query.ipynb</code> and <code>environment.yaml</code> and save them in the same directory. You may also need Anaconda and PostgreSQL installed on your computer (download link: <url>https://www.anaconda.com/</url> | <url>https://www.postgresql.org/</url>). Next, you will have to navigate with the <code>Anaconda Prompt</code> to the directory of the files. Create the environment using <code>conda env create -f environment.yaml</code> and activate it with <code>activate py3</code>. Now you can open the notebook by typing in <code>Jupyter Notebook</code> and run the IPYNB file from there.

### Without Installation:
You can just view the complete analysis and the used code from the included HTML file <code>university_db_query.html</code> or the notebook file <code>university_db_query.ipynb</code> using GitHub's built-in notebook reader without any installations.
