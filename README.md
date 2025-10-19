# Movie-Recommender
# 🎬 MovieFlix Recommender

**MovieFlix Recommender** is an interactive movie recommendation dashboard built using **HTML**, **Tailwind CSS**, and **JavaScript**.  
It simulates how data mining techniques like **Association Rule Mining** and **User Clustering** can be used to recommend movies to users.

🔗 **Live Demo:** [https://movirecommend.netlify.app/](https://movirecommend.netlify.app/)

---

## 🚀 Features

### 🎥 Association Rule Mining
- Select a movie you’ve enjoyed, and get recommendations for other movies that are **frequently watched together**.
- Mimics **“If you liked this, you’ll love…”** style recommendations.

### 👥 User Clustering
- Choose a **user persona** (Sci-Fi Voyager, Drama Connoisseur, or Comedy Lover).
- See their **taste profile** and top movie picks based on **clustering similar users**.

### 💅 Modern UI
- Fully responsive layout with **Tailwind CSS**.
- Dark theme with smooth hover animations.
- Clean, elegant design inspired by data-driven dashboards.

---

## 🧠 Tech Stack

| Technology | Purpose |
|-------------|----------|
| **HTML5** | Structure of the web page |
| **Tailwind CSS** | Styling and responsiveness |
| **JavaScript (ES6)** | Interactive logic and data simulation |
| **Netlify** | Deployment platform |

---

## ⚙️ How It Works

- The dashboard uses **precomputed JavaScript objects** (`associationData` and `clusterData`) to simulate backend logic.
- When a movie or user persona is selected:
  - JavaScript dynamically renders recommendation cards.
  - The UI updates instantly without any page reloads.

---

## 🧩 Future Enhancements

- Integrate with **TMDb API** to fetch real movie data and posters.
- Connect to a **Flask / Node.js backend** for dynamic recommendations.
- Add charts to visualize user clusters and similarity scores.
- Include a **search bar** for finding any movie instantly.

---

## 💻 Local Setup

If you want to run it locally:

```bash
# Clone this repository
git clone https://github.com/<your-username>/MovieFlix-Recommender.git

# Open the project folder
cd MovieFlix-Recommender

# Run the app
# Simply open index.html in your browser
```


