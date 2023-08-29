File MLBD.ipynb contains the machine learning model, the training as well as the evaluation of the results.
To run this file on your machine, you need Jupyter Notebooks.

Furthermore, make sure that the libraries used are avilable on your machine.
# Necessary libraries:
- numpy
- matplotlib
- scipy
- pandas
- tensorflow
- tensorflow_probability
- keras
- sklearn
- tensorflow
- random

# Stylistic libraries
- IPython.core.display

Provided everything mentioned above is installed on your machine, if you run everything on the MLBD.ipynb you should obtain the same results presented in the paper.
Don't forget to modify /PATH/ for saving/loading the model and adding the data files (clean_data.csv and noisy_data.csv) to your Jupyter Notebook directory.

To test the model performance on lab measured data, you can use the data provided in the folder Lab_Data. The lab measurement was performed using the technique Nonlinear Photoconductive Sampling [1].
- (noisy_white_light_measurement_NPS_time.txt) provides the time axis (x-axis) of the measurement
- (noisy_white_light_measurement_NPS.txt) provides the waveform amplitude (y-axis) of the measurement
- (pred_white_light_measurement_NPS.txt) is the model prediction of the same waveform





[1] https://www.nature.com/articles/s41467-019-14268-x
