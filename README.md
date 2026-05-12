# 🇮🇳 Smart India Travel Guide

##  Project Overview

Smart India Travel Guide is an AI-based travel assistant developed using Python and FastAPI. The project is designed to provide intelligent, explainable, and user-friendly travel recommendations for different tourist destinations across India.

Unlike traditional chatbot systems that depend on Large Language Models (LLMs) or external APIs, this project uses Semantic Networks and Rule-Based Natural Language Processing techniques to generate responses. The system works completely through symbolic reasoning over a custom-built knowledge base, making it lightweight, deterministic, and self-contained.

The chatbot helps users explore Indian travel destinations by answering questions related to beaches, hill stations, historical places, food, weather, festivals, and best visiting times. The system can perform both forward reasoning and reverse reasoning to provide accurate travel recommendations.

The project also implements Explainable Artificial Intelligence (XAI), where the chatbot can display the reasoning path used to generate answers. This helps users understand how the system reached a particular conclusion.

The application includes a modern web interface with an interactive chat system that allows users to communicate naturally with the travel guide.

This project demonstrates the practical implementation of Artificial Intelligence concepts such as Semantic Networks, Knowledge Representation, Rule-Based NLP, Explainable AI, and Intelligent Conversational Systems.

---

#  Objectives

- Provide intelligent travel recommendations
- Demonstrate semantic network reasoning
- Implement explainable AI techniques
- Create a rule-based conversational chatbot
- Support deterministic response generation
- Build a lightweight AI travel assistant

---

#  Features

- AI-powered travel chatbot
- Semantic network reasoning engine
- Explainable AI response generation
- Rule-based Natural Language Processing
- Forward and reverse reasoning support
- Interactive web-based chat interface
- FastAPI backend integration
- Deterministic and self-contained system
- User-friendly conversational responses

---

#  Core Techniques Used

## 1️ Semantic Networks

Semantic Networks are used to represent relationships between destinations, attractions, activities, and travel information.

The knowledge graph stores:

- Tourist destinations
- Weather information
- Food specialties
- Tourist attractions
- Travel categories

The chatbot traverses this graph to answer user queries intelligently.

---

## 2️ Rule-Based NLP

Rule-Based Natural Language Processing is used to identify user intent and generate conversational responses.

The NLP system performs:

- Query parsing
- Keyword matching
- Intent classification
- Response generation

This helps create natural and user-friendly interactions.

---

## 3️ Explainable AI (XAI)

The project includes explainable reasoning paths for every response.

The chatbot can show:

- Nodes visited
- Relationships traversed
- Reasoning steps used for inference

This improves transparency and trust in AI decision-making.

---

#  How the System Works

1. User enters a travel-related query
2. NLP module extracts keywords and intent
3. Semantic network searches related nodes
4. Graph traversal performs reasoning
5. Best matching travel information is identified
6. Conversational response is generated
7. Reasoning path is displayed with the answer

---

#  Frontend and Backend

## Backend

The backend is developed using Python and FastAPI.

It handles:

- Query processing
- Intent classification
- Semantic reasoning
- API response generation

---

## Frontend

The frontend is built using:

- HTML5
- CSS
- Vanilla JavaScript

It provides:

- Interactive chat interface
- Responsive UI
- Real-time chatbot interaction

---

#  Technologies Used

- Python
- FastAPI
- Pydantic
- HTML5
- CSS
- JavaScript
- Semantic Networks
- Rule-Based NLP
- Explainable AI Concepts

---

#  Project Structure

```bash
Smart-India-Travel-Guide/
├── main.py
├── data.py
├── network.py
├── nlp.py
├── index.html
├── start.bat
└── README.md
```

---

#  Installation

## 1️ Clone Repository

```bash
git clone https://github.com/your-username/smart-india-travel-guide.git
```

## 2️ Move to Project Directory

```bash
cd smart-india-travel-guide
```

## 3️ Create Virtual Environment

```bash
python -m venv venv
```

---

## 4️ Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

### macOS/Linux

```bash
source venv/bin/activate
```

---

## 5️ Install Dependencies

```bash
pip install fastapi uvicorn pydantic
```

---

#  Run the Project

##  1️ Using Batch File (Windows)

```bash
start.bat
```

---

##  2️ Using Uvicorn

```bash
uvicorn main:app --reload --port 8000
```

Open browser:

```text
http://localhost:8000/
```

---

#  Example Queries

```text
What is the best time to visit Goa?
```

```text
Which places are famous for beaches?
```

```text
Suggest a hill station in India
```

---

#  Example Output

```text
Goa is best visited between November and February.

Reasoning Path:
Goa → Weather → Winter Season → Best Travel Time
```

---

#  System Workflow

1. User submits travel query
2. NLP module identifies intent
3. Semantic network performs reasoning
4. Knowledge base retrieves related information
5. Chatbot generates conversational response
6. Reasoning path is displayed to user

---

#  Future Enhancements

- Voice-enabled chatbot
- Multilingual language support
- Interactive travel maps
- Hotel and restaurant recommendations
- Real-time weather integration
- Mobile application support
- Personalized travel suggestions

---

#  Author

Dipali Patil  
Second Year – Artificial Intelligence & Data Science  
Dr. D. Y. Patil College of Engineering, Akurdi

---

#  License

This project is developed for educational and research purposes under the MIT License.

---

#  Conclusion

The Smart India Travel Guide successfully demonstrates the implementation of Artificial Intelligence techniques such as Semantic Networks, Rule-Based NLP, and Explainable AI in an intelligent travel recommendation system. The project showcases how symbolic reasoning and knowledge representation can be used to build lightweight, explainable, and interactive conversational AI applications without relying on external Large Language Models.
