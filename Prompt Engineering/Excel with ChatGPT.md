# **Excel with ChatGPT**
<hr>

## **Exercise - 1**
* **Prompt -** `Create sales data for 20 FMCG items each for 12 months, i.e. January to December.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -** `Write the formulas to calculate Total, Maximum, Minimum, Average, Second Highest, Second Lowest for the data items from cell B2 to M2.`
2. Copy all the generated formulas and paste them in the respective columns from N2 to S2, and drag them for rest of the column values.
3. Give the column heads appropriately e.g. Total, Maximum, Minimum, Average, Second Highest, Second Lowest.
4. At cell T1 give a column head 'Status'
* **Prompt -** `Write one excel formula such that if N2 cell values is below 4000 then "Low Sale", if it is between 4000 to 5000 then "Medium Sale" otherwise "High Sale".`
5. Now copy the formula and paste it to the cell T2 and drag it for rest of the column values.
* **Prompt -** `Please write the steps to convert dataset at A1 to T21 to a table.`
6. Follow the steps given to do the needful actions to convert the dataset to a table.
## **Output:**
![abb4313f-d9b1-4de1-927b-d088c4fb3f98](https://github.com/user-attachments/assets/2d93edbd-c2cc-4fd3-b578-23c1ab08d892)
<hr>

## **Exercise - 2**
* **Prompt -** `Generate a table with column head 'Data' where there will be 20 data items containing 'Name', 'Age', 'Email' and 'Reg. No.' separated by commas.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -** `Write a formula in Excel which will split 'Name', 'Age', 'Email' and 'Reg. No.' separated by commas at cell A2.`
2. Copy the generated formula and paste it at cell B2 and drag them for rest of the column values.
3. Give the column heads appropriately e.g. 'Name', 'Age', 'Email' and 'Reg. No.'.
* **Prompt -** `In columns B to E from rows 2 to 21, we have Name, Age, Email, Reg. No. for employees. Mention steps to create a drop-down list on Name at cell K2.`
4. Follow the mentioned steps and create the drop-down list accordingly.
* **Prompt -** `Please mention formulas to get Age, Email and Reg. No. of that employee whose name is at cell K2 based on the above-mentioned table.`
5. Follow the given instructions. Copy the formulas and paste them at cells K3, K4 and K5 respectively.
## **Output:**
![d3f9abf7-3a21-4607-a531-63cf758d3944](https://github.com/user-attachments/assets/d1a1e4e0-518d-4d97-868b-526888959cbc)
<hr>

## **Exercise - 3**
* **Prompt -** `Generate a table with columns 'Employee Name' and 'Login Time' for 20 employees. All the 'Login Time' should be between 8.45am to 9.15am.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -** The time value is in cell B2. Write a formula if the time is less than or equal to 9 AM then "On Time" otherwise "Late Arrival"
2. Copy the generated formula and paste it at cell B2 and drag them for rest of the column values.
3. Give the column head as 'Arrival'.
* **Prompt -** Please mention steps to highlight cell from C2:C21 if it is 'Late Arrival'.
* Follow the steps and do the needful conditional formatting.
## **Output:**
![ec68e9c1-8709-451b-a6cf-6e6e87cd03ce](https://github.com/user-attachments/assets/4794bb02-b516-4bb3-b8bc-fe433146d369)
<hr>

## **Exercise - 4**
* **Prompt -** `Create an Excel Macro to make an 'EMI Calculator'.`
1. Follow all the steps as mentioned in the instruction list and do the needful.
## **Output:**
![60c29aa4-4fc6-4588-accd-3434d38ad2fb](https://github.com/user-attachments/assets/feaaf78d-f83b-4ed9-9391-b52d57ba2020)
<hr>

## **Exercise - 5**
* **Prompt -** `Create a list of 20 records with EmpName and EmpEmail.`
1. Copy paste the data set in Sheet5 at cell A1.
* **Prompt -** `Create another list of 25 records with EmpName and EmpEmail keeping some records same as were in the previous list generated.`
2. Copy paste the data set in Sheet6 at cell A1.
* **Prompt -** `I am having data in Sheet5 A1 to B21 and in Sheet6 A1:B27 with heading 'EmpName' and 'EmpEmail'. Select only duplicate data in these two sheets and copy them in Sheet7 in A and B columns with proper headings.`
3. Follow all the steps as mentioned in the instruction list and do the needful.
## **Output:**
![bfa723f4-fa5a-4695-8a49-ebd44d823b13](https://github.com/user-attachments/assets/fcd42243-6b32-45c5-9985-731c4d971287)
<hr>

## **Exercise - 6**
* **Prompt -** `Create sales data for 10 Building construction items each for 12 months, i.e. January to December.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -** `Item Name is given in cell Q2 and Month is given in cell Q3. Now generate a formula to find the sales amount in cell Q4 from the pre-generated table whose top-left header cell is at A1.`
2. Copy the generated formula and paste it to the cell Q4.
* **Prompt -** `Now also generate the steps to highlight the cell whose value is getting selected for that specific given Item Name and the Month based on the previous table whose top left header cell is at A1.`
* Follow all the steps as mentioned in the instruction list and do the needful. We may require a correction of the ChatGPT given formula. The correct formula will be - **=AND($A1=$Q$2, A$1=$Q$3)**
## **Output:**
![8e288d23-d54b-4c95-b063-0ca3e8c40e91](https://github.com/user-attachments/assets/d6777f5a-bfa2-44ae-a226-3a2e52699856)
<hr>

## **Exercise - 7**
* **Prompt -**
<pre>
Write a Basic VBA Code to create 5 new sheets from Sheet11 to Sheet15 every time we run the macro in a new workbook and also format the sheets with the below requirements:
a. Background color is cyan for all the cells of the current sheet.
b. Font color is deep blue.
c. Font style is bold and italics.
d. Width of all the columns 20.
e. Height of the first row should be 20.
f. Cell A1 of each sheet will contain the worksheet name.
</pre>
1. After creation of the macro, run the macro as instructions are given.
2. Go to Home -> Cell (Group) -> Format, to verify the row and column widths.
## **Output:**
![d68528d0-8598-4389-bf9a-8bdec3aec12a](https://github.com/user-attachments/assets/6187c4e3-c911-4dee-922b-cc1f692b936e)
<hr>

## **Exercise - 8**
* **Prompt -** `Create a dataset for 20 employees with First_Name, Last_Name, Gender, CTC between 5 Lac USD to 1 Crore USD. The First_Name and Last_Name columns will have values with mix of upper-case and lower-case letters arbitrarily.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -**
<pre>
I am having a dataset with column heads First_Name, Last_Name, Gender, CTC (USD) in row 1 starting from cell A1.
Now we require formulas to create new columns as mentioned below -
1. Full_Name: Combine First and Last Names and make them proper. And also prepend salutation 'Mr.' if 'Gender' is 'Male', otherwise 'Ms.'.
2. CTC in Lakhs: Convert CTC from USD to Lakhs (1 Lakh = 100,000 USD)
3. Gender_Code: Assign a code based on Gender (e.g., Male = 1, Female = 2)
4. CTC Category: Categorize CTC as Low, Medium, or High, if < 6000000, if >= 6000000 and < 8000000, otherwise respectively.
</pre>
2. Create column heads Full_Name, CTC in Lakhs, Gender_Code and CTC Category. Put required formulas under them as suggested.
3. Now drag those formulas for the rest of the cells in those columns.
## **Output:**
![bc41655d-04b7-4ed7-978d-9464021581ab](https://github.com/user-attachments/assets/38edb29b-3a37-4a90-a55f-41f7f9f8c92b)
<hr>

## **Exercise - 9**
* **Prompt -** `Create a table containing distinct EmpID, EmpName and EmpDept, were EmpDept has four distinct department names only.`
1. Copy the generated data and paste them to one blank excel worksheet at cell A1.
* **Prompt -**
<pre>
There is a dataset from A1 to C21 including header row containing EmpID, EmpName, EmpDept. Now find the following formulas to do the needful calculations -
1. Count of distinct department names.
2. Count of all employees.
3. List of distinct department names to be put from the column cell E6 onward.
4. Employee count of each distinct department.
</pre>
2. Now put proper headings as required and copy the respective formulas as suggested by ChatGPT to the respective worksheet cells.
## **Output:**
![ad803bd5-2c6c-4a72-98c1-e47f3808109f](https://github.com/user-attachments/assets/5409743d-3484-4ef8-86f4-6de29448c666)
<hr>

## **Exercise - 10**
* **Prompt -** `Please create 2024 sales dataset with 200 rows against the column heads Date, Product, Employee, Units Sold, Price per Unit (INR), Region, Total Amount (INR). We are having 10 distinct products and 5 Employees for the sales. Give these products and employees realistic names.`
* **Prompt -** `Clean and format our whole dataset.`
* **Prompt -** `I want to download the dataset.`
* **Prompt -** `Give me a bar chart for "Total Sales by Product".`
* **Prompt -** `Can you summarize the key insights?`
* **Prompt -** `Show me a trend analysis of sales.`
* **Prompt -** `How about comparing "Profitability by Region"?`
* **Prompt -** `Can we analyze "Sales by Product"?`
* **Prompt -** `Generate a scatter plot "Units Sold" vs. "Price per Unit (INR)".`
* **Prompt -** `Generate a pie chart for "Sales Distribution by Region".`
* **Prompt -** `Draw suitable line diagrams with markers based on the given dataset.`
* **Prompt -** `Suggest some more data visualizations based on the given dataset.`
* **Prompt -** `Can you draw all these suggested graphs and charts?`

## **Output:**
![a2aed3d9-38d7-412c-a7b3-5d9a99700eac](https://github.com/user-attachments/assets/800dce35-f3cf-443a-bb4c-2c6b50e11915)
<hr> <hr>

## **Exercise - 11**
1. Go to Home tab, click on Add-ins and add "ChatGPT for Excel".
2. Watch YouTube official video at https://www.youtube.com/watch?v=4raUaR-FK-M for more details.
3. Check the complete official documentation at https://appsource.microsoft.com/en-us/product/office/WA200005271?src=office&corrid=4e5d4162-8729-dbd3-9d38-ddaa55bf5012&omexanonuid=&referralurl=&ClientSessionId=b98ee656-7fc1-4fa9-99c6-c9b0a1acc093.
4. Here are just a few examples of how our add-in can help you sparkle:
  * **AI.ASK:** let AI answer questions and write engaging content
  * **AI.TABLE:** create AI-powered tables in seconds
  * **AI.TRANSLATE:** translate your content into dozens of languages
  * **AI.FORMAT:** quickly format your data with AI for consistency
  * **AI.EXTRACT:** extract valuable data insights
  * **AI.FILL:** clean your data and fill in missing ranges
  * **AI.LIST:** generate list outputs in separate rows
  * **AI.CHOICE:** chooses the most closely matching value from a given list of choices
<hr>

## **Exercise - 12**
* **Prompt -** `What are AI.ASK other similar ChatGPT addins functions? Describe their usages, examples and utilities.`
## **Output:**
The term **AI.ASK** and similar functions like **AI.QUERY**, **AI.EXTRACT**, **AI.SUMMARIZE**, etc., can be thought of as **custom add-in functions** that extend the capabilities of ChatGPT (or similar AI models) to work within various software environments such as Excel, Google Sheets, or other data processing tools. These add-ins are typically created by developers to allow users to leverage the power of AI for specific tasks like querying databases, generating summaries, extracting data, or automating content creation.

Here’s an overview of what **AI.ASK** and similar functions might do, along with some example uses, applications, and utilities:

---

### 1. **AI.ASK** — **Query-based AI Function**
**Function**: This function allows users to query a dataset or document in a natural language format, and the AI interprets the query to return relevant answers.

#### Uses:
- **Query Data**: Ask natural language questions about a dataset, like "What is the total sales for Product X?" or "List all employees from Marketing department."
- **Database Queries**: Integrate with databases and execute queries in natural language, making it easier for non-technical users to retrieve information without knowing SQL.

#### Example:
- **Excel/Google Sheets**: In a cell, you might use:
  ```excel
  =AI.ASK("What is the average salary for employees in the HR department?")
  ```
  The function would return the average salary value based on the data in your sheet.

- **Database Example**: If connected to a database, you could ask:
  ```sql
  AI.ASK("Show me all records of customers who made a purchase in 2023")
  ```

#### Utility:
- **Ease of Use**: Helps users who are not familiar with technical query languages (like SQL) to retrieve information easily.
- **Automated Reporting**: Allows for on-the-fly, conversational reporting without needing to set up predefined queries.

---

### 2. **AI.QUERY** — **Advanced Query Function**
**Function**: This function allows you to input complex queries in natural language to extract, filter, or manipulate data in various ways.

#### Uses:
- **Dynamic Data Filtering**: Filter and sort data based on user input.
- **Complex Query Execution**: Use complex natural language queries to interact with databases, tables, and spreadsheets.

#### Example:
In a **Google Sheets** or **Excel** environment, you could use the formula:
```excel
=AI.QUERY("Show me the list of employees whose salary is greater than $70,000 and are in the Sales or Marketing department.")
```
This query would filter the dataset based on the provided conditions and return the result dynamically.

#### Utility:
- **Data Management**: Ideal for managing large datasets, as it simplifies complex querying tasks.
- **Automation**: Streamlines operations like filtering, grouping, and analyzing data automatically.

---

### 3. **AI.EXTRACT** — **Data Extraction Function**
**Function**: This function is used to extract specific information from a large set of data or text. It can be used to find particular data points, pull out specific rows or columns, or extract key information from documents.

#### Uses:
- **Extract Specific Data**: Extract specific rows/columns or data points based on conditions.
- **Document Parsing**: Parse documents (PDFs, Word files, etc.) and extract relevant pieces of information.

#### Example:
- In a **spreadsheet**, use:
  ```excel
  =AI.EXTRACT("Extract all employees from HR with salaries above $60,000")
  ```
  The function would return only the rows from the **HR** department where the salary is above $60,000.

- **Document Parsing**:
  If using ChatGPT integration with document processing systems, the function could be used to extract particular sections from a document:
  ```python
  AI.EXTRACT("Find all dates and names from this contract document")
  ```

#### Utility:
- **Data Parsing**: Useful when dealing with unstructured data or large documents where you need to extract specific details.
- **Time-Saving**: Automates manual data extraction tasks that would otherwise be time-consuming.

---

### 4. **AI.SUMMARIZE** — **Summarization Function**
**Function**: This function summarizes long documents, reports, or text into concise, digestible information, preserving the core details while eliminating extraneous content.

#### Uses:
- **Document Summarization**: Summarize large documents, reports, or datasets.
- **Text Analytics**: Summarize customer reviews, feedback, or survey responses to generate actionable insights.

#### Example:
In **Excel** or **Google Sheets** with a large dataset or report:
```excel
=AI.SUMMARIZE(A2:A100)
```
This function would return a condensed summary of the data in the specified range (e.g., summarizing sales performance or employee records).

- **For Reports**: Summarize a 10-page research document into a 3-sentence overview.

#### Utility:
- **Data Overview**: Ideal for quickly understanding the essence of large datasets or reports.
- **Content Creation**: Helpful for content managers who need to generate summaries of articles, documents, or data.

---

### 5. **AI.PREDICT** — **Prediction Function**
**Function**: This function uses machine learning models to make predictions based on historical data or trends.

#### Uses:
- **Forecasting**: Predict future trends based on historical data (e.g., sales forecasts, demand predictions).
- **Risk Assessment**: Predict potential risks or outcomes based on certain variables.

#### Example:
In a **financial report** or **sales data** in a spreadsheet:
```excel
=AI.PREDICT("What will be the sales for next month based on previous trends?")
```
This would use historical data (from previous months) to predict sales for the upcoming month.

#### Utility:
- **Data Forecasting**: Helps businesses with budget planning, sales forecasting, and resource allocation.
- **Decision-Making**: Provides insights into potential future trends, aiding in better decision-making.

---

### 6. **AI.TRANSFORM** — **Data Transformation Function**
**Function**: This function allows you to apply transformations to the data such as cleaning, reformatting, or converting data based on predefined patterns.

#### Uses:
- **Data Normalization**: Automatically reformat or clean messy data (e.g., remove duplicates, fix inconsistent date formats).
- **Text Transformation**: Clean and transform textual data (e.g., converting text to proper case, removing unwanted characters).

#### Example:
- **Text Data Transformation**:
  ```excel
  =AI.TRANSFORM("Clean and normalize the phone numbers in column B")
  ```

- **Data Reformatting**: If you have a column with dates in different formats, use:
  ```excel
  =AI.TRANSFORM("Reformat all dates to YYYY-MM-DD format")
  ```

#### Utility:
- **Data Cleaning**: Automates repetitive data cleaning tasks, saving time for analysts.
- **Consistency**: Ensures that data is consistently formatted for analysis.

---

### 7. **AI.GENERATE** — **Content Generation Function**
**Function**: This function is used to automatically generate text content, such as reports, articles, summaries, or responses, based on a given prompt.

#### Uses:
- **Report Generation**: Automatically generate summaries or full reports from structured data.
- **Content Creation**: Generate blog posts, emails, and other forms of content based on prompts.

#### Example:
In a **Google Sheet** or **Excel**:
```excel
=AI.GENERATE("Create a summary of the Q2 sales performance from the data in column A")
```
This function could generate a brief summary of sales performance based on the raw data provided.

#### Utility:
- **Content Automation**: Helps automate the content creation process for marketers, writers, and content creators.
- **Report Automation**: Useful for quickly generating reports based on data inputs.

---

### Summary of Utility of These AI Functions:
- **Productivity Enhancement**: These add-ins can significantly increase productivity by automating tasks that would otherwise take considerable time, such as querying, summarizing, extracting, or transforming data.
- **Data Handling**: They are excellent tools for data analysts, researchers, and business analysts to perform advanced analysis without the need for complex formulas or programming.
- **Natural Language Processing**: These functions leverage AI's ability to understand and process natural language, allowing users to interact with data and systems intuitively, without needing to learn specialized query languages.

---

If these functions are available in your system or application, they can simplify many routine tasks and make it easier to handle and analyze data. If you're interested in implementing or using these add-ins, the specific syntax and setup may depend on the platform you're using (Excel, Google Sheets, Python, etc.). Let me know if you need further clarification or help!
<hr> <hr>










