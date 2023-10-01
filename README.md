# AutoML
The purpose of this repository was to execute AutoML tools, compare these and detect features to differentiate between them.

Therefore, the repository contains example code for using AutoML tools, ranging from loading the dataset to making predictions.
The tools AutoGluon, AzureAutoML, H2O-AutoML, Hypercluster, TPOT and Auto-Weka and Google AutoML were executed.

Open-source tools that required coding, have a Python notebook added together with the datasets that were used for the testing and execution of the tool.
This concerns the tools AutoGluon, H2O-AutoML, Hypercluster, and TPOT.
TPOT were tested fot the text classification. Hypercluster was tested for clustering with categorical fetures. These tools do not support text or categorical features preprocessing. 
Threfore, we included preprocessing for this step. 

The open-source tool Auto-Weka comes only with a graphical user interface. Here we give only the dataset that was used to test it.

AzureAutoML was completely automatically. In the final step the model was deployed and offered as executable Python code, where this model can be acessed to for the prediction.
This code is contained in the repository.

Google AutoML was done automatically, prediction was executed online with a google terminal.
Therefore, only the dataset used is provided.


#