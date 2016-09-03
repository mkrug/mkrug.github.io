---
layout: post
title: Machine Learning in Ruby
author: dalibor_nasevic
tags: [machine learning, redis, sinatra, ruby]
---

Time & Place: 01.12.2011, 7pm - 9pm at [Hacklab 2.0](https://maps.google.com/maps/ms?msid=202273220853331240819.0004b1c308bfec6b2e666&msa=0&ie=UTF8&t=h&vpsrc=0&ll=41.996171,21.41863&spn=0.006243,0.009334&source=embed "Hacklab 2.0 Google map")

Meeting agenda: Machine Learning in Ruby

In this presentation  [Dalibor Nasevic](http://twitter.com/dnasevic "Dalibor Nasevic") will introduce you to the basic concepts of machine learning. We will look at a prototype implementation of a news aggregator (code can be seen [here](https://github.com/dalibor/newsagg/ "News Aggregator source code")) that consist of the following components:

- training data set
- collection data from several news media
- parsing of RSS / HTML texts
- statistical classification method
- creating a cluster with statistical method

We will also look at the different tools used in the implementation of the prototype:

- Programming Language: Ruby 1.9.2
- Standard libraries: open-uri, net / http, rss (rss/2.0), json
- Other Ruby libraries: Sintara, Redis, Haml, Sass, Nokogiri
- Database: Redis

Purpose of the presentation:

- news aggregator as a concept and realization
- brief introduction to the tools used with emphasis on Redis and in what scenarios it can be used
- discussion of other algorithms for classification and clusterification of texts (Bayes, Latent Semantic Analysis, K-means
- discussion of the architecture for larger applications of this type (couchdb / mongodb, parsing and analyzing texts in Macedonian language)
- reviewing ideas for applications of this kind in Macedonia

Истава новост на македонски јазик можете да ја прочитате  [овде](http://b10g.spodeli.org/2011/11/ruby-01122011-19.html "Програмски јазици: Машинско учење во Ruby (01.12.2011, 19 час)").

