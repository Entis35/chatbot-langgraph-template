# chatbot-langgraph-template

Chatbot-LangGraph_v1 is the notebook for the 1st video : https://www.youtube.com/watch?v=0syiyhVyzxY

Chatbot-LangGraph_v2 is the notebook for the 2nd video : https://www.youtube.com/watch?v=QwTczDPMqTY

I am also attaching the url references I have used and might be useful for you for further development of the codes:
 - LangGraph: https://langchain-ai.github.io/langgraph/tutorials/workflows/
 - Qdrant: https://qdrant.tech/documentation/

 Before running the jupyter notebooks, please make sure you have docker client installed on you machine and then run the following command to activate the qdrant localhost:
 - docker run -p 6333:6333 qdrant/qdrant

 For running the notebooks, please run it following the below sequence:
- 0. Offline part: Setting up vector database and the data processing for data extraction and vector embedding
- 1. Constructing the basic langGraph flow
- 2. Let's enhance it where we will keep the conversation state using "graph.invoke"