# System design algorithms

Algorithm you should know for preparing system design interview. For example, Learn Geohash / S2 Geometry algorithm for "How to design Uber like system?"

#### Sponsor
[海外兔 - 程序员求职课程，入职不成功不收费](https://osjobs.net/co/)

#### How to contribute
The algorithm and its resources should:

1. Can answer a system design question. For instance, [Building a complete Tweet index](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html) can answer "How to implement Twitter search" or "How to implement hashtag in Twitter".
2. Free to read or watch.
3. Text would be better than videos.

#### Requirements
- Know when to use ☑️
- Know how it works ✅

#### Table of contents

- Bloom filter ✅
- Frugal Streaming ☑️
- Geohash / S2 Geometry ☑️
- HyperLogLog ✅
- Leaky bucket / Token bucket ✅
- Lossy Counting ☑️
- Operational transformation ☑️
- Quadtree / Rtree ☑️
- Ray casting ☑️
- Reverse index ✅
- Rsync algorithm ✅
- Trie algorithm ✅

### Bloom filter
A Bloom filter is a data structure designed to tell you, rapidly and memory-efficiently, whether an element is present in a set.

- [Build a Web Crawler](http://blog.gainlo.co/index.php/2016/06/29/build-web-crawler/)

- https://www.google.com/amp/s/www.geeksforgeeks.org/bloom-filter-in-java-with-examples/amp/

- https://www.baeldung.com/guava-bloom-filter

### Frugal Streaming
Frugal Streaming uses only one unit of memory per group to compute a quantile for each group

- [Find the nth percentile of the data stream](https://research.neustar.biz/2013/09/16/sketch-of-the-day-frugal-streaming/)

- https://agkn.wordpress.com/2013/09/16/sketch-of-the-day-frugal-streaming/

- https://gist.github.com/jroyalty/5401935f60a37adfa1799ca5194e4d76

### Geohash / S2 Geometry
Geohash can used by 1) dating apps to find romantic matches within a particular cell, and to create chat apps.2) Find nearby locations, and identify places of interest, restaurants, shops and accommodation establishments in an area. 3) Geohashers go on global expeditions to meet people and explore new places.

- [Location-based search results with DynamoDB and Geohash](https://read.acloud.guru/location-based-search-results-with-dynamodb-and-geohash-267727e5d54f)

### HyperLogLog
HyperLogLog is an algorithm for the count-distinct problem, approximating the number of distinct elements in a multiset.

- https://en.m.wikipedia.org/wiki/HyperLogLog
- [Redis HyperLogLog Explained](https://www.youtube.com/watch?v=MunL8nnwscQ)

### Leaky bucket / Token bucket
A mechanism to control the amount and the rate of the traffic sent to the network

- [Everything You Need To Know About API Rate Limiting](https://nordicapis.com/everything-you-need-to-know-about-api-rate-limiting/)
- [How to Design a Scalable Rate Limiting Algorithm](https://konghq.com/blog/how-to-design-a-scalable-rate-limiting-algorithm/)

### Lossy Counting
The lossy count algorithm is an algorithm to identify elements in a data stream whose frequency count exceed a user-given threshold.
Heavy Hitters.

- https://micvog.com/2015/07/18/frequency-counting-algorithms-over-data-streams/
- [Fast and Reliable Ranking in Datastore](https://cloud.google.com/datastore/docs/articles/fast-and-reliable-ranking-in-datastore)
- [Frequency Counts over Data Streams](https://www.cse.ust.hk/vldb2002/VLDB2002-proceedings/slides/S10P03slides.pdf)
- [How we built rate limiting capable of scaling to millions of domains](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)
- [Rate-limiting strategies and techniques](https://cloud.google.com/solutions/rate-limiting-strategies-techniques)

### Operational transformation
Operational transformation (OT) is a technology for supporting a range of collaboration functionalities in advanced collaborative software systems.
Algorithm behind Google Docs.

- https://medium.com/coinmonks/operational-transformations-as-an-algorithm-for-automatic-conflict-resolution-3bf8920ea447
- [How Google docs handle editing collisions](https://stackoverflow.com/a/36366174)
- [Collaborative editing](https://www3.ntu.edu.sg/home/czsun/projects/otfaq/#_Toc321146127)

### Quadtree / Rtree
- [Spatial Indexing with Quadtrees](https://medium.com/@waleoyediran/spatial-indexing-with-quadtrees-b998ae49336)
- Find nearby interest points
- https://algs4.cs.princeton.edu/92search/QuadTree.java.html

### Ray casting
Ray casting is the most basic of many computer graphics rendering algorithms that use the geometric algorithm of ray tracing. Given a point with longitude and latitude, return the Country of the point.

- [Ray Casting Algorithm](http://philliplemons.com/posts/ray-casting-algorithm)

### Reverse index
Reverse Index: a reverse index is an index of keywords which stores records of documents that contain the keywords in the list.

- [How search engines work: Crawling, Indexing, And Ranking](https://moz.com/beginners-guide-to-seo/how-search-engines-operate)
- [Building a complete Tweet index](https://blog.twitter.com/engineering/en_us/a/2014/building-a-complete-tweet-index.html)
- https://www.google.com/amp/s/www.geeksforgeeks.org/inverted-index/amp/

### Rsync algorithm
The rsync algorithm is a technique for reducing the cost of a file transfer by avoiding the transfer of blocks that are already at the destination.

- https://www.google.com/amp/s/www.geeksforgeeks.org/rsync-command-in-linux-with-examples/amp/
- [Dropbox Streaming File Synchronization](https://dropbox.tech/infrastructure/streaming-file-synchronization)

### Trie algorithm
Trie is an efficient information reTrieval data structure. Using Trie, search complexities can be brought to optimal limit (key length)

- [How to Design an Autocomplete System](https://dzone.com/articles/how-to-design-a-autocomplete-system)
- [Spell Checkers](https://stackoverflow.com/questions/21366631/how-do-i-use-a-trie-for-spell-checking)
- [prefix matching words (IP Addresses, Phone Numbers)](https://www.geeksforgeeks.org/longest-common-prefix-using-trie/)
- [Auto-complete feature using Trie](https://www.geeksforgeeks.org/auto-complete-feature-using-trie/)

