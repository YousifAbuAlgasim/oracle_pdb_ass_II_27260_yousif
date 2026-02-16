# oracle_pdb_ass_II_27260_yousif
# Oracle Pluggable Database Assignment II
**Student Information**
Name: Yousif  
Student ID: 27260  

## Overview

This assignment focuses on understanding and applying Oracle Multitenant architecture through practical exercises. The main objective was to create and manage Pluggable Databases (PDBs), configure user accounts, and monitor the database environment using Oracle Enterprise Manager.

The tasks included creating a main PDB, managing a temporary PDB, accessing OEM, and documenting all activities using GitHub. This assignment helped improve my practical skills in Oracle database administration and system management.



 **Task 1: Main PDB Creation**
The main Pluggable Database `yo_pdb_27260` was created using SQL*Plus from the CDB root container. The database files were generated using the FILE_NAME_CONVERT parameter. After creation, the PDB was opened successfully and its state was saved.

The session was switched to the new PDB and verified using the SYS_CONTEXT function. A user named `yousif_plsqlauca_27260` was created and granted CONNECT and RESOURCE privileges.

The open status of the PDB was verified using the V$PDBS system view.



 **Task 2: Temporary PDB Creation and Deletion**
A temporary Pluggable Database named `yo_to_delete_pdb_27260` was created for testing purposes. The database was opened and verified using a query on the V$PDBS view.

After verification, the PDB was closed immediately and dropped using the INCLUDING DATAFILES option. A final verification was done to confirm that the PDB was removed successfully.



**Task 3: Oracle Enterprise Manager (OEM)**
Oracle Enterprise Manager Express was accessed through a web browser. The database dashboard displayed the Oracle XE environment, version information, and the number of Pluggable Databases. This confirmed that the created PDB was running correctly.

The dashboard also showed system status and performance information.

**Challenges Faced**
During the assignment, some issues were faced when switching between containers and configuring user access in OEM. These issues were solved by using SYSDBA privileges and carefully following Oracle Multitenant commands.

---


## Assignment Submission Checklist

✔ Main PDB created successfully (`yo_pdb_27260`)  
✔ Main PDB opened and state saved  
✔ User `yousif_plsqlauca_27260` created inside the PDB  
✔ Temporary PDB `yo_to_delete_pdb_27260` created  
✔ Temporary PDB verified using V$PDBS  
✔ Temporary PDB closed and deleted  
✔ Deletion confirmed using system query  
✔ Oracle Enterprise Manager (OEM) accessed successfully  
✔ OEM dashboard screenshot included  
✔ All screenshots uploaded inside the `screenshots` folder  
✔ GitHub repository set to PUBLIC  
✔ README file completed and organized  
✔ Submission link prepared for Google Form 

