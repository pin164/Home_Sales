# Home_Sales
**brief description of the project**
knowledge of SparkSQL is used to determine key metrics about home sales data. Spark is used to create temporary views, to partition the data, to cache and uncache temporary tables, to measure runtimes for cached uncached and partioned tables.        Finally compare runtimes, and verify that the table has been uncached.

**summary of approach:**<br>
>1.Prepare the environment Install Spark & Java, import packages, Create a SparkSession, Read in the AWS S3 bucket into a DataFrame.Create a temporary view of the DataFrame.<br>
2.Calculate and print various metrics using SQL<br>
3.For a specific metric"average price of a home per "view" rating"
>>>3.1calculate the uncached run time <br>
>>>3.2calculate the cached runtime and Report<br>
>>>3.3calculate the parquet DataFrame runtime and Report<br>
4. Compare the runtimes
**location within repository**<br>
>data file : on amazon aws see dependencies 
code to run the model:Google Colab :Home_Sales.ipynb<br>
original template to assess model: Google Colabk :Home_Sales_starter_code_colab.ipynbb<br>

**Code source**:Home_Sales.ipymb<br>

**Instructions for running the code**:Google Colab.  No special instructions to run the code <br>

**dependencies** The python code relies on the data file <br>
url = "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv"<br>


Additional Comments :  This code is my original work with help from<br>
I have NOT worked with a peer on an assignment,<br>
I used google<br>
I used Stack Overflow (https://stackoverflow.com/)<br>
I used CanChat (https://canchat.dsai-sdia.ssc-spc.cloud-nuage.canada.ca/) to resolve issues<br>
I used the tutoring service on this homework challenge
The instructor did not assist in the homework challenge this week The TA did not assist in the homework challenge this week
