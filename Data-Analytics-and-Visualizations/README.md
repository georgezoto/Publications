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

**What do I look for in a modern Business Intelligence Tool**  
A research article published in Forbes back in 2016 found that 80% of the time data scientists spend is actually spent in collecting, cleaning and organizing our datasets. This is almost the equivalent of working on a project for five days, just to get the chance to analyze it and draw your conclusion on the weekend. I am not sure about you, but that seems like a lot of time.

Here are the twelve most important criteria I consider when evaluating a modern Business Intelligence tool. Criteria two to six orbit around the quality of the final product while criteria one and seven to twelve, focus on the technical side of a tool.

**I. Cleaning and Data Organization**  
An ideal tool should be able to recognize a structured dataset in a well defined format. A comma separated values (csv) format or web access logs are such good examples. In case where the underlying data is semi-structured and follows its own format, an option to parse it and extract only the relevant fields is a must-have feature for a modern tool. Finally, in the case of raw unstructured data or data in non-machine friendly format (pdf files for example, heavily nested headers and rows in a table or just raw numbers and text), there isn’t much any current tool can do. I see some great interest in using machine learning in discovering patterns and underlying data types in such cases, but from my experience, this is mostly a work in progress or a research topic thus far.

An important factor here is Data Quality. Tim Berners-Lee, the inventor of the Web and Linked Data initiator, suggested a 5-star deployment scheme for Open Data, where based on format and structure, different datasets are awarded a score based on how accessible and readable they are. Going from one star and progressing to five, a datasource author is not only providing raw data but also structure, non-proprietary open formats and sharable context. In many cases, this data quality can make or break data analysis in modern Business Intelligence tools.

**II. Cost**  
Like everything in life, all these great features and hard work come at a cost. It is important to make a budget analysis and think of two main directions:
1. The cost of the tool taking into account all the features it offers as well as the number of users that can use it over a long period of time. Many tools offer an upfront charge for a license per user or per installation, while others offer a subscription model per user, per month. It is good to think about scalability at this point and try to forecast how this number would change if your organization went from a 10% adoption rate to a 50% rate or later on to a 100% adoption rate.
2. The cost of having data silos and not being able to integrate all of your organization’s data sources on a common platform that would allow you to look at the bigger picture hiding behind your data. Unfortunately, in today’s world, this is not that uncommon, with each data management solution having its own language or format and not being able to “talk” to one another.

**III. Market Segment, Product Reviews and Online Presence**  
This is the case for almost every decision we make online. This is why the marketing field will always be a popular one in my opinion. Having great real cases, positive reviews and success stories is imperative for a modern platform. I try my best for my work to speak for itself, so I won’t have to say a word. This is why an instant surprise or impression on the capabilities of a tool is highly desirable.

It is also important to try and figure out where does each platform you are evaluating fit into the bigger picture. Is it geared more towards personal use? Can it handle high volume or scale of data? What about a wide variety of data? How about velocity or speed of data being generated? Can it assist you with validating any of the incoming datasets against others or reducing any noise or bias in your data (veracity of data)? Finally, is this platform production ready, battle proven and used by modern startups or larger companies? Does it allow you to setup your own data engineering and orchestration environment and does it allow you to do any performance tuning based on your specific use cases and scenarios ?
I guess the other side of the coin here is, do you and your organization really know what you need and therefore what to really look for?

**IV. 0 to 60**  
Zero to sixty literally means how easy and fast you can go from holding a dataset in your computer or available somewhere online, import it to a Business Intelligence tool, analyze it and create a simple visualization from it. Think of Microsoft Excel for example and how easy it is for someone to just open a CSV file, create a pivot table and visualize your findings in a few clicks. Personally, I have seen several tools that are experts in this topic and other ones that take a few extra steps to get to the finish line. If your day to day activities are around simple tasks with minimal or no development time at all, then obviously you would need to steer your attention in this direction. With several tools offering a trial period of exploring their main features, you should be able to get a basic understanding of where they score in this criterion.

**V. Interactivity, APIs and Accountability**  
Looking at modern Business Intelligence tools over time, I have noticed a movement towards user interactivity and user engagement. As a daily user of such a product you would perhaps prefer one that allows you to easily interact with it, keep the simple tasks simple and even customize parts of it to better fit your data exploration preferences. It would be ideal if a modern tool actually did some of the trivial tasks for you or at least recommend an initial analysis or data wrangling so you don’t have to start from scratch with every new dataset you explore. Personally, I have come across tools that actually allow you to ask your own questions in a simple language and let it identify the underlying task of performing the right analysis and present the results back to the user. I have also come across tools that based on a well known or well formatted dataset, perform an initial analysis for you and create live, interactive, dashboards automatically with zero involvement on your part.

Similar to user interaction, another criterion that is important today is the notion of “APIs as first citizens” or the ability for a modern tool to “speak” the modern machine-friendly language behind an Application Programming Interface. Think of it as the alphabet for a modern tool, without such a feature it cannot communicate or exchange information with any other tool or datasource out there. If you support it natively, a whole new world is open for exploration, as long as security in always kept in mind.

