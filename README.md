# Dataset-of-PCF-finite-element-models-under-embankment-loads
&ensp;&ensp;&ensp;&ensp;This dataset includes 5046 finite element models of pile composite foundation (PCF) with varying embankment loads and geological conditions. The above model is based on the Abaqus platform. This dataset can provide data support for machine learning-based research on the mechanical behavior of PCF.This dataset is applicable to cases with no pile caps and geogrids.

&ensp;&ensp;&ensp;&ensp;Pile composite foundation (PCF) is a common method for treating weak foundations, with settlement being the primary control indicator in its design. However, accurately and quickly obtaining PCF settlement under different geological environments and embankment loads remains challenging. Machine learning technology provides a new approach for rapidly predicting PCF settlement, with data serving as the foundation for the aforementioned research and also posing challenges in this field. We established a dataset containing 5046 finite element (FE) models of PCF under various embankment loads and geological conditions. This is currently the largest publicly available dataset of PCF finite element analysis models under embankment loads, providing data support for related research by other scholars.
&ensp;&ensp;In this dataset, the models take a row of piles and half of the pile spacing in the direction of the embankment extension as the scope for modeling and analysis. the piles were defined as elastic bodies, while other components were defined as elastoplastic bodies using the Mohr-Coulomb principal model. Normal contacts between the pile and soil, soil and cushion, and cushion and embankment were modeled as hard contact, while tangential contacts were modeled using penalty contact (Coulomb friction). Parameters for piles, cushion, embankments, soil, loads, and interfaces were selected based on literature, engineering surveys, and computational efficiency, as shown in Table 1.
In the PCF finite element model dataset, each model consists of six loading steps: the first five steps represent the process of layer-by-layer embankment construction, and the last step applies a uniformly distributed load on the surface of the embankment. This model dataset includes not only settlement field data but also stress and strain field data. However, this study only extracted the maximum displacement data from all models. We extract settlement data for each load step of all models, and publish it in the "PCF Settlement Data."


# Link


&ensp;&ensp;&ensp;&ensp;Links to the dataset of PCF finite element models：**https://pan.baidu.com/s/1C9iFNU4zauQnOm58C3NaCg?pwd=7459  &ensp;&ensp; password：7459**

# Citation
&ensp;&ensp;&ensp;&ensp;If you find this dataset helpful, please consider citing:

&ensp;&ensp;&ensp;&ensp;**Gao, S., Chen, C., Jiang, X., Zhu, S., Cai, H., Li, W., 2024. Transformer-based settlement prediction model of pile composite foundation under embankment loading. Computers and Geotechnics, 176, 106783. https://doi.org/10.1016/j.compgeo.2024.106783.**
