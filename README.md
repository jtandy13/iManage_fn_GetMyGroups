# iManage_fn_GetMyGroups.sql
Function to return all groups that a users belongs to.

It's very easy using the database administration tools provided by iManage to see which users belong to which groups. Unfortunately, they don't give the same option to select a user and see all of the groups that he/she belongs to. The function provided here takes the userid as the only parameter and returns the group name and id number.