Finally, a criterion that often gets overlooked, is the ability for a modern tool to monitor itself and report back to the user its performance over time during the data collection process, the data analysis process and the data presentation process. All these processes are covered later in detail. Think of it as the analogous of task manager or activity monitor in your computer or smartphone. This feature provides an accountability feature in terms of what is really happening under the hood. Are simple tasks taking too many resources to fulfill or can the tool run under the specifications mentioned upon purchase? With many tools running in a cloud environment, this might not be concern, but as an informed buyer, you should know what you really paid for and how many resources you would need in the future. It also helps your data engineering team in another aspect: scalability. Looking at your tool’s performance for 1 user, 10 datasets and 30 visualizations for example, you can roughly estimate your resources needs, either on-premise or in the cloud, to multiple users, datasets and visualizations.

**VI. Open-source vs Proprietary, Release Cycle, Support and Community**  
The last criterion related to the quality of a modern Business Intelligence tool has to do with the actual developers behind it, the support team, the sales team and most importantly for me, the community behind a product.

Personally, I feel it really makes a difference if you ask yourself one simple question: where do you feel most comfortable putting your data analytics investments in, behind a community or behind a product?

This is exactly what differentiates an open-source tool versus a proprietary one. In most cases, active open-source products have hundred or thousands of developers behind them, creating new features, fixing existing issues, releasing new versions and so on in a continuous cycle. The beauty of it is that you too can become part of this rich ecosystem. Thanks to discussion forums and GitHub, a modern web-based hosting service for software version control, you can:
1. Participate in discussions taking place online around any relevant topic.
2. Open an issue ticket and share with the rest of the community an issue or bug you found in one of the major or minor version of the tool you are using.
3. Request a new feature or enhancement that is currently lacking from your data engineering pipeline or implementation.
4. Fork or duplicate the existing master release and develop your own version of the tool or feature that is currently not available or is applicable specifically to your implementation.

Open-source products usually have a plurality of voices and opinions behind them. You can be one of them, shaping the look and feel of a product for a future release. It makes a difference between a lively and active community of thousands of developers versus a specific product meeting a given set of specifications.

Another aspect that is important to me is how often a company behind a tool organizes conferences, informs the community about its upcoming features, invites users from all spectrums of the industry sharing their best practices and applications of a tool in their data engineering pipeline and more. It also makes a big difference if the tool is heavily developed and released at least in annual cycles or ideally in 6-month cycles. This way hot features requested by the community and important bug fixes are addressed in a timely manner.

Finally, getting a sense early on of the level of technical support and sales team support and flexibility on the product is critical to success. Ideally, a great technical support team that does not over-promise any implementation details and is there when you need it the most, as well as a flexible sales team that is not just trying to sell their next product, but is instead actually interested in your use case of the tool, are important criteria that I pay attention to.

**VII. Data Collection and Data Resiliency**  
This part of the article, including the first criteria, focuses more on the technical side of each Business Intelligence tool. For this criteria, I look for a tool this is rich in inputs or data connectors. Modern tools offer support for flat files in csv, text, xml, excel, pdf , json or geojson format. They also offer support for SQL-like datasources like Salesforce or Oracle as well as No-SQL databases like MongoDB or Redis. Ideally, you would also need support for AWS products as datasources, Social Media, Email platforms, Point of Sale systems and Internet of Things devices. It might not seem necessary in the beginning of your Big Data platform deployment, but over time you will, most probably, see a need for it.

Also, a modern tool should support connectivity with public data sources like Data.gov or World Bank or even more publicly available sources for example on government, global issues, scholarly articles, social media, marketing, science, journalism, media and much more. Some tools rely on the underlying APIs that these datasources offer, while others have special connectors that hide all the connectivity details to the user and abstract away the notion of accessing metric X from public datasource Y.

Finally, as data flows through your data collection pipeline, your platform may encounter situations that prevents it from delivering new data or events to your expected output. Data resiliency ensures that a policy is in place for such scenarios that would at least notify you when unexpected data types appear or a process you are listening to, terminates abnormally. A desired feature would be to record such unexpected events or new data for further processing or have a best-effort approach where some basic transformation is applied before a second data ingestion process initiates. Also, due to the native bursting nature of streaming data, a modern tool should be able to integrate with queuing platforms such as Apache Kafka. This way, any momentarily increase in data traffic would not be lost, but buffered for further processing.

**VIII. Data Storage and Data Wrangling**  
It is important to perform research on the underlying storage engine each tool uses and therefore which data types and formats are treated as first class citizens by such a platform. Columnar storage engines, for example, tend to better suit a need where you know your data structure well in advance and require minimum setup and maintenance. Adding a new datatype in the future is doable, but is an expensive process. A document oriented storage engine on the other hand, can allow for any data structure as well adding or deleting new fields from upcoming traffic. Modern Business Intelligence tools might hide away all these technical details but an informed data engineer should be able to research such details or at least estimate the underlying storage engine used.

