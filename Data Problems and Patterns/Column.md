THINK: how can I organize these.  One option seems to be to have higher level "Problems" and then "Patterns" to address each problem.

# Column Transformation Patterns
Column patterns look for data problems in a single column.  Examples include:
* making values consistent (F, Fem, Female, M, Male, etc)
* make data types appropriate (ID like 999-99-9999 should be string so it's treated like a factor)
* imputing  values (NAs)
* correcting inaccurate values (anaomolies?)


## Inconsistent Values 

### 1) Find and Replace

## Incomplete Columns
Define as missing values (NA, NULL, empty, etc)

### 1) Remove Incomplete Column

### 2) Remove Rows

### 3)  Impute Column Mean

### 4) Impute Random Value in Column Range

### 5) Impute Column Mode

## Invalid Values
Invalid values are determined by business policies and processes.

### 1) Policy/Process-based Corrections


### 2) Correct Outliers
Defined as more than 2 standard deviations from the mean.


## Multi-valued Columns
### 1) Split Column
For a single delimiter (example: lastname, firstname)

### 2) Create Separate Table
For multiple delimiters (3+ values per cell).  For example, Degrees may contain B.S., MBA, Ph.D.


## Inappropriate Data Type 
* Numeric
	* need to aggregate (SUM, AVG, MAX, MIN, etc).
* Text
	* need to treat column as dimension
* Date
	* need to operate with date functions
	* 



