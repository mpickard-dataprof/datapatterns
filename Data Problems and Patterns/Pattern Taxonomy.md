[Refactoring Guru](https://refactoring.guru/design-patterns/classification) categories design patterns as follows:
* Creational patterns
* Structural patterns
* Behaviorial patterns

[Software design pattern on Wikipedia](https://en.wikipedia.org/wiki/Software_design_pattern#Concurrency_patterns), in addition to the three classifications above also includes: Concurrency patterns. It also lists patterns under each category.


- Structural - patterns related to the structure of the data (relational tables, need to split out columns, tidy vs. untidy data, pivoting/melting data)
	- pivoting / unpivoting columns
	- splitting columns (text to columns)
- Feature Engineering
	- composite of columns (some formula drawing from multiple columns)
	- 
- Dimensionality reduction (column reduction) - deals solely with reducing the number of columns
	- Feature selection
		- redundant columns
		- Low-variance
		- Missing values
		- Correlation
	- Feature extraction
		- PCA
		- Factor analysis
		- tSNE
		- UMAP
- Row reduction (aggregation) - deals solely with reducing the number of rows (observations)
	- Removing sparse observations
	- aggregation
- Validity
	- data inconsistency
	- split column
	- create separate table
	- inappropriate data types
	- 
- Completeness
	- data imputation
- Data merging
	- Union
	- Joins
		- Inner
		- Left
		- Right
		- Full Outer
		- Anti-join



- Column Patterns
	- Data imputation 
	- Data consistency
	- Dimsionality reduction
		- Feature selection
			- Low-variance
			- Missing values
			- Correlation
		- Feature extraction
			- PCA
			- Factor analysis
			- tSNE
			- UMAP
- Table Patterns
- Combination Patterns




- Accuracy
	- outliers
	- policy / process-based corrections
- Validity
	- data inconsistency
	- split column
	- create separate table
	- inappropriate data types
	- 
- Completeness
	- data imputation
	- 