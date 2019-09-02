---
title: Amazon Keyword Entry Simplified
subtitle: We built our own tool to streamline Amazon keyword entry.
category:
  - About Awake
author: Jan Gierlach
date: 2019-08-21T21:45:15.162Z
featureImage: /uploads/keywords.jpg
---
# Amazon Keyword Formatter

This small project came out of a genuine need to streamline efficiency when we took on a large work load from a new client.

When creating and optimizing a new listing for search in the Amazon market place one of the first places to start is keyword research.

For us that looks like pulling data from a variety of sources to figure out what competing listings are ranking for, and what words and phrases have opportunity.

We amass a list of potential keywords that will be used throughout the copy of our listing. The process gets messy with lots of repetitive bullet points.

We put notes in parentheses if there is something special or significant about a keyword or phrase. Below is what one of these lists might look like after the first few rounds of research.

* **pin**
* **enamel pin**
* **pins for backpacks**
* **memes**
* **enamel pins**
* **pride pin**
* **lapel pins**
* **hat pins**
* **button pins (PPC ad they are running)**
* **backpack pins**
* **cute pins**
* **button pins**
* **pins for jackets**

From this initial list a lot of important decisions are made about how we go about crafting the listings title, bullet points, and description.

Let's fast forward a lot of the hard work that goes into writing all the sales copy, and we now arrive at one of the final stages in launching a new listing on Amazon.

We are looking at the keywords field in the backend of our Amazon account and we must now translate our bulleted list above to the keyword format amazon requires.

![alt text](/uploads/amazon_keyword_entry_field.png "Amazon Keyword Entry Field")

Amazon lays out specific rules for how keywords should be entered into this field. The rules our keywords must follow are simple, yet somehow filtering from our master list of keywords to the format Amazon requires felt unnecessarily time consuming.

There is so much ground work involved in properly getting a new listing created and launched, but after manually formatting keywords about 30 times it felt like a step in the process that could to some degree be automated.

We made this **[tool](https://amazon-keyword-formatter.herokuapp.com/index.html)**. Take all the keywords from our master list above, and simply drop them into the input field. When you click the button all the comments in the parentheses are removed and the text is parsed to be formatted to Amazon's exact requirements.

If you use my above keywords as a sample input you should see something that looks exactly the same as this.

**pin enamel for backpack meme pride lapel hat button cute jacket**

The functionality could likely be cobbled together using google sheets or even excel, but we want this tool accessible to anyone who might find it useful.