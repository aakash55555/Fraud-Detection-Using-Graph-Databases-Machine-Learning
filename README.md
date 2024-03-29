![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)

### FPG

**F**raud **P**rediction using **G**raph features.

Evaluations and results are summarized in the direcory [evaluations](https://github.com/PratikBarhate/fpg/blob/master/evaluations/evaluations.md)

#### Dataset

1. We have used a dataset available on Kaggle - [Synthetic data from a Financial payment system](https://www.kaggle.com/ntnu-testimon/banksim1).
2. All the raw data is copied to [data](https://github.com/PratikBarhate/fpg/tree/master/data) directory.

#### Software dependencies

1. Python - v3.6
2. To install the required packages run the command `pip install -r requirements.txt` or `pip3 install -r requirements.txt` depending on your system configuration.

#### Step required to execute code

1. To execute the jupyter notebooks go into the notebooks directory - `cd code/notebooks`, and start the jupyter notebook on your system. From the jupyter notebook's web UI you can start any of the notebooks.

2. To execute the self paced sampling example - `cd code/sampling` and execute command `python3 using_self_paced.py`.

3. To execute persona -cd code/persona' and execute command 
'python3 -m graph_embedding.persona.persona --input_graph=${graph} \ --output_clustering=${clustering_output}'.

#### References

1. _Bryan Perozzi, Rami Al-Rfou, Steven Skiena_. DeepWalk: Online Learning of Social Representations 2018

2. _Epasto, Alessandro, and Bryan Perozzi_. "Is a single embedding enough? learning node representations that capture multiple social contexts." In The World Wide Web Conference, pp. 394-404. 2019.

3. _Zhining Liu, Wei Cao, Zhifeng Gao, Jiang Bian, Hechang Chen, Yi Chang, Tie-Yan Liu_. Self-paced Ensemble for Highly Imbalanced Massive Data Classification.  September 2019

4. _Brownlee, Jason_. SMOTE Oversampling for Imbalanced Classification with Python - https://machinelearningmastery.com. January 2017

5. dzone.com (2020). Finding Needles in a Haystack With Graph Databases and Machine Learning - DZone AI. [online] Available at: https://dzone.com/articles/finding-needles-in-a-haystack-with-graph-databases [Accessed 22 Feb. 2020].

6. Learn How to Perform Feature Extraction from Graphs using DeepWalk  https://www.analyticsvidhya.com/blog/2019/11/graph-feature-extraction-deepwalk/

#### Contributors

CSE 573 Spring 2020 Group 12

* Aakash Rastogi
* Amruta Tapadiya
* Kshitij Kashettiwar
* Pratik Barhate
* Richa Nagda 
* Vrushabh Jambhulkar
