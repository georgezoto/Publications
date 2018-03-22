# Data Analytics and Visualizations - A personal journey  

A companion repository for my Medium article avaialble at: https://medium.com/datajournos/data-analytics-and-visualizations-a-personal-journey-b1a1318e24db

![alt text](images/Data-Analytics-and-Visualizations.jpg)

Over time we have seen several Business Intelligence tools emerge, some of them promising to take our analysis to the next level, while others assist us with developing stunning visualizations that tell a compelling story. Discovering such stories behind massive datasets is my day to day job at a local non-profit that is dedicated to end childhood hunger. I thought I would share my journey and comparison criteria with you when evaluating a modern Business Intelligence tool. Please keep in mind that this analysis is completely subjective and based on my previous experience. Before we dive right in, let me give you some more context on my background and how I approached the task of evaluating several such tools, not so long ago.

**Table of Content:**  
* My experience in the field of data analytics and visualizations  
* What do I look for in a modern Business Intelligence Tool  
* I. Cleaning and Data Organization  
* II. Cost  
* III. Market Segment, Product Reviews and Online Presence  
* IV. 0 to 60  
* V. Interactivity, APIs and Accountability  
* VI. Open-source vs Proprietary, Release Cycle, Support and Community  
* VII. Data Collection and Data Resiliency  
* VIII. Data Storage and Data Wrangling  
* IX. Data Analysis, Enrichment and Join  
* X. Data Visualization and Storytelling  
* XI. Data Sharing  
* XII. Security and Data Governance  
* Conclusion and Survey  

**My experience in the field of data analytics and visualizations**  
Education wise, I have a B.S. in Computer Engineering and Telecommunications and a M.S in Electrical Engineering. Before graduating back in 2012, my favorite and awesome Business Intelligence tool was Matlab. For many of you out there who do not know Matlab, think of it as a scientific workbench.

Matlab requires you to learn its syntax, but I really like the fact that “out of the box” you could:
1. Import your own data.
2. Perform analysis on it.
3. Visualize your findings and share them with the world, or in most cases your colleagues or your class professor.

If you think that sounds great, it gets better. The tool allows you to share your work with others or import their work in your environment as well as access literally hundreds of packages and tutorials from math and physics to control systems and biology. It’s not a coincidence that it is still the most popular tool in academia, at least in the STEM field.

In my first job as a System’s Engineer in a leading satellite communications company, I quickly saw the benefits of using a tool that in a few words, would allow us to:
1. Gather performance related data from many of the components that made all the magic happen and allowed a user from any place in the world to reach any other person or the Internet.
2. Analyze such data against our own performance benchmarks.
3. Identify outliers or patterns, especially when multiple users were using the system simultaneously.
4. Alert us on such patterns, if possible real-time.
5. Generate for us daily and weekly reports so we can allocate our resources in an optimum way over time and forecast for us our needs, in terms of resources, in the long-term future.

As much as I really liked Matlab, clearly it was not the right tool for the job. With that said, our company in general and not just me, had been developing their own tools that would accomplish as many items from this list as possible and in other cases purchased production level tools that would get the job done. Needless to say, both the in-house and purchased solutions needed to talk to each other and be able to exchange information when needed.

My team and I also wrote such tools mainly in Python and Java and utilizing open-source technologies and libraries such as Django, Pandas, Scikit, MongoDB, Fusioncharts, Hicharts, D3 and so on. I also designed and developed a feature that combined the easiness of asking human friendly questions with getting answers instantly in various formats such as graphs, timelines, dashboards or interactive queries. Making these tools even more accessible to users, I developed a popularity or community pulse feature where all users would see which topics, issues or searches were the most popular in the recent past and be able to ask the same question with the click of a button. Towards the end, I also started exploring machine learning. I was working towards integrating forecasting in one of our custom solutions, as well as towards generating weekly articles from the underlying data using natural language processing, coming one step closer to automated storytelling. In the end of a couple of months of hard work, we had our own custom Business Intelligence tools that fulfilled 99% of the criteria and tasks we originally aimed for. For every new feature needed, we simply had to develop, test and deploy it in production ourselves. Note, this was before modern Business Intelligence tools were popular or affordable so we didn’t really have any other choice. Even the ones that were present, Tableau being an example, didn’t satisfy more than 30% to 40% of our needs.

By the end of this beautiful journey in my previous company, new players had made their appearance such as Splunk, Hadoop and its rich ecosystem around Big Data, AWS, Tableau, Artificial Intelligence, IBM Watson and this new platform called Elasticsearch. Educating myself on many such platforms, with the help of Coursera, Udemy and Udacity and attending several meetups in the area, I started exploring the capabilities that such tools and platforms had to offer. I wanted to explore their kept and unkept promises as well as the teams behind them, their vision for their products and the communities around them. The next part of this article will hopefully shed some light in what do I look for in a modern Business Intelligence tool, as well as what did I have in mind while I was building my own custom tools.


