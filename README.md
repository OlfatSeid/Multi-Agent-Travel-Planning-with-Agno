# Multi-Agent Travel Planning with Agno


Multi-Agent travel planning with agno is a multi-agent system that leverages the agno framework along with Groq’s language models and additional tools (DuckDuckGo, Tavily) to generate comprehensive, step-by-step travel plans. This project demonstrates how to combine specialized agents for travel research, itinerary planning, and budget analysis into a unified team to provide detailed and organized travel recommendations.

## Features

- **Multi-Agent System:**  
  Combines several agents—Travel Researcher, Itinerary Builder, and Budget Analyst—that work together to generate a complete travel plan.
  
- **Organized, Step-by-Step Output:**  
  Outputs the travel plan in a clearly formatted, step-by-step manner (with headings and organized sections) to simplify user understanding.
  
- **Interactive Gradio UI:**  
  A simple, single-column Gradio user interface allows users to input travel requests and view results directly below the query.
  
- **Extensible and Modular:**  
  Easily modify the agents or add additional agents and tools to further customize the travel planning experience.

### Requirements

- Python 3.7+
- [Gradio](https://gradio.app/) (`pip install gradio`)
- [agno](https://pypi.org/project/agno/) (multi-agent framework)
- [groq](https://pypi.org/project/groq/) (Groq API integration)
- [DuckDuckGo Tools](https://pypi.org/project/duckduckgo-tools/) (for search functionality)
- [pydantic](https://pydantic-docs.helpmanual.io/) (for data validation)

#### Setup
**API Keys:
Set up your API keys for Groq and Tavily. In Colab, you can use google.colab.userdata or environment variables to store and access these keys.

**Output Directory:
The application creates an ./travel_output directory for saving the generated outputs. Ensure you have write access to this directory.
