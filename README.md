# MongoDB-statement-analysis

The goal of the project is to extract MongoDB's financial data using the YahooFinance API in python thereby automating a process that would usually be much more time consuming.
After automatically(a few seconds) importing the company's financial statements, some of the most significant values were selected and used to calculate financial ratios commonly used in the world of business analysis

After the values were displayed on graphs for better understanding and to find insights.
Continue reading to see the values found

In alternative:

 [click here](https://github.com/EdoPedrocchi/MongoDB-statement-analysis/blob/main/code-with-graphs.pdf) to see the graph and the code
 
 [click here](https://github.com/EdoPedrocchi/MongoDB-statement-analysis/blob/main/CODE) to see only the code

# income statement
|   index   |     2020       |     2021       |     2022       |      2023       |
|:---------:|:--------------:|:--------------:|:--------------:|:---------------:|
| revenues  | 421,720,000.0  | 590,380,000.0  | 873,782,000.0  | 1,284,040,000.0 |
|   EBITDA  | -128,092,000.0 | -184,772,000.0 | -264,909,000.0 | -317,473,000.0  |
|    EBIT   | -147,866,000.0 | -209,304,000.0 | -289,364,000.0 | -346,655,000.0  |
|     i_e   |   20,983,000.0 |   56,107,000.0 |   11,316,000.0 |     9,797,000.0 |
|      NE   | -175,522,000.0 | -266,944,000.0 | -306,866,000.0 | -345,398,000.0  |

# balance sheet

|          index           |      2020      |      2021      |      2022      |      2023      |
|:------------------------:|:--------------:|:--------------:|:--------------:|:--------------:|
|           PPE            |   69,463,000.0 |   96,951,000.0 |  104,370,000.0 |   99,035,000.0 |
|       Good will          |        1        |        1        |        1        |        1        |
|     Net Receivables      |   55,830,000.0 |   55,830,000.0 |   57,775,000.0 |   57,779,000.0 |
|            CL            |        1        |        1        |        1        |        1        |
|            CA            |   85,554,000.0 |  135,176,000.0 |  195,383,000.0 |  285,192,000.0 |
|            WC            |  242,384,000.0 |  354,541,000.0 |  526,735,000.0 |  588,512,000.0 |
|   Invested Capital       |1,113,196,000.0 |1,141,887,000.0 |2,117,402,000.0 |2,236,584,000.0 |
|         Net Debt         |  870,812,000.0 |  787,346,000.0 |1,590,667,000.0 |1,648,072,000.0 |
| Stockholders Equity      |  993,933,000.0 |  932,696,000.0 |1,803,221,000.0 |1,879,388,000.0 |


# ratio

| index                       | 2020        | 2021         | 2022        | 2023        |
|-----------------------------|-------------|--------------|-------------|-------------|
| ROI                         | -0.148769   | -0.224408    | -0.160471   | -0.184451   |
| ROS                         | -0.350626   | -0.354524    | -0.331163   | -0.269972   |
| Capital Turnover            | 0.424294    | 0.632982     | 0.484567    | 0.683222    |
| EBITDA Analysis             | -0.303737   | -0.312971    | -0.303175   | -0.247245   |
| WC/Revenues                 | 2.064906    | 1.333626     | 1.820439    | 1.283505    |
| Days Sales Outstanding (DSO)| 73.032913   | 82.427182    | 80.498202   | 79.957883   |
| Debt Sustainability         | -1.599499   | -2.749508    | -2.5013     | -2.154684   |
| Leverage                    | 2.4727      | -100.940195  | 0.993876    | 0.925012    |
| EBITDA/Interest Expense     | -6.104561   | -3.293208    | -23.410127  | -32.405124  |
