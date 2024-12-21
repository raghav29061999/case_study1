<!-- 1. Business Case: <brand> - Descriptive Statistics & Probability -->


# Mindset:

    Evaluation will be kept lenient, so make sure you attempt this case study.
    Read the question carefully and try to understand what exactly is being asked.
    Brainstorm a little. If you’re getting an error, remember that Google is your best friend.
    You can watch the lecture recordings or go through your lecture notes once again if you feel like you’re getting confused over some specific topics.
    Discuss your problems with your peers. Make use of the Slack channel and WhatsApp group.
    Only if you think that there’s a major issue, you can reach out to your Instructor via Slack or Email.
    There is no right or wrong answer. We have to get used to dealing with uncertainty in business. This is exactly the skill we want to develop.

# About <brand> 

    <brand> is a leading brand in the field of fitness equipment. <brand> provides a product range including machines such as treadmills, exercise bikes, gym equipment, and fitness accessories to cater to the needs of all categories of people.


# Business Problem

    The market research team at <brand> wants to identify the characteristics of the target audience for each type of treadmill offered by the company, to provide a better recommendation of the treadmills to the new customers. The team decides to investigate whether there are differences across the product with respect to customer characteristics.

    Perform descriptive analytics to create a customer profile for each <brand> treadmill product by developing appropriate tables and charts.
    For each <brand> treadmill product, construct two-way contingency tables and compute all conditional and marginal probabilities along with their insights/impact on the business.

    Dataset

    The company collected the data on individuals who purchased a treadmill from the <brand> stores during the prior three months. The dataset has the following features:

    <!-- Dataset link: <brand>_treadmill.csv -->

    Product Purchased:	KP281, KP481, or KP781
    Age:	In years
    Gender:	Male/Female
    Education:	In years
    MaritalStatus:	Single or partnered
    Usage:	The average number of times the customer plans to use the treadmill each week.
    Income:	Annual income (in $)
    Fitness:	Self-rated fitness on a 1-to-5 scale, where 1 is the poor shape and 5 is the excellent shape.
    Miles:	The average number of miles the customer expects to walk/run each week

## Product Portfolio:

    The KP281 is an entry-level treadmill that sells for $1,500.
    The KP481 is for mid-level runners that sell for $1,750.
    The KP781 treadmill is having advanced features that sell for $2,500.

## What good looks like?

    Import the dataset and do usual data analysis steps like checking the structure & characteristics of the dataset
    Detect Outliers (using boxplot, “describe” method by checking the difference between mean and median)
    Check if features like marital status, age have any effect on the product purchased (using countplot, histplots, boxplots etc)
    Representing the marginal probability like - what percent of customers have purchased KP281, KP481, or KP781 in a table (can use pandas.crosstab here)
    Check correlation among different factors using heat maps or pair plots.
    With all the above steps you can answer questions like: What is the probability of a male customer buying a KP781 treadmill?
    Customer Profiling - Categorization of users.
    Probability- marginal, conditional probability.
    Some recommendations and actionable insights, based on the inferences.
    Later on, we will see more ways to do “customer segmentation”, but this case study in itself is relevant in some real-world scenarios.


# Evaluation Criteria

    Defining Problem Statement and Analysing basic metrics (10 Points)
    Observations on shape of data, data types of all the attributes, conversion of categorical attributes to 'category' (If required), statistical summary
    Non-Graphical Analysis: Value counts and unique attributes ​​(10 Points)
    Visual Analysis - Univariate & Bivariate (30 Points)
    For continuous variable(s): Distplot, countplot, histogram for univariate analysis (10 Points)
    For categorical variable(s): Boxplot (10 Points)
    For correlation: Heatmaps, Pairplots(10 Points)
    Missing Value & Outlier Detection (10 Points)
    Business Insights based on Non-Graphical and Visual Analysis (10 Points)
    Comments on the range of attributes
    Comments on the distribution of the variables and relationship between them
    Comments for each univariate and bivariate plot
    Recommendations (10 Points) - Actionable items for business. No technical jargon. No complications. Simple action items that everyone can understand

### Submission Process:

    Type your insights and recommendations in the text editor.
    Convert your jupyter notebook into PDF (Save as PDF using Chrome browser’s Print command), upload it in your Google Drive (set the permission to allow public access), and paste that link in the text editor.
    Optionally, you may add images/graphs in the text editor by taking screenshots or saving matplotlib graphs using plt.savefig(...).
    After submitting, you will not be allowed to edit your submission.