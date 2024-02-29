# fg24-codabench-challenge

## Requirements
CUDA 11.2
Python 3.8.16

### Libraries

| name           | version  |
| -------------- | -------- |
| cudnn          | 8.1.0.77 |
| cudatoolkit    | 11.2.2   |
| tensorflow-gpu | 2.9.3    |
| tensorflow     | 2.9.3    |
| numpy          | 1.23.5   |
| pandas         | 2.0.3    |
| scikit-learn   | 1.3.0    |
| jupyter        | 1.0.0    |

I recommend using the Anaconda terminal to install everything. If you use it, just copy everything from requirements.txt and past to the terminal.
I recommend starting every code in jupyter-notebook. You just need to write in the Anaconda terminal: jupyter-notebook.

If you want to start training, you need to run train_nn.ipynb. 
If you want to start prediction, you need to run save_test_predictions.ipynb.

Data has to be csv files and be placed in test, train or validation folder (it depends on the purpose of using your data).
