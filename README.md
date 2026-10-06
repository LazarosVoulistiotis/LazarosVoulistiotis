# Hi, I'm Lazaros 👋

**MSc Artificial Intelligence student** at Metropolitan College / University of East London (2026–2027), with a **BSc (Hons) Computer Science** completed in 2026. Focused on **applied machine learning** and **backend engineering**.

I like building things end to end: training and evaluating a model properly, explaining its decisions, and serving it behind a tested, documented API.

📍 Athens, Greece &nbsp;·&nbsp; 💼 Open to junior roles in **ML / AI Engineering**, **Data**, and **Backend Software Engineering** (on-site, hybrid or remote)

---

## 🔭 Right now

- Studying for an MSc in AI: computer vision, machine learning on big data, intelligent systems
- Looking for my first role in tech, where I can work on real ML or backend systems

---

## ⭐ Featured: [Credit Card Fraud Detection with Explainable ML](https://github.com/LazarosVoulistiotis/cc-fraud-detection)

My BSc thesis: a fraud detection system for **extreme class imbalance** (284,807 transactions, only 0.17% fraud), taken from EDA to a deployed API.

| Locked test set (56,746 transactions) | |
|---|---|
| PR-AUC | **0.817** |
| ROC-AUC | **0.970** |
| Precision / Recall | **0.83 / 0.81** |
| False alarms | **16** out of 56,651 legitimate transactions |

- Compared Logistic Regression, Decision Tree, Random Forest and **XGBoost**
- Picked the **decision threshold** on validation data as a risk policy (≥ 80% precision), instead of the default 0.5; the test set was never used for tuning
- **SHAP** for global and per-prediction explanations, **LIME** for case-level review
- **FastAPI** service with schema validation and structured logging, containerised with **Docker** and deployed to **Google Cloud Run**
- 22 automated tests with **pytest**, run on every push through **GitHub Actions**

`Python` `XGBoost` `scikit-learn` `SHAP` `LIME` `FastAPI` `Docker` `Cloud Run` `GitHub Actions`

---

## 🗂️ Other projects

**Machine learning & security**

| Project | What it is | Stack |
|---|---|---|
| [Heart Disease ANN](https://github.com/LazarosVoulistiotis/heart-disease-ann) | Feed-forward neural network predicting heart disease severity (multiclass), with preprocessing, tuning and evaluation | Python, Neurolab, NumPy, scikit-learn |
| [MITM Tools Evaluation](https://github.com/LazarosVoulistiotis/CN6003_MITM_Bettercap_vs_Ettercap) | Isolated lab comparing Bettercap and Ettercap on measurable criteria, backed by packet captures | Kali Linux, Bettercap, Ettercap, Wireshark |

**Mobile & backend**

| Project | What it is | Stack |
|---|---|---|
| [SmartLedger](https://github.com/LazarosVoulistiotis/SmartLedger) | Android FinTech app for expense tracking and group bill splitting, with offline storage and biometric login | Kotlin, Jetpack Compose, Firebase, Room, Retrofit |
| [Theatre Reservation App](https://github.com/LazarosVoulistiotis/theatre-reservation-app) | Three-tier mobile system with JWT auth, seat availability and double-booking prevention | React Native, Expo, Node.js, Express, MariaDB |
| [Restaurant Reservation App](https://github.com/LazarosVoulistiotis/restaurant-reservation-app) | Mobile reservation system with secure auth and a relational backend | React Native, Node.js, Express, MariaDB |
| [Cinema Booking](https://github.com/LazarosVoulistiotis/cinema-booking-php-app) | Responsive web app for cinema reservations | PHP, MySQL |
| [Travel Booking System](https://github.com/LazarosVoulistiotis/TravelBookingSystem-JavaFX) | Desktop app for managing customers, itineraries and bookings | Java, JavaFX, JAXB |

---

## 🧰 Tech stack

**ML & Data:** Python, scikit-learn, XGBoost, SHAP, LIME, NumPy, pandas, Jupyter  
**Backend:** FastAPI, Node.js, Express, REST APIs, JWT, bcrypt  
**Databases:** MariaDB, MySQL, Oracle, SQL (modelling, indexing, normalisation)  
**Mobile:** Kotlin, Jetpack Compose, Room, Firebase, React Native, Expo  
**Tools:** Git, GitHub Actions, pytest, Docker, Google Cloud Run, Postman, Android Studio, VS Code

---

## 🧭 How I work

- **Evaluate honestly:** metrics that fit the problem (precision/recall, PR-AUC, cost-based thresholds), not just accuracy
- **Keep it explainable:** a model's decision should be something you can show and defend
- **Structure the code:** layered architecture, validation, clear error handling, real database constraints
- **Document everything:** every repo has setup steps, test evidence and screenshots

---

## 📫 Contact

[LinkedIn](https://www.linkedin.com/in/lazaros-voulistiotis/) &nbsp;·&nbsp; [GitHub](https://github.com/LazarosVoulistiotis)
