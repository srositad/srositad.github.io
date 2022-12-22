# Featured Projects
---
## Natural Language Processing

### CS224n: Natural Language Processing with Deep Learning

My complete implementation of assignments and projects in [***CS224n: Natural Language Processing with Deep Learning***](http://web.stanford.edu/class/cs224n/) by Stanford (Winter, 2019).

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/CS224n-NLP-Solutions/tree/master/assignments/)

**Neural Machine Translation:** An NMT system which translates texts from Spanish to English using a Bidirectional LSTM encoder for the source sentence and a Unidirectional LSTM Decoder with multiplicative attention for the target sentence ([GitHub](https://github.com/chriskhanhtran/CS224n-NLP-Solutions/tree/master/assignments/)).

**Dependency Parsing:** A Neural Transition-Based Dependency Parsing system with one-layer MLP ([GitHub](https://github.com/chriskhanhtran/CS224n-NLP-Assignments/tree/master/assignments/a3)).

<center><img src="images/nlp.png"/></center>

---
### Detect Non-negative Airline Tweets: BERT for Sentiment Analysis

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1f32gj5IYIyFipoINiC8P3DvKat-WWLUK)

<div style="text-align: justify">The release of Google's BERT is described as the beginning of a new era in NLP. In this notebook I'll use the HuggingFace's transformers library to fine-tune pretrained BERT model for a classification task. Then I will compare BERT's performance with a baseline model, in which I use a TF-IDF vectorizer and a Naive Bayes classifier. The transformers library helps us quickly and efficiently fine-tune the state-of-the-art BERT model and yield an accuracy rate 10% higher than the baseline model.</div>

<center><img src="images/BERT-classification.png"/></center>

---
### Detect Food Trends from Facebook Posts: Co-occurence Matrix, Lift and PPMI

[![Open Notebook](https://img.shields.io/badge/Jupyter-Open_Notebook-blue?logo=Jupyter)](projects/detect-food-trends-facebook.html)
[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/chriskhanhtran/facebook-detect-food-trends)

<div style="text-align: justify">First I build co-occurence matrices of ingredients from Facebook posts from 2011 to 2015. Then, to identify interesting and rare ingredient combinations that occur more than by chance, I calculate Lift and PPMI metrics. Lastly, I plot time-series data of identified trends to validate my findings. Interesting food trends have emerged from this analysis.</div>
<br>
<center><img src="images/fb-food-trends.png"></center>
<br>

---
### Optimize Route and Price

[![Open Result Map](https://img.shields.io/badge/R-Open_R_Map-blue?logo=R)](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/37d381f2-ef43-44b5-96db-f521d573a898/YKMAP.html?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221222%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221222T033926Z&X-Amz-Expires=86400&X-Amz-Signature=3279f610398e237de07a97ddcb90ab136e98a0f9f348c76e65f20a604722f86f&X-Amz-SignedHeaders=host&x-id=GetObject)

<div style="text-align: justify">In this intern project, I analyze route for optimization minimum distance and price from outlet center to Yogyakarta outlet using Travelling Salesman Problem and then applied visualize in Google Maps to make it easier for drivers to determine the route based on the clusters (zona).
<br>
**Travelling Salesman Problem (TSP): Given a set of cities and distance between every pair of cities, the problem is to find the shortest possible route that visits every city exactly once and returns to the starting point.**
<br>
Tools that I used was Microsoft Excel and R Programming (to visualize map), click on the badge.</div>
<br>
<center><img src="images/cluster_R_map.jpg"/></center>
<br>

---
## Research Projects (Publication)


---
### Optimizing Planning Service Territories by Dividing Into Compact Several Sub-areas Using Binary K-Means Clustering According Vehicle Constraints

[![Open Research Paper](https://img.shields.io/badge/PDF-Open_Research_Paper-blue?logo=adobe-acrobat-reader&logoColor=white)](https://arxiv.org/abs/2010.10934)

<div style="text-align: justify">**This aim of the study was cast in the framework of determining the most effective way to deliver services from customer to other customers within a specified area, subject to limitations on resources such as service personnel and vehicle volume. Most of these algorithms employ a cluster-first and route-second strategy in order to address real application problems effectively.**
<br>
Another commonly encountered challenge in solving these problems arises from the fact that,
due to the limited availability of resources, a service or logistics provider is generally unable to
service all customers within a service territory. The problem then arises: ‘how to create these
sub-areas to meet the business logic’. The service resource is limited. We are required to develop a
decision-support system to help the user create sub-areas within this territory so that each sub-area
can be serviced directly. Each sub-area should be as compact as possible so that the expected
service cost and especially the travel time and distance to service the sub-areas will be minimal. In
the following discussion we will use the term cluster to represent a sub-area.
<br>
Expressed more generally, the problem consists in determining how to group or cluster the
customers, which may abstractly be treated as points within the service territory, while honoring
the rules imposed by business practice such as restrictions on total service capacity (total working hours combined with vehicle capacities including weights and volumes), balanced workload
(service levels or delivery quantities), non-overlapped subareas, etc.
<br>
To optimize vehicle capacity used, the future work would be to set a threshold minimum
capacity assigned to vehicles after clustering. Create a binary tree cluster for another cluster below
threshold. We assume it would cause a better utilization for each vehicle and also decrease
mileage of the vehicles that cut delivery time.</div>
<br>
<center><img src="images/WP_Research_1.jpg"/></center>
<br>


---
### Set Best Threshold in Vehicle Routing Problem for Better Utilization

[![Open Research Paper](https://img.shields.io/badge/PDF-Open_Research_Paper-blue?logo=adobe-acrobat-reader&logoColor=white)](https://www.researchgate.net/publication/346926919_Set_Best_Threshold_in_Vehicle_Routing_Problem_for_Better_Utilization)

<div style="text-align: justify">**This aim of the study was set a minimum capacity threshold for each vehicle that is considered as well utilized before an order is assigned for the delivery process. So that vehicle is well utilized such that the cost of vehicle rent is also minimal.**
<br>
In this case, we define a set of thresholds and then evaluate predicted probabilities under each to find and select the optimal threshold. This paper is a development study of previous research (https://arxiv.org/abs/2010.10934) done by our paper to cover research gaps such as the consideration of vehicle capacity that constrains each cluster. We demonstrate that our approach could result in a preferable balance among the vehicle route and vehicle rental cost.
<br>
Refer to the previous work we still use the same data, then continuing to use the binary tree clustering as the iterative algorithm to get the maximum sum of volume vehicle capacity constraints in each cluster. After that, we collect the cluster in which the sum of the volume is more than the threshold of maximum vehicle volume capacity. The rest of the cluster would become one cluster that would proceed with binary tree clustering again.
<br>
The present paper focuses on the threshold selection in capacity vehicle routing problem. According to the comparison between 0.65 to 0.9 threshold, using OR-Tools CVRP we get the optimal threshold in 0.75. For future work, we need to analyze more and can implement on platforms with the real-time data shown in the maps. Another thing is for different data, it would be a different threshold that would optimize the result.</div>
<br>
<center><img src="images/WP_Research_2.jpg"/></center>
<br>


---
### Grouping of province in Indonesia based on the condition of the cooperative using K-Means Clustering

[![Open Research Paper](https://img.shields.io/badge/PDF-Open_Research_Paper-blue?logo=adobe-acrobat-reader&logoColor=white)](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/85cff0da-d55f-4926-9750-eec1a3c1d4a3/PUBLICATION.pdf?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20221221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20221221T092037Z&X-Amz-Expires=86400&X-Amz-Signature=9aee3783dac75d7a1c595282192813acb16bfab5aab5012cb7c4da06e76cdb52&X-Amz-SignedHeaders=host&response-content-disposition=filename%3D%22PUBLICATION.pdf%22&x-id=GetObject)

<div style="text-align: justify">In 2017, I joined Hokkaido Indonesian Student Association Scientific Meeting was held in Sapporo, Japan. Our paper about "**Grouping of province in Indonesia based on the condition of the cooperative using K-Means Clustering**"

The cooperative is a business entity that consists of persons or legal entities with cooperative base its activities as the movement of people's economy which is based on the principle of family. However, development of the role of cooperatives in the areas of the economy has not been significant. This is due to the existence of a policy that has not yet been drawn up on the basis of potential cooperation. **The main objective of this paper is to identify the potential of cooperatives in Indonesia based on conditions.** The variables used in this study i.e. cooperatives are active, not active, the number of cooperative members, the annual Member meeting (RAT), manager, employee numbers, capital of its own, beyond the capital, volume of business and the rest of the business results (SHU). The analysis was done by k-means cluster approach and a diagram of the Spider Web. The results of this research show that the condition of cooperatives in Indonesia is divided into four groups. From the results of this research it is known that there is still very little regard for the province of existing variables.</div>
<br>
<center><img src="images/Koperasi-Indonesia.jpg"/></center>
<br>


---
## Arts by Me

<!-- [![View My Films](https://img.shields.io/badge/YouTube-View_My_Films-grey?logo=youtube&labelColor=FF0000)](https://www.youtube.com/watch?v=vfZwdEWgUPE) -->

<div style="text-align: justify">Besides Data Science, I also have a interest on arts and design like abstract paint or watercolor. Below is a list of my paints.</div>
<br>

<div class="gallery">
<img src="images/Untitled I.jpg" alt="Northern Lights" width="450" height="250">
  <div class="desc">Untitled I</div>
<img src="images/Untitled II.jpg" alt="Northern Lights" width="450" height="250">
  <div class="desc">Untitled II</div>
<img src="images/Untitled III.jpg" alt="Northern Lights" width="450" height="250">
  <div class="desc">Untitled III</div>
  </div>
  
---
<center>© 2022 Syarifah Rosita Dewi. Powered by Jekyll and the Minimal Theme.</center>
