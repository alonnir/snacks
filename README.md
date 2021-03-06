# snacks
SNAck size awesome list for social network analysis resources.


## Intro

_Not another awesome list._

While awesome lists can indeed be awesome, they can also be daunting and evoke a strong sense of FOMO.
This repo's mission is to be a snack size version of an awesome list, providing a highly curated, human friendly, and most importantly digestible list of resources for anyone interested in SNA.

The idea here is that unlike an awesome list, one can definitely get though all the resources here, and come out the other end knowledgeable and happy.

Still want the awesome list? [Look no further](https://github.com/briatte/awesome-network-analysis).

***

## Table of Contents
- [Intro](#intro)
- [Getting Started](#getting-started)
- [Getting Smarter](#getting-smarter)
- [MOOCs](#moocs)
- [Tools](#tools)
- [Datasets](#datasets)
- [Future](#future)
- [Full Disclosure](#full-disclosure)
- [Footnotes](#footnotes)

***

## Getting Started

0. Play with [Nick Case](https://twitter.com/ncasenmare)'s excellent **[the wisdom and/or madness of crowds – an interactive guide to human networks](https://ncase.me/crowds/)** to get some inspiration. This is not a must step in your learning journey, but could definitely make you excited and hungry to learn more.

- _Optional:_ [Vaidehi Joshi](https://github.com/vaidehijoshi) has a very palatable [A Gentle Introduction To Graph Theory](https://dev.to/vaidehijoshi/a-gentle-introduction-to-graph-theory) blog post, and the content is also available as a [video](https://dev.to/vaidehijoshi/graph-theory--basecs-video-series-1cpo). This is optional material as it's very introductory and lacks a lot of the terminology you'll come across later (for example, in the next resource).

1. **[D3 Graph Theory - learn graph theory interactively](https://d3gt.com/index.html)** - a friendly broswer based introduction to graph theory. This is a great place to get started and learn the terminology, basics, and logic behind it all.

2. Nailed down the basic theory? Great! The next step is to get your hands dirty and see it in action in Python. The best place to start is with the **[`NetworkX`](http://networkx.github.io/)**. It has friendly API, [great documentation](https://networkx.github.io/documentation/stable/index.html), it's vast and stable. Available in a package manager near you!

  - `pip install networkx`
  
  - Get familiar with [The NetworkX API](https://ericmjl.github.io/Network-Analysis-Made-Simple/01-introduction/02-networkx-intro/).

3. Take 3 hours for **Network Analysis Made Simple - PyCon 2019.** [Video](https://www.youtube.com/watch?v=eZs4MECCuYY) and [notebooks](https://github.com/ericmjl/Network-Analysis-Made-Simple), a workshop by [Mridul Seth](https://github.com/MridulS), [Eric Ma](https://github.com/ericmjl) which ties together introductory theory and hands-on practice (with NetworkX, of course).

4. Practice. The [Game of Thrones](https://ericmjl.github.io/Network-Analysis-Made-Simple/05-casestudies/01-gameofthrones/) and [Airport Network](https://ericmjl.github.io/Network-Analysis-Made-Simple/05-casestudies/02-airport/) case studies are a good place to practice what you've learned - and level up your knowledge and understanding.


## Getting Smarter

A few good resources for those comfortable with the fundamentals and want to pursue a deeper and wider understanding. These can be challenging at times, so don't feel bad if you're making slower progress here. Of course, feel free to pick and choose the contents (or chapters) that you're most interested in.

- **Network Science** by [Albert-László Barabási](https://en.wikipedia.org/wiki/Albert-L%C3%A1szl%C3%B3_Barab%C3%A1si) is [available freely](http://networksciencebook.com/) online, in a jazzed up version of the book.

- **Networks, Crowds, and Markets** by [David Easley](https://en.wikipedia.org/wiki/David_Easley) and [Jon Kleinberg](https://en.wikipedia.org/wiki/Jon_Kleinberg)<sup>[1](#fn1)</sup> is an excellent book. The authors made it freely available online:
  - [Book as one long PDF file](https://www.cs.cornell.edu/home/kleinber/networks-book/networks-book.pdf)
  - or [table of contents with a PDF per chapter](http://www.cs.cornell.edu/home/kleinber/networks-book/)

  If you prefer a [MOOC](#MOOCs), Easley, Kleinberg and [Eva Tardos](https://en.wikipedia.org/wiki/%C3%89va_Tardos) offered a similar course on EdX, which has been archived but the materials are still available [here](https://www.edx.org/course/networks-crowds-and-markets).


***

## MOOCs

Massive Open Online Courses, to those who like a course-like experience. Free to learn courses:
- [Coursera - Applied Social Network Analysis in Python](https://www.coursera.org/learn/python-social-network-analysis)
- [Coursera - Social Network Analysis](https://www.coursera.org/learn/social-network-analysis#syllabus)
- [Coursera - Social and Economic Networks: Models and Analysis](https://www.coursera.org/learn/social-economic-networks)



***

## Tools

#### Python:
- **[`NetworkX`](https://networkx.github.io/)**: as mentioned above, this is the preferred place to start. Easy API, great documentation, rich functionality. If you're just getting started with network analysis in Python, this is the module you'd like to use.
- **[`PyGraphistry`](https://github.com/graphistry/pygraphistry)**: great tool for visually exploring larger graphs (one of the things where NetowrkX lags behind). Plays nicely out-of-the-box with NetworkX graphs or even Pandas (as well as plenty of other popular tools).
- **[`nxviz`](https://github.com/ericmjl/nxviz)**: A declarative package for plotting NetworkX graphs _rationally_. Implements Circos plots, adjacency matrix plots, and more.

#### Other:
- **[Gephi](https://gephi.org/)**: an open-source desktop software to explore and analyse networks. Also check out the tutorial by [kateto](https://github.com/kateto) [here](https://kateto.net/tutorials/).

***

## Datasets

The following resources contain a large selection of network related datasets for you to practice and learn from:
- [Network Repository](http://networkrepository.com/) - a scientific network data repository with interactive visualization and mining tools.
- [Netzschleuder](https://networks.skewed.de/) - network catalogue, repository and centrifuge.
- [SNAP](https://snap.stanford.edu/data/) - Stanford large network dataset collection.

***

## Future

There exists a future where this resource includes:

* a well structured learning path or curriculum, or perhaps a taxonomy that states the best resource (or few resources) for each given topic.
* a glossary, one centralised, clear and consistent place for definitions and terminology.

But... baby steps.

***

## Full Disclosure
Some of the materials linked above are by [Eric Ma](https://github.com/ericmjl), who is a contributor to this repo.

***

## Footnotes

<a name="fn1"><sup>1</sup></a> Kleinberg developed the [HITS Algorithm](https://en.wikipedia.org/wiki/HITS_algorithm), which you'll come across sooner or later.
