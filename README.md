# Detecting fraudulent cryptocurrency transactions 

## Objective

- Detect fraudulent cryptocurrency transactions using Graph Neural Networks (GNNs) to represent users and transactions as nodes and edges in a graph.
- Enhance fraud detection accuracy by employing GNN models, improving both precision and recall.
- Analyze complex transactional relationships and patterns in cryptocurrency ecosystems using graph-based approaches like Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs).

## Introduction

Cryptocurrency transactions have been increasingly targeted by fraudulent activities due to the decentralized and anonymous nature of blockchain systems. Traditional fraud detection techniques struggle to keep up with the evolving tactics employed by cybercriminals. This project explores the use of Graph Neural Networks (GNNs) to detect fraudulent activities within cryptocurrency transactions. The project leverages the graph-based nature of blockchain networks, representing users and transactions as nodes and edges in the graph, and applying advanced GNN models to identify suspicious behaviors.


## Data Collection

### Sources and Datasets

- #### Crypto Transaction Data

  - **Elliptico Bitcoin Transaction Dataset**: Focused on real-world cryptocurrency transactions involving Bitcoin.
  - **Fraudulent Label Data**: Provided by Elliptico to distinguish between legitimate and fraudulent transactions. 
  - **Graph-based Representation Data**: Used to model relationships between users and transactions, essential for GNN-based fraud detection.

## Data Analysis

This analysis was conducted using Python and the following steps:

### Data Preprocessing (EDA)

- Cleaning and preparing the dataset for graph-based modeling
- Normalizing and handling missing values to ensure consistency across features 

### Fraud Detection Models

- Utilized Graph Neural Networks, specifically Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs), to build fraud detection models
- Analysis of graph-based clusters to detect suspicious activity

## Results

Key findings from the analysis include:

- **Emerging fraud trends:** Identified an increase in fraudulent activities, with a noticeable shift in techniques used
- **Clustering of Incidents:** Detected anomalies and fraudulent behaviors using graph clustering techniques
- **Pattern Recognition:** Enhanced fraud detection through the identification of recurring transactional patterns linked to fraud

## Lessons Learned

- **Data Quality:** Ensured accurate graph representations and cleaned transaction data for model input
- **Graph Complexity:** Graph-based modeling of relationships highlighted the importance of well-structured graphs in identifying fraud patterns.
- **Visualization:** GNN models proved effective in detecting complex fraud patterns within the cryptocurrency ecosystem.

## Challenges

This project demonstrated the effectiveness of Graph Neural Networks in detecting fraudulent Bitcoin transactions. The findings can guide future efforts in improving fraud detection models and enhancing security within decentralized finance systems.

## Conclusion

This project demonstrated the effectiveness of Graph Neural Networks in detecting fraudulent Bitcoin transactions. The findings can guide future efforts in improving fraud detection models and enhancing security within decentralized finance systems.


## References

- Elliptic, www.elliptic.co.
- M. Weber, G. Domeniconi, J. Chen, D. K. I. Weidele, C. Bellei, T. Robinson, C. E. Leiserson, "Anti-Money Laundering in Bitcoin: Experimenting with Graph Convolutional Networks for Financial Forensics", KDD ’19 Workshop on Anomaly Detection in Finance, August 2019, Anchorage, AK, USA.
