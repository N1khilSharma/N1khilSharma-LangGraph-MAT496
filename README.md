# N1khilSharma-LangGraph-MAT496


## ***Module 1 Start***

**Video - 1  MOTIVATION**

What I learned - 

1. Langgraph helps in bending the reliability curve by giving higher reliability for same amount of agent control.
2. Pillars of Langgraph that include Persistence, Streaming, Human-in-the-loop, Controllability.
3. What is Control Flow and an idea of what happens when LLM is injected in it.



**Video - 2  SIMPLE GRAPH**

What I learned - 

1.	What are edges , nodes, states in a graph
2.	What is Graph Construction and the components of it like the StateGraph function and adding nodes
3.	Graph invocation using invoke and what it means for a graph to run synchronously.

Changes I made-
1.	Altered the prompts in the code.
2.	Altered the weight for nodes in the code.
3.	Created a new graph at the end with 3 nodes.


<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/de2cf8dd-c602-4a37-a723-fe2165aaa62a" />

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-1/simple-graph.ipynb



**Video - 3  Langsmith Studio**

What I learned - 

1.	Interacting with the Langgraph ide in studio.
2.	Tracking the run of the graph in studio using Threads.



**Video - 4  CHAIN**

What I learned - 

1.	What are Chains in Langgraph and how they bind tools.
2.	What are messages, types of messages in Langgraph and that chat models interact using messages.
3.	What are tools and how to do tool calls on chat models. 
4.	Using messages as GraphStates.

Changes I made-
1.	Altered the prompts in the code.
2.	Created a graph at the end which performs tool calls and uses message as GraphState to perform arithmetic operations.

<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/4d8ba0fa-4cc1-47e0-a022-50b9da5fdd08" />

Soruce Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-1/chain.ipynb


**Video - 5  ROUTER**

What I learned - 
1.	How a LLM can act as a Router.
2.	Using built in ToolNode from Langgraph used to call Tools.
3.	Using built in tools_condition which is very useful when working with tool calling models.
4.	Representation of tool calls in studio.

Changes I made-
1.	Altered the prompts in the code.
2.	Created a graph at the end using ToolNode and tools_condtion that prints fancy font print for entered prompt based on the conditional edge.

<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/fa0af8f1-2395-4bed-ba0f-a3f737e37fa7" />

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-1/router.ipynb



**Video - 6  Agent**

What I learned - 
1.	What is ReAct architecture that is used for agents and the three components of ReAct.
2.	Adding recursive edges between tools and the LLM and keep it running till the LLM sees it fit to end.
3.	Checking traces of Langgraph on studio which shows the tools used as well.
   
Changes I made-
1.	Altered the prompts in the code a little.
2.	Added my own example at the end demonstrating recursion.

<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/02706cf5-6dd4-44fc-9afc-b162c29b0556" />


Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-1/agent.ipynb




**Video - 7  Agent Memory**

What I learned - 
1.	How persistence and independence introduce the idea of memory, Checkpointers in Langchain after each GraphState.
2.	MemorySaver function for graphs and the contents of a CheckPointer.
3.	Association of CheckPointers using Threads.
4.	Checkpointers give access to the entire state of the previous graph for future invocations.
   
Changes I made-
1.	Altered the prompts in the code a little.
2.	Extended the existing checkpointer thread and added my own code block to continue in the thread.



Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-1/agent-memory.ipynb



## ***Module 2 Start***

#**Video - 1  State Schema**

What I learned - 
1. What is State Schema and its application.
2. What are Dataclasses and what is Pydantic.
3. Application of Pydantic for data validation and using @validator.

Changes I made - 
1. Altered the prompts in code.
2. Added a code cell at the end to test out Pydantic

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-2/state-schema.ipynb


**Video - 2  State Reducers**

What I learned -
1. Langgraph errors library and InvalidUpdateError function in the library.
2. What are Reducers and why they are needed.
3. How to make Custom Reducers.

Changes I made - 
1. Altered the prompts in code.
2. Added a code cell at the end to test out Custom Reducers.

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-2/state-reducers.ipynb


**Video - 3  Multiple Schemas**

What I learned - 
1. What are private states, overall states and how to use them.
2. Particular Input and Output Schemas and when to use them.


Changes I Made - 
1. Altered the prompts in code.

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-2/multiple-schemas.ipynb


**Video - 4 Trim and Filter Messages**

What I learned - 
1. How to use Messages as states.
2. Why it is Token intensive to have long dialogues.
3. RemoveMessage function in langchain_core.messages library
4. How to filter messages using ID and grab them.


Changes I made - 
1. Altered the prompts in code.
2. Created a cell of code at the end that takes number of messages to be deleted as input and removes all but the last x elements.


<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/f49e87cb-cc01-45b6-997e-129df4596e89" />

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-2/trim-filter-messages.ipynb



**Video - 5 Chatbot w/ Summarizing Messages and Memory**

What I learned - 
1. Summarization of Conversation after setting a number of messages after which all messages should be summarized.
2. Saving the summary in state using memory and checkpointers.
3. This enables us to not have a conversation in state that run lot longer.

Changes I made - 
1. Altered the prompts in the code.
2. Added a code block at the end that takes number of messages before summarization as an input and then summarizes the earlier messages.

<img width="256" height="256" alt="image" src="https://github.com/user-attachments/assets/1c0e2c60-1dec-4c2d-b1a6-738a5223ada5" />

Source Link : https://github.com/langchain-ai/langchain-academy/blob/main/module-2/chatbot-summarization.ipynb














