# 5GFederated

# 5G Federated Learning and Simulation Tools: A Comprehensive Guide

This README outlines the necessary steps to effectively utilize the tools designed for the "5G Federated Learning Tool" and "5G Simulation System". Be sure to adhere to these instructions for a seamless experience with our systems.

Before you begin, ensure that your dataset is appropriately configured and placed in the respective directory of the system you wish to work with. The dataset can be sourced from the following GitHub link: [https://github.com/sevgicansalih/nwdaf_data](https://github.com/sevgicansalih/nwdaf_data).

## Pre-requisites
To get the most out of our tools, the following resources are required:
- A suitable code editor.
- Python 3 installed in your system.
- Poetry for dependency management.
- Crucial Python libraries such as Scikit-learn, TensorFlow, Keras, Numpy, Pandas, and XGBoost.

These resources can be installed via pip using the following commands:

```sh
pip install poetry
pip install scikit-learn
pip install tensorflow
pip install keras
pip install numpy
pip install pandas
pip install xgboost
```

## 5G Federated Learning Tool
To commence the operation of the federated learning tool, you'll need to navigate into the directory containing the tool. Depending on your operating system, run the appropriate command.
Note: Make sure to split the dataset before running the programme; 80/20 split, and name the files to be test_data.csv and train_data.csv. You could also chose to use your own data.
For UNIX-based systems, use the following:

```sh
cd <directory_path>
./run_all.sh
```

For Windows systems, utilize this command:

```sh
cd <directory_path>
/runall.bat
```

The above commands will run a simulation for linear regression involving multiple clients connecting to a server. Note that the system will automatically enter the Poetry shell and install the relevant dependencies. 

## 5G Simulation Tool
For the simulation tool, you are required to access the provided Jupyter notebook and run all the cells. This process will provide a complete demonstration of the simulation system, offering valuable insights into its capabilities and potential applications.
Note: Jupyter notebook or google colab are best for runing the script (make sure you have the dataset in the same directory)
Remember, the right utilization of these tools is the first step towards leveraging the full potential of 5G in the realm of federated learning and simulations. Enjoy your exploration!
