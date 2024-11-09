# show-rules-and-regulations-of-different-countries


Agent-Based Task Automation with CrewAI project:

Agent-Based Task Automation with CrewAI
This project utilizes CrewAI to automate the extraction and writing of rules and cultural insights for a specified country. The agents work collaboratively to gather information and generate a summary of the country’s cultural rules and regulations. This workflow consists of two agents: a Researcher agent responsible for gathering data and a Writer agent that crafts a well-written summary based on the research.

Project Overview
The Agent-Based Task Automation with CrewAI project showcases the use of agents for task automation. By leveraging CrewAI’s agent framework, we break down the task into two main processes:

Researcher Agent: This agent is responsible for searching and extracting relevant rules and regulations from multiple sources, including web pages.
Writer Agent: After the researcher gathers the data, the writer crafts a detailed, organized summary about the country’s rules and cultural habits.
The agents are part of a Crew, which orchestrates the task execution, ensuring efficient and collaborative processing. This project is useful for gathering specific knowledge about countries, including their legal systems and cultural norms.

Key Features
Agent-based Task Execution: Use of two agents working in tandem to gather and organize data.
Dynamic Data Extraction: The Researcher agent utilizes various tools, like SerperDevTool, WebsiteSearchTool, and FileReadTool, to fetch the most relevant and recent information.
Writing and Formatting: The Writer agent structures the gathered information into an engaging and readable format.
Flexibility: The project can be adapted to extract rules and culture data for different countries by changing the input parameters.
Technologies Used
CrewAI: Framework for creating and managing intelligent agents.
LangChain: Tools like DuckDuckGo and SerperDevTool used for web search and data extraction.
Python: The project is built in Python, which is utilized for scripting agent actions, tool usage, and task execution.
Code Overview
The code utilizes CrewAI to define and execute tasks through the collaboration of two agents. Below is the key workflow:

Agents Initialization:

Researcher: Extracts rules and cultural insights from various sources.
Writer: Organizes the gathered data into a structured summary.
Tools:

SerperDevTool: Used for conducting search queries.
WebsiteSearchTool: Searches through websites for relevant information.
FileReadTool: Reads and processes files related to the data.
Task Definition:

Research: The researcher agent fetches relevant rules and regulations.
Write: The writer agent formats the research results into a readable summary.
Crew Assembly:

Both agents (researcher and writer) are part of a crew that works together on the tasks.
Execution:

The kickoff() method initiates the tasks, executing them in the defined order.
