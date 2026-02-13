# Oracle Pluggable Database (PDB) Management – Assignment II
Student ID: 27435  
Student Name: Manzi  

---

## Assignment Objective

This assignment demonstrates practical understanding of Oracle Multitenant Architecture, including:

- Creation of a Pluggable Database (PDB)
- User creation inside a PDB
- Creation and deletion of a temporary PDB
- Usage of Oracle Enterprise Manager (OEM)
- Professional documentation using GitHub

---

## Oracle Environment Used

- Oracle Database 21c
- Oracle SQL Developer
- Oracle Enterprise Manager Express (EM Express)
- Operating System: Windows

---

# Task 1: Creation of Main Pluggable Database

## PDB Details

PDB Name: `ma_pdb_27435`  
Username Created: `manzi_plsqlauca_27435`  
Password: (Configured during creation)

## Steps Performed

1. Connected to the CDB as SYS with SYSDBA privileges.
2. Created the PDB using the required naming convention.
3. Opened the PDB in READ WRITE mode.
4. Switched session to the new PDB.
5. Created the required user inside the PDB.
6. Granted CONNECT and RESOURCE privileges.
7. Verified successful creation using system views.


---

# Task 2: Creation and Deletion of Temporary PDB

## Temporary PDB Name

`ma_to_delete_pdb_27435`

## Steps Performed

1. Created temporary PDB from CDB$ROOT.
2. Verified its existence in v$pdbs.
3. Closed the PDB.
4. Dropped the PDB including datafiles.
5. Verified complete deletion.



---

# Task 3: Oracle Enterprise Manager (OEM)

Oracle Enterprise Manager Express was accessed through:https://localhost:5500/em


## Actions Performed

1. Logged in as SYS (SYSDBA).
2. Verified CDB and PDB status.
3. Confirmed `ma_pdb_27435` is in READ WRITE mode.
4. Confirmed database environment configuration.

## Evidence

all screenshot are provided in the screenshot folder






