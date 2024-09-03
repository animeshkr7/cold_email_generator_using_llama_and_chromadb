# cold_email_generator_using_llama_and_chromadb

Setting up the environment :

`` python -m venv myenv
`` myenv/sripts/activate
`` pip install -r requirements.txt


PROBLEM STATEMENT : Creating a cold email generator for companies which provide manpower with the relevent skills the customer is searching


### tech-stack used : llama LLM , Chromadb , Streamlit(for deployment)


APPORACH : 
1) Extracting the job requirements from the customer page
2) converitng it into json format (using llm)
3) storing the relevent manpower portfolio in chromadb
4) Prompting llm to generate the mail by passing the json job requirements and chromadb db 