# Data-Quality
Writing a piece of code to improve the consistency of a few fields of data

Work with three data fields in the attached csv file namely, 
areaLand column data
name column data
location column data

Work to be done on the data fields:
1. Create a set of data types for the data fields as highlighted in the html document. 
2. Work with the areaLand column data such that all values are replaced by corresponding float values. Keep in mind all kinds of data that might appear in the column. In case of a list as a value, make a decision on what value you want to retain. Justify your decision. 
3. Work with the name column data such that all values are replaced by list type data of corresponding value. 
4. Crossfield auditing: There are some columns that seem to have the same information. "point" seems to be the combination of "wgs84_pos#lat" and "wgs84_pos#long". Check whether that's true by writing a function check_loc
