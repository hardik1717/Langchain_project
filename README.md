# Langchain_project

This is an  LLM project based on Google Palm and Langchain.We are building a system that can talk to MySQL database. User asks questions in a natural language and the system generates answers by converting those questions to an SQL query and then executing that query on MySQL database. 
T-shirt store where maintain inventory, sales and discounts data in MySQL database.![result](https://github.com/hardik1717/Langchain_project/assets/101920338/6b46ab43-bf44-4420-b04f-8dfdbf2f10c6)


Project Highlights :
-  AtliQ Tees is a t shirt store that sells Adidas, Nike, Van Heusen and Levi's t shirts
-  Their inventory, sales and discounts data is stored in a MySQL database
-  We will build an LLM based question and answer system that will use following,
   1. Google Palm LLM
   2. Hugging face embeddings
   3. Streamlit for UI
   4. Langchain framework
   5. Chromadb as a vector store
   6. Few shot learning
In the UI, store manager will ask questions in a natural language and it will produce the answers


#Usage
1. Run the Streamlit app by executing:
streamlit run main.py
