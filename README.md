## Emotion-Recognition-From-text
![1_QbnbVSRoAyqLG76ZtF-oew](https://github.com/Mariamelawadly/Emotion-Recognition-From-text-/assets/85554891/ada02141-40b1-426a-81df-3dfee4424e8e)

This project is created as a university project under the supervision of Dr Mustafa Youssef
————————————————————————————————————————
## Train your own model

Requirements (tested with):
- Python 3.6
- Numpy 1.14.5
- Pandas 0.24.1
- Sklearn 0.19.0
- Tensorflow 2.0.0-beta0

### To run the project:

*Downloading/clone the codes 
*Put the dataset in the data folder. To use the dataset in the paper you can download tweets based on their tweet ids available with their classes in “./data/“ and remove the hashtags at the end of each tweets. The final dataset should have the following format: id,text,emotion with one record (tweet) per line.
*The embedding file should be placed in “./vectorss/”
*Use the configuration.cfg to set the name of dataset and embedding file, maximun numer in the vocabulary (max_features), maximum length of terms in the text (maxlen), bactch size and number of epochs to run the training. 
*Then run the handler.py: $python3 handler.py.

## Testing the project:

You can download the trained models used for our project at : https://drive.google.com/drive/u/0/folders/12JT7zFMR4t4YcpYEA04ra4FJl0WudUcc . To run, put the test file into the data forlder. test file should be one tweet per line with no additional columns. set the name of the file in test_configuration.cfg and run handler-test.py. 

## Citation
Please use the following citation when using the code or the paper:

@article{seyeditabari2019emotion,
  title={Emotion Detection in Text: Focusing on Latent Representation},
  author={Seyeditabari, Armin and Tabari, Narges and Gholizadeh, Shafie and Zadrozny, Wlodek},
  journal={arXiv preprint arXiv:1907.09369},
  year={2019}
}
