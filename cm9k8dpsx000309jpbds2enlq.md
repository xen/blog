---
title: "What happen to Ask Solem"
datePublished: Wed Apr 16 2025 17:54:11 GMT+0000 (Coordinated Universal Time)
cuid: cm9k8dpsx000309jpbds2enlq
slug: what-happen-to-ask-solem
tags: python, opensource, celery

---

Many Python developers know the **Celery** project. This is an important part of the Python ecosystem, a project that allows you to effectively manage and orchestrate background tasks. For example, you upload a video to a site and click the "convert video" button. It is clear that while you are clicking and releasing the button, a video several gigabytes in size will not be able to be processed so quickly. Therefore, such tasks are usually launched as a separate process, waiting for it to finish. And then a lot of things start:

* what if the task completes with an error, it is often enough to simply restart it after a short time
    
* what if many users upload a lot of videos
    
* are there any important tasks that should always be launched first as soon as there are at least some resources
    
* or maybe you need to run tasks on a schedule, for example, issue invoices once a month
    

And to manage this entire zoo, the Celery project appeared a long time ago. The first public release was published on [Pypi.org](http://Pypi.org) in 2009. The author of this project was a developer with a funny nickname `ask`. I think I first used this project around 2011, judging by the **Django** versions that were released at that time. I don't remember anything significant about project I was working on, but the approach to using Celery was unusual and that's why the project was memorable. Instead of writing tasks separately, you could mark some functions in the existing code using decorators, and then run a separate script that worked as a separate server, but without Django.

The project gained popularity. But around 2016, `ask` abandoned it and managed to create another project, Faust, which was somewhat similar. We needed to process a large number of messages, preferably asynchronously, and I was looking for a way to do this. And I found a project that allowed you to connect to **Kafka**, listen for new messages and allow you to run tasks for them. In some ways similar to Celery, but Celery can change brokers and backends for storing task statuses. And what was my surprise that this project was written by the same developer as Celery. I immediately thought that since this developer had already done one project, he most likely understands what he is doing.

I also noticed that the avatar was a woman, but very similar to a photo that I had once seen before. Despite the fact that I am not very good at remembering faces. But I went to see who it was and only after that I remembered the name Ask Solem. It turned out that he had changed his gender and now began to write everywhere that he is now a woman. His new place of work was Robin Hood, a company about which I had heard that they have very aggressive marketing. But I had never heard that they support any open source projects. I thought that Ask must be a good developer, that the employer allowed him to release an internal project on GitHub.

Project I was working on at some point was closed. I no longer used Faust. Also, Kafka is not the technology you choose for every next project. I remembered just fact that Faust exists, but doesn’t care about it. A few years later, the idea of ​​using Kafka arose again, and I went to de-dust my memories about Faust. And what was my surprise when it turned out that it was already abandoned. And other people picked it up and were already developing a fork. I started looking at what happened to the developer, but he (she) disappeared.

A similar story, but much earlier, happened to **Mark Pilgrim**. He wrote several popular books *Dive into Python*, *Dive into HTML5*, *Dive into Accessibility*, *Dive into Greasemonkey*. He posted them on websites, they became table books for many beginning developers. His popularity grew a lot. He became a very popular author. But on October 4, 2011, all his websites went down. And at the same time, his Twitter, Reddit, GitHub and Google+ accounts were deleted. I don’t know what this can be compared to, probably an episode from Black Mirror. Of course, many began to worry. Because in this situation, nothing was normal. After some time [it was discovered](https://en.wikipedia.org/wiki/Mark_Pilgrim#%22Disappearance%22_from_the_Internet) that Mark was alive, but committed **infosuicide**. And he decided to hide from his popularity and just turned everything off. As far as I know, he has not appeared publicly anywhere since then. I hope he is okay.

Mark's disappearance was probably cruel to those who read him. I can definitely say that I kinda went through the loss. But on the other hand, he definitely has the right for his life. Developers are not the most sophisticated people in terms of soft skills. They can live their popularity and success in a completely different way. Not like influencers, stars or popular musicians.

Again, an example is the story of Perl 6 developer Audrey Tan, the developer was developing Perl 6, changed his gender, became a woman and changed his area of ​​interest. Wikipedia says he became Taiwan's Minister of Digital Affairs. Basically, he got involved in politics.

In general, I thought that something similar happened to Ask, and don’t worry much. But every time I returned to Celery or Faust, I did small research and tried to find out what happened to him or how he now called himself "her". But apparently Ask was not so popular that someone would investigate his disappearance. I'm sure there were people who were interested in him as much as I was, but I didn't come across them or their posts. At some point, I stopped reading the mailing lists and blogs of the Python developer community. I think there were such posts, but I couldn't even find them.

So I just checked sometimes and didn't find anything. I am also a person with my own history and sometimes I also feel tired of social networks, I can immerse myself in work for a long time. I had periods when I felt that social networks had too much influence on my mood and blocked them on all my devices.

In short, I realized that Ask could have simply disappeared somewhere, he could have been given some higher position where he no longer had time to write open source code, or he could have simply started living his own life.

Today I sat down to reread the Celery documentation, because I see that the project is actively being updated and developed, and I again made an attempt to find out what happened to Ask.

Unfortunately, I found it by the request "What happened to Ask Sol". Not even on the first page of the Google.

Ask Solem Hoel was born on 11.05.1982, and the date of death is 05.12.2021. There is a website on the Internet with an online cemetery and on which [Ask's memorial page is located](https://flataas.vareminnesider.no/memorial_page/memorial_page_personal_info.php?order_id=3957458&set_site_id=831&cat=home&sign=bf0ba6c7eb4ed19e97572a293d4d1ef2). It is in Norwegian, which is probably why I couldn't find it before. If you dig around, you can find and expand a small block in English:

> Our beloved dad, son and brother Ask’s life took place in London and later in San Francisco. But his roots and his family background was in Trondheim. He created Celery Project and worked as a software engineer at Robin Hood in Palo Alto. You had an amazing ability to concentrate and focus in on whatever fascinated you, such as creating music. You made techno, deep house and hiphop, playing all instruments by yourself. You could be in the same groove for weeks. You perused thick manuals consisting solely of numbers, you loved your work! You built Lego, nursed flowers and read a lot for Robin. Robin was the sunshine of your life, he totally changed your life.

I think this text was written by his mother, who regularly visits the site and congratulates her son on his birthday, writes that she misses him. It turns out that Ask was the father.

I don’t know the details, I don’t even know what kind of person Ask was. I only know that in almost every project we use what he wrote.

For some reason, it seems to me that the story with the sex change did not end well, that the early death was somehow connected with this. Or there were some other reasons and the attempt to change sex was an attempt to solve them. In any case, mental health is a very important part of life.

Today I revealed to myself the secret of where one of the open source developers disappeared to. True, now I am very sad. I feel very sorry for his mother. One of the biggest fears of a parent is to bury their children.

R.I.P. Ask Solem Hoel.