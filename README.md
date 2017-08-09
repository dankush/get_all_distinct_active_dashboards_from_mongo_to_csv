## Tool for getting all sisense active dashboards to CSV

Steps:

1. Download this repository with zip option to your Sisense server.
2. Unzip the file.
3. If you have Sisense version 6.7 and above, make sure you create WriteUser for accessing your mongo.  
	https://documentation.sisense.com/accessing-sisense-application-database
4. Open mongo authentication configuration file ("sisense_mongo_authentication.ini") 
5. Update your mongo user and password as required.
6. Run "get_all_distinct_active_dashboards_from_mongo_to_csv.exe" 
7. Go to the desktop and explore your CSV
