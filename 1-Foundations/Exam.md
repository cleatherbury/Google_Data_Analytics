## Course challenge

* Scenario 1, question 1-5 *

~~~
You’ve just started a new job as a data analyst. You’re working for a midsized pharmacy chain with 38 stores in the American Southwest. Your supervisor shares a new data analysis project with you.
She explains that the pharmacy is considering discontinuing a bubble bath product called Splashtastic. Your supervisor wants you to analyze sales data and determine what percentage of each store’s total daily sales come from that product. Then, you’ll present your findings to leadership.
You know that it's important to follow each step of the data analysis process: ask, prepare, process, analyze, share, and act. So, you begin by defining the problem and making sure you fully understand stakeholder expectations.
One of the questions you ask is where to find the dataset you’ll be working with. Your supervisor explains that the company database has all the information you need. 
Next, you continue to the prepare step. You access the database and write a query to retrieve data about Splashtastic. You notice that there are only 38 rows of data, representing the company’s 38 stores. In addition, your dataset contains five columns: Store Number, Average Daily Customers, Average Daily Splashtastic Sales (Units), Average Daily Splashtastic Sales (Dollars), and Average Total Daily Sales (All Products). 
~~~

### Question 1
Considering the size of your dataset, you decide a spreadsheet will be the best tool for your project. You proceed by downloading the data from the database. Describe why this is the best choice.

* Only spreadsheets let you download and upload data.
* Spreadsheets are most effective when working with queries.
* ```Spreadsheets work well for processing and analyzing a small dataset, like the one you’re using.```
* Databases can’t be used for analysis.

~~~
* Scenario 1 continued *
You’ve downloaded the data from your company database and imported it into a spreadsheet. IMPORTANT: To answer questions using this dataset for the scenario, click the link below and select the “Use Template” button before answering the questions.
Link to template: 
Course Challenge - Scenario 1
OR 
If you don’t have a Google account, you can download the template directly from the attachment below.
Course Challenge Dataset - Scenario 1 - Scenario 1_ Pharmacy Data - Part 1
CSV File
￼
Now, it’s time to process the data. As you know, this step involves finding and eliminating errors and inaccuracies that can get in the way of your results. While cleaning the data, you notice there’s missing data in one of the rows. 
~~~

### Question 2
What might you do to fix this problem? Select all that apply.

- [ ] &ensp;Delete the row with the missing data point
- [x] &ensp;```Ask a colleague on your team how they've handled similar issues in the past```
- [ ] &ensp;Sort the spreadsheet so the row with missing data is at the bottom
- [x] &ensp;```Ask you supervisor for guidance```

~~~
* Scenario 1 continued *
Once you’ve found the missing information, you analyze your dataset. During analysis, you create a new column F. At the top of the column, you add the attribute Average Percentage of Total Sales - Splashtastic. 
~~~

Question 3
Fill in the blank: An attribute is a characteristic or _____ of data used to label a column.

* ```collection```
* quality
* observation
* number

~~~
* Scenario 1 continued *
Next, you determine the average total daily sales over the past 12 months at all stores. The entire range of cells that contain these sales are E2:E39. To do this, you type a formula. You input =AVERAGE(E2-E39), but this returns an error. 
~~~

## Question 4
What is the correct command?

* =AVERAGE(E2;E39)
* =AVERAGE(E2+E39)
* ```=AVERAGE(E2:E39)```
* =AVERAGE(E2,E39) 

~~~
* Scenario 1 continued *
~~~

## Question 5
Fill in the blank: You’ve reached the share phase of the data analysis process. One of the things that you can do in this phase is to prepare a _____ about Splashtastic’s sales and practice your presentation.

* ```slideshow```
* record
* prediction
* finding

