# Self-Supervised Pre-training For EEG Classification Using SwAV
We run the experiment on Colab and here are the requirements:
Python 3.7  
PyTorch install = 1.8.0, CUDA 11.1 (pre-training)  
PyTorch install = 1.4.0, CUDA 10.1(fine-tune)  
torchvision  
Apex with CUDA extension  
GPU Tesla P100-PCIE-16GB  
Other dependencies: scipy, pandas, numpy,mne  
  
  The project includes the following files：  
  swav_impl.py: Implementation of SwAV model  
  eval_linear.py: Implementation of linear classifier based on frozen feature  
  supervised.ipynb: Implementation of supervised learning model  
  run_exp.ipynb: Main file to run our experimrnt on Colab   
  MI_preprocess.ipynb: Data preprocessing for MI dataset  
  BCI_preprocess.ipynb: Data preprocessing for BCI dataset  
  evaluation.ipynb: Visualize the performance of SwAV and supervised model on downstream task  
  apex: Apex with CUDA extension 
  swav: Facebook Research's implementation of SwAV  
  swav_train: Save the pre-training model and log of SwAV  
  eval: Save the classifier model and log of SwAV  
  supervised_train: Save the pre-training model and log of supervised model  
  supervised_eval: Save the classifier model and log of supervised model   
