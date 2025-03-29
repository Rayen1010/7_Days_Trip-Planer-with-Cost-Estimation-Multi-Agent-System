# 🌍 AI Trip Planner Crew

An intelligent travel planning system that uses Ollama's LLM to create personalized trip itineraries based on your preferences.

## 📦 Installation

### Prerequisites
- Python 3.8+
- [Ollama](https://ollama.ai/) installed and running
- SERPER API key (free tier available)

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/trip-planner.git
   cd trip-planner

Create and activate virtual environment:
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate    # Windows

Install dependencies:
pip install -r requirements.txt

Set environment variables:
echo "SERPER_API_KEY=your_api_key_here" > .env

Architecture:
graph TD
    A[User Input] --> B(Select Best City)
    B --> C(Gather City Info)
    C --> D(Create Itinerary)
    D --> E(Generate Final Report)
    E --> F[Output]

Requirements:
langchain-ollama
langgraph
requests
python-dotenv
typing-extensions





 

