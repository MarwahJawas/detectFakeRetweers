# Detect fake retweeters on Twitter's network

[![Up to Date](https://img.shields.io/badge/Python-3.7-green)](https://github.com/ikatyang/emoji-cheat-sheet/actions?query=workflow%3A%22Up+to+Date%22)
This repository contains the source code of my master's thesis :mortar_board: titled (Structures of Retweets Manipulation on Twitter: Case Study of Trending Topics in Saudi Arabia)
 you can find it in this link in [Thesis](<https://kausp.sa/Details/Thesis/146506/>)

I developed a new method that detects fake retweeter's based on their Twitter's connection. It consists of 4 components: <br>

1. collecting data Using Twitter API 
2. extracting data and building a database 
3. building a graph based on user's retweeting activity 
4. extract some features: temporal, profile,  connection in the network 

Finally, that results in predict fake retweeters based on top important feature.  <br>
All code with Python 

# Getting Started
## Installing
install many packages that can be installed using pip:

```
pip install tweepy
pip install combinations
pip install sqlite3 
pip install networkx
pip install community
pip install pandas
```
