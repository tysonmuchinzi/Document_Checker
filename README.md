# Document Checker using NLP: a work in progress

The Document Checker is a deep learning model that will be able to distiguish among 15 different 
types of documents whether the document is a resume, letter, cv, email, handwritten, advertisement, 
scientific report, scientific publication, check, news article, budget, invoice, presentation, 
questionnaire, memo. By the end of this project I will reduce the number of documents to less than 10.

# What's the goal
At the end of this project am going to have an app that will be able to get relevante information from a document 
or the user can select what they want to view on the document instead of viewing the entire 
information on the document. 

#Project Plane

## Stage 1 (completed):
Get the data set from hugging face. It was difficult for me to get my own data I decide to use the dataset from hugging face.

## Stage 2 (in progress):
Build a model to extract text from the dataset (which are images of the documents). I started with a few data 
for this stage to see the peformance of the model then increase the dataset afterwards.

## Stage 3:
At this stage I need to train a model that will get the extracted information from stage 2 into text and 
and learn the patterns to differentiate the documents.

## Stage 4:
Once all the models are train I will build a streamlit app, this will tell the user to upload the file and ask them 
if the want to view specific information from the document all the entire document.I will make some more changes on this
stage.

## Stage 5
On this stage I will create an API using fastapi and connect it to the streamlit app for deployment. More changes will 
be made here in the process
  