# AI-Remote-View
This is a course project for the Machine Learnining for Physicist, 2020 Fall semester at Boston University.
It test if machine learning algorithms, including logistic regression, vector support machine and basic recurrent neural network, can do "remote view" using the pictures and IDs provided by remote viewing advocates. Transfer learning was applied by using the layers from ReNet50 as feature extractor for images.
The data can be either obtained using a simple web crawler notebook "Remote view data.ipynb" or download from https://drive.google.com/drive/folders/16U3MFa5hmrLZqUTkfCeBJPf11xLOoPig?usp=sharing, which is the result of running the notebook. Download the data to a file called "data_RV" under the same directory of the "classification.ipyn" notebook. 

To reproduce the result shown in the notebook, load 
"test_dir_list.txt" "train_dir_list.txt" from the repository instead of running the second cell.

The result are summarized in the "remote view project report.pdf".
