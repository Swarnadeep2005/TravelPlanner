# TravelPlanner
🧭 AI Travel Planner
An AI-powered travel planning assistant that uses LangChain, LangGraph, and multi-agent coordination to generate personalized day trip itineraries based on city and interests provided by the user.

📌 Features
📍 Accepts user input for city and preferences

🤖 Utilizes multiple AI agents to generate suggestions

🧠 Employs LangGraph to manage conversation flow

🧳 Generates an optimized day plan including attractions, activities, and breaks

🖼️ Visualizes agent interactions using Mermaid diagrams


🛠️ Tech Stack
Python 3.x

LangChain

LangGraph

OpenAI / Groq LLM support

Jupyter Notebook (for demonstration)

⚙️ Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/AI-Travel-Planner.git
cd AI-Travel-Planner
Install required dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Or manually install:

bash
Copy
Edit
pip install langchain langchain_core langchain_groq langchain_community langgraph
🚀 How to Run
Open the TravelPlanner(fully working).ipynb notebook in Jupyter or Google Colab.

Run all the cells sequentially.

Input a city and interests when prompted.

Receive a personalized itinerary powered by AI agents.

🧩 Architecture:

This planner is built using LangGraph and multi-agent flow. Each agent handles a specific task in the itinerary generation process. The state is passed through nodes to collaboratively build a final plan.

Mermaid flowcharts are used to visualize the conversation structure between agents.

📈 Future Enhancements
🌐 Add real-time weather and event data integration

📆 Support multi-day itinerary planning

📱 Deploy as a web or mobile app interface using Gradio or Streamlit

🗣️ Add voice interaction support
