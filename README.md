# Agentic AI Research Project  

An **agentic AI system** that automates the research workflow using multiple specialized agents.  
This project leverages **CrewAI** to coordinate AI agents that research, write, and proofread insightful articles with relevant sources.  

---

## 🚀 Features  
- **Research Agent** – Finds the latest trends, pros & cons, opportunities, and risks on a given topic.  
- **Writer Agent** – Drafts a structured, digestible, and engaging article in markdown.  
- **Proofreader Agent** – Finalizes the article, ensures readability, and adds reliable sources.  
- **Automated Workflow** – Uses tasks and tools like Google Search to generate a complete research pipeline.  
- **Markdown Export** – Final output is stored as `newsletter.md`.  

---

## ⚙️ Installation & Setup  

### 1. **Clone the repository**  
git clone https://github.com/yourusername/agentic_ai_research_project.git
cd agentic_ai_research_project

### 2. Install dependencies using Pipenv
pipenv install
pipenv shell

### 3. Configure Environment Variables
Create a .env file and add your API keys.
GOOGLE_API_KEY=your_api_key
SERPAPI_KEY=your_serpapi_key

### 4. Run the research pipeline with:
python crew.py --topic "Artificial Intelligence in Healthcare"



## 👤 Author
**Siddharth Bhimpure**  
- 🎓 B.Tech in AI & Data Science  

