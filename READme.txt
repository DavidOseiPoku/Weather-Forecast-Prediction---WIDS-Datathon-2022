Analysis and Interpretation - Adapting to Climate Change
Last modified: 2023-Mar-19 Data Version: 2023-Jan-14

Dataset Description
Within this folder you will find 3 files. The other 2 files directly related to the project's implementation are can be obtained from the following link: https://www.kaggle.com/competitions/widsdatathon2022/data . The following are the 3 files contained in this folder :
1.final_WiDS-ANN.ipynb - this is a jupyter notebook file containing the implementation of an Artificial Neural Network utilized in solving the problem this project addresses, along with all the preprocessing steps required for the most efficient implementation of this model.

2.WiDS_Datathon_Climate.ppt- this is a powerpoint presentation highlighting the definition of the problem and the results of our analysis.  

3.Data_dict.pdf - this is a file containing a short description of all the features present in the dataset.  


How To Use It
Download the notebook file contained in this folder, along with its dependencies. The notebook file can be ran using an instance of Jupyter Notebooks or Google Collaboratory. When loading the data, be sure to check that the file path matches where the data is stored on your local machine. In the “Model” section of the notebook, during model implementation, the number of units is set to 256, the activation is set to relu (example with linear activation also still exists in the notebook) and the model is set to train for 20 epochs. These parameters can be adjusted as seen fit by the user of the notebook to investigate changes in the results of the ANN.  

Requirements
The script is run using Python3 and requires the installation the tensorflow, keras, sci-kit learn, pandas and matplotlib python packages. All packages can be installed using pip install in the command line.  

– Python:		https://www.python.org/downloads/
– Pandas:		pip install pandas
– Tensorflow:		pip install tensorflow
– Keras: 		pip install keras
– Sci-kit learn:	pip install -U scikit-learn
– Matplotlib:		pip install -U matplotlib


Challenges/Limitations
Time: increasing the number of epochs used to train the model could significantly increase the time taken to train the model. 
  
Future Improvements
Explore working with ensemble modeling. 

Documentation
The documentation for Tensorflow used in this project can be found here:
https://www.tensorflow.org/api_docs
The documentation for keras can be found here:
https://keras.io/
The documentation for sci-kit learn can be found here:
https://scikit-learn.org/stable/
The documentation for pandas can be found here:
https://pandas.pydata.org/docs/
The documentation for matplotlib can be found here:
https://matplotlib.org/stable/index.html

