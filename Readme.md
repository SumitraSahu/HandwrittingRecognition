Cursive Handwritten Text Recognition system implemented using Pytorch and trained on the IAM datasets. 
This Neural Network model recognizes the text contained in the images of segmented texts lines.

Data pre-processing is totally based on [handwritten text recognition](https://github.com/arthurflor23/handwritten-text-recognition).


## Tutorial (Google Colab/Drive)

A Jupyter Notebook is available for demo  Under ./notebook

1. 1_Train_Model_Beam_Spell.ipynb Used for Training
2. 2_HRT_Page_Segmentation.ipynb is used for Segmenting Paragraph in to lines
3. 3_Paragraph_Transformer_Beam_Spell.ipynb is used for Converting line image to digital Text

## Datasets supported


a. [IAM](http://www.fki.inf.unibe.ch/databases/iam-handwriting-database)



## Requirements

- Python 3.x
- OpenCV 4.x
- editdistance
- Pytorch 1.x

## Command line arguments

- `--source`: iam
- `--transform`: transform dataset to the HDF5 file
- `--image`: prediction on a single image with the source parameter
- `--train`: train model using the source argument
- `--test`: evaluate and predict model using the source argument
- `--epochs`: number of epochs
- `--batch_size`: number of the size of each batch
- `--lr`: Learning rate

