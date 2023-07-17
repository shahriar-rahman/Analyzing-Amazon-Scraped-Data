===========================================================================
# Feature analysis of Amazon-Scraped Data 
Exploratory Data analysis of Amazon data which was scraped using Selenium Webdriver, an automation crawling tool for web scraping.
This data analytic research is a follow-up to the project [Scraping Amazon Products based on a User Search](https://github.com/shahriar-rahman/Amazon-Product-Scraping).

</br></br>

![alt text](https://github.com/shahriar-rahman/EDA-Amazon-Scraped-Data/blob/main/img/amazon_logo1.jpg)

</br></br>

### ◘ Introduction
Despite Amazon often being regarded as one of the world's most valuable brands, it is important to mention that browsing the site can pose some challenges as it is quite confusing due to the lackluster layouts and inconsistent web page structure. Furthermore, the site can often be quite slow to browse due to extensive traffic. As a result, comparing multiple products can be a much more difficult process than it seems as it affects the user's decision-making as it requires browsing all the links for the same type of products with different specifications. Therefore, it is imperative to bypass the inconvenience a user might face otherwise, by automating the search procedure on the Amazon site, scraping relevant information, and displaying comprehensively in a tabular format making it easy for the user to compare and analyze for a better purchase decision on Amazon

The data extracted from the site consists of 4 columns: Product Name or Title Name, Prices, Product Descriptions, Ratings, Total Ratings, ASIN, and Product Links. Various examinations have been performed to analyze and explore the scraped raw data.

</br></br>

![alt text](https://github.com/shahriar-rahman/EDA-Amazon-Scraped-Data/blob/main/img/amazon_logo2.jpg)

</br></br>

### ◘ Objective
The primary incentive of this research is to:
* Process dataset by analyzing its integrity, missing values, duplicated values, and so forth.
* Perform various clean-ups, if required, and improve accessibility for more convenient exploratory analysis.
* Conduct exploratory analysis using a myriad of graphing tools to reach a conclusion.

</br></br>

### ◘ Approach
This research is classified into 2 steps:
1. Construct proper data
2. Analyse Missing Values
3. Inquire about Duplicate units, if any
4. Analyze Data using:
* Univariate Analysis
* Bivariate Analysis
* Multivariate Analysis
5. Save the processed data set.

</br></br>

### ◘ Study Flowchart
![alt text](https://github.com/shahriar-rahman/EDA-Amazon-Scraped-Data/blob/main/img/FlowChart.png)

</br></br>

### ◘ Methodologies & Technologies applied
* Look for data inconsistencies
* Diagnose and fix structural errors
* Check and Clean data
* Address duplication
* Univariate inspection
* Bivariate inspection
* Feature correlations
* Seaborn & Matplotplib visualizations

</br></br>

### ◘ Required Packages
* pandas~=2.0.3
* missingno~=0.5.2
* seaborn~=0.12.2
* matplotlib~=3.7.0

</br></br>

◘ Jupyter core packages
* IPython : 8.10.0
* ipykernel : 6.19.2
* ipywidgets : 7.6.5
* jupyter_client : 7.3.4
* jupyter_core : 5.2.0
* jupyter_server : 1.23.4
* jupyterlab : 3.5.3

</br></br>

## Project Organization
---------------------------------------------------------

    ├── LICENSE
    |
    ├── README.md            # The top-level README for developers using this project
    ├── scraping_data        # Scraped Data stored in various formats
    │   ├── csv              
    │   ├── excel          
    │   └── json            
    │
    ├── img                    # Contains Project related files
    │   
    ├── graphs                # Graphs generated from the scraped data
    │
    ├── requirements.txt        # The requirements file for reproducing the analysis environment
    │                         			
    │  
    ├── notebook                # ipynb script for data exploration
    │                         			
     
---------------------------------------------------------

</br></br>

### ◘ Installation (using pip)
In Jupyter, the console commands can be executed by the *‘!’* sign before the command within the cell. For example, If the following code is written in the Jupyter cell, it will execute as a command in CMD.
To intall any modules effectively, the sys python package is used and works as follows:
```
import sys
!{sys.executable} -m pip install [package_name]                               
```
1. For Pandas, run:
```
!{sys.executable} -m pip install pandas                                                  
```
2. To install missingNo:
```
!{sys.executable} -m pip install missingno                                                  
```
3. Matplotlib can be installed by running the following command:
```
!{sys.executable} -m pip install matplotlib
```
4. Lastly, for seaborn:
```
!{sys.executable} -m pip install seaborn
```

<br/><br/>

### ◘ Import Packages
To *import* the dependencies, simply open the preferred IDE or Notebook: 
1. For Pandas, run the following command:
```
import pandas as pd                                   
```
2. To use missingno, run:
```
import missingno as msn                                      
```  
3. Import matplotlib using:
```
import matplotlib.pyplot as plt                                     
```
4. Seaborn can be accessed by:
```
import seaborn as sns                                      
```
<br/><br/>

### Supplementary Resources
* https://pypi.org/project/pandas/
* https://pypi.org/project/matplotlib/
* https://pypi.org/project/seaborn/
* https://pypi.org/project/missingno/

<br/><br/>

### ◘ MIT License
Copyright (c) 2023 Shahriar Rahman

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

<br/>

===========================================================================
