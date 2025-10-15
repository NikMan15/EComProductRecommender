# 🛍️ E-commerce Product Recommender

An **AI-powered recommender system** that combines classical recommendation algorithms with **LLM-based natural-language explanations** to tell users *why* a product is recommended to them.

---

## 🎯 Objective
To build a hybrid product recommender that:
- Analyzes user behavior and product attributes  
- Suggests the most relevant products  
- Generates short, human-friendly explanations using an LLM  

---

## 🧩 Features
- **Personalized Recommendations** (Hybrid, Collaborative, Content-based, Popularity)
- **AI-Generated Explanations** (“Why this product?”)
- **Interactive Dashboard** with charts and analytics
- **REST API** for integration and testing
- **Modular Design** — separate frontend and backend

---

## 🗂️ Project Structure
```bash
📦 ecommerce-recommender
├── frontend/
│   ├── index.html
│   ├── style.css
│   ├── app.js
│   ├── api.js
│   └── components.js
├── backend/
│   ├── server.js
│   ├── data.js
│   ├── models/
│   │   ├── productModel.js
│   │   ├── userModel.js
│   │   └── interactionModel.js
│   ├── recommender.js
│   └── explanationService.js
├── README.md
└── package.json
```
---

## ⚙️ Tech Stack
| Layer | Technology |
|--------|-------------|
| Frontend | HTML5, CSS3, JavaScript, Chart.js |
| Backend | Node.js, Express.js |
| Database | MongoDB (can use mock data for demo) |
| AI / LLM | OpenAI API (or any other LLM provider) |

---

