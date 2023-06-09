# DICA Data Cleaning
This dataset is used for trainning Dengue Information Chatbot (DICA)- a LLM based chatbot for answering questions related to dengue fever. The chatbot is developed by Dirigent.ai

## Data source
The dataset is collected from `vnexpress.net` and `vinmec` using web scraping. The dataset is then cleaned to remove identity information of the question and answer.

The dataset contained 5000+ Q&A health-related entries.

Language: Vietnamese

## Data format
The data is organized in csv format with 2 columns `question` and `answer`

## Data cleaning

A language model is being used to censored identity information of the question and answer. 

## Usage

The cleaned data is `cleaned_df.csv` 

The accompanies cleaning notebook is `data_cleaning.ipynb`

The source data is `clean_25_05_2023.csv`

## License
[MIT](https://choosealicense.com/licenses/mit/)
