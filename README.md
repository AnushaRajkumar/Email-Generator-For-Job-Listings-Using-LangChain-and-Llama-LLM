#**Email Generator Using LangChain and Llama LLM** <br/></br>
**Tools Used:** Llama3-8b-8192 (LLM Engine), LangChain (orchestration), ChromaDB (vector store), and Streamlit (UI) <br/>
**RAG Pipeline:** Combines job data with user portfolio using Retrieval-Augmented Generation.
**Result:** Generative-AI application that generates emails<br/> <br/>
**Description:** <br/>

The project is a full-stack end-to-end Generative-AI application that generates highly personalized cold emails for sales outreach. <br>
It takes a company’s careers page URL as input, scrapes job listings and extracts relevant information like required skills and job descriptions. 
This data is then analyzed using Llama3-8b-8192 LLM hosted on Groq Cloud for ultra-fast language model inference. <br>
The app uses LangChain to coordinate the workflow and ChromaDB as a vector database to store the user’s portfolio or resume data for retrieval-augmented generation. <br>
The tool intelligently matches the user’s profile with open roles at the target company to create custom emails. <br>
These emails include specific references to company roles and demonstrate an understanding of their needs, making outreach more effective. <br>
The app is deployed with a clean, interactive UI built using Streamlit, allowing easy user inputs and real-time results. <br>
Designed mainly for software services companies, it helps sales teams scale personalized outreach without manual effort.<br>
The architecture is modular and scalable, making it suitable for production environments. <br> 
Overall, the project is a strong example of applying LLMs and RAG pipelines to automate and enhance business development tasks.<br>


