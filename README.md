## Pet Seasonal Allergy Predictor & Care Chatbot

Making pet care smarter, faster, and stress-free for allergy-prone dogs

---
## 🚀 Overview

Seasonal allergies in pets, especially dogs, are a *silent struggle* for many owners. Symptoms like itching, sneezing, and lethargy are often dismissed as minor issues until they escalate into costly vet emergencies.

This project is a *Gen Z–friendly AI-powered Pet Seasonal Allergy Predictor & Behaviour Chatbot* designed to:

1. Predict *seasonal allergy risk* based on your dog's breed, coat type, season, and symptoms.
2. Provide *personalized care suggestions* instantly.
3. Advise when it’s time to *visit the vet*.
All of this happens inside a *beautiful, modern Gradio interface* with a calming theme that enhances user experience.
---

## 💡 Key Features

### *1️⃣ Interactive Allergy Risk Form*

* Select *current season* (e.g., Summer, Monsoon, Winter, Spring).
* Choose *dog’s coat type* (Short coat, Long coat, Allergy-prone).
* Pick your *dog’s breed* from popular and allergy-prone options.
* Tick *observed symptoms* (e.g., Itching, Sneezing, Red eyes, Lethargy, Loss of appetite).
* *One-click analysis* → Instantly predicts *Low, **Medium, or **High* allergy risk.

### *2️⃣ AI-Driven Chatbot for Pet Behaviour*

* Describe your pet’s behaviour in everyday language.
* AI interprets symptoms and *gives actionable care tips*.
* If risk is *high, the bot **strongly advises a vet visit*.
* Risk-based recommendations:

  * ✅ Low → Regular care advice
  * 🔍 Medium → Close monitoring + optional vet check
  * ⚠️ High → Urgent vet recommendation

### *3️⃣ Smart Allergy Risk Prediction*

The algorithm uses a *weighted scoring model* considering:

* 🌸 *Seasonal allergen levels* (spring & summer scored higher)
* 🐕 *Coat type* (long coat and allergy-prone get extra weight)
* 🏷 *Breed susceptibility* (e.g., German Shepherds & Pugs are more allergy-prone)
* 📋 *Number of symptoms*

### *4️⃣ Gen Z–Optimized UI*

* Clean, minimal *multi-tab layout*.
* Aesthetically appealing theme with *soft gradients* and *modern typography*.
* Simple navigation between *Risk Form* and *Chatbot*.
* Mobile-friendly design for pet owners on the go.

---

## 🛠️ Tech Stack

| Component            | Technology                            |
| -------------------- | ------------------------------------- |
| *Frontend UI*      | [Gradio](https://gradio.app/)         |
| *Backend Logic*    | Python 3                              |
| *Hosting*          | Google Colab (with Gradio share link) |
| *Data Inputs*      | User form responses                   |
| *Prediction Logic* | Custom scoring model                  |
| *Chatbot*          | Rule-based + form data integration    |

---

## 📊 How It Works

1. *User completes the form* with dog’s season, coat, breed, and symptoms.
2. *Risk Analysis Engine* scores each factor and calculates the allergy risk.
3. *Behaviour Chatbot* tailors its response based on the predicted risk level.
4. The chatbot *summarizes the form data* with every conversation, so owners always know the context.

Future Enhancements

* 🌍 Integrate *real-time pollen & weather data* via API for even more accurate predictions.
* 📱 Create a *mobile app* version for push notifications on high allergen days.
* 🧠 Upgrade to *LLM-powered chatbot* for deeper pet health conversations.
* 📊 Allow *symptom history tracking* for long-term allergy pattern analysis.
