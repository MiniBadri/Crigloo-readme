# 📱 Crigloo Mobile Dashboard App

> **Built using React Native** | End-to-end mobile analytics app for digital marketers  
> 🧠 **Solo Developer** | 🛠️ Production-Ready | 🔒 Auth + 🔌 API + 📊 Charts

---

## 🔍 Overview
Crigloo Mobile is a React Native app that allows digital marketing managers to monitor real-time ad performance across platforms (Google, Facebook, Instagram, LinkedIn, YouTube). It connects to the company’s AWS backend and visualizes KPIs, funnel metrics, and social engagement through a mobile-friendly dashboard.

---

## 🧭 Features
- 📊 **Marketing Summary** (Impressions, CTR, CPC, ROAS)
- 🔁 **Funnel Analysis** (New/Repeat Users, Bounce Rate, Conversions)
- 📣 **Social Media Performance** (Likes, Comments, Views, Subscribers)
- 📅 Time filter: 1 week, 2 weeks, 1 month, 3 months
- 📱 Optimized for mobile data scanning with a scrollable carousel UI

---

## 🏗️ Architecture
- **Component-based React Native App** using Hooks
- **Carousel-based dashboard** using `react-native-snap-carousel`
- **Navigation** via React Navigation
- **Charts** via `react-native-gifted-charts` and `chart-kit`
- **Global state** managed with Context API

---

## 🔐 Authentication
- Handled via **Amazon Cognito (AWS Amplify)**
- Token refresh check via `/check_access_token` API
- Local session stored in **AsyncStorage**

---

## 🔌 API Integration
- API calls made using **Axios**
- Auth: `Bearer <JWT>` + `x-api-key` in headers
- Environment-based config (`.env.*`) managed via `react-native-config`

---

## 🧩 Tech Stack

| Category            | Tools/Libraries                                        |
|---------------------|--------------------------------------------------------|
| UI Components       | NativeBase, React Native Paper                         |
| Charts              | react-native-gifted-charts, chart-kit                 |
| Forms & Validation  | react-hook-form, Yup                                   |
| Navigation          | react-navigation                                       |
| Auth & Tokens       | Amazon Cognito, aws-amplify, jwt-decode                |
| API Requests        | Axios                                                  |
| Animations          | Lottie                                                 |
| Alerts              | react-native-alert-notification                        |
| Local Storage       | AsyncStorage                                           |
| Analytics           | Firebase                                               |

---

## 📷 Screenshots

*(Add screenshots here: drag images into the repo or link to hosted images)*
```md
![Dashboard Carousel](./screenshots/dashboard.png)
![Marketing Performance](./screenshots/marketing.png)
![Funnel Insights](./screenshots/funnel.png)
```

---

## 🚀 Getting Started *(Optional)*
```bash
# Clone repo (if public later)
git clone https://github.com/yourusername/crigloo-mobile
cd crigloo-mobile

# Install dependencies
npm install

# Start development server
npm run android:dev
# or
npm run ios
```

> You can provide `.env` file templates and API keys guidance if open sourcing this project in the future.

---

## 📄 License *(Optional)*
Add an open-source license if making the repo public, like MIT or Apache 2.0.

---

## ❓ FAQ *(Optional)*
- **Can I make the README public without making the repo public?**
  - GitHub doesn't support a fully "public README in a private repo." However, you *can* create a **separate public repo** named something like `crigloo-readme` and put just this `README.md` and screenshots there.
  - That way, you can share it with others while keeping your actual code private.

Let me know if you'd like help creating that secondary public repo.
ok

