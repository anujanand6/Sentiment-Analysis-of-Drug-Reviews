## Sentiment Analysis of Drug Reviews

This project is done by Anuj Anand and Ashish Juneja as part of the course Text Analytics and Natural Language Processing.

---------------------

### Project Structure
1. ProjectNotebook_AA_AJ.py - This contains the code for EDA, data preprocessing, tokenization, sentiment classification, and so on.

2. Deployment_AA_AJ.py - This contains Flask APIs that receives a drug review, computes the sentiment of the review based on the output of a pre-trained model and returns it.

3. Data Files - This folder contains the files to run the notebook 'ProjectNotebook_AA_AJ.py' and predict the sentiment.

4. Deployment -  This folder contains the files to run the notebook 'Deployment_AA_AJ.py' and deploy the project.

5. Project Report - A detailed description of the project with the observations, results and conclusions.

----------------------

### Running the project
1. Open the notebook called 'ProjectNotebook_AA_AJ.py'
2. Clone the GitHub repository to Google Colab
3. Change runtime to GPU.
3. Run the code.

-----------------------

### Running the deployment
1. Open the notebook called 'Deployment_AA_AJ.py'
2. Clone the GitHub repository to Google Colab.
3. Navigate to the directory called 'Deployment' that contains the required files. 
4. Run the code.
5. To view the HTML page, navigate to the second URL present in the output console. (Eg. http://557929ff7dac.ngrok.io)
3. Enter the review in the text box.
4. Click on 'Predict'
5. If everything goes well, you should see the predicted sentiment along with the its probability!

-----------------------