~~~
* Scenario 2, questions 6-10 *
You’ve been working for the nonprofit National Dental Society (NDS) as a junior data analyst for about two months. The mission of the NDS is to help its members advance the oral health of their patients. NDS members include dentists, hygienists, and dental office support staff. 
The NDS is passionate about patient health. Part of this involves automatically scheduling follow-up appointments after crown replacement, emergency dental surgery, and extraction procedures. NDS believes the follow-up is an important step to ensure patient recovery and minimize infection. 
Unfortunately, many patients don’t show up for these appointments, so the NDS wants to create a campaign to help its members learn how to encourage their patients to take follow-up appointments seriously. If successful, this will help the NDS achieve its mission of advancing the oral health of all patients. 
Your supervisor has just sent you an email saying that you’re doing very well on the team, and he wants to give you some additional responsibility. He describes the issue of many missed follow-up appointments. You are tasked with analyzing data about this problem and presenting your findings using data visualizations. 
An NDS member with three dental offices in Colorado offers to share its data on missed appointments. So, your supervisor uses a database query to access the dataset from the dental group. The query instructs the database to retrieve all patient information from the member’s three dental offices, located in zip code 81137.
~~~

### Question 6
The table is dental_data_table, and the column name is zip_code. How do you complete the following query?

| SELECT * |
| FROM dental_data_table |
| - |

* zip_code = 81137
* ```WHERE zip_code = 81137```
* WHERE = 81137
* WHERE_zip_code = 81137

~~~
* Scenario 2 continued *
The dataset your supervisor retrieved and imported into a spreadsheet includes a list of patients, their demographic information, dental procedure types, and whether they attended their follow-up appointment. To use the dataset for this scenario, click the link below and select “Use Template.”
Link to template: 
Course Challenge - Scenario 2
OR 
If you don’t have a Google account, you can download the template directly from the attachment below.
Course Challenge Dataset - Scenario 2
CSV File
￼
The patient demographic information includes data such as age and gender. As you’re learning, it’s your responsibility as a data analyst to make sure your analysis is fair. 
~~~

## Question 7
The fact that the dataset includes people who all live in the same zip code might get in the way of fairness.

* ```True```
* False

~~~
* Scenario 2 continued *
As you’re reviewing the dataset, you notice that there are a disproportionate number of senior citizens. So, you investigate further and find out that this zip code represents a rural community in Colorado with about 800 residents. In addition, there’s a large assisted-living facility in the area. Nearly 300 of the residents in the 81137 zip code live in the facility. 
You recognize that’s a sizable number, so you want to find out if age has an effect on a patient’s likelihood to attend a follow-up dental appointment. You analyze the data, and your analysis reveals that older people tend to miss follow-ups more than younger people. 
So, you do some research online and discover that people over the age 60 are 50% more likely to miss dentist appointments. Sometimes this is because they’re on a fixed income. Also, many senior citizens lack transportation to get to and from appointments. 
With this new knowledge, you write an email to your supervisor expressing your concerns about the dataset. He agrees with your concerns, but he’s also impressed with what you’ve learned and thinks your findings could be very important to the project. He asks you to change the business task. Now, the NDS campaign will be about educating dental offices on the challenges faced by senior citizens and finding ways to help them access quality dental care. 
~~~

### Question 8
The business task has changed. What is the nature of that change?

* Using a database instead of a spreadsheet
* ```Defining the new question or problem to be solved```
* Creating a graphical representation of the data
* Conducting a gap analysis

~~~
* Scenario 2 continued *
You continue with your analysis. In the end, your findings support what you discovered during your online research: As people get older, they’re less likely to attend follow-up dental visits. 
But you’re not done yet. You know that data should be combined with human insights in order to lead to true data-driven decision-making. So, your next step is to share this information with people who are familiar with the problem professionally. They’ll help verify the results of your data analysis.
~~~

## Question 9
Fill in the blank: Subject matter experts are people who are familiar with a problem. They can help by identifying inconsistencies in the analysis, _____, and validating the choices being made. 

* creating a presentation with the data
* collecting data relevant to the business problem
* redefining the business problem
* ```offering insights into the business problem```

~~~
* Scenario 2 continued *
The subject-matter experts are impressed by your analysis. The team agrees to move to the next step: data visualization. You know it’s important that stakeholders at NDS can quickly and easily understand that older people are less likely to attend important follow-up dental appointments than younger people. This will help them create an effective campaign for members.
It’s time to create your presentation to stakeholders. It will include a data visualization that demonstrates the lifetime trend of people being less likely to attend follow-up appointments as they get older.
~~~

## Question 10
You recognize that this data is given in series. What type of data visualization is most effective to visualize this data?

* A doughnut chart
* ```A line chart```
* A box plot
* A table
