Hey SQL enthusiasts!,

Here, I am sharing the solutions from the LeetCode Study Plan SQL 50! These exercises offer a fantastic opportunity to hone your SQL skills from basic to intermediate level.

Let's break down some of the important functions, commands and keywords used in these solutions:

**Select Statements**
-	𝗦𝗘𝗟𝗘𝗖𝗧: The fundamental keyword in SQL, used to retrieve data from a database.
-	𝗪𝗛𝗘𝗥𝗘: Used to filter rows based on a specified condition.
-	𝗙𝗥𝗢𝗠: Specifies the table(s) from which to retrieve data.
-	𝗔𝗡𝗗: A logical operator used to combine multiple conditions in a WHERE clause, where all conditions must be true for the row to be selected.
-	𝗢𝗥: Another logical operator used to combine multiple conditions in a - WHERE clause, where at least one condition must be true for the row to be selected.
-	𝗢𝗥𝗗𝗘𝗥 𝗕𝗬: Sorts the result set based on specified columns in ascending or descending order.
-	𝗡𝗢𝗧 𝗘𝗤𝗨𝗔𝗟 (<>): Compares values to determine if they are not equal, offering flexibility in data comparisons.
-	𝗜𝗦 𝗡𝗨𝗟𝗟: An operator used to check if a value is NULL.

**Basic Joins**
-	𝗚𝗥𝗢𝗨𝗣 𝗕𝗬: Used to arrange identical data into groups, often combined with aggregate functions to produce summary results.
-	𝗝𝗢𝗜𝗡: Combines rows from two or more tables based on a related column between them.
-	𝗜𝗡𝗡𝗘𝗥 𝗝𝗢𝗜𝗡: Returns records that have matching values in both tables.
-	𝗟𝗘𝗙𝗧 𝗝𝗢𝗜𝗡: Returns all records from the left table and matched records from the right table. Unmatched records from the right table will be NULL.
-	𝗖𝗥𝗢𝗦𝗦 𝗝𝗢𝗜𝗡: Produces the Cartesian product of the two tables, meaning it returns all possible combinations of rows from the tables.
-	𝗗𝗔𝗧𝗘𝗗𝗜𝗙𝗙: Calculates the difference between two dates, often used to measure time intervals.
-	𝗥𝗢𝗨𝗡𝗗: Rounds a number to a specified number of decimal places.
-	𝗔𝗩𝗚: Calculates the average value of a numeric column.
-	𝗛𝗔𝗩𝗜𝗡𝗚: Similar to WHERE, but used with aggregate functions to filter groups of rows.
-	𝗖𝗢𝗨𝗡𝗧: Returns the number of rows that match a specified condition.

**Basic Aggregate Functions**
-	𝗗𝗘𝗦𝗖: Sorts the result set in descending order.
-	𝗔𝗦𝗖: Sorts the result set in ascending order (It is the default value for the ORDER BY clause).
-	𝗥𝗢𝗨𝗡𝗗(): Rounds a number to a specified number of decimal places.
-	𝗦𝗨𝗠(): Calculates the total sum of a numeric column.
-	𝗠𝗜𝗡(): Retrieves the minimum value from a specified column.
-	𝗜𝗙(): Returns a value if a condition is TRUE, and another value if the condition is FALSE.
-	𝗗𝗜𝗦𝗧𝗜𝗡𝗖𝗧: Selects unique values from a column.
-	𝗗𝗔𝗧𝗘_𝗔𝗗𝗗(): Adds a specified time interval to a date.

**Sorting and Grouping**
-	𝗗𝗔𝗧𝗘_𝗦𝗨𝗕(): Subtracts a specified time interval to a date.
-	𝗠𝗔𝗫(): Retrieves the maximum value from a specified column.

**Advanced Select and Joins**
-	𝗨𝗡𝗜𝗢𝗡: Combines the result set of two or more SELECT statements.
-	𝗠𝗔𝗫: Returns the largest value.
-	𝗟𝗜𝗠𝗜𝗧: Specifies the number of records to return.
-	𝗖𝗧𝗘 (𝗖𝗼𝗺𝗺𝗼𝗻 𝗧𝗮𝗯𝗹𝗲 𝗘𝘅𝗽𝗿𝗲𝘀𝘀𝗶𝗼𝗻𝘀): Result set of a query which exists temporarily and for use only within the context of a larger query.

**Subqueries**
-	𝐍𝐎𝐓 𝐍𝐔𝐋𝐋: An operator used to check if a value is NULL.
-	𝐍𝐔𝐋𝐋: Represents missing or undefined data in a table.
-	𝐂𝐀𝐒𝐄: A conditional expression used to create different outputs based on given conditions.
-	𝐖𝐇𝐄𝐍: Used within CASE to define a condition and corresponding result.
-	𝐔𝐍𝐈𝐎𝐍 𝐀𝐋𝐋: Combines the result sets of two queries, including duplicates.
-	𝐋𝐈𝐊𝐄: Searches for a specified pattern in a column, commonly using % or _ wildcards.
-	𝐃𝐄𝐍𝐒𝐄_𝐑𝐀𝐍𝐊: Assigns a rank to each row in a result set, without skipping ranks for duplicate values.

**Advanced String Functions / Regex / Clause**
-	𝐂𝐎𝐍𝐂𝐀𝐓: Combines two or more strings into a single string.
-	𝐔𝐏𝐏𝐄𝐑: Converts all characters of a string to uppercase.
-	𝐋𝐎𝐖𝐄𝐑: Converts all characters of a string to lowercase.
-	𝐒𝐔𝐁𝐒𝐓𝐑𝐈𝐍𝐆: Extracts a portion of a string starting at a specified position and with an optional length.
-	𝐈𝐅𝐍𝐔𝐋𝐋: Returns a specified value if the expression is NULL, otherwise returns the expression.
-	𝐎𝐅𝐅𝐒𝐄𝐓: Skips a specified number of rows before starting to return rows.
-	𝐆𝐑𝐎𝐔𝐏_𝐂𝐎𝐍𝐂𝐀𝐓: Concatenates values from a group into a single string with a specified separator.
-	𝐁𝐄𝐓𝐖𝐄𝐄𝐍: Filters the result set for values within a specified range.
-	𝐑𝐄𝐆𝐄𝐗𝐏: Filters the result set using a regular expression pattern.

These commands and keywords form the backbone of SQL queries, allowing us to manipulate and extract data efficiently.

Thank You!
