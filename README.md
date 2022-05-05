# JsonPowerDB

JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database.

Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

0.3.2 / 2021-12-03
==================

* Added: New DBMS mode (pluggable) to upload, download and manage files and folders i.e. "PowerDrive" introduced.
* Added: ExecTime, ReqResTime, and ParseTime for all KvpDB APIs.
* Added: Methods for uploading, unloading, reloading & removing plugin apis in running JPDB instance.
* Added: ServerTime, execTime, parseTime, reqResTime with all JPDB responses.
* Added: Plugin API dashboard with upload, view, enable, disable and remove functionalities.
* Added: Plugin API tab in company dashboard to upload pluggable apii.
* Added: Serverless counter API, INIT command - alternative to incValue is now initValue.
* Added: documentation for Drive APIs.
* Improved: In IDL command, "ADD_INDEX" and "REMOVE_INDEX" command names are improved to "INDEX_COLUMN" and "UNINDEXED_COLUMN" respectively.
* Improved: API "send_email" validates email addresses for- to, cc, and bcc in JsonPowerDB.
* Improved: Error mail interval is reduced and can be set from the company dashboard.
* Improved: Type "REMOVE" for SET and SET_ALL cmd that will also check foreign Keys reference in other relations before removing from a given relation.
* Improved: First version of new jpdb-commons.js for version 0.0.5 created from 0.0.4
* Fixed: Various Important bugs fixed.


            
