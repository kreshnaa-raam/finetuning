# Fine-tuning Customer Support Model

This notebook demonstrates the process of fine-tuning a customer support model using OpenAI’s GPT-3.5-turbo. The steps include loading a dataset, preparing the data, converting it to the appropriate format, uploading the data to OpenAI, and evaluating the fine-tuned model.

## Contents

	1.	Load and Prepare Dataset
        •	Loading a dataset using the datasets library.
        •	Splitting the dataset into training and evaluation sets.
	2.	Convert Dataset for Fine-tuning
    	•	Function to convert the dataset to the chat completion format required for fine-tuning.
	    •	Saving the converted datasets as JSONL files.
	3.	Setup OpenAI Client
	    •	Connecting to the OpenAI API using API keys stored in environment variables.
	4.	Upload Data Files
	    •	Uploading the training and evaluation JSONL files to OpenAI.
	5.	Fine-tune the Model
    	•	Setting up the fine-tuning job with specified hyperparameters.
	6.	Store and Retrieve Fine-tuned Model
	    •	Retrieving the fine-tuned model after the completion of the fine-tuning job.
	7.	Evaluate the Fine-tuned Model
	    •	Evaluating the model’s performance using the Ragas library with metrics such as faithfulness, answer relevancy, and answer correctness.

## Prerequisites

	•	Python 3.7 or higher
	•	Required Python libraries:
	•	datasets
	•	json
	•	openai
	•	dotenv
	•	pandas
	•	ragas
	•	nest_asyncio
	•	langchain_openai


# Generating Predictions with Fine-tuned Model

This notebook demonstrates how to generate predictions using a fine-tuned customer support model. The steps include setting up the OpenAI client, retrieving the fine-tuned model, and generating responses to user queries.

## Contents

	1.	Setup OpenAI Client
	    •	Connecting to the OpenAI API using API keys stored in environment variables.
	2.	Generate Predictions
	    •	Function to generate responses using the fine-tuned model.
	    •	Example usage to generate a response to a sample query.

## Prerequisites

	•	Python 3.7 or higher
	•	Required Python libraries:
	•	openai
	•	dotenv
