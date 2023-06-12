# Project Title

ICI_chatbot

## Project Description

The ICI Chatbot is a project designed to provide users with easy access to information about ICI (International College Institute). The chatbot utilizes a trained AI model to answer questions related to ICI's website, courses, admissions, curriculum, student experiences, and more. It aims to improve student engagement, enhance efficiency, and save time by providing immediate responses and handling routine inquiries.

## Getting Started

To get started with the ICI Chatbot, follow these steps:
   1. Run the Python code 
   2. Interact with the chatbot by inputting your questions or queries on    Gradio
   3. See how the chatbot answers


## File Structure

The file structure of the ICI Chatbot project is as follows:
- README.md: Contains information about the project, including instructions and descriptions.
- FAQs.txt: Contains the dataset which is use to generate the answers from
- Final Chatgpt bot BRI llama-index.py: The main Python file that implements the chatbot application.


## Analysis

The ICI Chatbot uses a combination of data ingestion, indexing, querying, and response generation techniques. It employs the llama_index package to build LLM (Language Model)-based applications. The code reads documents from a text file, indexes then using GPTVectorStoreIndex for efficient searching, after that QueryEngine is used to query the stored documents. The responses are synthesized using the ResponseSynthesizer, which utilizes the LLM model.

The accuracy rate of the chatbot is reported to be 99%. However, it is important to note that if users input inquiries unrelated to ICI or beyond the scope of the provided data set, the answers may seem strange. The project emphasizes the need for future updates to the data set to maintain a high accuracy rate.


## Results

The ICI Chatbot project successfully provides an efficient and user-friendly way to access information about ICI. Users can input questions and receive immediate responses related to ICI's website, admissions, courses, curriculum, student experiences, and more. The chatbot's 24/7 availability ensures that queries are answered at any time.

In conclusion, the ICI Chatbot project offers an effective solution for students and individuals seeking specific information about ICI. Its accuracy rate of 99% and constant availability contribute to enhanced student engagement, improved efficiency, and time savings. Future updates to the data set will be necessary to further improve the accuracy and relevance of the chatbot's responses.


## Contributors

Jongsung Shin, Pingfa, Varinthon, Eugene

## Acknowledgments

Project supervisor: Professor Chung Pei Pien
Data provider: ICI office

## References

1. https://llamahub.ai/l/file
2. https://gpt-index.readthedocs.io/en/stable/guides/primer/usage_pattern.html
3. https://github.com/jerryjliu/llama_index/issues/1900
4. https://github.com/jerryjliu/llama_index

