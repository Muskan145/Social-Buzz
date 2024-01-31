
# Social Buzz

- **Client name:** Social Buzz

- **Client industry:** Social media & content creation

- **Year established:** 2010

- **Location of HQ:** San Francisco

- **Number of employees:** 250

Social Buzz emphasizes content by keeping all users anonymous,
only tracking user reactions on every piece of content.
There are over 100 ways that users can react to content, spanning beyond the traditional reactions of likes, dislikes, and comments. 

Over the past 5 years, Social Buzz has reached over 500 million active users each month. They have scaled quicker than anticipated and need the help of an advisory firm to oversee their scaling process effectively. Every day over 100,000 pieces of content, ranging from text, images, videos and GIFs are posted. All of this data is highly unstructured and requires extremely sophisticated and expensive technology to manage and maintain.

## Problem Statment:

        An analysis of their content categories that highlights the top 5 categories with the largest aggregate popularity.

### The client has sent the data you have to work with:

- **7 data sets** - each data set contains different columns and values
- **A data model** - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.

### Tasks to be delegated:
- Extraction of sample data sets using SQL
- Requirements gathering, Data cleaning and Data modelling
- Merging of sample data set tables
- Analysis of sample data sets with visualizations

## Steps Followed

**Step 1:** Clean the data by:

- removing rows that have values which are missing
- changing the data type of some values within a column
- removing columns which are not relevant to this task

**Step 2:** Create a final data set by merging three tables together

- Using Reaction table as a base table
- first join the relevant columns from Content data set, and then the Reaction Types data set using “VLookUp” formula

**Step 3:** Figure out the Top 5 performing categories

- Add up the total scores for each category by using “Sum If” formula
- find the top 5 categories according to total scores
- find total reaction of top 5 categories overall and monthwise

**Step 4:** visualizations of findings using bar graphs 
- Bar graph shows top 5 categories
- Bar graph shows total reaction of top 5 categories
- Bar graph shows total reaction monthwise
- pi chart shows percentage of total reactions


        Snap of visualizations
![2024-01-28](https://github.com/Muskan145/Social-Buzz/assets/105537965/b4d77d71-94f6-4613-8e13-9db9ba2fd631)

## Analysis

Animals and Science are the two most popular categories of content, showing that people enjoy "real-life" and "factual" content the most.

## Insight

Food is a common theme with the top 5 categories with "Healthy Eating" ranking the highest.
you could use a insight to create a campaign and work with healthy eating brands to boost user engagement.