Another feature that modern tools offer is the ability to adapt your underlying data format according to your best knowledge. They allow you to convert data types, extract subfields, convert fields based on local or external lookups, mutate fields, delete fields or records, deserialize data in popular formats and more. No platform knows the data better than the actual user, so this is a highly desirable feature.

Finally, from my personal experience, it is worth highlighting the notion of available but intractable data versus easily found data in any underlying collection of datasets. For example, your organization could posses a very large collection of datasets but if you cannot look at a sample document or a collection of documents satisfying a given criteria, data storage behaves more like data archiving. Search is an important feature in today’s world of exploding data and over time it will probably become one of the most important ones. Being able to create a “hot” and “cold” data pipeline is critical in a production environment where data-driven decisions are made based on a high volume of temporarily short dataset. A combination of two different storage technologies or formats is usually able to support such pipeline architectures.

**IX. Data Analysis, Enrichment and Join**  
It is important to understand that all previous steps and features aim to fuel this core step, the actual analysis and exploration of your data, finding patterns, looking at correlation between different fields or building a model that can describe an underlying phenomenon in your data with some level of accuracy. From my experience, a modern Business Intelligence tool can assist a user to go from data to information, from seemingly unstructured or noisy data to structured data and ultimately from questions to answers. A tool should also aim to be efficient and recognize any inherent parallelism that can be exploited in the underlying data during data processing.

Given that each data analysis process follows the pattern: Question -> Data wrangling -> Exploration -> Conclusions -> Communication, it is important to realize that the first three to four steps will undergo a continuous loop until a satisfying level of conclusions are reached. In practice, this means that during the data analysis step, the user will most probably have to enrich the underlying data with other datasets or also join them with existing or new datasets on a common key. This need for continuous search of new dataset and integration with existing ones is key to in-depth analysis.

Finally, several Business Intelligence tools offer the capability to perform temporal analysis, location based analysis, keyword based analysis, graph or connection based analysis, statistical analysis, machine learning analysis and more. It is important to understand the opportunities and limitations that each approach and capability offers.

**X. Data Visualization and Storytelling**  
If the previous step of data analysis was the cake, this step is definitely the frosting and cherry on top of a long process. Several Business Intelligence tools allow the user to select a visualization from a given set of predefined visualizations such as:

1. Line, Area or Bar charts
2. Pie charts
3. Data tables, Metrics, Goals and Gauges
4. Heat maps
5. Coordinate maps and Region maps
6. Timeseries
7. Scatter plots
8. Tree maps
9. Word cloud
10. Custom visualization library

As data scientists, knowing when to apply which type of visualization can make the difference between finding and telling an underlying story versus skipping it completely. As experts mention, data storytelling is a structured approach for communicating data insights, and it involves a combination of three key elements: data, visuals, and narrative. Combining your data with a narrative can explain your users what is really happening in the underlying dataset. When visuals and data are combined, patterns and outliers emerge that would otherwise be lost in a large data table. Also, combining narrative with visuals can engage the user to either investigate further or share findings with a larger audience. Finally, when all the elements of data, visualizations and narrative are combined, you have created a story that can drive decisions and affect change in your environment.

Personally, I have seen that a top-down approach can be an effective mechanism for storytelling. You keep in mind your audience’s existing knowledge, their curiosity and engagement on the subject you are covering as well as the depth and breadth of information your audience can consume. You then start with the highest possible level of explanation based always on aggregated data, narrative and visualizations. Then you slowly start descending your analysis and user attention to a more detailed and highly grained level, trying to keep the audience highly engaged in the meantime. Think of it as a detailed plane landing description from the pilot to your favorite vacation destination. It starts all the way high in the sky, to lower altitude, until you can actually see the mountains, lakes, buildings or the beach and sand at your favorite destination.

Deep knowledge of your data, creative thinking and “out of the box” narrative are necessary ingredients for compelling storytelling. They can reveal insights, influence decisions and drive users to action and engagement.

**XI. Data Sharing**
It is finally time to share and communicate your findings and interactive dashboard with the rest of your team, your organization or perhaps the entire world. Modern Business Intelligence tools allow you to export the entire data behind your analysis, or a filtered version of it, in various formats such as csv or pdf files. Some of them also allow you to share your findings with other tools such as AWS products. In many cases, the final product is a URL that can be embedded in an existing website as part of a larger product, campaign or storytelling. Either way, modern tools support a plethora of options.

In the spirit of reciprocity, few tools will actually support access to their underlying datasets, visualizations and dashboards over an API. This way they become themselves datasources for other tools in a similar way that another tool or platform was a datasource for them. Passing on the torch of responsible data sharing is part of larger concept known as data democratization that I will touch upon in the Summary section.  


 
