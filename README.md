# Design and construction of tripartite network from Reddit

Datasets from multipartite complex networks with 3 or more levels (tripartite, quadripartite, etc.) are very scarce, unlike the case of only 2 levels better known as bipartite graphs, which are quite common.

I designed and began to construct a tripartite network for my Ph.D. thesis, using the website [Reddit](https://www.reddit.com). According to their own description, "*Reddit is a network of communities where people can dive into their interests, hobbies and passions. There's a community for whatever you're interested in on Reddit*". In this context, I use the term *groups* instead of *communities* for technical reasons and to avoid misunderstandings.

The tripartite network I defined is composed of:
1. **Users** (usernames)
2. **Groups** (subreddits)
3. **Keywords** (words)

My main interest is the tripartite network analysis in two important topics:
* **Link prediction**. This can be used in recommendation systems for example, so we could recommend an user certain groups that might find interesting based on our anaylsis.
* **Community detection**. Also called clustering in (sligthly) different contexts, and it can be used to detect clusters of users based on the groups they frecuent and the keyword they use, for instance.

I already developed many algorithms to do **link prediction** and **community detection** in multipartite networks, but I was lacking of datasets to test them.

# NETWORK VISUALIZATION

Testing an [interactive network visualization](https://raw.githack.com/JorgeRuizBerlin/reddit-tripartite-network/main/bipartite_ggu.html), where it's possible to move around the nodes and more.
