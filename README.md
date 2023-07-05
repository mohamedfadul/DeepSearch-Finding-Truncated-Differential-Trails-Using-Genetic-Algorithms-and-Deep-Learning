# DeepGen-Finding-Truncated-Differential-Trails-Using-Genetic-Algorithms-and-Deep-Learning
# This repository contains code for three different files:
  •	ANN Baseline Model to Predict Trail Validity.
  •	Neural Network Model and GA to Predict TWINE Round 15.
  •	Verification Script.
# ANN Baseline Model to Predict Trail Validity
  This file uses an artificial neural network (ANN) to predict the validity of differentials in GFS block ciphers using a deep learning model trained on features such as truncated differences, number of rounds, and permutation patterns.
# Neural Network Model and GA to Predict TWINE Round 15
  This file uses a neural network and a genetic algorithm to predict the differentials of TWINE Round 15. The proposed differential validity prediction model was used alongside an active S-box prediction model to find differentials through prediction. The genetic algorithm was used to identify suitable starting points for the search.
# Verification Script
  The purpose of this script is to validate the results generated by DeepGen for predicting differentials. The script scans for specific strings that confirm the presence of differentials.
# How to use the code
  To use the code, you will need to have Python and the following libraries installed:
  •	NumPy.
  •	Pandas.
  •	Keras.
  •	Matplotlib.
  •	Cipher Datasets (targeted round).
# Once you have installed the necessary libraries, you can run the code by following these steps:
  1.	Clone the repository to your local machine.
  2.	Open the files in a Python notebook.
  3.	Specify the location of the cipher dataset in the code.
  4.	Run the cells in the notebook.
# Citation
  If you use the code in your research, please cite the following paper:
  CryptoUSM. (2023). DeepGen: A deep learning framework for predicting trail validity and TWINE round winners. arXiv preprint arXiv:2307.00001.
# License
  The code is licensed under the MIT License.
# Disclaimer
  The code is provided as-is and the author does not offer any warranty or guarantee. The author is not responsible for any damages that may occur as a result of using the code.
