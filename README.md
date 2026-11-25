```markdown
# 🌱 EcoQuest: Your Daily Quest for a Greener Planet

**EcoQuest** is a gamified sustainable living and waste reduction tracker that turns everyday eco-friendly habits into an engaging, rewarding journey. By combining real-time impact tracking, AI-powered waste sorting, social accountability, and real-life plant nurturing, EcoQuest helps individuals build lasting green habits.

---

## 🚀 The Problem
Individuals often feel disconnected from their environmental impact, making it difficult to stay motivated with sustainable practices. Information on proper recycling and waste reduction is fragmented, and existing trackers rarely offer personalized guidance, community support, or tangible rewards.

## 💡 The Solution
EcoQuest bridges the gap between daily habits and planetary impact through four core pillars:
* **Gamified Action & Waste Logging:** Earn **EcoPoints**, maintain daily streaks, unlock badges, and level up from *Seedling* to *Forest Guardian* by logging sustainable actions.
* **AI "What Goes Where?" Waste Scanner:** Scan or search everyday items (e.g., e-waste, greasy pizza boxes, cooking oil) for instant, location-aware recycling and disposal instructions.
* **My Plants Tracker:** Nurture real-life houseplants and herbs with hydration meters, care schedules, and growth tracking that tie virtual rewards to physical greenery.
* **Community Eco-Feed & Leaderboards:** Share milestones, cheer on friends, complete daily quests, and compete on neighborhood leaderboards.

---

## 🛠️ Architecture & Tech Stack
* **Frontend:** Interactive HTML5, CSS3, and Vanilla JavaScript (prototype) / React Native & Flutter (mobile target)
* **Backend & Hosting:** Google Cloud Run (containerized microservices behind a Global Load Balancer)
* **Database & Security:** Cloud SQL for PostgreSQL (relational logs & vector embeddings) + Secret Manager
* **AI Engine:** Vertex AI Agent Engine (smart waste categorization & personalized eco-recommendations)

---

## 💻 Running the Demo Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR-USERNAME/ecoquest.git](https://github.com/YOUR-USERNAME/ecoquest.git)
   cd ecoquest

```

2. **Launch the app:**
Open `index.html` directly in your browser, or run a local server:
```bash
python3 -m http.server 8080

```


Then visit `https://sites.google.com/view/ecoquest-web-prototype/full-page-embed` in your browser.

---

## 🔮 Future Roadmap

* [ ] Live camera computer-vision integration for real-time barcode & material recognition
* [ ] Google Maps API integration for nearby hazardous waste & recycling drop-off points
* [ ] AI leaf-health diagnostics for indoor and garden plants
* [ ] Local eco-friendly marketplace and community swap boards

