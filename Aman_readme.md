Title: PROG8420 Assignment 10 - Exploring Advanced Python Tools for Machine Learning and AI

Overview:
The goal of PROG8420 Assignment 10 is to delve into advanced Python tools for machine learning. Throughout this assignment, you will leverage publicly accessible datasets from GitHub repositories or Kaggle to undertake a range of tasks. These tasks encompass data exploration, preprocessing, the implementation of machine learning models, and the visualization of outcomes using Python programming.

Requirements:

Installing Jupyter:
To begin, the installation of Jupyter on your local system is necessary. Initiate the command prompt and execute the ensuing command:

pip install jupyterlab

Launching JupyterLab:
Following the installation of Jupyter, launch JupyterLab by employing the subsequent command:

jupyter lab

his command will trigger the commencement of a JupyterLab session within your local environment. Access to this session can be achieved by navigating to http://127.0.0.1:8888/tree.

Installing Required Libraries:
Installation of specific libraries is imperative for project work. Execute the following commands to install the necessary libraries:

!pip install seaborn
!pip install matplotlib
!pip install scikit-learn   # For implementing SVM & Random Forest Machine Learning Models
!pip install tensorflow     # For implementing Neural Network Machine Learning Models
!pip install keras          # For implementing Neural Network Machine Learning Models


Please be aware that as of TensorFlow 2.0, Keras is integrated as a high-level API within TensorFlow. Consequently, separate installation of TensorFlow and Keras is not obligatory.

Working in JupyterLab:
Once JupyterLab is launched, ensure the opening of a new notebook. Execution of commands within the notebook environment can be accomplished using the Shift + Enter keys.

Task Format:
For each task, utilize Markdown to furnish a header or title. For instance, the following format is suitable: