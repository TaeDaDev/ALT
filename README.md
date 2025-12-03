# **ALT — AI-Powered Healthy Alternatives App**

ALT is a mobile-first application that helps people find **healthier alternatives** for the food they eat, the medicine they take, and the everyday products they use. Whether someone is avoiding harmful ingredients or simply wants cleaner options, ALT makes better choices feel effortless.

This project serves two purposes:

* **Provide real public value** by helping users make healthier decisions.
* **Act as a full-stack learning journey** across mobile, backend, AI, and system design.

---

#  **Why ALT Matters**

Modern products hide behind complicated labels. ALT cuts through the noise with:

* Plain‑language ingredient explanations
* AI‑generated health scoring
* Cleaner alternatives you can trust
* Natural or DIY replacements when possible

ALT empowers users to make small, daily swaps that add up to long-term health.

---

#  **Features**

### ✔️ **Scan Products Instantly**

Use your phone's camera to scan labels. ALT extracts text using OCR and identifies every ingredient.

### ✔️ **AI Ingredient Analysis**

Each ingredient gets:

* A safety score
* A clear explanation
* Risk flags (allergens, toxicity, harshness)
* Categorization (food, medicine, skincare, household)

### ✔️ **Healthy Alternatives**

ALT suggests:

* Cleaner commercial alternatives
* Natural remedies when relevant
* DIY mixes if appropriate

### ✔️ **Product Search**

Look up products without scanning.

### ✔️ **Offline Caching**

Recent scans load instantly.

### 🔜 **User Profiles & Saved Products**

Custom sensitivity lists and favorite items.

### 🔜 **Personalized Risk Alerts**

The app learns what you should avoid.

### 🔜 **Deep Ingredient Graph**

A relationship map between ingredients for powerful insights.

---

<!--# 🧱 **Architecture Overview**

```
                ┌───────────────────────────┐
                │       React Native        │
                │        (Expo App)         │
                └─────────────┬─────────────┘
                              │
                              ▼
                ┌───────────────────────────┐
                │         FastAPI           │
                │  (API + Orchestration)    │
                └─────────────┬─────────────┘
                              │
     ┌────────────────────────┼───────────────────────────┐
     ▼                        ▼                           ▼
┌──────────┐          ┌────────────────┐        ┌───────────────────┐
│  OCR     │          │ Ingredient AI  │        │  Supabase / DB    │
│ (Textract│          │  LLM Agents    │        │ Auth + Storage    │
└──────────┘          └────────────────┘        └───────────────────┘
                              │
                              ▼
                     ┌────────────────┐
                     │ Vector Search  │
                     │  (pgvector)    │
                     └────────────────┘
```

---

# 🧠 **Tech Stack**

### **Frontend**

* React Native (Expo)
* TypeScript
* Clean and modern mobile UI

### **Backend**

* FastAPI
* Python
* Docker
* Supabase (Postgres + Auth + Storage)
* pgvector (similarity search)

### **AI / ML**

* OCR (AWS Textract or Tesseract)
* LLM ingredient reasoning
* Embeddings for product similarity
* Custom scoring engine

---

# 🛠️ **Installation & Setup**

### **Clone the Repository**

```
git clone https://github.com/yourname/alt.git
cd alt
```

## **Frontend Setup**

```
cd alt-app
npm install
npx expo start
```

## **Backend Setup**

```
cd alt-backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## **Environment Variables**

Create a `.env` in both frontend and backend:

```
SUPABASE_URL=...
SUPABASE_KEY=...
OPENAI_KEY=...
OCR_PROVIDER=...
```

---

# 🧪 **Testing the API**

```
GET  /health
POST /scan
POST /analyze
GET  /alternatives
```

All endpoints return structured JSON.

---

# 🏆 **Project Goals**

* Master mobile development
* Build a real backend with authentication
* Implement AI agents
* Learn vector search and ranking
* Ship a scalable product end-to-end

ALT is your full-stack proving ground.

---

# 🧩 **Project Badges**

```
![React Native](https://img.shields.io/badge/React_Native-Expo-blue)
![FastAPI](https://img.shields.io/badge/FastAPI-Backend-green)
![Supabase](https://img.shields.io/badge/Supabase-Postgres-lightgrey)
![AI Powered](https://img.shields.io/badge/AI-Powered-orange)
![Open Source](https://img.shields.io/badge/Open_Source-Licensed-black)
```

---

# 🎨 **ALT Logo (Placeholder)**

```
    █████  ██      ████████
   ██   ██ ██         ██
   ███████ ██         ██    ALT
   ██   ██ ██         ██    Healthy Alternatives
   ██   ██ ███████    ██
```

*A real vector logo can replace this later.*

---

# 🤝 **Contributions**

Contributions, ideas, and data sources are welcome! Open a PR or create an issue.

---

# 📬 **Contact**

Have feedback or suggestions? Reach out or open an issue.

---

ALT is built to help people live healthier lives — and to sharpen full‑stack engineering skills along the way.
