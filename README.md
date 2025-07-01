# 🌐 Innovation Diffusion in Silicon Valley Startups

This project explores how social networks—specifically shared investor relationships—shape the **spatial diffusion of innovation** among tech startups in **Silicon Valley**. Using data from Crunchbase, we apply network analysis techniques to map the startup ecosystem, identify central actors, and simulate how innovation spreads like a virus across the network.

---

## 📌 Objectives

- Build a social network of Silicon Valley startups based on shared investors.
- Analyze network structure using centrality and community detection.
- Simulate diffusion of innovation from key players (e.g., Airbnb).
- Draw insights into how clustering and brokerage roles affect innovation flow.

---

## 🗃️ Dataset

- **Source**: [Crunchbase on Kaggle](https://www.kaggle.com/datasets/chhinna/crunchbase-data)
- **Filtered** for startups in Silicon Valley (e.g., San Francisco, Palo Alto, San Jose)
- Final graph: `1,376 nodes` and `3,478 edges`

---

## 🔍 Methods Used

- NetworkX (Python)
- Degree & Betweenness Centrality
- Modularity-based Community Detection
- Innovation Spread Simulation (Virus Model)

---

## 📊 Key Findings

- **Airbnb**, **AngelList**, and **Airware** are central diffusion hubs.
- Innovation often spreads **within clusters** (e.g., FinTech, HealthTech).
- High-betweenness startups act as **brokers**, bridging communities.
- The diffusion of innovation mimics **epidemic-style transmission** from hubs.

---

## 📁 Files

| File                        | Description                                       |
|----------------------------|---------------------------------------------------|
| `Project_Report.pdf`       | Full written report with figures and results      |
| `*.ipynb` (optional)       | Python notebooks for data processing & modeling   |

---

## 🛠️ Tools & Libraries

- Python 3
- pandas
- NetworkX
- matplotlib
- community (Louvain)

---

## 👥 Team
 
- Bhupender Bhupender (466758)  

Master’s in Data Science & Business Analytics  
University of Warsaw

---

## 📜 License

This project is for academic purposes and available under the MIT License.

