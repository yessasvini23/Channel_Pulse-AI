# 📊 ChannelPulse AI – Dynamic Multi-Channel Insights App

**ChannelPulse AI** is a Flutter-powered, AI-driven application that dynamically adapts onboarding flows and business dashboards based on a user’s source channel. Leveraging **Gemini-style intent prediction**, it personalizes everything — from UI layout and CTAs to AI-generated storytelling insights.

> _“Feels like the app was made just for them.” – Your users, after using ChannelPulse AI_

---

## 🚀 Demo & App Access

🎥 **[Watch the Demo Video](https://youtu.be/HD-4uaFh_v8)**  
📲 **[Try the App](https://pulse-ai-stories.lovable.app/)**

---

## 🧠 Inspiration & UX Philosophy

Inspired by **Gemini AI** and **FlutterFlow UX best practices**, ChannelPulse AI reimagines user onboarding and insights delivery for growth-oriented teams and digital products.

---

## 📌 Features

| Category              | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| 🔍 **Source Detection**   | Detects user source via UTM, Firebase Dynamic Links, or deep linking        |
| 🎯 **Intent Prediction**  | Uses Gemini-style prediction to determine user persona (e.g., buyer, explorer) |
| 🧩 **Adaptive UI**        | Tailors onboarding and CTA copy based on predicted intent                   |
| 📈 **AI Narrative Dashboard** | Real-time, AI-generated insights with storytelling visuals and charts    |
| 🔊 **Voice Script (Optional)** | Gemini-generated voice narration for accessible insights (TTS)         |
| 📤 **Executive Report Export** | One-click PDF summary of key insights for stakeholders              |

---

## 🛠 Tech Stack

- **Frontend**: Flutter (Dart)
- **Backend**: Gemini API (mocked or real), Firebase (optional)
- **State Management**: Flutter `Navigator`, `FutureBuilder`, conditional rendering
- **Charts**: `syncfusion_flutter_charts` or `fl_chart` (recommended)

---

## 📂 Project Structure

lib/
├── main.dart # App entry point
├── pages/
│ ├── landing_page.dart # Detect & select traffic source
│ ├── dynamic_onboarding_page.dart # Adaptive onboarding flow
│ └── ai_insights_dashboard.dart # Narrative insight dashboard
├── services/
│ └── gemini_service.dart # Intent prediction integration
├── models/
│ └── insight.dart # Data model for AI insights
assets/
└── banners/ # Custom illustrations per user intent


---

## ⚙️ Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/channelpulse-flutter.git
   cd channelpulse-flutter

2. **Install Dependencies**
   flutter pub get

3. **Run the App**
   flutter run

Optional: Connect Firebase Dynamic Links or pass UTM parameters for realistic simulation.


🤖 Gemini API (Mock or Real)
You can simulate Gemini-style responses by editing gemini_service.dart, or integrate with a real Gemini-compatible backend (Flask/FastAPI).

Sample Response Format

{
  "intent": "highly motivated buyer",
  "heroTitle": "Start your fitness journey today!",
  "ctaButton": "Join the Movement",
  "tone": "Casual, energetic"
}


✨ Example Use Cases
 | Channel Source | Predicted Intent             | UI Behavior                                      |
| -------------- | ---------------------------- | ------------------------------------------------ |
| Instagram      | High visual engagement       | Minimal text, colorful UI, vibrant CTA           |
| LinkedIn       | Professional research intent | Informative layout, trust-building tone          |
| Referral       | Ready to signup              | Direct signup, strong CTA like “Get Started Now” |


📊 AI-Powered Dashboard
Smart Cards: Summarized KPIs with contextual highlights

Interactive Charts: Visualize data trends with fl_chart / syncfusion_flutter_charts

Narrated Insights: Voice-over summaries (TTS enabled)

Export Summary: Generate PDF/CSV insight reports with one click


📄 License
This project is licensed under the MIT License.


👩‍💻 Author
Sudarshanam Yessasvini
📧 yessasvini.s@gmail.com
🌐 Portfolio
🔗 LinkedIn


💡 Contributing
PRs and suggestions are welcome! If you find a bug or want to add new Gemini-powered features, feel free to open an issue or fork the repo.


⭐️ Show Your Support
If you like this project, give it a ⭐️ and share it with your AI/Flutter community!



