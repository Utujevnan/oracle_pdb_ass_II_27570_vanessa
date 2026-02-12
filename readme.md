# Oracle PDB Assignment II - Vanessa 27570

## Overview
This repository contains my practical work for **Oracle Pluggable Database (PDB) Management**, as part of the INSY 8311 course. The purpose of this assignment is to demonstrate skills in creating, managing, and deleting PDBs, as well as using Oracle Enterprise Manager (OEM).

## Oracle Environment
- Oracle Database 19c (19.3.0.0.0) Enterprise Edition  
- Windows 10 x64  
- SQL*Plus and Oracle Enterprise Manager Express (EM Express)

---

## Task 1: Create a New Pluggable Database

**PDB Name:** `VA_PDB_27570`  
**User inside PDB:** `VANESSA_PLSQLAUCA_27570`  
**Password:** `Oracle123`

**Steps performed:**
1. Checked existing PDBs.
2. Created new PDB using `CREATE PLUGGABLE DATABASE`.
3. Opened the PDB.
4. Created user inside the PDB.

**Screenshots:**
- ![Check Existing PDBs](screenshots/01_check_PDBs.png)  
- ![PDB Creation Command](screenshots/02_create_PDB.png)  
- ![PDB Open State](screenshots/03_open_PDB.png)  

---

## Task 2: Create and Delete a Temporary PDB

**Temporary PDB Name:** `VA_TO_DELETE_PDB_27570`  

**Steps performed:**
1. Checked container before creating temporary PDB.  
   - ![Check Container](screenshots/Task2_01_Check_Container_27570.png)  
2. Created temporary PDB.  
   - ![Temp PDB Created](screenshots/Task2_02_TempPDB_Created_27570.png)  
3. Opened temporary PDB to confirm creation.  
   - ![Temp PDB Opened](screenshots/Task2_03_TempPDB_Opened_27570.png)  
4. Dropped temporary PDB completely.  
   - ![Temp PDB Dropped](screenshots/Task2_04_TempPDB_Dropped_27570.png)  
   - ![VA_TO_DELETE_PDB Screenshot](screenshots/VA_TO_DELETE_PDB_27570.png)  

---

## Task 3: Oracle Enterprise Manager (OEM)

**Steps performed:**
1. Opened EM Express via browser: `https://localhost:5500/em`  
2. Logged in using:  
   - Username: `sys`  
   - Password: `Oracle123`  
   - Connect As: `SYSDBA`  
   - Container: `CDB$ROOT`  
3. Confirmed database environment and status.

**Screenshot:**  
- ![OEM Dashboard](screenshots/Task3_OEM_Dashboard_27570.png)  

---

## Challenges Faced
 
- SYS user password was initially unknown; had to reset it.  
er.  
- PDB not immediately visible in EM Express; had to rely on SQL*Plus verification.

---

## Integrity Statement
I confirm that all work in this repository is my own and reflects my **individual effort**, following the course’s academic integrity guidelines.

---
