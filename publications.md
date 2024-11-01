---
layout: default
---

# Publications

## 2024

### S+SSPR

Downloads: [PDF](./pdfs/Fankhauser-24_Spatio_Temporal_Graph_Neural_Networks_for_Water_Temperature_Modeling.pdf)

Recurrent Neural Networks do show their performance in time series modeling. So do Graph Neural Networks in modeling irregular neighboring structures. We propose a novel spatio-temporal architecture suited for water temperature modeling as well as other node-with-id networks.

```
In progress
```

### ANNPR

Downloads: [PDF](./pdfs/Fankhauser-24_Leveraging_LSTM_Embeddings_for_River_Water_Temperature_Modeling.pdf)

We propose a novel LSTM tailored for water temperature modeling using embeddings. Not only do we improve state-of-the-art performance by five percent, we also reduce the amount of learnable parameters by two orders of magnitude.

```
@InProceedings{10.1007/978-3-031-71602-7_24,
author="Fankhauser, Benjamin and Bigler, Vidushi and Riesen, Kaspar",
title="Leveraging LSTM Embeddings for River Water Temperature Modeling",
booktitle="Artificial Neural Networks in Pattern Recognition",
year="2024",
publisher="Springer Nature Switzerland",
address="Cham",
pages="283--294",
isbn="978-3-031-71602-7"
}
```


### ICPRAM
Poster: [View](./icpram_poster)
<br>Downloads: [PDF](./pdfs/Fankhauser-24_Impute_Sensor_Data_in_the_Swiss_River_Network.pdf)

We use the connectivity of water stations to improve data imputing. We have a lot of missing data in our dataset and using the available measurements of neighboring stations improves the quality of data imputing by a lot.

```
@conference{icpram24,
author={Benjamin Fankhauser. and Vidushi Bigler. and Kaspar Riesen.},
title={Impute Water Temperature in the Swiss River Network Using LSTMs},
booktitle={Proceedings of the 13th International Conference on Pattern Recognition Applications and Methods - ICPRAM},
year={2024},
pages={732-738},
publisher={SciTePress},
organization={INSTICC},
doi={10.5220/0012358100003654},
isbn={978-989-758-684-2},
issn={2184-4313},
}
```

## 2023

### GBR: Graph Based Deep Learning on the Swiss River Network
Downloads: [PDF](./pdfs/Fankhauser-23_Graph_Based_Deep_Learning_on_the_Swiss_River_Network.pdf)

In this work we use the connectivity of water stations (namely the rivers). In a first step we predict the water temperature at each water station using an LSTM. Then we use the connectivity to refine these first predictions. Using the connectivity improves the state of the art at around 5%.

```
@inproceedings{fankhauser2023graph,
  title={Graph-Based Deep Learning on the Swiss River Network},
  author={Fankhauser, Benjamin and Bigler, Vidushi and Riesen, Kaspar},
  booktitle={International Workshop on Graph-Based Representations in Pattern Recognition},
  pages={172--181},
  year={2023},
  organization={Springer}
}
```

# Theses


## Imputing the entire Swiss River Network
Carlo Robbiani, 2024, Download: [PDF](https://prg.inf.unibe.ch/wp-content/uploads/2024/08/BA_CarloRobbiani.pdf)

The process of measuring hydrological variables is not perfect. Due to scheduled service or malfunctions, data is missing. Depending on the case, a different strategy to fill these resulting gaps is required. This work uses the latest state-of-the-art models to fill each gap with the most suited method. The result is a gap free dataset with 80 stations over 40 years with an estimated RMSE of an astonishing 0.652.


## Clustering of Hydrological Stations
Jan Zurbrügg, 2023, Download: [PDF](http://prg.inf.unibe.ch/wp-content/uploads/2023/09/Bachelor_Thesis_Jan_Zurbrugg_Clustering_of_Hydrological_Stations.pdf)

In this work, a method has been developed to extract important characteristics of hydrological stations. These characteristics have been used to cluster stations with similarities in temperature and discharge patterns using an fully automated way.

[back](./)



