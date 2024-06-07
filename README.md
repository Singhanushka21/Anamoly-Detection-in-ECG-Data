# Anamoly-Detection-in-ECG-Data
In this project, we learnt how to detect anomalies in Time Series data using an LSTM Autoencoder. We used real-world ECG data from a single patient with heart disease to detect abnormal hearbeats. The project has been implemented using python.
The dataset contains 5,000 Time Series examples (obtained with ECG) with 140 timesteps. Each sequence corresponds to a single heartbeat from a single patient with congestive heart failure.

We have 5 types of hearbeats (classes):
* Normal (N)
* R-on-T Premature Ventricular Contraction (R-on-T PVC)
* Premature Ventricular Contraction (PVC)
* Supra-ventricular Premature or Ectopic Beat (SP or EB)
* Unclassified Beat (UB).

Necessary Libraries:
* Pytorch
* Copy
* Pandas
* Seaborn
* Pylab
* Matplotlib
* Sklearn
* Arff2

How to run the code?
- Install necessary libraries in the anaconda/collab environment.
- Download and upload the dataset on Jupiter notebook.
- Run the notebook in your browser (Jupiter Notebook)
