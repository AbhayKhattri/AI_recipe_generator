 AI-Powered Recipe Generator
🔹 An intelligent chatbot that generates personalized recipes based on user input using Rasa, spaCy, and Python.

📖 About the Project
This project is an AI-powered recipe generator that suggests dishes based on user queries. It uses Rasa for chatbot interaction, spaCy for Named Entity Recognition (NER), and fuzzy matching to find the best dish recommendations. Users can also specify dietary preferences (e.g., vegan, gluten-free) to receive tailored recipes.

 Key Features
✅ Intelligent Recipe Search – Finds dishes using exact & fuzzy matching
✅ Rasa Chatbot Integration – User-friendly conversational experience
✅ Dietary Preference Support – Vegan, gluten-free, low-carb options
✅ Step-by-Step Instructions – Clear ingredient lists and preparation steps
✅ Natural Language Processing (NLP) – spaCy NER for better dish name recognition

 Technologies Used
Python – Core development

Rasa – Conversational AI chatbot

spaCy – Named Entity Recognition (NER)

Pandas – Handling recipe datasets

FuzzyWuzzy – Approximate string matching

 Dataset & Functionality
The chatbot uses a CSV dataset of 500+ recipes, including dish names, ingredients, and cooking steps. When a user requests a recipe, the system:
1️⃣ Checks for an exact match in the dataset
2️⃣ If no match, suggests similar dishes using fuzzy matching
3️⃣ Filters results based on user preferences (e.g., "Show me a vegan pasta recipe")
4️⃣ Returns a detailed recipe with ingredients and steps
