# Data_Visualization using T-SNE
Visualization of data using t-distributed stochastic neighbor embedding plots to a huge dataset.

**Overview Of Data**:
The human activities dataset contains 5 classes (sitting-down, standing-up, standing, walking, and sitting) collected on 8 hours of activities of 4 healthy subjects. The dataset is downloaded from the link mentioned below.
The code downloads the data, cleans it , creates feature vector and then uses T-SNE to reduce dimensionality of the feature vector to just 2, and matplotlib was then used to visualize the data.


**Dependencies** :

* pandas(http://pandas.pydata.org/) 
* numpy (http://www.numpy.org/) 
* scikit-learn (http://scikit-learn.org/) 
* matplotlib (http://matplotlib.org/) 

Install dependencies via '[pip](https://pypi.python.org/pypi/pip) install'. (i.e pip install pandas). 
        
**Dataset Link** - https://d396qusza40orc.cloudfront.net/predmachlearn/pml-training.csv

_***How To Run?***_
        Just Type the following command in your Terminal:
                
                >git clone https://github.com/spriya14/Data_Visualization-101.git
                >cd Data_Visualization-101
                >python dataset_visualization_101.py
                



