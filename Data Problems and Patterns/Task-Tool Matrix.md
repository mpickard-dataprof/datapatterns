**R**: use tidyverse (dplyr, stringr, lubridate, etc)
**Python**: Use pandas where applicable
**Excel**: Use built-in Excel functions (no PowerQuery)
**Power BI**: use PowerQuery Editor (Table Tools >> Transform Data)
**Alteryx**: use only built-in tools

| Task                      | R                     | Python                           | Excel            | Power BI | Alteryx |
| ------------------------- | --------------------- | -------------------------------- | ---------------- | -------- | ------- |
| Inner Join                | `dplyr::inner_join()` | `df.join(how='inner')`           |                  |          |         |
| Left Join                 | `dplyr::left_join()`  | `df.join(how='left')`            |                  |          |         |
| Right Join                | `dplyr::right_join()` | `df.join(how='right')`           |                  |          |         |
| Full Join                 | `dplyr::full_join()`  | `df.join(how='outer')`           |                  |          |         |
| Union                     | `dplyr:bind_rows()`   | `df.concat() or df1.append(df2)` |                  |          |         |
| Remove Duplicates         |                       |                                  |                  |          |         |
| Profiling                 |                       |                                  |                  |          |         |
| Normalization (z-value)   |                       |                                  |                  |          |         |
| Calculated Columns        |                       |                                  |                  |          |         |
| Pivot (to wide)           |                       |                                  |                  |          |         |
| Unpivot (to long)         |                       |                                  |                  |          |         |
| Missing Values - Drop     |                       |                                  |                  |          |         |
| Missing Values - Impute   |                       |                                  |                  |          |         |
| Identifying Outliers      |                       |                                  |                  |          |         |
| Find and Replace          |                       |                                  |                  |          |         |
| Split Column              |                       |                                  |                  |          |         |
| Extract Value from Column |                       |                                  |                  |          |         |
| Extract Date Part         |                       |                                  |                  |          |         |
| Concatenating Text        | `stringr::str_c`      | `+` or `%`                       | `=CONCATENATE()` |          |         |
| Rounding Values           |                       |                                  |                  |          |         |
|                           |                       |                                  |                  |          |         |
