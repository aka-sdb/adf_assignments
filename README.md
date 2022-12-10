# adf_assignments

Scenario 1:
Assume that you have one table in your database which is getting updated very frequently.
You are moving the data from this table to cloud blob storage. You have been asked to sync the data on daily basis.
Use the highwater mark concept to create the incremental pipeline.
Instead of creating the highwater file, try to keep the highwater mark info within the database itself.

Scenario 2:
Assume that you have 3 tables in your database which is getting updated very frequently.
You are moving the data from these 3 table to cloud blob storage. You have been asked to sync the data on daily basis.
Use the highwater mark concept to create the incremental pipeline.
Instead of creating a separate pipeline try to create one generic pipeline to handle this scenario.
