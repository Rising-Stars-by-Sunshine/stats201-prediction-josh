# Machine Learning Analysis of Philippines' GDP
## Project information
- **Author**: [Josh][Manto], [Data Science], [2024], Duke Kunshan University
- **Instructor**: Prof. Luyao Zhang, Duke Kunshan University
- **Disclaimer**: Submissions to the Problem Set 2 for STATS201 Introduction to Machine Learning for Social Science, 2022 Autumn Term (Seven Week - Second) instructed by Prof. Luyao Zhang at Duke Kunshan University.
- **Acknowledgments**: [How to Acknowledge?](https://www.scribbr.co.uk/thesis-dissertation/acknowledgements/)
[notes: please include all professors, students, and staff who have contributed to your completetion of the project.]
- **Project Summary**: [Predicting the Philippines' gross domestic product (GDP) is a crucial task for both government and businesses in the country. In this project I apply machine learning algorithms to analyze Philippines' GDP based on historical data from 1960-2021 and identifying patterns that can be used to make predictions about the future. The intellecetual merits of this project are that the same method can be applied to study the GDP of other couontries. 

## Table of Contents
| Contents  | URL |
| ------------- | ------------- |
| Data  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/tree/main/data |
| Code  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/tree/main/code  |
| Spotlight  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/tree/main/spotlight  |

## Data
| Contents  | URL |
| ------------- | ------------- |
| Data Source | https://data.worldbank.org/indicator/NY.GDP.MKTP.KD.ZG?locations=PH  |
| Queried Data  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/data/phlgdp1.csv  |
| Processed Data  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/tree/main/data/Processed_Data  |

## Code
| Contents  | URL |
| ------------- | ------------- |
| Process Data  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/code/Process_Data_ipynb_josh.ipynb  |
| Analyze Data  | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/code/Data_analysis_josh.ipynb  |
| Spotlight Explanation Data | https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/code/Explanation_Data_josh.ipynb |

## Spotlight
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/spotlight/figures/AAVE.png)
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/spotlight/figures/COMP.png)
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-josh/blob/main/spotlight/figures/LUSD.png)
- Images are created by [Plotly](https://plotly.com/python/distplot) px.histogram functionality. The data was sourced from [SoK: Blockchain Decentralization](https://arxiv.org/abs/2205.04256)

All three figures show the decentralization index of AAVE, COMP, and LUSD from April 2020 - Oct 2022. The X-axis represents the date and Y-axis represents the decentralization value. The higher the box, the higher the decentralization index in that time span. One can observe that COMP was most decentralized at the beginning of 2020 and decentralization gradually decreased until the end of 2022. From AAVE, the same behavior can be observed as there is a sharp increase in decentralization at the beginning of 2021, withn highest decentralization in July 2021, and then gradual decrease as we appproach the end of 2022. LUSD shows similar behaviors. The trend in these three tokens is that they are becoming more and more centralized as we approach 2022's end. 



