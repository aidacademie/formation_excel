# VLOOKUP (short of "vertical" look up)
* VLOOKUP function works only with data organised into columns. 
* VLOOKUP function performs a vertical lookup by searching for a value in the first column of a table and returning the value in the same row in the index_number position

## Function = VLOOKUP( value, table, index_number, [approximate_match] )
* value
The value to search for in the first column of the table.
* table
Two or more columns of data that is sorted in ascending order.
* index_number
The column number in table from which the matching value must be returned. The first column is 1.
* approximate_match
Optional. Enter FALSE to find an exact match. Enter TRUE to find an approximate match. If this parameter is omitted, TRUE is the default.
