# WalmartVirtual-experience-program
Completed the Advanced Software Engineering Job Simulation where I solved some technical projects for a variety of teams at Walmart.

Your task is to insert all of the data contained in the provided spreadsheets into the SQLite database. You will write a Python script which:

Reads each row from the spreadsheets.
Extracts the relevant data.
Munges it into a format that fits the database schema.
Inserts the data into the database.
Spreadsheet 0 is self contained and can simply be inserted into the database, but spreadsheets 1 and 2 are dependent on one another. Spreadsheet 1 contains a single product per row, you will need to combine each row based on its shipping identifier, determine the quantity of goods in the shipment, and add a new row to the database for each product in the shipment. The origin and destination for each shipment in spreadsheet 1 are contained in spreadsheet 2. You may assume that all the given data is valid - product names are always spelled the same way, quantities are positive, etc. 

