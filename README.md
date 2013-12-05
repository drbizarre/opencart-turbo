Opencart Turbo
==============

Version: 0.1  
Developed by Atomix  
http://www.atomix.com.au  


This script will apply several changes to boost the performance of OpenCart, including:
*   DONE: Convert MySQL DB Storage Engine from MyISAM to InnoDB
*   DONE: Add indexes to all foreign keys (columns ending with '_id')
*   TODO: Delete Script Function
*   TODO: Replace config.php and admin/config.php with dynamic Git-friendly version
*   TODO: Accurately Detect and Remove Demo Data
*   TODO: Remove Unwanted Zones

###Notes###
*   This script should be deleted immediately following use  
*   This script should be run again following OpenCart upgrades (as the optimizations will be removed during upgrade)  

###Installation###
1.  Upload **turbo.php** to your OpenCart root directory (next to config.php).  
2.  Load **http://yoursite/turbo.php** in your browser and follow the instructions on screen.  
