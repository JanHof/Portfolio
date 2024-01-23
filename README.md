# Portfolio

Top-performing professional with 10 years of experience in the Private Banking and Business 
Banking sector. Extensive experience in Online and Digital Banking. Experienced customer service 
professional with sound organisational, marketing and interpersonal skills with proven ability 
managing large workloads. Dedicated to providing exceptional customer service in order to develop 
lasting customer relationships and have a proven track record working in sales-focused 
environments exceeding set targets and KPIs. Ability to prioritise and resolve enquiries and issues in 
a timely and effective manner and am a valued team member who believes in being positive and 
helpful at all times. With excellent written and verbal communication skills, enjoys working at a fast
pace, am enthusiastic and hardworking and thrive on challenging myself. A strong desire to 
succeed, self-motivated, positive and adaptable. 
After 11 years in the banking industry I decided to take a break and explore a new direction.
This led me to coding and data analysis.

Adress:  7 La Boheme Close, Tamboerskloof, Cape Town
email address: hofmeyrjh@gmail.com
LinkedIn: https://www.linkedin.com/in/jan-hendrik-hofmeyr-79153a7/

EDUCATION:
Completed a degreed in BComm Entrepreneurship and followed it up with an Honours degreee in General Business Management.
Recently I have completed a  Data Scientist Bootcamp at Hyperion Dev.

Below are some links to some early projects completed during studying:

SCRATCH: - https://github.com/JanHof/Project-Zero

My first project for CS50 is just a short scratch animation which is more of an inside joke among friends.


LEVEL 2 CAPSTONE PROJECT 2 - https://github.com/JanHof/Level-2-Capstone-Project-2

For this task, I cleaned, sanitised and explored data using the 'movies' dataset.
The 'movies' dataset is a csv file that contains a table of movie titles with categorical and numeric information about the movies. Revenue, Budget and popularity of the movie is included in the dataset. I answered questions about the 'movies' dataset in the Capstone Project II.ipynb notebook.
I then used the automibile.txt. A txt table that contains data of different makes of vehicles. The dimensions of the vehicle's body and engine are included in the dataset. Some output variables include mile per gallon and rpm. The vehicle price is also included.
I cleaned and did exploratory data analysis on the data. I created data visualisations in automobile-checkpoint.ipynb, and wrote a report on investigations, visualisations and findings.

LEVEL 3 CAPSTONE PROJECT 2 - https://github.com/JanHof/Level-3-Capstone-Project-2

This is the Capstone project 2 on the 3rd level of the Data Science bootcamp through HyperionDev. The dataframe UsArrests contains data about the crime levels of all the cities in the USA. The city column as the index and murder, assualt, rape and urban population as the columns. Data Exploration in jupyter notebook:  I initially explored the data and checked for missing values but found no missing values. I checked the data types and created visualisations of the range values for the respective columns.

Data Visualisation: I calculated the correlation of the different columns and created a heatmap to visualise the results. I created a biplot to illustrate the differeces of importance of the various features and the signifcant differneces in the standard deviation. I standardised the data nad created a new biplot which shows the crime level of the different US cities according to the correlation of the column variables. I used the complete linkage method to plot a dendogram to visualise thet respective clusters in the dataset. I created a scatter plot to further visualise the 4 distinct clusters of the cities' crime rates.


LEVEL 3 CAPSTONE PROJECT 3 - https://github.com/JanHof/Level-3-Capstone-Project-3

Training a recurrent neural network to classify the sentiment of book reviews: This is the Third Capstone Projject on Level 3 for the Data Science Bootcamp through HyperionDev. For this project we are required to use recurrent neural networks in Keras to try and classify a movie review as either positive or negative.

The dataset consists of two text files: positive.txt and negative.txt. Each file contains positive and negative book reviews respectively. we will be using the title field for training purposes.

there are 5 functions to load and process the data: The 'filter_words' function strips the unwanted charaacters from the lines and converts characters to lower case. load_ata function loads the text files in to the jupyter notebook and reads only the titles. The titles are then added to a 'data' list. The remaining functions convert the predictions from numeric to word and visa versa, to classes from categrorical.

The two text files are concatenated into the data list. Another list is created with the words 'positive' and 'negative' equal in lenght to the input data files. This is then converted to a 1 or a zero depending on the response.

Data Exploration: Further exploration is done on the data using a pandas dataframe. Displayed the shape and the head to get a better understanding of the data. Calculated and report the mean review size, its standard deviation and created a boxplot Calculated the number of unique words in the dataset. There were no missing values in the dataset.

Data manipulation:

The dataset was tokenized to prepare for the neural network. padded data was tokenised to a length of 4 words. I split the data so that 20% was used for testing.

Building the Neural Network and Analysis:

I added a recurent neural network with input dimension of 2560 and the output of 40 initially but the output of 100 resulted in a more accurate model. 'binary_crossentropy' was used as the 'loss' and 'accuracy' as metrics. The'asess_model' function calculated the predictions, precision f1 score, recall and displayed the confucion matrix. Further predictions were made wih a sample outside of the dataset.
