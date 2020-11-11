# Microsoft-x-PIE-Datathon

This is a project Lauren Lee, Daniel Zou, Raymond Lui, and Michelle Cheung did for the 2020 Microsoft x PIE (Pioneers in Engineering) Datathon. We created a support classifier which ultilizes key words to categorize a support request to the proper theme from the customer data set we were provided. You can find more information about the datathon and the original data sets at [this repo](https://github.com/microsoft-us-ocp-ai/ucbazureworkshop).

## Usefulness of the Support Classifier
Our project is to help create a tool that customer service departments can implement. It can do the following:
- Direct customers to the right department quicker
- Better customer experience, better business efficiency 
- Example Implementation: When a customer calls customer service, an automated bot will ask them what they’re looking for. The bot will then redirect the customer to the right department based on what the customer says. Instead of listening to a menu of options and then picking a category that only generally fits your problem description, you’ll be able to quickly present your problem and be taken exactly where it can be resolved.

## Project Highlights
1. Key Phrase Extraction
   - Utilize Text Anaylytics resource on Azure
   - Focus on more important keywords instead of distracting and redundant features
2. Bag of Words
   - Processed key phrases into format suited for ML (`key_phrase_extraction(client, df)` method in `exploration.ipynb`)
   - Exported to CSV (can be found in the file called `data`)
3. Azure ML Workspace
   - Upload process data to Azure cloud for high performance training
   - Tried to train classification model to predict the theme of a new ticket



