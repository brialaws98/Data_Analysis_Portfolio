## Project Understanding
#### Here are some key facts:
* You are working as a ***Data Analyst*** at *Accenture*
* You work with a larger team, where each member has a different role and level of responsibility
* Your team has been assigned a new project for a client called ***Social Buzz***
* You're hoping for a promotion at work, and this is an exciting opportunity for you to showcase your data analysis and visualization skills
#### Key roles and responsibilities of a Data Analyst
* A data analyst sits between the **business** and the **data**
    * What does that mean?
        * ***The Business*** refers to the client and your internal team members who won't be involved in detailed data analysis
            1. They rely on your analysis to make strategic business decisions
            2. Not everyone will have a strong understanding of data. Your job is to communicate your data findings simply and clearly for everyone to understand
        * ***The Data*** refers to the relevant data sources that you will clean, process, and use to generate interesting insights for the business
#### Brief Business Task
  * The client has reached a massive scale within recent years and does not have the resources internally to handle it
      * Stated the scale was a big problem of theirs and they are struggling to manage the scale with the resources that they currently have
      * Looking for help with the management of their journey into such a large scale
#### Meet your team
  * The team is structured into 3 groups:
      * ***Industry experts*** in social media space to ensure we accurately understand Social Buzz's sector
      * ***IPO exports*** who will deliver on the IPO requirement
      * ***Data exports*** who will provide Big Data insights and content category analysis. This is where you sit!
          * You will analyze sample data sets with visualizations to understand the popularity of different content categories
  * Your team will consist of a:
      * ***Chief Technology Architect***
      * ***Senior Principal***
      * ***Data Scientist***

## Modeling data to create valuable insights
#### Diving into the data
* Here is what the client has sent:
     * ***7 data sets*** - each data set contains different columns and values
     * ***A data model*** - This shows the relationships between all of the data sets, as well as any links that you can use to merge tables
#### Requirements gathering
* You won't need all 7 datasets to find what you are looking for
* What is the first step?
     * Use the ***data model*** to identify which datasets will be required to answer your business questions
          * Figure out which the ***top 5 categories*** with the largest popularity
     * Three data sets you will need to complete your analysis:
          * Reaction
          * Content
          * Reaction Type
#### Data sets - Quick Explanations
* The brief states that the client wanted to see "An **analysis** of their **content categories** showing the **top 5** categories with the largest popularity"
* As explained in the data model, popularity is qualified by the "Scors" given to each reaction type
* We therefore need data showing the content ID, category, content type, reaction type, and reaction score
* To figure out the popularity, we'll have to add up which content categories have the largest score
#### Data Cleaning
1. Download the CSV files
2. Clean the data by:
      * Removing rows that have values that are missing
      * Changing the data type of some values within a column
      * Removing columns that are not relevant to this task
           * *Think about how each column might be relevant to the business question you're investigating. If you can't think of why a column may be useful, it may not be worth including it*
#### Data Modelling
1. ***Create a final dataset by merging your three tables together***
   * Use the Reaction table as your base table, then first join the relevant columns from your Content data set, and then the Reaction Types data set
2. ***Figure out the Top 5 performing categories***
   * Add up the total scores for each category
***Tools used for this section***
* BiqQuery for SQL
