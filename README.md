# 📱 Social Blade Scraper

![Social Blade Scraper Cover Image](https://i.imgur.com/i1VDGe3.png)
| Try our other scrapers ► | [TikTok Video Scraper](https://apify.com/radeance/tiktok-video-scraper-premium) | [Similarweb Scraper](https://apify.com/radeance/similarweb-scraper)| [Wellfound Scraper](https://apify.com/radeance/wellfound-job-listings-scraper)
|----------------------------|-----------------------------|-----------------------------|-----------------------------|

Welcome to this **Social Blade Scraper** on Apify!
This lightning-fast, full-featured actor is built to extract comprehensive creator stats from Social Blade — the go-to platform for influencer analytics. Whether you’re a brand strategist, influencer marketer, data analyst, or just curious about your favorite creator’s growth, this scraper has you covered.

It effortlessly pulls in-depth metrics from Social Blade, including estimated earnings, detailed subscriber history, growth trends, social links, and platform-specific stats across YouTube and TikTok.

Built for speed and reliability — scrape dozens of creators in seconds! 💨
<br>

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/socialblade-api)

## ✨ Key Features

-   **✅ Comprehensive Creator Analytics**
    -   Scrapes creators by platform and unique handle or ID (YouTube, Instagram, Twitter)
    -   Retrieves detailed performance data: subscribers, uploads, views, daily/weekly/monthly growth
    -   Fetches Social Blade rankings and estimated earnings
-   **✅ Estimated Earnings Insights:**
    -   Extracts average estimated earnings for daily, weekly, monthly, and yearly windows
    -   Extracts daily estimated earnings up to the last 14 days
-   **✅ Time-Series Growth Insights:**
    -   Extracts subscriber and follower change data across 3, 7, 14, 30, 60, and 90-day windows
    -   Provides a structured overview of audience growth over time
    -   Perfect for identifying trends and momentum shifts
-   **✅ Multi-Platform Social Footprint:**
    -   Gathers all linked social media accounts from the creator’s profile
    -   Centralizes social presence across platforms into one unified JSON output
-   **✅ High-Speed, Scalable Scraping:**
    -   Supports bulk scraping of multiple creators in one run
    -   Built with concurrency and smart retries for reliable, high-speed performance
-   **✅ Flexible Output Formats:**
    -   Outputs clean, structured data in JSON, CSV, XLSX, and JSONL formats
    -   Ready for dashboards, BI tools, influencer databases, or automated workflows

## 🔖 Output Preview

![Output Table View](https://i.imgur.com/1DDVa4g.png)

```json
{
  "data_captured_at": "2025-05-26T18:35:40.409864",
  "creator_id": "UCX6OQ3DkcsbYNE6H8uQQuVA",
  "creator_handle": "mrbeast",
  "display_name": "MrBeast",
  "platform": "youtube",
  "created_at": "2012-02-20T00:00:00.000Z",
  "verified": null,
  "avatar": "https://yt3.ggpht.com/nxYrc_1_2f77DoBadyxMTmv7ZpRZapHR5jbuYe7PlPd5cIRJxtNNEYyOC0ZsxaDyJJzXrnJiuDE=s88-c-k-c0x00ffffff-no-rj",
  "banner": "https://yt3.googleusercontent.com/5KWiriZZ_KEoEdSMFTJKj2M6vR_XSiRZeQ-ix0cvG3TGZuGoi8sfAjrSiZAP0GzXBkmF8ZGytw=w2560-fcrop64=1,00005a57ffffa5a8-k-c0xffffffff-no-nd-rj",
  "country": "US",
  "category": "entertainment",
  "made_for_kids": false,
  "sb_grade": "A+",
  "socials": [
    "https://www.youtube.com/channel/UCX6OQ3DkcsbYNE6H8uQQuVA",
    "https://instagram.com/mrbeast",
    "https://twitter.com/MrBeast"
  ],
  "subscribers": 398000000,
  "views": "83918312023",
  "videos": 873,
  "subscribers_last_3d": "1000000",
  "subscribers_last_7d": "2000000",
  "subscribers_last_14d": "5000000",
  "subscribers_last_30d": "11000000",
  "subscribers_last_60d": "20000000",
  "subscribers_last_90d": "32000000",
  "subscribers_last_180d": "66000000",
  "subscribers_last_365d": "137000000",
  "views_last_3d": "448519279",
  "views_last_7d": "888291666",
  "views_last_14d": "1532706368",
  "views_last_30d": "3376442811",
  "views_last_60d": "7539573807",
  "views_last_90d": "10188180018",
  "views_last_180d": "18636944777",
  "views_last_365d": "34415845266",
  "videos_last_3d": "1",
  "videos_last_7d": "2",
  "videos_last_14d": "3",
  "videos_last_30d": "9",
  "videos_last_60d": "16",
  "videos_last_90d": "25",
  "videos_last_180d": "28",
  "videos_last_365d": "28",
  "estimated_earnings": {
    "daily": {
      "min": 27297.67,
      "max": 436762.78,
      "currency": "USD",
      "formatted": "$27.3K - $436.8K"
    },
    "weekly": {
      "min": 211020.31,
      "max": 3376324.95,
      "currency": "USD",
      "formatted": "$211.0K - $3.4M"
    },
    "monthly": { # Subscription only
      "min": 818930.2,
      "max": 13102883.26,
      "currency": "USD",
      "formatted": "$818.9K - $13.1M"
    },
    "quarterly": { # Subscription only
      "min": 2561355.62,
      "max": 40981689.95,
      "currency": "USD",
      "formatted": "$2.6M - $41.0M"
    },
    "half_yearly": { # Subscription only
      "min": 4683849.2,
      "max": 74941587.21,
      "currency": "USD",
      "formatted": "$4.7M - $74.9M"
    },
    "yearly": { # Subscription only
      "min": 8554558.38,
      "max": 136872934.09,
      "currency": "USD",
      "formatted": "$8.6M - $136.9M"
    }
  },
  "estimated_earnings_daily": [
    {
      "date": "2025-05-15 00:00:00",
      "amount": "$17K - $273K"
    },
    {
      "date": "2025-05-16 00:00:00",
      "amount": "$16K - $252K"
    },
    {
      "date": "2025-05-17 00:00:00",
      "amount": "$31K - $495K"
    },
    {
      "date": "2025-05-18 00:00:00",
      "amount": "$37K - $597K" # Subscription only
    },
    {
      "date": "2025-05-19 00:00:00",
      "amount": "$41K - $657K" # Subscription only
    },
    {
      "date": "2025-05-20 00:00:00",
      "amount": "$24K - $385K" # Subscription only
    },
    {
      "date": "2025-05-21 00:00:00",
      "amount": "$22K - $359K" # Subscription only
    },
    {
      "date": "2025-05-22 00:00:00",
      "amount": "$22K - $358K" # Subscription only
    },
    {
      "date": "2025-05-23 00:00:00",
      "amount": "$50K - $801K" # Subscription only
    },
    {
      "date": "2025-05-24 00:00:00",
      "amount": "$21K - $333K" # Subscription only
    },
    {
      "date": "2025-05-25 00:00:00",
      "amount": "$41K - $660K" # Subscription only
    },
    {
      "date": "2025-05-26 00:00:00",
      "amount": "$26K - $418K" # Subscription only
    },
    {
      "date": "2025-05-27 00:00:00",
      "amount": "$28K - $448K" # Subscription only
    },
    {
      "date": "2025-05-28 00:00:00",
      "amount": "$15K - $245K" # Subscription only
    }
  ],
  "daily_growth": [
    {
      "date": "2025-05-12T00:00:00.000Z",
      "subscribers": 393000000,
      "views": "82368842393",
      "videos": 870
    },
    {
      "date": "2025-05-13T00:00:00.000Z",
      "subscribers": 394000000,
      "views": "82454664001",
      "videos": 870
    },
    {
      "date": "2025-05-14T00:00:00.000Z",
      "subscribers": 394000000,
      "views": "82521775256",
      "videos": 870
    },
    ...
  ],
  "weekly_growth": [
    {
      "date": "2024-06-03T00:00:00.000Z",
      "subscribers": 9000000,
      "views": "558881586",
      "videos": 0
    },
    {
      "date": "2024-06-10T00:00:00.000Z",
      "subscribers": 8000000,
      "views": "1335624432",
      "videos": 0
    },
    {
      "date": "2024-06-17T00:00:00.000Z",
      "subscribers": 6000000,
      "views": "696410489",
      "videos": 0
    },
    ...
  ],
  "monthly_growth": [
    {
      "date": "2022-05-31T00:00:00.000Z",
      "subscribers": 0,
      "views": 0,
      "videos": 0
    },
    {
      "date": "2022-05-31T00:00:00.000Z",
      "subscribers": 0,
      "views": 0,
      "videos": 0
    },
    {
      "date": "2022-06-30T00:00:00.000Z",
      "subscribers": 1700000,
      "views": 375092717,
      "videos": 0
    },
    {
      "date": "2022-07-31T00:00:00.000Z",
      "subscribers": 2300000,
      "views": 468441605,
      "videos": 0
    },
   ...
  ],
  "projections": [
    {
      "date": "2025-05-27 00:00:00+00:00",
      "subscribers": 398484516.5,
      "views": 83867026225.02
    },
    {
      "date": "2025-05-28 00:00:00+00:00",
      "subscribers": 398869604.74,
      "views": 83984823504.39
    },
    {
      "date": "2025-05-29 00:00:00+00:00",
      "subscribers": 399255055.36,
      "views": 84102770586.74
    },
   ...
  ],
  "ranks": {
    "metadata": {
      "country": "US",
      "category": "entertainment"
    },
    "position": {
      "sb": 16,
      "subscribers": 1,
      "views": 11,
      "country": 1,
      "category": 1
    },
    "shared": {
      "subscribers": 0,
      "views": 0,
      "country": 0,
      "category": 0,
      "sb": 3
    },
    "ahead": {
      "subscribers": 0,
      "views": 10,
      "country": 0,
      "category": 0,
      "sb": 60
    }
  },
  "ranks_max": {
    "subscribers": 5032,
    "views": 5025183,
    "sb": 1182236,
    "countries": [
      [
        "NONE",
        5
      ],
      [
        "US",
        4755
      ],
      [
        "CA",
        4718
      ],
      [
        "IN",
        4748
      ],
      ...
    ],
    "categories": [
      [
        "games",
        4522
      ],
      [
        "entertainment",
        4784
      ],
      [
        "people",
        4575
      ],
      ...
    ]
  }
}
```

## 🗂️ Use Cases

-   **Marketers & Agencies:** Monitor influencer growth across platforms, compare creators by performance, and identify rising stars for collaborations.

-   **Influencer Managers:** Quickly pull detailed stats to evaluate creator reach, engagement history, and cross-platform presence for talent scouting and reporting.
-   **Data Scientists & Analysts:** Access clean, structured creator data to model audience growth, detect virality trends, or run predictive analytics.
-   **Content Creators & Streamers:** Track your own channel performance, benchmark against competitors, and fine-tune your content strategy based on real growth metrics.
-   **Academics & Researchers:** Study digital influence, platform dynamics, and the evolution of creator economies using longitudinal, quantitative Social Blade data.

## 📌 Input

![Scraper Sample Input](https://i.imgur.com/C0G47jo.png)

-   `Creators`: (Required) (Array of Strings) (Up to 5 for free users, unlimited for subscribers)<br>
    Provide one or more content creator usernames to scrape. You can add them individually or use the Bulk edit option to paste in multiple links at once.
    <br>💡 Example: "mrbeast"
-   `Platform`: (Optional) (Literal)
    Select betwen different platforms. Youtube and TikTok are available at the moment.
    Default: Youtube
-   `Projections`: (Optional) (Boolean)
    If projections are available, projection data will be provided.
    Default: true

### 🎛️ Advanced Options

![Scraper Sample Advanced Options Input](https://i.imgur.com/6rNGXQi.png)

-   `Proxy Configuration`: (Optional) (Object)
    Customize the proxy settings used by the scraper. For example Apify Residential proxies from the US can be used for stability and region-specific access.
    You can change the proxy group or country as needed.
    Default: { useApifyProxy: false, apifyProxyGroups: ["RESIDENTIAL"]}

### ✏️ JSON Input

Sample JSON input if you use the apify api via CURL, Python, JS etc.
![Scraper Sample JSON Input](https://i.imgur.com/2h8bOk7.png)

## 📎 Detailed Output Information

🎥 Creator Overview

Provides a snapshot of key information about the creator:
• Creator ID, username/handle, platform (YouTube, TikTok, etc.)
• Profile URL, display name, and profile image (if available)
• Verified status, total uploads, total views, and account creation data (where applicable)

📈 Subscriber & Follower Growth

Tracks detailed audience growth across multiple timeframes:
• Subscriber/follower counts over 3, 7, 14, 30, 60, and 90 days
• Growth deltas and trends to help identify surges or declines in popularity
• Includes ranks and percentile scores from Social Blade (e.g., subscriber rank, video view rank)

💰 Estimated Earnings & Engagement

Estimates the creator’s monetization potential and public reach:
• Daily/weekly/monthly estimated earnings (where available)
• Average views per day/month and engagement stats for each time window

🌐 Social Presence

Captures the creator’s full digital footprint:
• All linked social platforms (e.g., Instagram, Twitter, TikTok, etc.)
• Consolidated into a structured socials array for cross-platform analysis

🗃 Export Formats
• Output is available in JSON, CSV, XLSX, or JSONL
• Fully structured and normalized for easy use in dashboards, reports, or databases
• Automatically stored in your Apify dataset

## ⚙️ While the scraper is running

During the run, the actor will output log messages letting you know what is going on at any point. Each message always contains specific information about the process including which url / page the actor is working on.

If you provide invalid inputs to the actor, it will immediately stop with a failure state and output log messages explaining what is wrong. If you are unsure what went wrong feel free to open up an issue in the issue tab.

## 🔗 Legality of web scraping and scraping of job listings

The **Social Blade Scraper** is designed to ethically extract **only publicly available data**, and it **does not** scrape private user data such as personal email addresses or personal identifiers.

Our scrapers are ethical and do not extract any private user data, such as email addresses, gender, or location. They only extract what the user has chosen to share publicly. We therefore believe that our scrapers, when used for ethical purposes by Apify users, are safe. However, you should be aware that your results could contain personal data. Personal data is protected by the GDPR in the European Union and by other regulations around the world. You should not scrape personal data unless you have a legitimate reason to do so. If you're unsure whether your reason is legitimate, consult your lawyers. You can also read our [blog post](https://blog.apify.com/is-web-scraping-legal/) on the legality of web scraping

## 💬 Feedback and Support

**Your satisfaction** is **important** to us! Therefore we are constantly striving to enhance the performance of our Actors.

If you have any technical feedback or encounter any bugs with the **Social Blade Scraper**, please create an issue in the Actor’s Issues tab on the Apify Console.

You can also contact us directly for custom integrations or project use cases at business@radeance.com.
<br>

### [Try it today for free with our 3-day free trial! ](https://apify.com/radeance/socialblade-api)