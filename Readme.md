🎉 Multi-Agent Routing System with LangChain & LangGraph 🚀
🌌 Welcome to a Next-Gen AI Adventure!Buckle up for the Multi-Agent Routing System, a dazzling AI-powered marvel that zips user queries to the perfect destination—be it a vector-powered knowledge base or the vast expanse of Wikipedia! Fueled by LangChain, LangGraph, Groq LLMs, and Astra DB, this system is a whirlwind of precision, speed, and scalability, wrapped in a modular masterpiece. 🎇

🌠 Project Overview
This project is a vibrant dance of AI innovation, using LangChain and LangGraph to orchestrate a multi-agent system that twirls user queries to the right stage:  

🔍 Wikipedia for worldly wisdom.  
🧠 Astra DB Vector Store for niche expertise (think AI agents, prompt engineering, and LLM attacks).

Built for real-world flair, it blends cutting-edge LLMs, embeddings, and vector magic to deliver answers that pop with accuracy and style! 💥

✨ Key Features

🌟 Smart Query Routing: Powered by Groq's Gemma-2 9B Instruct LLM, spinning queries to the perfect source with laser precision.  
🔄 State Machine Wizardry: LangGraph conducts a seamless flow, twirling through conditional paths like a cosmic ballet.  
📚 Document Ingestion: WebBaseLoader swoops in to load data with effortless grace.  
🧩 Embedding Magic: HuggingFace all-MiniLM-L6-v2 crafts sparkling sentence embeddings.  
💾 Vector Vault: Astra DB stores domain-specific gems for lightning-fast retrieval.  
🌍 Wikipedia Whirl: WikipediaQueryRun dives into the global knowledge pool.  
📡 Streaming Spectacle: Watch answers stream in with real-time, animated flair!


🛠 Tech Stack



Tool/Library
Purpose



🎨 LangChain
Chains LLM components with elegance


⚙️ LangGraph
Orchestrates state and routing logic


🧠 Groq + Gemma-2
Powers query routing with brilliance


🤗 HuggingFace
Crafts stellar sentence embeddings


💿 Astra DB
Stores domain data in a vector galaxy


🌐 WikipediaAPIWrapper
Fetches worldly knowledge with finesse


📓 Google Colab
Prototypes in a dynamic coding cosmos



📂 Project Structure
multi-agent-langgraph/
├── multiagent_1.ipynb   🌌 Core notebook bursting with AI magic
├── README.md            📜 Your animated guide to the project


🚀 Blast Off: Getting Started

Clone the Cosmic Repo:  
git clone https://github.com/khuramshahz/Multi-Agent-Routing-System-with-LangChain-LangGraph.git
cd Multi-Agent-Routing-System-with-LangChain-LangGraph


Summon Dependencies: Ensure Python 3.8+ is ready, then spark the magic:  
pip install langchain langgraph groq wikipedia-api sentence-transformers astrapy


Configure the Cosmos: Create a .env file and sprinkle in your keys:  
GROQ_API_KEY=your_groq_api_key
ASTRA_DB_ENDPOINT=your_astra_db_endpoint
ASTRA_DB_TOKEN=your_astra_db_token


Launch the Nebula: Open multiagent_1.ipynb in Google Colab or a local Jupyter environment and watch the cells ignite! 🔥



🎮 How to Play

Query the Galaxy: Toss in a question, and the system spins it to either Astra DB (for niche queries) or Wikipedia (for general knowledge).  
Example Sparks:  
"What’s new in prompt engineering?" ✨ → Zips to Astra DB.  
"Who won the Nobel Prize in 2023?" 🌍 → Dives into Wikipedia.


Streaming Showtime: Answers flow in with animated, real-time dazzle! 🎥


🤝 Join the Cosmic Crew
Want to add your stardust? Contributions are a blast!  

Fork the repo.  
Create a feature branch: git checkout -b feature/YourCosmicFeature.  
Commit your spark: git commit -m 'Add Cosmic Feature'.  
Push to the stars: git push origin feature/YourCosmicFeature.  
Open a Pull Request and light up the galaxy! 🌠


📜 License
Licensed under the MIT License. Check the LICENSE file for the fine print.  

📬 Contact
Got a supernova of an idea? Ping Khuram Shahzad or launch an issue on GitHub! 🚀  

🌟 A pulsating, AI-driven query router—crafted for precision, scalability, and cosmic flair! 🌟
