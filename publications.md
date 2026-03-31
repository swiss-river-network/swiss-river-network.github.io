---
layout: default
---

# Publications

## Journal Papers

### 2025

_Under Review_

**Abstract**: In this work we compare four differnet methods based on their usage of graph structure and/ or embeddings. We curated
three novel datasets with different topological properties to comapre the methdos in different hydrological settings. We conclude that
incorporating structural information consistently enhances the baseline models. As well as massive parameter reduction when using embedding based methods.

**Downloads**: [Preprint](./pdfs/Fankhauser-25_Evaluating_Graphs_and_Embeddings.pdf)

## Conference Papers

### 2026

#### Embedding Techniques for Modeling Ambiguous Time Series in River Water Networks

_Under Review_

**Abstract**: As the basic concatenation embedding technique has shown promising results on water temperature modeling, we investigate further embedding techniques. The Gated Memory Embedding is a natural extension of the LSTM and the alpha-Interpolation applies embeddings
directly on the weight matrices of any neural network. The two more sophisticated methods show both an increase in performance in the task
of water temperature modeling.

**Downloads**:


#### Benchmarking Transformers on Spatio-Temporal River Water Temperature Modeling

_Under Review, 1st Author: Linlin Jia_

**Abstract**: We compare transformer based architectures to LSTM models in the setting of water temperature modeling. To do so we
propose a combined score that incorporates various runtime and accuracy measurements. While transformer demonstrate slightly higher
accuracy, they come with massive drawbacks in training and inference times.

**Downloads**:

### 2025

#### Exploring a Graph Regression Problem in River Networks

_Published in the International Workshop on Graph-Based Representations in Pattern Recognition_

**Abstract**: We investigate on a novel graph regression problem with interesting information bottlenecks and long range dependencies.
We set various baselines using Graph Neural Network (GNN) models. In a detailed ablation study we show that GNNs
have degenerated performance under noise compared to other architectures. A rarely mentioned limitation of GNNs.

**Downloads**: [PDF](./pdfs/Fankhauser-25_Exploring_Graph_Regression.pdf), [BIB](./bibs/gbr25.bib)

### 2024

#### Spatio-Temporal Graph Neural Networks for Water Temperature Modeling

_Published in Joint IAPR International Workshops on Statistical Techniques in Pattern Recognition and Structural and Syntactic Pattern Recognition_

**Abstract**: Recurrent Neural Networks do show their performance in time series modeling. So do Graph Neural Networks in modeling irregular neighboring structures. We propose a novel spatio-temporal architecture suited for water temperature modeling as well as other node-with-id networks.

 **Downloads**: [PDF](./pdfs/Fankhauser-24_Spatio_Temporal_Graph_Neural_Networks_for_Water_Temperature_Modeling.pdf), [BIB](./bibs/sspr.bib)

#### Leveraging LSTM Embeddings for River Water Temperature Modeling

_Published in IAPR TC3 Workshop on Artificial Neural Networks in Pattern Recognition_

**Abstract**: We propose a novel LSTM tailored for water temperature modeling using embeddings. Not only do we improve state-of-the-art performance by five percent, we also reduce the amount of learnable parameters by two orders of magnitude.

 **Downloads**: [PDF](./pdfs/Fankhauser-24_Leveraging_LSTM_Embeddings_for_River_Water_Temperature_Modeling.pdf), [BIB](./bibs/annpr.bib)


#### Impute Sensor Data in the Swiss River Network

_Published in International Conference on Pattern Recognition Applications and Methods_


**Abstract**: We use the connectivity of water stations to improve data imputing. We have a lot of missing data in our dataset and using the available measurements of neighboring stations improves the quality of data imputing by a lot.

**Poster**: [View](./icpram_poster)

**Downloads**: [PDF](./pdfs/Fankhauser-24_Impute_Sensor_Data_in_the_Swiss_River_Network.pdf), [BIB](./bibs/icpram.bib)

### 2023

#### Graph Based Deep Learning on the Swiss River Network

_Published in International Workshop on Graph-Based Representations in Pattern Recognition_

**Abstract**: In this work we use the connectivity of water stations (namely the rivers). In a first step we predict the water temperature at each water station using an LSTM. Then we use the connectivity to refine these first predictions. Using the connectivity improves the state of the art at around 5%.

**Downloads**: [PDF](./pdfs/Fankhauser-23_Graph_Based_Deep_Learning_on_the_Swiss_River_Network.pdf), [BIB](./bibs/gbr.bib)


## Theses

#### Imputing Gaps in Swiss River Dataset

_Carlo Robbiani, 2024_

**Abstract**: The process of measuring hydrological variables is not perfect. Due to scheduled service or malfunctions, data is missing. Depending on the case, a different strategy to fill these resulting gaps is required. This work uses the latest state-of-the-art models to fill each gap with the most suited method. The result is a gap free dataset with 80 stations over 40 years with an estimated RMSE of an astonishing 0.652.

**Downloads**: [PDF](https://prg.inf.unibe.ch/wp-content/uploads/2024/08/BA_CarloRobbiani.pdf), [BIB](./bibs/carlo_robbiani.bib)


#### Clustering of Hydrological Stations
_Jan Zurbrügg, 2023_

**Abstract**: In this work, a method has been developed to extract important characteristics of hydrological stations. These characteristics have been used to cluster stations with similarities in temperature and discharge patterns using an fully automated way.

**Downloads**: [PDF](https://prg.inf.unibe.ch/wp-content/uploads/2024/08/BA_ZurbruggJan.pdf), [BIB](./bibs/jan_zurbruegg.bib)

[back](./)



