# Stat236 Final Project
## Network based Recommender System

Team Members: Lyla Kiratiwudhikul, Mina Lee, Tom Zhang

### 1. Introduction and Problem Statement
Recommendation systems have become ubiquitous in today's business landscape, showing in various forms across online platforms like social media and shopping websites. Amazon’s recommendation system is a prominent example, using co-purchasing history to offer tailored suggestions to users. The significance of a robust product recommendation system cannot be overstated in current business models.

Traditionally, recommendation systems have relied on two recommender systems, content-based approaches which analyze properties of recommended items and collaborative filtering which determines recommendations based on similarities between users or items. However, this project adopts a network approach, concentrating solely on the network properties and structure to facilitate recommendations. 

For network approach, the task will be to predict missing links in the co-reviewing network. The specific goal is to retrieve a ranked list of restaurants to recommend to a customer/visitor who has ranked a particular restaurant. The method involves a network-centric perspective, focusing on the structure of the co-reviewing network to predict missing links. In this context, the incomplete graph is defined by vertices representing restaurants and edges connecting restaurants frequently visited together. The challenge lies in predicting nonexistent edges, constituting the task of link prediction.

