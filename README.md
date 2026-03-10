# CityPulse Montgomery

CityPulse Montgomery is a real-time civic intelligence dashboard that aggregates public sentiment about city infrastructure, construction projects, and community concerns in Montgomery, AL. It scrapes live data from 5+ sources (Google News RSS, Reddit, YouTube, local news outlets like AL.com, WSFA, and Montgomery Advertiser), runs AI-powered sentiment analysis and topic extraction via Gemini, and presents an interactive map-based dashboard where residents and city officials can see what people are saying about specific projects, neighborhoods, and civic topics.

## Demo Video

[![Watch the Demo](https://img.shields.io/badge/Watch%20Demo-Google%20Drive-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1hkvywfBpmbUZCkErY-2_vpTGyLfA2Cel/view?usp=drive_link)

## Key Features

- Interactive map with 20 real Montgomery infrastructure projects (road work, construction, parks, utilities)
- Live sentiment analysis linking public mentions to specific projects
- AI chatbot ("Ask Your City") that answers natural-language questions about city projects using scraped data as context
- Suggested Actions engine that surfaces actionable insights (e.g., "Investigate budget complaints" when negative sentiment clusters around a topic)
- Clickable sentiment stats for quick access to public concerns

## Challenge Track

**Civic Access & Community Communication** — the project directly matches "scrape live city updates, power resident-facing chatbots, and track sentiment" from the track description. It also touches Smart Cities/Infrastructure through its construction project tracking.

Submitted to the [WorldWide Vibes Hackathon](https://academy.genai.works/hackathon).

---

## Important Notice for Reviewers & Visitors

> **Please avoid repeatedly refreshing or triggering data updates within the live dashboard.** This project is deployed on the **Google Cloud free tier** and relies on **Google AI (Gemini)** for sentiment analysis and natural language processing, as well as **Bright Data** web scraping credits generously provided for the hackathon. All of these services operate under strict usage quotas. Excessive data refresh requests may exhaust available credits and render the live demo inaccessible for other reviewers. We appreciate your understanding and cooperation in helping keep the demo available throughout the evaluation period.

**[Access Live Project Here](https://citypulse-montgomery-421382570350.us-central1.run.app/)**

---

> **Note:** Full source code and technical documentation are currently being prepared and will be published to this repository shortly.
