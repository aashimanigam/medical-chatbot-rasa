# medical-chatbot-rasa
# 🩺 AI Medical Health Assistant (Rasa Chatbot)

An intelligent, task-oriented chatbot built using the **Rasa Framework** to assist users with basic medical symptom checks (specifically fever) and provide initial healthcare guidance.

## 🚀 Features
- **Symptom Recognition:** Accurately identifies fever-related intents.
- **Smart Fallback:** Uses `NLU Fallback` with a 0.7 confidence threshold to avoid giving incorrect medical advice for unknown queries.
- **Contextual Conversation:** Handles multi-turn dialogues using Rasa Stories and Rules.
- **Out-of-Scope Handling:** Gracefully manages off-topic questions.

## 🛠️ Tech Stack
- **Framework:** Rasa Open Source
- **Language:** Python 3.10
- **NLU:** DIETClassifier, ResponseSelector
- **Configuration:** YAML

## 📁 Project Structure
- `data/nlu.yml`: Training data for intent classification.
- `data/stories.yml`: Dialogue paths for the bot.
- `data/rules.yml`: Specific logic for greetings, goodbyes, and fallbacks.
- `domain.yml`: Bot's universe including intents, responses, and actions.
- `config.yml`: Pipeline and policy configurations.

## ⚙️ How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/medical-chatbot-rasa.git](https://github.com/YOUR_USERNAME/medical-chatbot-rasa.git)
