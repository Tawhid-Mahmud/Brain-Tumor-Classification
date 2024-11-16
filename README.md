# Brain-Tumor-Classification

NOT SURE WHY COLAB FILE IS NOT LOADING IN GITHUB

To run this code please download the notebook 
Open Google Colab and upload the notebook 
Click on runtime -> change runtime type -> T4 GPU
This will run and train models on GPU. Makes the runtime much lower

Once you are ready with the set up run all the files. It will take some time to 
get the models ready 

First models will run on 5 epochs and it will save a file names "xception_model.weights.h5"
Second models is for custom CNN that runs on 8 epochs and saves a file named "cnn_model.h5"

These two files are essential for running the streamlit app 
Rest of the code is to render a streamlit app using python

once you have the two files saved or downloaded you can use them to run the streamlit file 
The last few lines of code will create a link usng ngrok link with local host that you can see on your browser

You also need a .env file with google AI api key
that code is commented out, once you run that cell of code. Comment it out again 
As long as you have the .env file with the key you shoudl be okay to run the next few lines of cells.

Make sure to run os library at the top of of the notebook 
Now you can run the streamlit app without any errors. 

Good luck.........
