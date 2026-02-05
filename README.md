SQL Learning Project

A simple SQL project for learning database operations with SQLite.


FILES

SCHEMA.SQL          - Creates the database tables
SAMPLE.DATA.SQL     - Inserts sample data
BLOCKED_INVENTORY.sql - Query to analyze blocked inventory


TABLES

ORDER_DATA       - Purchase order transactions
INVENTORY_DATA   - Blocked inventory records
MATERIAL_MASTER  - Product/material reference data


QUICK START

1. Create database and load data:
   sqlite3 inventory.db < SCHEMA.SQL
   sqlite3 inventory.db < SAMPLE.DATA.SQL

2. Run a query:
   sqlite3 inventory.db < BLOCKED_INVENTORY.sql


CONNECT TO DBEAVER

1. Open DBeaver
2. New Connection and select SQLite
3. Browse to inventory.db
4. Click Test Connection then Finish
