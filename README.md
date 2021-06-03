# Database-
<h1>EmployeeDatabase Form</h1>
  <h2> Description </h2>
  This Application is all about the CRUD operation performed in the *JsonPowerDB* and how to use the JsonPowerDB
  Don't worry if not knowing about it, do visit our website https://login2explore.com/jpdb/
  
  <h3>Benefits of using JsonPowerDB</h3>
    * JsonPowerDB is a Database Server with Developer friendly REST API services:
    
     * High Performance 
     * Light Weight, Ajax Enable
     * Serverless
     * Simple to Use
     * Real-time Database
     * Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.
     
<h3>Release History</h3>    
> 0.3.2 / 2021-04-10
==================

* Added : New type "REMOVE" in Set API for delete operations, in compliance with RDBMS constraints.
* Added : New response headers that display time taken by the JPDB server to serve request.
* Added : ForeignKeys functionality in SET and SET_ALL API to provide complete support for the soft implementation of RDBMS.
* Added : Started Reporting of All Unhandled Exceptions via email.
* Added : A new version of jpdb-commons.js 0.0.4 added with SET & SET_ALL methods and help for all commands
* Improved : Parsing time for request now reduced.
* Improved : Response message for syntax error in case of empty body in request.
* Improved : Known exception handling.
* Improved : Help Documentation.
* Improved : jUnit Test Cases.
* Various bug fixes.

> 0.3.2 / 2020-10-08
==================

* Added : Added Plugin API Framework in JsonPowerDB.
* Added : Added a new class APISyntaxValidator to check syntax of request json.
* Added : Added a new APIs for column operation and implement it using pluggable framework:
             Copy Column - It will copy column in database.
             Rename Column - It will rename column in database.
             RemoveColumn - It will remove column in database.
             Change Column type - It will change type of column in database.
* Improved : In Geospatial distance API to pick create time column (sorted in ascending) as time range 
             (by default it should pick the record creation time from the JPDB system file internal 
             recorded time) defined in request fromTime to toTime.
* Fixed : Fixed important bugs.  

> 0.3.2 / 2018-11-27
==================

 * Added: New implementation of JsonPower SQL Query using HTTP REST API.
    - User can now query their data using JsonPower SQL Query which is :
       - Easy To understand.
       - Fast.
 * Added: Added support to generate a new connection-token.
    - To use it directly in any application to access JPDB IML, IRL, IDL, ISL and serverless api.
    - Increase security of data as user does not need to provide his user-id and password. 
 * Added: Added support for creating new column in UPDATE command.
 * Added: Added support to get workspace name and workpspace ID of a given workspace in key-value DB.
 * Added: Added support to set or change the time limit for user-token.
 * Improved: Improved the performance of Backup, PUT and PUTALL command, Commit and Recovery.
 * Changed: UI of "User Tools" & "Company-Settings".
 * Fixed: Important bugs.

<h3> Output</h3>
![emp](https://user-images.githubusercontent.com/71522972/120610539-e8707f00-c470-11eb-8f6a-96019d126d48.png)
![emp1](https://user-images.githubusercontent.com/71522972/120610552-ec040600-c470-11eb-8fca-fec901a0ddb6.png)
![emp2](https://user-images.githubusercontent.com/71522972/120610571-eefef680-c470-11eb-8c81-e30cda92ae42.png)
![result](https://user-images.githubusercontent.com/71522972/120610578-f1f9e700-c470-11eb-933d-325be57bfda2.png)

