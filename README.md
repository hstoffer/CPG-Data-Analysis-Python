# CPG-Data-Analysis-Python

To make data useful is dependent on building solid foundational skills such as managing data structures, performing data wrangling, computing and visualizing statistical relationships, managing various environments conducive for statistical analysis, and performing machine learning modeling. 

Nowadays, data scientists still spend an excessive amount of time obtaining data, diagnosing data quality issues, and preprocessing data into usable form. In fact, research has illustrated that this portion of the data analysis process is the most tedious and time consuming, often consuming 50 to 80% of an analyst's time. Consequently, strong foundational skills in statistical computing and data science remains the fundamental building block to any successful data analysis, and that is the purpose of this course. You will learn the fundamental skills required to acquire, manage, transform, manipulate, and visualize data in a computing environment that fosters reproducibility. 

We will start this course by learning the mental model of the data science ecosystem, and this includes commonly used libraries and capabilities, often the vocabulary that is often used across industry, and many other widely available Python resources for the purpose of statistical computing and data science. By the end of this course, you'll have the ability to use Python both within interactive and non-interactive environments. That is, we will be using Jupyter notebooks (interactive) and gain the skills of writing a Python script and executing that script in a non-interactive way, which is extremely common within the industry. 

You'll be able to perform core data wrangling activities, such as importing data, reshaping data transforming data, and exporting data, and you'll learn how to compute descriptive statistics and visualize key patterns and relationships within your data. You'll also be exposed to modeling via scikit learn, and we'll discuss the fundamentals of building models in Python. And you'll also be exposed to resources that you can use to continue building that capability even after this class. And most importantly, you're going to end up having the resources and understanding to continue advancing your statistical computing capabilities within Python on your own. 

The class is structured as weekly modules. Consequently, there are seven modules to complete, and each module will have three or four lessons to work through. For each lesson, you will read and work through tutorials. Short videos will be sprinkled throughout the lesson to further discuss and reinforce lesson concepts. And these lessons are designed to be very hands on so that you get comfortable writing code to perform your data analysis. There will be a short quiz associated with each lesson. These quizzes will be done via Canvas. There will be a lab associated with each module. These labs will guide you through a case study, step by step. The goal is to provide a detailed view on how to manage a variety of complex real-world data, how to convert real problems into data wrangling and data analysis problems and apply Python to address these problems and extract insights from the data. Upon completing the lab, you will use your analysis to answer questions contained in a lab quiz. Details and dates for these lab submissions can be found on Canvas. And lastly, there will be a final project to complete by the end of the last week of class. This final project is designed for you to put to work the tools and knowledge that you gain throughout this course to complete and deep dive analytic report and presentation. You can find more details on this project in Canvas. The course covers a lot of material, and if you're not proactive and you don’t keep up with the work, you will fall behind quickly. Therefore, work together and collaborate with your classmates. Data science is not done in isolation in the real world, and so is this course. 

1. Installed Anaconda
2. Create Python Environment -> Launched Anaconda Navigator
3. Installed JupyterLab and Notebook
4. Launched JupyterLab

5. Scenario
You are working as a data scientist for a national grocery chain named Regork. You have been charged with identifying a potential area of growth where the company could invest future resources to increase revenue and profits. Your manager has asked that you prepare a report that outlines your findings along with a 3-minute presentation for the CEO. Good luck!

Business Question
Organizations are always looking for growth opportunities. Unfortunately, this can be quite vague and you, as the data scientists, are required to interpret, identify, and defend your proposition.  So where do we find growth opportunities? The following are some examples:

Maybe a certain demographic group is generating large amounts of revenue for a particular product, and we could invest to capture market share in this area?
Is there a certain demographic group that we notice is not buying particular products? This could be for valid reasons, or it could be because there is insufficient marketing to this group. This could be an opportunity to increase awareness of these products for this demographic group to gain more interest.
Do we notice a trend (positive or negative) where purchasing behavior is changing over time. Maybe sales volume is increasing for a particular product or customer segment, and we could invest in marketing to hopefully compound this trend?
Do certain products tend to be purchased with other products on a regular basis? For example, when customers purchase frozen pizzas, do they often purchase beer at the same time? Identifying these relationships can help marketing develop paired product marketing plans.
Do certain products have spikes on particular dates (i.e., holidays)? Identifying these relationships can help marketing create relevant marketing plans based on the calendar.
Are certain marketing campaigns more successful than others in driving sales volume or revenue? 
Are certain coupons or promotions more impactful than others?

The list is endless and it's your job to propose the business question of interest and use the data and your data wrangling skills to answer the question. Keep in mind that your initial business question may change as you dive deeper into the data and find insights. Regardless of the business question you start researching, your final report should have one clear business question that is addressed.

Analytic Approach
Coming up with a business question is one thing but interpreting the business question into the analytic approach is another.  You will be charged with defining the logical approach to answer the business question of your choice. For example, say the business question is "Do customers that purchase frozen pizzas have a greater tendency to also purchase beer at the same time?"  To answer this question your analytic approach could include:

Joining transactions with product information data.
Performing regular expressions to identify relevant pizza and beer products.
Creating a variable that indicates when both items are purchased versus transactions where neither (or one but not the other) are purchased.
Computing relevant summary statistics that will indicate if the probability of purchasing these together are greater than the probability of purchasing one but not the other.
Along the way you should be asking yourself:  Do subgroups matter in the data? Do there appear to be data quality concerns? Are trends over time important? Could other variables be impacting my findings?

Regardless of the approach, your report should be a logical, cohesive story that addresses the business problem --- not simply a bunch of graphs created for the sake of making them. 

Also, simplicity is often the key to great analyses. Simple descriptive statistics can (and usually) yield more of an immediate impact than a complicated model. Brooke WatsonLinks to an external site. gave a compelling and enlightening presentation at the 2019 RStudio Conference on how the ACLU used various R packages to count and reunite families.

Data
You will be using the Complete Journey dataLinks to an external site. to answer your business problem. You are required to use the full data sets rather than the sampled data sets (i.e. get_transactions() rather than transactions_sample, get_promotions() rather than promotions_sample). At a minimum you should be using at least two different data sets to address your problem (in other words I expect you to have to join data sets in various ways). 

Deliverables
You will have two deliverables: (i) a report and (ii) a 3-min presentation.

Report
This is an analytic report that is written and published as a Jupyter Notebook PDF report that provides the sections in the grading rubric below. You will need to import, assess, clean & tidy the data, and then come up with your own research questions that you would like to answer from the data by performing exploratory data analysis (if you’d like to perform a predictive model to answer your hypothesis that is fine, but it is not required).  

https://www.loom.com/share/fc95348d123c4c97bd3664fd7a8bb13e?sid=cd17342f-f468-44c1-95c3-414bffee0989 
