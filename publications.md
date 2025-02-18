---
layout: default
---

# Publications

## Conference Papers

### 2025

#### Exploring a Graph Regression Problem in River Networks

_Under Review_

**Abstract**: We investigate on a novel graph regression problem with interesting information bottlenecks and long range dependencies.
We set various baselines using Graph Neural Network (GNN) models. In a detailed ablation study we show that GNNs
have degenerated performance under noise compared to other architectures. A rarely mentioned limitation of GNNs.

**Downloads**:

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



