#  ChannelPulse AI – Dynamic Multi-Channel Insights App

**ChannelPulse AI** is an AI-powered Flutter application that dynamically adapts onboarding flows and business dashboards based on a user’s source channel. It uses Gemini-style intent prediction to personalize the experience — from UI layout and call-to-action copy to AI-generated performance insights.

> 🧠 Inspired by Gemini AI + FlutterFlow UX Principles  
> 📱 Built with Flutter · AI-Powered · Data-Driven · Production-Ready

---

## 📌 Features

| Category               | Description                                                                 |
|------------------------|-----------------------------------------------------------------------------|
| 🔍 Source Detection     | Detects user source via UTM, Firebase Dynamic Links, or deep linking       |
| 🎯 Intent Prediction    | Integrates with Gemini API to predict user type (e.g., buyer, researcher)  |
| 🧩 Adaptive UI          | Dynamic onboarding flow tailored to intent and channel                     |
| 📈 AI Narrative Dashboard | Real-time, AI-generated business insights with storytelling visuals        |
| 🔊 Voice Script (Optional) | Gemini-powered voice narration of insights                              |
| 📤 Report Export        | One-click generation of executive summary reports                          |

---

## 🛠 Tech Stack

- **Frontend**: Flutter
- **Backend**: Gemini API (simulated via REST), Firebase (optional)
- **State & Routing**: Flutter Navigator, `FutureBuilder`, conditional rendering
- **Charts**: `syncfusion_flutter_charts` / `fl_chart` (recommended)

---

## 📂 Project Structure
lib/
├── main.dart # App entry point
├── pages/
│ ├── landing_page.dart # Detect & select traffic source
│ ├── dynamic_onboarding_page.dart # Adaptive onboarding based on intent
│ └── ai_insights_dashboard.dart # AI-powered narrative insights
├── services/
│ └── gemini_service.dart # API integration (mock or real Gemini)
├── models/
│ └── insight.dart # Insight model structure
assets/
└── banners/ # Custom images per source intent


---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/channelpulse-flutter.git
cd channelpulse-flutter

2. Install Dependencies
flutter pub get

3. Run the App
flutter run

Optional: Connect Firebase Dynamic Links or pass UTM params during launch for real simulation.

### Gemini API (Mock or Real)
For demo purposes, Gemini intent prediction can be mocked locally using gemini_service.dart.

You can also create a simple Flask/FastAPI backend to call the Gemini API and return:

{
  "intent": "highly motivated buyer",
  "heroTitle": "Start your fitness journey today!",
  "ctaButton": "Join the Movement",
  "tone": "Casual, energetic"
}

✨ Demo Use Cases
| Channel Source | Predicted Intent             | UI Behavior                                         |
| -------------- | ---------------------------- | --------------------------------------------------- |
| Instagram      | High visual engagement       | Minimal text, colorful onboarding, energetic CTA    |
| LinkedIn       | Professional research intent | Informative journey, trust-building layout          |
| Referral       | Ready to signup              | Direct signup screen, strong CTA: "Get Started Now" |

## AI Magic Behind the Scenes
Gemini API analyzes source metadata + device context to predict user intent.

Flutter app conditionally renders screens, widgets, and tone based on the returned intent.

AI-generated dashboards present insights using cards, charts, and narration.

📄 License
This project is licensed under the MIT License.

👩‍💻 Author
Sudarshanam Yessasvini
🔗 LinkedIn
🌐 Portfolio
📧 yessasvini.s@gmail.com

“Feels like the app was made just for them.” – Your users, after using ChannelPulse AI.

---


