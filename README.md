# Production Data Analysis
Record of production flaws 
This file is designed for analyzing production waste. 
The operator is helped by the automatic filling of the master data, so they only need to enter the quantity produced by the machine and the quantity of defects, divided by type, found during processing. 
Connecting it to PowerBI, it would be better not to have pre-made groupings, but having one row per product would be cumbersome to fill out, and with large productions, it would result in a very heavy Excel file. 
Imagine asking seven operators to fill out this file on seven different machines for each shift, with each machine producing at least 7,000 pieces per shift. Over two shifts, the Excel file would have 98,000 rows by the end of the day. Also, imagine having to expand the table first by 259 cells, then by another 130, then by 347, and so on. To solve this problem, I find it convenient to have the same file on each machine, so there are multiple lightweight files instead of one heavy file.
Also, by having a file for each machine instead of one shared file, it eliminates the risk that an operator might accidentally fill in someone else's row.