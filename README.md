# Hi, I'm Parvej Sikdar 👋

**Frontend Engineer** with 4+ years building production web applications with **React, Next.js and TypeScript**, and cross platform mobile apps with **React Native** and **Expo**. Most recently at MuseCool, an EdTech platform in the UK and USA serving 19,000+ students and 4,400+ tutors, where I owned frontend architecture as the sole engineer.

- 🌐 **Next.js** with the App Router, Server Components, SSR and ISR, with a focus on Core Web Vitals, page speed and SEO
- 📱 **React Native** and **Expo** on iOS and Android, including store releases and OTA updates
- 💳 **Stripe** integrations that enabled 27,000+ transactions: 3D Secure checkout, Connect onboarding, payouts and recurring billing
- 🔐 NextAuth, Google OAuth, Apple Sign In, JWT, and native to web WebView bridges
- 📍 Dhaka, Bangladesh. Experienced working with UK and US teams, open to remote Frontend and React Native roles

**Reach me:**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/parvej-sikdar/)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=googlechrome&logoColor=white)](https://parvej.is-a.dev/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:parvejsikdar.42@gmail.com)

---

## 🛠 Tech Stack

**Core:** TypeScript · React · Next.js · React Native · Expo · Stripe · Tailwind CSS

<details>
<summary>Full stack</summary>

<br>

**Web:** TypeScript · JavaScript (ES6+) · React · Next.js (App Router, Server Components, SSR, ISR, Middleware, Route Handlers, Turbopack) · Tailwind CSS · CSS Modules · Styled Components · shadcn/ui · Radix UI · Framer Motion · HTML · CSS · Core Web Vitals

**Mobile:** React Native · Expo (Expo Router, EAS Build, EAS Update, OTA) · WebView with two way JavaScript bridge

**State & Forms:** Redux Toolkit · Zustand · Context API · SWR · TanStack Query · React Hook Form · Formik · Yup

**Payments:** Stripe (Checkout, PaymentSheet, Connect, Subscriptions, PaymentIntents, 3D Secure, Webhooks) · iOS and Android in-app purchases

**Auth & APIs:** NextAuth · Google OAuth · Apple Sign In · JWT · REST APIs · Google Maps (Places Autocomplete, Geocoding) · Google Calendar API

**Data:** Firebase (Firestore, Auth, Storage)

**Analytics & Monitoring:** Google Tag Manager · GA4 · Meta Pixel · TikTok Pixel · Microsoft Clarity

**Tooling & Practices:** Git · GitHub · Jira · Jest · React Testing Library · CI/CD · Vercel · Figma · Agile · Scrum · Code reviews

</details>

---

## 🚀 Shipped to Production

Closed source work for MuseCool, an EdTech platform operating in the UK and USA.

### Web

**[Student Lesson & Payments Platform](https://app.musecool.com/)** · Next.js · account required
The primary client app for students and parents, replacing a manual, password heavy booking journey with a self service flow covering tutor discovery, scheduling, Stripe subscriptions and progress tracking. Serves 14,000+ students, has supported 96,000+ lessons, and gets a user from search to checkout in under 45 seconds. Passwordless magic link onboarding on a custom NextAuth credentials provider carries new clients from a private email link through tutor recommendation, scheduling and Stripe checkout with 3D Secure.

**[Lycaeum Admin](https://admin.lycaeum.co.uk/)** · Next.js · staff access only
Internal operations and payments console with 30+ modules, used daily by about 25 operations and finance staff. It consolidates Stripe payments, tutor matching, lesson and payout oversight, commission configuration and tutor onboarding (2,019 tutors onboarded), and reduced manual admin work by ~48.75% and refund processing time by ~35%. Includes a Google Maps tutor discovery tool with Places Autocomplete and Geocoding for UK and US postcode search, plus embedding based tutor recommendations.

**[Tutor Onboarding Platform](https://tutor.musecool.com/)** · Next.js
Dual path tutor signup with Google OAuth, Google Calendar sync through CSRF protected server side token exchange, per day availability scheduling, and QR code onboarding.

**[Smart Practice & Progress Tracker](https://musecool.com/the-muse)** · Next.js
Product site for an AI lesson companion. Interactive 3D device prototype, a playable piano synthesised in real time from oscillators and filters, and device aware download flows with conversion tracking.

**[Partner Storefront](https://shop.musecool.com/)** · Next.js · account required
Commerce surface for partner ordering and fulfilment.

### Mobile

**Student App** · React Native and Expo
Hybrid native shell that embeds learning content through WebView, with a two way JavaScript bridge and shared authentication. Stripe PaymentSheet checkout, two subscription tiers through iOS and Android in-app purchases with backend receipt verification, and OTA delivery through EAS Update. 40K+ monthly active users, 99.7% crash free sessions and 800+ paid subscribers.

[![Google Play](https://img.shields.io/badge/Google_Play-01875F?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.lycaeummusic.musecool)
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white)](https://apps.apple.com/gb/app/musecool/id6476098253)

**Tutor App** · React Native and Expo
Stripe Connect onboarding with live verification tracking, a native WebView bridge with two way JavaScript messaging, and a resumable chunked audio upload queue with retry, backoff, and crash recovery.

[![Google Play](https://img.shields.io/badge/Google_Play-01875F?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.lycaeummusic.musecooltutor)
[![App Store](https://img.shields.io/badge/App_Store-0D96F6?style=flat-square&logo=appstore&logoColor=white)](https://apps.apple.com/gb/app/the-muse-tutor/id6473702165)

---

## 📦 Personal Projects

**[SikdarMart](https://agriyo.netlify.app/)** · Next.js
Agriculture ecommerce storefront modelled on how farm supplies sell in Bangladesh, with unit weight pricing, local crop variety search, and VAT and delivery rules. Hybrid rendering on the App Router keeps the catalogue server rendered and isolates client interactivity to cart, wishlist, and checkout.

**[Sikdar Learning Academy](https://sikdar-learning-academy.vercel.app/)** · Next.js
Bengali localised EdTech platform with a reusable widget based UI system on Tailwind CSS and shadcn/ui, and a type safe domain layer for courses, quizzes, and dashboards.

**[AgroManager](https://apkpure.com/p/com.parvejsikdar.AgroManager)** · React Native
Bilingual farm management app for dairy farmers. Offline first Firestore layer mirrored to AsyncStorage, a feedlot profitability engine and multi sheet Excel export.
