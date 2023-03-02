# Accenture-Internship---data-analysis

## Intro

### What you’ll achieve

1. You get relevant work experience taught by our team
2. Add the program as a Certification to your Resume and LinkedIn
3. Stand out in applications and interviews - talk about the job skills you've learned and why you're a good fit for the team.

### Key facts

- You are working as a Data Analyst at Accenture.
- You work within a larger team, where each member has a different role and level of responsibility.
- Your team has been assigned a new project for a client called **Social Buzz.**
- You’re hoping for a promotion at work, and this is an exciting opportunity for you to showcase your data analysis and visualization skills.

### Key roles and responsibilities of a Data Analyst

A data analyst sits between the **business** and the **data.**

- **The Business** refers to the client and your internal team members who won’t be involved in detailed data analysis.
    - They rely on your analysis to make strategic business decisions.
    - Importantly, not everyone will have a strong understanding of data. Your job is to communicate your data findings simply and clearly for everyone to understand.
- **The Data** refers to the relevant data sources that you will clean, process, and use to generate interesting insights for the business.

### The brief

Your first task is to read the brief from Social Buzz and complete a short knowledge check before the call.

Read the brief to:

- Understand the client and business problem at hand.
- Identify the requirements that need to be delivered for this project.
- Identify which tasks you should focus on as a Data Analyst.

Here are some resources to help you

**Big Data** refers to large, diverse sets of information that grow at ever-increasing rates. It includes the volume of information, the velocity or speed at which it is created and collected, and the variety or scope of the data points being covered (known as the "three v's" of big data). Source: [Investopedia](https://www.investopedia.com/financial-edge/0312/ipos-for-beginners.aspx).

An **IPO** stands for Initial Public Offering - this happens when a private company becomes public by selling its shares on a stock exchange.

The client has sent through:

- 7 data sets - each data set contains different columns and values
- A data model - this shows the relationships between all of the data sets, as well as any links that you can use to merge tables.

Follow these steps:

1. [Requirements gathering](https://www.notion.so/Accenture-Virtual-Internship-4707e42767594f8b93ca047153f970e2)
2. Data cleaning
3. Data modelling

Definitions of different data types:

- **String** - Sequence of characters, digits, or symbols—always treated as text
- **UUID -** Universally Unique Identifiers
- **Array -** List with a number of elements in a specific order—typically of the same type
- **Integer -** Numeric data type for numbers without fractions
- **Timestamp** - Number of seconds that have elapsed since midnight (00:00:00 UTC), 1st January 1970 (Unix time)


**Reaction, Content, Reaction Types**

To clarify why you made this selection:

- The brief carefully it states that the client wanted to see “An **analysis** of their **content categories** showing the **top 5** categories with the largest popularity”.
- As explained in the data model, popularity is quantified by the “Score” given to each reaction type.
- We therefore need data showing the content ID, category, content type, reaction type, and reaction score.
- So, to figure out popularity, we’ll have to add up which content categories have the largest score.

### Data Cleaning

Clean the data by:

- removing rows that have values which are missing,
- changing the data type of some values within a column, and
- removing columns which are not relevant to this task.
    - *Think about how each column might be relevant to the business question you’re investigating. If you can’t think of why a column may be useful, it may not be worth including it.*
    
    ### Columns to keep

**Reaction** 

Content ID 
Type

**Content**

Category
Content ID
Type

**ReactionType (all)**

Type
Sentiment
Score

### Data Visualisation

### Create a presentation

Planning the presentation structure

- Agenda - What will your presentation cover?
- Project Recap - What are the key points from the brief?
- Problem - What is the problem that you answer in this presentation?
- The Analytics team - Who is on your team?
    - As a reminder from the earlier task - this includes: Andrew Fleming (Chief Technical Architect), Marcus Rompton (Senior Principle), and yourself!
- Process - How did you complete your analysis?

### Create data charts

Present the top 5 categories. 

There are also some other interesting insights that we might want to share with them. For example:

How many unique categories are there?
How many reactions are there to the most popular category?
What was the month with the most posts?
