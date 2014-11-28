---
layout:     post
title:      Connecting the dots between news articles
date:       2014-11-17
summary:    Information overload is one the biggest problem in media. Dafna Shahaf, and her research group, shows some really interesting approaches in order to satisfy this need. They try to develop different techniques to present data in a meaningful way.
---

Today I've come into the figure of [Dafna Shahaf](http://i.stanford.edu/~dshahaf/), a computer science researcher at Stanford.

Her research focuses on the __information overload__ problem. In the last days I red three of her last papers talking about this topic: namely "Connecting the Dots Between News Article", "Metro Maps of Science" and "Information Cartography: Creating Zoomable, Large-Scale Maps of Information". As she states on her front-page, her work aims at providing more expressive options for specifying complex information needs, while at the same time presenting the retrieved results in a structured and annotated manner that better enables the user to connect the dots.

And connecting the dots is the main topic of the first paper I red. The idea of this research is to extract useful knowledge from large datasets in order to keep up with the larger and larger amounts of content published every day. [^1] In this world full of information is easy for users to __miss the big picture__. During my thesis research this is somenthig I noticed being really common. Readers have difficulties having an good overview of a particular topic. That's why Dafna says that there is an increasing need for techniques to present data in a meaningful way. The idea behind the paper is to find a good path between two articles. Starting from two stories her work aims at building a chain of articles that will help us understand what happened between story one and story two. 

Starting from the resulting algorithms of this paper she has move into the world of scientific papers. In "Metro Maps of Science" she claims how the surge of the Web has brought down the barriers of distribution, and the scientific community finds itself overwhelmed by the increasing numbers of publications. While search engines are highly effective in retrieving publications, __the task of fitting those publications into a coherent picture remains difficult__. [^2] As a result her research group developed a new way of representing this huge collection of scientific papers: maps. Like a subway map, the resulting visualization of her algorithm displays the interaction between several publications showing also relevant citations. The map consists of a set of _metro lines_. Each metro line is a sequence of metro stops; each line follows a coherent and narrative thread, and different lines focus on different ascpects of a story. [^3]

The last step of her research is to make this maps zoomable, showing different levels of granularity, with each level of zoom showing finer details and interaction. [^4] In the latest paper I red, "Information Cartography: Creating Zoomable, Large-Scale Maps of Information", the research gruop pays particular attention to the _structure_ of the maps, and accommodates different _granularities_ of information through multi-resolution zooming.[^5] 

This researches confirm my theory about information overload, which make users miss the big picture, and the lack of interactivity which denies users moving from a source to another easily. The results of Dafna and her research group are really interesting and show how interaction (in their case zooming) and user experience are at the core of every nowadays application.

[^1]: Dafna Shahaf, Carlos Guestrin. _Connecting the Dots Between News Articles_. Stanford University.
[^2]: Dafna Shahaf, Carlos Guestrin, Eric Horvitz. _Metro Maps of Science_. Stanford University.
[^3]: Dafna Shahaf, Jaewon Yang, Caroline Suen, Jeff Jacobs, Heidi Wang, Jure Leskovec. _Information Cartography: Creating Zoomable, Large-Scale Maps of Information_. Stanford University.
[^4]: Dafna Shahaf, Jaewon Yang, Caroline Suen, Jeff Jacobs, Heidi Wang, Jure Leskovec. _Information Cartography: Creating Zoomable, Large-Scale Maps of Information_. Stanford University.
[^5]: Dafna Shahaf, Jaewon Yang, Caroline Suen, Jeff Jacobs, Heidi Wang, Jure Leskovec. _Information Cartography: Creating Zoomable, Large-Scale Maps of Information_. Stanford University.