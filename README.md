# TripGenius  
Developing AI-powered personalized travel itineraries with budget optimization and preference matching  

🌄 **Smart Travel Planner**  
TripGenius is a full-stack application that generates optimized travel itineraries using RAG (Retrieval-Augmented Generation) technology. It suggests attractions based on user preferences, budget constraints, and duration, with detailed cost breakdowns and time allocations.

## 🚀 Features  
- **City Selection**: Choose from popular destinations (Ooty, Munnar, Coorg, Wayanad)  
- **Preference Matching**: Finds attractions based on interests (nature, historical, wildlife, etc.)  
- **Budget Optimization**: Automatically calculates costs including ₹200/day for lunch  
- **Time Management**: Plans daily activities within 8-hour windows  
- **Vector Search**: FAISS-powered similarity matching for relevant attractions  
- **AI Generation**: FLAN-T5 LLM for creating coherent itineraries  

## 🧩 Tech Stack  
**Frontend**:  
- Custom CSS for UI styling  

**Backend**:  
- LangChain (RAG pipeline)  
- FAISS (Vector similarity search)  
- HuggingFace Transformers (FLAN-T5 model)  
- Sentence-Transformers (all-MiniLM-L6-v2 embeddings)  

**Data Processing**:  
- JSON dataset with 40+ attractions  
- PyYAML for configuration  

## 📁 Project Structure  
trip-planner/
├── backend/
│ ├── rag_pipeline.py # RAG itinerary generator
│ ├── vector_db.py # FAISS vector operations
│ └── data/ # Attractions dataset
│ └── places.json
├── notebooks/
│ └── Trip_Planner.ipynb # Jupyter notebook version
