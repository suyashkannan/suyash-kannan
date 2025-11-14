Creating a vector of 3 elements:
- a <- c(1,2,3)
- c refers to 'create'
- a is the variable in which the new vector will be stored.
Creating a dataframe:
- `name <- data.frame(variable,variable)`
- Viewing a dataset:
	- `View(name of dataframe)`
	- It is case sensitive
- Access parts of a dataframe:
	- `name$partname` - can be used in operations.
	- Component wise operation takes place here. 
- New column of dataframe: 
	- `name$newpartname <- variable_containing_values`
- To reduce number of displayed digits to a certain value:
	- `options(digits=value)`

Mean function
- mean(variable containing vectors) = value

Writing CSV file
- `write.csv(name,"name_of_file.csv")`
- can be opened using notepad++
- to remove the row numbers at the start - additional flag:
	- `write.csv(name,"name_of_file.csv",row.name=NULL)`

Importing Dataframes:
- workspace -> import data -> from text file -> import.

Standard Datasets of R:
- data()
- View(name of dataset)

### data.frame command
| Arugments          | Definition                                                                                                                                                                                                                                                                                         |
| ------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `row.names`        | `NULL` or a single integer or character string specifying a column to be used as row names, or a character or integer vector giving the row names for the data frame.                                                                                                                              |
| `check.rows`       | if `TRUE` then the rows are checked for consistency of length and names.                                                                                                                                                                                                                           |
| `check.names`      | logical. If `TRUE` then the names of the variables in the data frame are checked to ensure that they are syntactically valid variable names and are not duplicated. If necessary they are adjusted (by `[make.names](http://127.0.0.1:29105/help/library/base/help/make.names)`) so that they are. |
| `fix.empty.names`  | logical indicating if arguments which are “unnamed” (in the sense of not being formally called as `someName = arg`) get an automatically constructed name or rather name `""`. Needs to be set to `FALSE` even when `check.names` is false if `""` names should be kept.                           |
| `stringsAsFactors` | logical: should character vectors be converted to factors? The ‘factory-fresh’ default has been `TRUE` previously but has been changed to `FALSE` for **R** 4.0.0.                                                                                                                                 |
 `check.names` needs to be FALSE in order to allow duplicate names.


`View(x, title)`

### Median Function
`median(1:4)` takes median of all numbers from 1 to 4 = 2.5
`median(1:3,10,100)` = 3

```r
median(x, na.rm = FALSE, ...)
```
`na.rm` - a logical value indicating whether `NA` values should be stripped before the computation proceeds.|

