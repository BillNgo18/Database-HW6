# Homework 6 - Bookstore Database + Python CLI

Name: Bill Ngo

## Description
Harmony Pages is a bookstore database focused on music-related books. It includes categories such as biographies, learn-to-play books, music theory, and scores/collections. The project uses SQLite for database management and a Python command-line interface (CLI) to allow users to interact with the data.

## Files
- createTables.sql
- insertRows.sql
- bookstore.db
- bookstore_cli.py
- README.md

## How to Create the Database

Using the sqlite3 command line:

```bash
sqlite3 bookstore.db < createTables.sql
sqlite3 bookstore.db < insertRows.sql
