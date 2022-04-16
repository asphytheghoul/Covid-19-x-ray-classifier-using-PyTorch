# Covid-19-x-ray-classifier-using-PyTorch
A convolutional neural network to classify uploaded chest x-ray images as infected or normal hosted using Streamlit

How to use:
# Downloading and using the python file locally


**Step1**: Clone the repository with the link found in the 'Code' Section or download it as a zip file 
\
\
\
![Screenshot 2022-04-16 222055](https://user-images.githubusercontent.com/91832216/163684141-cb64b449-a4b4-40bd-84ff-4e05295495e4.png)
\
\
\
**Step2**: run `pip install -r requirements.txt ` to install all the required packages 
\
\
\
![pipinstall](https://user-images.githubusercontent.com/91832216/163684248-17b7db42-0d0f-4ac6-bba2-ce1e8d27f487.png)
\
\
\
**Step3**: in the `cnn_for_covid_xray_public.py` file , there's a section to mention the full path to the dataset, update it to the path of the downloaded dataset. 
\
\
\
![datapath](https://user-images.githubusercontent.com/91832216/163684300-d41ffa1e-cc41-4d93-b283-e5d33df75f17.png)
\
\
\
**Step4**: Head over to a terminal and run `streamlit run streamlit.py` where 'streamlit.py' is the name of the Streamlit user interface python file 
\
\
\
![Screenshot 2022-04-16 221806](https://user-images.githubusercontent.com/91832216/163684325-07f018d4-af03-4afa-a39c-1fbfdfc3ac89.png)
\
\
\
**Step5**: Upload an x-ray image using the 'browse files' button that you can see on screen \
\
\
\
![Screenshot 2022-04-16 221831](https://user-images.githubusercontent.com/91832216/163684338-c185f6f5-3d27-4e36-8674-b09affd726a4.png)
\
\
\
Step6: Get your predictions, *The predicted output with a higher score is displayed on screen followed by the second probable output*  \
\
\
\
![Screenshot 2022-04-16 221916](https://user-images.githubusercontent.com/91832216/163684360-487a4b34-cd56-41c0-895b-b9c9435c4c1b.png)
\
\
**P.S. The model may not be a 100% accurate on all systems if downloaded and run, it depends strictly on your system and its capabilites**

# A link to a website running the app will be available soon!
