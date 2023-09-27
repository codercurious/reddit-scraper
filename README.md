Reddit Scraper offers a range of features that allow you to **extract data from [Reddit](https://reddit.com)** without any limitations

By utilizing our unofficial **Reddit API**, you can retrieve posts, comments, and user information

With Reddit Scraper you can do these: 
- **Scrape  subreddits** and retrieve their top posts, along with various details such as the post's title, text, username, number of comments, votes, and media elements. 
- **Scrape Reddit comments**
- **Scrape reddit user** details, their most recent posts, and comments. 

From Reddit, you can extract a wide range of data including popular subreddits, subreddit details such as the name, number of members, community URL, and category. 
Additionally, you can retrieve Reddit posts, their title and text, timestamps, usernames, as well as the URLs of the posts and comments. Furthermore, you can obtain user details, votes, media elements, as well as their recent posts and comments.

## Reddit api cost

The cost of scraping Reddit using Reddit Scraper on the Apify platform is far cheaper than official **reddit api pricing**. You can scrape thousands of reocrds with $5 free credits per month that comes with every Apify Free plan.
If you require regular access to more data from Reddit, we recommend [subscribing to Apify](https://apify.com/pricing). 

Scraping Reddit with Reddit Scraper does not require any coding skills. 
You simply need to create a free Apify account using your email, open the Reddit Scraper, and add one or more subreddits, users, or post URLs from which you wish to extract information. 
After clicking "Start," you can wait for the scraper to extract the data. 
Once the extraction is complete, you can download your data in JSON, XML, CSV, Excel, or HTML format. 

## Use cases of reddit scraper

- You can monitor discussions about your brand or product across Reddit communities, 
- Conduct research on topics that interest you, gain a wide range of opinions, 
- Stay informed about debates on finance, politics, new technology, and news in general, 
- Identify new trends, attitudes, and PR opportunities. 
- Reddit data can be leveraged to automatically track mentions of your business or desired topics and support sentiment analysis through scraping Reddit comments.

To scrape Reddit by URLs, you can input various types of URLs including those for scraping communities, channels within communities, popular communities, users, user comments, posts, popular posts, and search results for users, communities, or posts. 

For a complete list of input parameters, default values, and instructions on how to set your own values, please refer to the Input Schema tab.

Here is the sample output of this actor:

```json
[
	{
		"$type": "post",
		"id": "t3_14etyqz",
		"numComments": 8,
		"created": 1687312127000,
		"title": "Am I crazy?",
		"thumbnail": {
			"url": "self",
			"width": null,
			"height": null
		},
		"author": "Healy_Mcfeely",
		"authorId": "t2_6iy8hjdc",
		"upvoteRatio": 0.54,
		"numDuplicates": 0,
		"discussionType": null,
		"viewCount": 0,
		"goldCount": 0,
		"isArchived": false,
		"contestMode": false,
		"postCategories": null,
		"isSponsored": false,
		"isMediaOnly": false,
		"permalink": "https://www.reddit.com/r/pasta/comments/14etyqz/am_i_crazy/",
		"sendReplies": true,
		"voteState": 0,
		"isCrosspostable": true,
		"contentCategories": null,
		"subreddit": {
			"__typename": "Subreddit",
			"id": "t5_2qoor",
			"name": "pasta",
			"detectedLanguage": "en",
			"isEligibleForContentBlocking": true,
			"allowedMediaInComments": [
				"EXPRESSION"
			],
			"directoryRankings": {
				"rankings": [
					{
						"pageNumber": 9,
						"position": 2058,
						"sort": "MEMBERS",
						"totalRanked": 336527
					}
				]
			}
		},
		"text": "Hey guys, I was just wondering if I'm in the minority here. Everytime I cook/eat pasta, I prefer it on the firmer side. Not super firm or crunchy, just not mushy. But it seems everyone else I know likes the pasta to be as squishy as possible without falling apart. Everytime I eat pasta like that it just reminds me of spaghetti day in school. I was just wondering if I'm the crazy one here or what."
	},
	{
		"$type": "comment",
		"author": "Tommytrojan1122",
		"authorId": "t2_f19nsxjy",
		"collapsed": false,
		"collapsedBecauseCrowdControl": null,
		"collapsedReason": null,
		"collapsedReasonCode": null,
		"created": 1687313531,
		"deletedBy": null,
		"distinguishType": null,
		"editedAt": null,
		"gildings": null,
		"goldCount": 0,
		"id": "t1_jowtrda",
		"isAdmin": false,
		"isDeleted": false,
		"isGildable": true,
		"isLocked": false,
		"isMod": false,
		"isOp": false,
		"isSaved": false,
		"isScoreHidden": false,
		"isStickied": false,
		"parentId": null,
		"permalink": "/r/pasta/comments/14etyqz/am_i_crazy/jowtrda/",
		"postAuthor": null,
		"postId": "t3_14etyqz",
		"postTitle": null,
		"profileImage": "https://styles.redditmedia.com/t5_548ni7/styles/profileIcon_snoo9799d87d-5efd-4b19-bb55-250455255ce0-headshot.png?width=256&height=256&crop=256:256,smart&v=enabled&s=4f4d8dfca2986b14968d3202eeb2f3af483dfe73",
		"score": 6,
		"sendReplies": true,
		"subredditId": "t5_2qoor",
		"voteState": 0,
		"text": "I suspect you are in the majority. I love my pasta al dente."
	}
]
```

## FAQ

### Is Reddit scraping legal?
When engaging in Reddit scraping, it is crucial to adhere to Reddit's terms of service and uphold the site's usage policies. While scraping publicly available data from Reddit is generally permitted, it is essential to use the scraper responsibly, avoid excessive requests, and ensure that the scraped data is utilized in compliance with applicable laws and regulations. For more information on compliance with the terms of service, please refer to our blog post.

### Can I use Reddit API to scrape Reddit?
Reddit API is expected to transition into a paid service. Utilizing a Reddit web scraper, such as the one provided, offers advantages over the official API, as it does not require authentication, special authorization for commercial use, or registration for a token.

## How can I scrape Reddit comments?
The Reddit Scraper tool allows for the scraping of specific sections of Reddit, including comments. This tool enables the extraction of posts and comments, along with associated user information, such as timestamps, vote counts, usernames, post URLs, and comment URLs. With this functionality, you can gather comprehensive comment data from subreddits and Reddit users.

## Do you need proxies for scraping Reddit?
Using proxies is highly recommended. Subreddits are open for access and do not require a login to retrieve information. Employing proxies ensures successful Reddit scraping. While datacenter proxies may yield some results, residential proxies are preferred for Reddit scraping. Fortunately, our Free plan offers an Apify Proxy trial, allowing you to get started.

## Can I scrape reddit data using API?
Yes, it is possible to scrape reddit using API. The Apify platform has API endpoints for facilitating the management, scheduling, and execution of any Apify Actor, including the one used for Reddit scraping. Additionally, the API enables access to datasets, performance monitoring of Actors, result retrieval, version creation and updates, and more.

To utilize the API with Node.js, utilize the apify-client NPM package. For Python users, employ the apify-client PyPi package.

Please refer to the Apify API reference docs for comprehensive details or navigate to the API tab for relevant code examples.

## How can I build a Reddit scraper in Python?
You have two options for building a Reddit web scraper in Python. Firstly, you can utilize a [Python scraper template](https://apify.com/templates?category=python) directly on the Apify platform and maintain your production there. Alternatively, you can develop the scraper locally on your computer and only deploy it to the Apify cloud when ready. 

If you possess coding skills, there's another method to extract data from Reddit, and that's by developing your own web scraper using Python, a powerful programming language. Additionally, you can leverage third-party libraries and frameworks to streamline the creation of scrapers and web crawlers.

To retrieve Reddit data using Python, the Python Reddit API Wrapper (PRAW) module is a valuable tool that simplifies the utilization of Reddit's API through Python scripts.

Here's a step-by-step guide on how to scrape Reddit with Python:

### Step 1: Install PRAW
Begin by installing the PRAW module. Open your command prompt and execute the following command: `pip install praw`.

### Step 2: Create a Reddit App
To extract data, you'll need to create a Reddit app. Opt for the developer option and proceed with app creation.

### Step 3: Create PRAW Instances
After your app is successfully created, you'll need to create PRAW instances. There are two types: read-only instances and authorized instances.

## Step 4: Execute Data Extraction
Depending on the specific data you want to retrieve, issue the appropriate command. As the command is executed, the data extraction process will commence.

You check also this complete guide to [web scraping reddit with python](https://medium.com/geekculture/a-complete-guide-to-web-scraping-reddit-with-python-16e292317a52)
