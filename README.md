##ASgrank a.k.a. AS number peer graphs and ranking
###Prerequisites
```
MongoDB, PyMongo, NetworkX, argparse, json
```
```
asnum.py
Queries RIPE API for AS belonging to particular countries
 - for each AS number of country queries for peers
 - for each AS queries BGPrank for reputation rank.
```

```
graphbuild.py
Creates the graph of peerings along with BGPRank of each AS.
```
#### The red colored edges in the graph represent bad reputation of AS neighbours 
![Graph](http://raw.github.com/cokebottle/ASgrank/master/cool_weighted.png)

