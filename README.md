## 2016 Presidential Election
### County Level data  

Example of data structure  

| cod   | name  | votes | candidate1 | candidate2 | candidate3 | c | t | j | c1v | c2v | c3v | c1p   | c2p   | c3p  |
|-------|-------|-------|------------|------------|------------|---|---|---|-----|-----|-----|-------|-------|------|
| 38001 | Adams | 1206  | t          | c          | j          | 2 | 1 | 3 | 904 | 216 | 65  | 74.96 | 17.91 | 5.39 |


**cod**: county flip  
**name**: county name  
**votes**: total votes  
**candidate1**: first leter of last name of the main candidates => t = trump, c = clinton, j = johnson  
**candidate2**: ...  
**candidate3**: ...  
**c**: candidate position. t = 1, Trump was first candidate in this county (more vote percent).  
**t**: ...  
**j**: ...  
**c1v**: number of votes of first candidate => c1v ~ candidate 1 votes  
**c2v**: ...  
**c3v**: ...  
**c1p**: vote percent of first candidate => c1p ~ candidate 1 percent  
**c2p**: ...  
**c3p**: ...  

> In **Adams** county **Donald Trump** was the first candiate with **74.96%** (PCT) and **904 votes**.  
> **Hillary Clinton** the second one with **17.91%** and **216 votes**.  
> **Gary Johnson** the third with **5.39%** and **65 votes**.  

County codes: https://www.census.gov/2010census/partners/pdf/FIPS_StateCounty_Code.pdf.  
Data from [nytimes](http://www.nytimes.com/elections/results/president).
