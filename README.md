# coding_10min_a_day-prep_for_capstone

# Begginer task 
setup environment/compiler and print out hello world

declare 2 string variables, 1 is hello, 1 is world, concatenate to say hello world

Trim whitespace from strings using built in function

uppercase-all and lowercase-all strings using built in function

capitalize(uppercase first letter of each word) strings using built in function

concatenate integer and string without getting an error

concatenate float and string without getting an error

contatenate boolean and string without getting an error

convert array to a comma separated string (array join)

split string using a delimiter

split string to an array of (single) characters

loop through a numeric array preferrably not using manual index increment

loop through a numeric array printing both the index and the value

split a name string into a char-array, then capitalize the first letter by overwriting char-array item zero, then reconstruct into a string

print a defined array, then remove the last item using array pop or equivalent

print array, and then push a new item using array push or equivalent

print out unique characters from a string using built-in array-unique function or it's equivalent

Ask for a input, print out the unique characters on that input

output a number, and wait for a keypress, then increment the number and print it out, then repeat

output fibonacci sequence (base 1) on each keypress

Ask for a number input, print an error when it's not a number using if else

Ask for a number input, throw an error if it's more than 100 or less than zero

Ask for a string input for numbers 1 to 10 in words (e.g. one, two...) then output it's translation in tagalog

(formerly day18) print out unique characters and their count on a string

Create function: add(x,y) that returns the sum of 2 numbers

Create functions: subtract(x,y), divide(x,y), multiple(x,y)

Create a function that will subtract y from x, but only until zero

Create a function square(x) that returns the square of the number

Create a function greatest(x,y,z) that returns which of the 3 given numbers are greater (using > or < signs)

Create a function roll() that generates 2 numbers between 1 to 6

print out current date/time

print out current date; then print out current time; using 2 separate function call, but outputting on the same line

print out current unix timestamp in seconds and milliseconds using built in functions if available

print out the current date time but with the specific format: Mon Jan 13 2025 14:54:30

output remaining seconds on the current day

get remaining milliseconds of current the day

get remaining microseconds of the current day

ask for a year input and output if it's a leap year or not using built in functions if possible

ask for date input and convert to unix timestamp

print out the date/time on New York City

add 1 hour interval to current time and output (date/time manipulation [oop??])

get date yesterday and output (date/time manipulation [substraction and rounding off])

attempt to list 24 timezones list (numeric array of objects/assoc array)

Censor the word fuck and dead with constant length asterisk

Censor bad words but with equal amount asterisk

Check if string contains '@'

Check if string contains '.'

Check if string contains '@' and '.' using regex

Check if the string matches email pattern .+\@.+\..+

Check if string contains at least 1 digit

Check if string contains at least 1 symbol

Check if string contains at least 1 upper case letter

Check if string contains at least 1 lowercase letter

Check if string contains 1 digit, 1 symbol, 1 uppercase letter and 1 lowercase and is more than 10 characters long

Check if string is 8 digits

Check if string contains 8 digits (even if there's dash)

Check if string contains 8 digits (even if there's dash, space or +)

Check if string contains 8 or 10 digits

Check if string contains 8 or 10 digits (even if there's dash, space or + parenthesis) (02) 8-555-6677

Check if string is 8 digits or 11 (09123456789)

Check if string is 8 digits or 11 or starting with +, plus 12 digits (+63)

Check if string has 8 digits, or 11 digits starting with zero, or string begins with +, and contains 12 digits; valid: 8812-5566; (0922)3334455; +63922-3334455

Ask for an input, but instead of echo-ing the output asterisk for each keypress

Ask for an input, and output asterisk for each character presses

Ask for an input, output asterisk for each char press, and support backspace

Ask for a password input and save to a variable (and print out)

Ask for a password input(with backspace support) and save to a txt file

Ask for a password input and save to a txt file as md5 hash

Ask for a password input and save to a txt file as sha1 hash

Ask for a password input and save to a txt file as sha256 hash

Ask for a password and validate using a stored hash on txt file

Ask for a password and validate using a stored sha1 hash on txt file

Check if password hash file exists, ask for a new password if not, if it exists, ask for the password, then validate using the stored hash txt file

Ask for password input and check if it contains a digit w/o using regex

Ask for password input and check if it contains lowercase letter w/o using regex

CheckAsk for password input and check if it contains uppercase letter w/o using regex

Ask for password input and check if it contains a symbol w/o using regex

Ask for passsword input and require all (digit, symbol, uppercase, lowercase)

Ask for passwoord input and require at least 3 (digit, symbol, uppercase, lowercase)

Ask for a password input, if new, require strong password and register, if password exists(hashed password txt file), require existing password

Ask for a credit/debit card input then validate using regex

Ask for a credit/debit card input allow spaces

create function addToCsv() that will create a csv file or append a row to an existing csv file, returning the row#

create function readCsvRow(rowId) that returns a numeric array of the row values

using readCSVRow(), create function readAllCsvRows()

create function getCsvColumnNumber(columnName) returns the position of the column (base 1)

create function getCsvCellValue(rowId, columnNumber)

using readAllCsvRows(), create function searchCsvRows(columnName, value) return array of rowId

using readCSVRow() create function findFirstCsvRow(columnName, value)

updateCSVRow(rowId, column, value) - updates the specified rowId row's column value

day91 - deleteCSVRow(rowId) deletes a row from csv specified by the rowId

ask for an email input, add to csv (Create)

ask for an email input, do not allow duplicates (findFirst)

ask for an email & name input, add to csv (2 columns) (Create)

ask for an email & name input, if email is duplicate, update name(Update)

Ask for a name, output all matching csv row (exact match) searchMultiple

Ask for a name, output all matching csv row (first/lastname only match)

Ask for a text, search email or name then output matches

Ask for a rowid, delete csv row immediately

Ask for a rowid, delete csv row after confirmation prompt

read all csv row and output

output csv as pretty table (text format)

press S to search use feature in day98

press A to add new row, feature in day83

press D to delete a row, do feature from day100

refactor the search to also include partial text matches

absolute row number display (including on search result)

change color of column names

case insensitive search

press 'u' to update a row, ask for a rowId, then ask for the field values

terminal width responsive table (expanding to vacant space)

when searching, highlight the row with color instead of printing it as separate

cursor-like navigation using up and down, can use update or delete when a row is highlighted

make the columns dynamic, so that create or update iterates through the csv columns instead of hardcoded

refresh table using "clear screen" routine coded before responsive pretty print, adjust the columns according to the terminal size create pretty print function
