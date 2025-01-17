---
layout: post
title: Final Project
categories: [content, progress]
---

#### The Incentive

There have been noticeable changes in how Christian religiosity deals with queer lifestyles. Instead of rejection, it is not uncommon to come across flyers and brochures in which communities explicitly advertise themselves as queer-inclusive. These changes, their triggers and the concretely treated topics of queer Christianity can be examined using different methods. In this final project, I would like to show how the first steps with digitally supported tools can look like and how they give us access to the content of Christian websites.
<!--more-->

#### The Project

I was already familiar with the website evangelisch.de and its queer blog 'kreuz und queer' from the context of another work. Using web scraping I wanted to extract the articles. The collected data can then be examined and processed using various tools. The first thing I wanted to know was how many articles there are and what years they are from. This could be used to determine whether the number of articles has increased or decreased. I then also extracted the authors and now knew how many people actually write for the blog. I then had the idea of adding a month-only column to my spreadsheet to check if there were more entries at certain times than at others. For this analyses I used Palladio.

![Overview of authors and number of articles per year](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/palladio01.png)
Overview of authors and number of articles per year.
<br/><br/>

![Data only from Rainer Hörmann](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/palladio02.png)
Data only from Rainer Hörmann.
<br/><br/>

![Cluster view of articles per year](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/palladio03.png)
Cluster view of articles per year.
<br/><br/>

![Cluster view of articles per month](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/palladio05.png)
Cluster view of articles per month.

#### Palladio results
Although a decrease in articles can be determined numerically, a density of regular articles remains. Also, we can see who writes the most articles and even in which years they are most actively involved. It can also be seen that around 2018 the annual posts are already between 40-50 and that there are slightly more articles in the first half of a year.

### Start of content analysis
Now that it has been clarified who wrote when, it remains unclear what was written. The Voyant tool can be used for this analysis. After I uploaded the article texts there, I was greeted directly by a word cloud that showed me which words occur most frequently: people, church, life, God, queer.

![word cloud](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/wortwolke01.png)

In the next step, a meaningful list of stopwords should definitely be included. This should be checked so that no project-relevant words are filtered out. Various methods can then be used with Voyant Tool. I was interested in topic modeling, to see in which contexts certain keywords appear and which topics appear more frequently in the articles. This can be used to examine whether the topics have changed over the years and how many articles are devoted to which topic. It requires sufficient time to use this method extensively to benefit from it. Unfortunately, my analysis was not deep enough.

![word cloud](https://raw.githubusercontent.com/itspepps/itspepps.github.io/main/assets/image/topic01.png)
