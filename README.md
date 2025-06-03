# AI-Agent
# 🔍 AI Domain Deep Research Agent

An advanced AI research agent built using the Agno Agent framework, Together AI's Qwen model, and Composio tools. This agent helps users conduct comprehensive research on any topic by generating research questions, finding answers through multiple search engines, and compiling professional reports with Google Docs integration.

## 🚀 GitHub Repository

**[CodeWithHarshAI](https://github.com/CodeWithHarshAI)**

## Features

- 🧠 **Intelligent Question Generation**
  - Automatically generates 5 specific research questions about your topic
  - Tailors questions to your specified domain
  - Focuses on creating yes/no questions for clear research outcomes

- 🔎 **Multi-Source Research**
  - Uses Tavily Search for comprehensive web results
  - Leverages Perplexity AI for deeper analysis
  - Combines multiple sources for thorough research

- 📊 **Professional Report Generation**
  - Compiles research findings into a McKinsey-style report
  - Structures content with executive summary, analysis, and conclusion
  - Creates a Google Doc with the complete report

- 🖥️ **User-Friendly Interface**
  - Clean Streamlit UI with intuitive workflow
  - Real-time progress tracking
  - Expandable sections to view detailed results

## 🛠️ How to Run

1. **Setup Environment**

   ```bash
   # Clone the repository
   git clone https://github.com/CodeWithHarshAI/awesome-llm-apps.git
   cd advanced_ai_agents/single_agent_apps/ai_domain_deep_research_agent

   # Install dependencies
   pip install -r requirements.txt

   composio add googledocs
   composio add perplexityai
   ```

2. **Configure API Keys**

   - Get Together AI API key from [Together AI](https://together.ai)
   - Get Composio API key from [Composio](https://composio.ai)
   - Add these to a `.env` file or enter them in the app sidebar

3. **Run the Application**

   ```bash
   streamlit run ai_domain_deep_research_agent.py
   ```

## 🧪 Usage

1. Launch the application
2. Enter your Together AI and Composio API keys in the sidebar
3. Input your research topic and domain
4. Click "Generate Research Questions"
5. Click "Start Research"
6. Click "Compile Final Report" to generate a professional report
7. View the report in-app or on Google Docs

## 🧰 Technical Stack

- **Agno Framework** for AI agent orchestration
- **Together AI (Qwen 3 235B)** for LLM functionality
- **Composio** for search engine and Google Docs integration
- **Streamlit** for building the interface

## 🎯 Example Use Cases

- Academic Research
- Market Analysis
- Policy Research
- Tech Evaluation

## 📦 Dependencies

- `agno`
- `composio_agno`
- `streamlit`
- `python-dotenv`
