# AstroTreasure---Nawabs 

Members: Archit Agarwal (Y24), Aditya Anand (Y24), Harpuneet Singh (Y24), Mayank Pattnaik (Y23), Sujal Aggarwal (Y23) and Yash Giri (Y22) (PS Lead)

One-Drive Link for Submission (GitHub doesn't allow data submission >25MB): https://iitk-my.sharepoint.com/:u:/g/personal/yashg22_iitk_ac_in/EcktOjglRQ1HuRLjr-0_Y40B1fwGzlAphqeuryo2wBGJUQ?e=TKxVSS

Note: Download the dataset beforehand and make sure your Laptop has great amount of RAM as well as CUDA. Happy Exploring !

Steps to be followed to Run the 3 models:

IMAGE CLASSIFICATION MODEL
Requirement modules: shutil, random, numpy, matplotlib, astropy, torch, torch.nn, torch.optim and specially CUDA for GPU enforcement.
Step 1) Open the file "Astro_Submission.ipynb". There is .pth (Pytorch State dictionary) file which has trained model of the classification algorithm. Keep it intact.
Step 2) Mention the Training dataset directory (labelled) in the "input_folders =" command. The output_folder will convert them into JPG images as a temporary file.
Step 3) Model is trained in ResNet/RNN model method. Splitting of Training and testing data is in 50:50 ratio
Step 4) GPU needs to enforced using "cuda"
Step 5) Run the Jupyter Notebook Codeblock while keeping Laptop power on Charging.
Step 6) Accuracy, Fine tuning of hyper parameters as well as Val Loss is shown in 20 Epochs and then 10 Epochs (for fine tuning).

IMAGE ENHANCEMENT MODEL

Requirement Modules: pandas, numpy, sklearn..
Step 1) Load the file into the Colab environment.
Step 2) Copy path/directory of the FITS file and paste it onto "fits_file" in the first snippet.
Step 3) Put the same directory in the next block of code in the "fits_file". 
Step 4) Run the Model and You'll see the Output to be a very enhanced image.


LIGHT CURVE CLASSIFICATION MODEL

Requirement Modules: sklearn, tensorflow, scipy, keras

Step 1) Open the "Light_Curve_Submission.ipynb" after downloading all requirement modules assuming light curve data is downloaded.
Step 2) Attach the Path of the downloaded data along with combined training and testing data in csv for effective model training. Ratio of training:Testing data is 50:50
Step 3) Do the folder/directory mapping in thr following way:
Folder 1 asteroids target 92 
Folder 2 Comets target 95
Folder 3 Eclipsing binaries target 88
Folder 4 nebula target 65 
Filder 5 planets target 42 
Folder 6 Quasars target 62 
Folder 7 Stars target 16
Folder 8 Supernovae target 67 
Folder 9 Galaxies target 15

This is done to run the module very effectively using Google Colab (without Pro subscription)

Step 4) Run the CNN model for the training data and test it using the test data, data gets trained and validated.
Step 5) Accuracy and Validation is shown.

Nawabs thoroughly enjoyed the Problem Statement and it trained every of the six member great ML concepts, file handling and various modules
