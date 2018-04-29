# SIH2018-Jobs_and_admission_prediction
Extract screenshots folder to see the images of working project.
Extract all the files in a directory, set up a php server(wamp or xamp preferably) and create a MySQL database as instruced in the code to run the project in your local server

This repository contain the codes and data created during Smart India Hackathon '18 for admission and jobs prediction based on demographic location. Smart India Hackathon is organised by MHRD and AICTE.

Our problem statement:
PREDICTION OF ADMISSION & JOBS IN ENGINEERING AND TECHNOLOGY/MANAGEMENT/PHARMACY WITH RESPECT TO DEMOGRAPHIC LOCATIONS

For demonstration purpose and prototyping, we chose some target areas and used limited number of parameters. We did case study of those areas and got the expected outputs. These results can later be generalised to a very large area,even to the scale of countries, provided we get the required data. The data used in the creating this project is synthetic which was made after a complete experimentation and research of the area. The credibility of data lies in the fact that all the values and parameters chosen are taken from valid sources which includes annual report of colleges and companies, cagr of companies etc. The working of this project depends upon the quality and availibility of data.

We used HTML, CSS and other web development tools to create a web app. PHP is used for server-side linkages. MySQL database is used to store the data from various forms on the website

A neural network model is used for the prediction of admission and jobs. The network is a simple Feed-Forward model consisting of one hidden layer and 40 neurons. The model approximated all the functions well and the loss obtained is significantly low(of the order e^-6). TensorFlow is used to create the model and python is used for all implementations. i-python notebook is used for all the experimenntations and demonstrations

Structure of the frontend:
The product target two types of user:
1. AICTE/UGC or other granting committees who will use our product to decide the number of admission and hence, the number of seats in any new college
2. Users and enthusiasts willing to study the trends and see the availibility of jobs at a particular location
There is a separate company login where companies can post any new job opening at a particular location

The predictions we made are shown in the form of graphs. The website has dynamic capabilities but due to inavailibility of data, the graphs are the static based on predictions from previous data