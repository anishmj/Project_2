## URL-Based Q&A Answering System
This project builds an AI-powered research tool that extracts answers from web pages based on user queries. By leveraging LangChain, OpenAI’s LLM, and FAISS, the system efficiently retrieves precise answers from URLs, reducing the need for manual searching.

## About
Traditional search engines provide a list of links without directly answering user questions. This project enhances information retrieval by:
Extracting relevant text from given URLs.
Storing text embeddings in a FAISS vector database.
Using LangChain’s RetrievalQAWithSourcesChain to fetch relevant answers.
Providing direct, structured responses instead of just listing search results.
## Features
Uses an advanced NLP model with OpenAI’s GPT for question answering
Extracts meaningful text from web pages through URL scraping and parsing
Splits large texts efficiently using RecursiveCharacterTextSplitter
Converts extracted text into vector representations for quick retrieval with FAISS
Provides an interactive Streamlit user interface for inputting URLs and queries

## Requirements
Operating System: Windows 10 or Ubuntu (64-bit)
Development Tools: Python 3.8 or later, VSCode
Key Libraries:
streamlit for the user interface
langchain for AI processing
faiss-cpu for vector search
openai for language model integration
unstructured for web scraping
dotenv for managing environment variables

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![sys_arch](https://github.com/user-attachments/assets/ec32d139-325a-44f3-b223-67541c8654f8)



## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Name of the output

![op3](https://github.com/user-attachments/assets/2941158a-426e-4186-a3ed-72cfabed18b1)


#### Output2 - Name of the output
![op4](https://github.com/user-attachments/assets/a6528f48-4557-4767-b514-ca70b5257b82)


\.


## Results and Impact
Provides faster information retrieval by eliminating the need for manual searches
Delivers contextual answers extracted from relevant sections of web content
Includes cited sources for improved credibility and verification

This project serves as a foundation for future developments in assistive technologies and contributes to creating a more inclusive and accessible digital environment.

## Articles published / References
S. S. Naaz, Artificial Intelligence in Information Retrieval: AI-based Techniques for Improving Search and Information Retrieval Systems in Both Libraries and Other Knowledge Hubs, Dr. Babasaheb Ambedkar Marathwada University, 2023.

T. Mandl, Artificial Intelligence for Information Retrieval, in Encyclopedia of Artificial Intelligence, J. R. R. Dopico, J. D. de la Calle, and A. P. Sierra, Eds. IGI Global, 2008, pp. 1–10. Available: https://doi.org/10.4018/9781599048499.ch023.

C. Collins, D. Dennehy, K. Conboy, and P. Mikalef, Artificial intelligence in information systems research: A systematic literature review and research agenda, International Journal of Information Management, vol. 60, p. 102383, 2021. Available: https://doi.org/10.1016/j.ijinfomgt.2021.102383.

D. De Jaco and G. Garbolino, An information retrieval system based on artificial intelligence techniques, in Proceedings of the 9th ACM International Conference on Research and Development in Information Retrieval, 1986, pp. 214–217. Available: https://doi.org/10.1145/253168.253215.

H. Zamani, F. Diaz, M. Dehghani, D. Metzler, and M. Bendersky, Retrieval-enhanced machine learning, arXiv preprint, 2022. Available: https://arxiv.org/abs/2205.01230.

W. R. Hersh, Search still matters: Information retrieval in the era of generative AI, arXiv preprint, 2023. Available: https://arxiv.org/abs/2311.18550.

A. Trotman, An artificial intelligence approach to information retrieval, in Proceedings of the ACM SIGIR Conference on Information Retrieval, 2003.

M. Feng, W. Y. Liu, N. F. Xie, and W. Chen, Answer clustering and fusion in a user-interactive QA system, in Proceedings of the 2nd International Conference on Semantics, Knowledge and Grid (SKG 2006), November 1–3, 2006, Guilin, China.

E. M. Voorhees, Overview of the TREC-9 question answering track, in Proceedings of the Twelfth Text REtrieval Conference (TREC 9), 2000, pp. 71–80.












