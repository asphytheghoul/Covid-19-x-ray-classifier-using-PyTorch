# Covid-19-x-ray-classifier-using-PyTorch
A convolutional neural network to classify uploaded chest x-ray images as infected or normal hosted using Streamlit

How to use:
# Downloading and using the python file locally


Step1: Clone the repository with the link found in the 'Code' Section or download it as a zip file

Step2: run `pip install -r requirements.txt ` to install all the required packages


Step3: in the `cnn_for_covid_xray_public.py` file , there's a section to mention the full path to the dataset, update it to the path of the downloaded dataset.


Step4: Head over to a terminal and run `streamlit run streamlit.py` where 'streamlit.py' is the name of the Streamlit user interface python file


Step4: Upload an x-ray image using the upload button that you can see on screen


Step6: Get your predictions, *The predicted output with a higher score is displayed on screen followed by the second probable output* 


**P.S. The model may not be a 100% accurate on all systems if downloaded and run, it depends strictly on your system and its capabilites**


# Running the model on heroku
To run the model on Heroku , visit this link: 

