# Hi, I'm Nishal Dilanga Ranasinghe 👋

**Software Developer & Product Builder | Co-founder at [AwakenDev](https://awakendev.com)**

I build practical software products for real businesses and take them from requirements to production: backend, databases, web and Android apps, testing, deployment and day-to-day operations. At AwakenDev I'm the primary developer behind two live products and three more in development.

## 🚀 Live products

### 🧾 ADPOS — multi-tenant retail POS · [pos.awakendev.com](https://pos.awakendev.com)
A cloud point-of-sale and retail management platform for small and mid-sized shops, used in production by a real shop. I architected, built, tested and deployed it as the sole developer.

- Selling with barcode scanning (hardware scanner or phone camera), discounts, cash and credit payments
- Batch-level inventory with FIFO stock and cost allocation, quotations, suppliers and customer ledgers
- Tax, sales and inventory reporting, plus an English/Sinhala interface with Sinhala/Singlish product search
- Multi-tenant architecture: a master database plus a separate database per shop, with strict tenant isolation
- Security: MFA login, role-based permissions, subscription gating, rate limiting and audit logging
- **2,500+ automated tests** (PHPUnit, plus Playwright browser tests) and CI/CD with GitHub Actions to staging and production, a production drift check and automated backups

**Stack:** Laravel · PHP · MariaDB · Redis · JavaScript · Vite · Docker · nginx · Cloudflare · Linux VPS\
**Portfolio:** [awaken-pos-portfolio](https://github.com/NDsasuke/awaken-pos-portfolio)

### 🖨️ Awaken Print — one-tap Bluetooth receipt printing for Android · [print.awakendev.com](https://print.awakendev.com)
An Android app that prints receipts from a web POS to a cheap Bluetooth thermal printer in one tap: no print preview, no printer picker, no watermark. Any web app can add it with one script.

- The web page renders the receipt to 1-bit printer dots and hands it to the app over an intent link, so Sinhala, Tamil and English print pixel-exact
- Also a system **Android PrintService**, so every app on the phone can print through it
- ESC/POS raster printing over Bluetooth Classic (SPP) and BLE, printer status checks, 58/80 mm paper
- Business model built in: offline ECDSA-signed shop licences and Google Play Billing subscriptions
- Open-source web script **[`pos-printer.js`](https://github.com/NDsasuke/awaken-print-portfolio/tree/main/pos-printer)** (MIT), with a [developer guide](https://print.awakendev.com/developers/) and [demo](https://print.awakendev.com/demo/)

**Stack:** Kotlin · Jetpack Compose · Android PrintService · Bluetooth SPP/BLE · Google Play Billing · JavaScript · JUnit · Robolectric · Roborazzi\
**Portfolio:** [awaken-print-portfolio](https://github.com/NDsasuke/awaken-print-portfolio)

## 🛠️ In development

- **AwakenDev Wedding Studio**: a SaaS for wedding websites, digital invitations, RSVPs, guest lists, tasks, budgets and vendors.
  *Next.js · TypeScript · Hono + OpenAPI · PostgreSQL (Row-Level Security) · Drizzle · Better Auth · pg-boss · Docker · Vitest · Playwright*
- **Gewaththa (ගෙවත්ත)**: a marketplace where people across Sri Lanka sell extra home-grown fruit and vegetables to people nearby.
  *Laravel · PHP · Docker*
- **Fitness RPG**: a mobile fitness app with RPG-style progression, where workouts and personal records earn XP, levels and daily quests.
  *React Native (Expo) · TypeScript · Supabase*

All AwakenDev products run on infrastructure I set up and maintain: Docker on a Linux VPS behind nginx and Cloudflare tunnels, with separate staging and production environments.

## 🧰 Technologies

**Languages**\
PHP · TypeScript · JavaScript · Kotlin · Python · Java · SQL · C · C++

**Frameworks & Libraries**\
Laravel · Next.js · React Native (Expo) · Jetpack Compose · Hono · Drizzle · Spring Boot · PyTorch · pandas · NumPy

**Databases**\
MariaDB · MySQL · PostgreSQL · Redis · Supabase · Oracle Database

**DevOps & Infrastructure**\
Docker · Docker Compose · Linux VPS · nginx · Cloudflare (DNS, TLS, Tunnels) · GitHub Actions CI/CD · automated backups

**Testing**\
PHPUnit · Playwright · Vitest · JUnit · Robolectric · Roborazzi

**Android**\
Bluetooth Classic & BLE · ESC/POS printing · PrintService · Google Play Billing

## 📌 Selected public work

- **[ADPOS portfolio](https://github.com/NDsasuke/awaken-pos-portfolio)**: screenshots, features and architecture of the live retail POS.
- **[Awaken Print portfolio](https://github.com/NDsasuke/awaken-print-portfolio)**: architecture and screenshots of the Android print app, plus the open-source `pos-printer.js`.
- **[Autocorrelation Function Diagnostics and Prediction](https://github.com/NDsasuke/Autocorrelation-function-Diagnostics-and-prediction)**: time-series analysis, forecasting, cross-validation and model evaluation.
- **[Classification, Regression & Clustering](https://github.com/NDsasuke/Classification-Regression-Clustering)**: supervised and unsupervised machine-learning work.

## 🎓 Education

**BSc (Hons) in Computer Science, University of Kelaniya**\
Second Class Upper Division · GPA 3.55/4.00

## 🤖 How I work

I use AI coding tools such as Claude Code extensively for implementation, debugging and testing. I stay responsible for every change: I review it, test it, and check it works in the real product before it ships. I keep decisions, open issues and changelogs written down for each product, and I pick up unfamiliar technologies when a project needs them, from Android Bluetooth printing to PostgreSQL row-level security.

## 📫 Connect

- LinkedIn: [Nishal Dilanga Ranasinghe](https://www.linkedin.com/in/nishal-dilanga-ranasinghe/)
- AwakenDev: [awakendev.com](https://awakendev.com) · [hello@awakendev.com](mailto:hello@awakendev.com)
- GitHub: [@NDsasuke](https://github.com/NDsasuke)
