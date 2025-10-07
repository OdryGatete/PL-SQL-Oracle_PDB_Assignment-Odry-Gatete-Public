# Oracle PDB Report
# Student name : Gatete Odry
# student Id : 28450
# Course: PLSQL and Database Administration 

 **Step 1** Overview of Tasks :

This practical assignment focused on learning how to create, delete, and monitor Pluggable Databases (PDBs) using Oracle 21c.
The tasks were divided into three main parts:

Task 1: Create a New Pluggable Database (PDB)

I created a new PDB named od_pdb_28450 using SQL commands.

I also created an administrative user odry_plsqlauca_28450.

The database was successfully created.

Task 2: Create and Delete a PDB

Another PDB was created with the name od_to_delete_pdb_28450.

After confirming its creation, I deleted it using the DROP PLUGGABLE DATABASE command.

Screenshots were taken before and after deletion to confirm the process.

Task 3: Configure Oracle Enterprise Manager (OEM)

I accessed Oracle Enterprise Manager Express (OEM) to manage and monitor the databases.

Although I could not log in using my PDB user, I successfully logged in as the SYSTEM user to view the PDBs.

The OEM dashboard screenshot was taken showing the configuration result.

Overall, the practical helped me understand the creation, deletion, and management of pluggable databases and how to monitor them using OEM Express.

**step 2** screenshots 


![Task 1](/image/task1.png)

Screenshot of task 1  showing the creation of the PDB 'od_pdb_28450' and verification using SHOW PDBS.
The PDB is successfully created and ready for use.


![Task 2](/image/Task%202%20.png)

Screenshot showing the creation of the PDB 'od_to_delete_pdb_28450'. and verification using SHOW PDBS
The PDB is successfully created 

![Task 2 Deletion](/image/Task%202.1.png)

Screenshot showing the deletion of the PDB 'od_to_delete_pdb_28450'.

![Task3](/image/Task3.1.png)

Screenshot of Oracle Enterprise Manager (OEM) dashboard.
Logged in as SYSTEM user, showing the container database and the PDB 'od_pdb_28450'


**issues and how I solved it** 


![Error](/image/Error%20Task.png)

Tried to close a PDB that was already in the CLOSED state.

**solution**

Checked the PDB status using SHOW PDBS.  
Skipped the close step because it was already closed, then dropped the PDB successfully using DROP PLUGGABLE DATABASE.








  

