# *llSPS-INT-62-AI-Powered-News-Search-App-Level-1*
## *AI Powered News Search App (Level-1)*
### *Project Summary:*
*The web is home to massive amounts of data, with more being created every day. Organizations can harness this constant stream of information to gain understanding, plan strategies, and find opportunities. Enriched news data can help your application make dynamic connections across current events faster.*


### *Description*
*This code pattern shows you how to tap into massive data sets to mine insight. You'll build a news mining web application with the Watson Discovery service using the Watson Node.js SDK.*


##### *The app demonstrates two use cases using Watson Discovery News:*
###### *Search*: 
- *Query for the most relevant new articles about a specific topic or subject. Because the news collection is pre-enriched with natural language processing, you can query not just on keywords or categories but also on concepts, sentiment, and relations to get richer search responses.*

###### *Trending topics in the news:* 
- *Identify popular topics over the past 24 hours. Topics can be general, or specific to an industry or category.*



*To do this, we’ll use:*

   - *Build a Server Side Application using Node-RED.*
   - *Use the pre-built Watson Discovery News collection.*
   - *Access the Watson Discovery Service through the Discovery API.*
   - *Use a Slack interface to query the data.*
   - *Deploy the app on IBM Cloud.*


![](Readme%20images/flow.jpg) 

1.	*The user interacts with the app UI(Built with Node-RED or Cloud or Local) to request relevant news content.*
2.	*The app sends user requests to Watson Discovery News.*
3.	*The Watson Discovery Service is continually crawling the web to update its Discovery News collection.*
4.	*The Watson Discovery Service responds to Slack search requests.*



### *Technologies Used:*
   - *Node.js: An asynchronous event driven JavaScript runtime, designed to build scalable applications.*
   - *React: Javascript library for building User Interfaces.*
   - *Express: A popular and minimalistic web framework for creating API and Web server.*
   - *Slack: Slack is a cloud-based set of team collaboration tools and services with chat bot integration.*
   - *Botkit: Framework for creating and managing chat bots.*
   - *Watson Discovery: A cognitive search and content analytics engine for applications to identify patterns, trends, and actionable insights.*


#### *Project Presentation Link:*
*https://drive.google.com/open?id=18Gh1b_thENi3hUAf-CnReQVL6rM2tfH2*

