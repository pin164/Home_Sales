# Home_Sales
**brief description of the project**
knowledge of SparkSQL is used to determine key metrics about home sales data. Spark is used to create temporary views, to partition the data, to cache and uncache temporary tables, to measure runtimes for cached uncached and partioned talbles.and finally compare runtimes.and verify that the table has been uncached.

**summary of approach:**<br>
>1.Prepare the environment Install Spark & Java, import packages, Create a SparkSession, Read in the AWS S3 bucket into a DataFrame.Create a temporary view of the DataFrame.<br>
2.Calculate and print various metrics using SQL<br>
3.For a specific metric"average price of a home per "view" rating"
>>>3.1calculate the uncashed run time <br>
>>>3.2calculate the cashed runtime and Report<br>
>>>3.3calculate the parquet DataFrame runtime and Report<br>
4. Compare the runtimes
**location within repository**<br>
>data file : Credit_Risk/Resources/lending_data.csv<br>
code to run the model:Jupyter Notebook :Credit_Risk/credit_risk_classificationV1.ipymb<br>
original template to assess model: Jupyter Notebook :Home_Sales.ipymb<br>
**Code source**:Home_Sales.ipymb<br>

**Instructions for running the code**:google colab.  No special instructions to run the code <br>

**dependencies** The python code relies on the data file <br>

Additional Comments :  This code is my original work with help from<br>
I have NOT worked with a peer on an assignment,<br>
I used google<br>
I used Stack Overflow (https://stackoverflow.com/)<br>
I used CanChat (https://canchat.dsai-sdia.ssc-spc.cloud-nuage.canada.ca/) to resolve issues<br>
I used the tutoring service on this homework challenge
The instructor did not assist in the homework challenge this week The TA did not assist in the homework challenge this week
