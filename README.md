# 📰 NewsNova

> *Stay Updated. Stay Smart. Powered by Flutter, NewsAPI & Firebase.*

NewsNova is a *real-time news dashboard app* built with *Flutter*.  
It fetches the latest headlines from *NewsAPI.org, lets users **save favorite articles, toggle between **dark and light modes, and even **share news instantly* across platforms.  
All favorites are *synced via Firebase* for a seamless experience.

---

## 🚀 Features

✅ *Live News Feed* — Get the latest updates from Tech, Sports, Business, Health & more.  
✅ *Category Filter* — Browse by your favorite topics.  
✅ *Search Functionality* — Instantly find articles across multiple sources.  
✅ *Dark/Light Mode* — Smooth theme toggle for modern UI.  
✅ *Save Favorites* — Store news offline (Hive) & online (Firebase Firestore).  
✅ *Share Articles* — Instantly share links via WhatsApp, Telegram, etc.  
✅ *Pull to Refresh* — Real-time feed updates.  
✅ *Cloud Sync* — Access favorites across devices using Firebase.  

---

## 🧱 Tech Stack

| Layer | Technology |
|-------|-------------|
| *Frontend* | Flutter (Dart) |
| *Backend API* | [NewsAPI.org](https://newsapi.org) |
| *State Management* | Riverpod |
| *Local Storage* | Hive |
| *Cloud Database* | Firebase Firestore |
| *Authentication* | Firebase Auth (optional) |
| *Article Sharing* | share_plus package |

---

## 📂 Folder Structure

lib/ │ ├── main.dart ├── core/ │   ├── constants.dart │   ├── utils.dart │   └── app_routes.dart │ ├── models/ │   └── news_article.dart │ ├── services/ │   ├── news_api_service.dart │   ├── firebase_service.dart │ ├── providers/ │   ├── news_provider.dart │   └── favorites_provider.dart │ ├── screens/ │   ├── home_screen.dart │   ├── details_screen.dart │   └── favorites_screen.dart │ ├── widgets/ │   ├── news_card.dart │   ├── category_selector.dart │   └── error_view.dart │ └── theme/ └── app_theme.dart

---

## ⚙ Setup & Installation

1️⃣ *Clone the repository*
```bash
git clone https://github.com/<your-username>/newsnova.git
cd newsnova

2️⃣ Get dependencies

flutter pub get

3️⃣ Add your NewsAPI key

Get a free API key from https://newsapi.org

Add it inside lib/services/news_api_service.dart:

final String apiKey = "YOUR_API_KEY";


4️⃣ Add Firebase

Create a Firebase project named newsnova-app

Add Android app → download google-services.json → put it in android/app/

Initialize Firebase in main.dart

Run:

flutterfire configure


5️⃣ Run the app

flutter run


---

🖼 Screenshots

Home	Details	Favorites	Dark Mode

			



---

🔥 Future Enhancements

🔔 Push Notifications (new article alerts)

🌍 Multi-language support

🧠 AI-powered news summarization

📊 Analytics dashboard for most read topics



---

💡 Project Tagline

> “NewsNova — Stay Updated, Stay Smart.”




---

👨‍💻 Developer

Developed  by: Tejas Rastogi
GitHub: tejasrastogileet



---

🧠 License

This project is licensed under the MIT License — free to use and modify with attribution.
