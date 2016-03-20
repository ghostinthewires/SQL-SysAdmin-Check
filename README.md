# Checking for users with sysadmin privileges #

One thing I like to do occasionally, or when “inheriting” a new SQL server, is to check which users have sysadmin privileges. As these users have access to perform any activity in SQL Server it’s important to keep the number of these users to a minimum especially on production systems. 

The **SysAdminCheck.sql** script will do this for you.