
# Daily Dashboard

A modern, web-based dashboard displaying **weather, news, stocks, a chatbot, and bookmarks** in a sleek, responsive interface.

---

## Features

* **Weather:** Powered by Open-Meteo API (no API key required).
* **News:** Powered by OpenAI API for fresh headlines.
* **Stocks:** Real-time stock data via Alpha Vantage.
* **Chatbot:** Daily updates assistant powered by OpenAI.
* **Bookmarks:** Local storage based quick-access links.
* Fully responsive and page-width friendly layout.

---

## Installation

Follow these steps to run the dashboard locally:

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/daily-dashboard.git
cd daily-dashboard
```

### 2. Open the Project in a Browser

Since this is a static HTML/CSS/JS project, you can open the `index.html` file directly:

* On **Windows:** double-click `index.html`
* On **Mac/Linux:** open with your favorite browser

Or, use a local development server:

```bash
# Using Python 3
python -m http.server 8000
```

Then navigate to: `http://localhost:8000`

### 3. Configure API Keys (Optional)

Some features require API keys:

* **OpenAI:** For news headlines and chatbot

  * Replace `OPENAI_API_KEY` in the `<script>` section with your key:

```js
const OPENAI_API_KEY = "YOUR_OPENAI_KEY";
```

* **Alpha Vantage:** For stock prices

  * Replace `ALPHA_VANTAGE_KEY` in the `<script>` section with your key:

```js
const ALPHA_VANTAGE_KEY = "YOUR_ALPHA_VANTAGE_KEY";
```

> Note: Weather via Open-Meteo works without an API key.

### 4. Use the Dashboard

* **Weather:** Enter a city or use geolocation.
* **News:** Select topics using chips.
* **Stocks:** Enter stock symbols and click Load.
* **Chatbot:** Ask for daily updates and market insights.
* **Bookmarks:** Add and remove bookmarks locally.

---

## Dependencies

* [Chart.js](https://www.chartjs.org/) (loaded via CDN)
* [Open-Meteo API](https://open-meteo.com/) (no key required)
* [OpenAI API](https://openai.com/) (for news & chatbot)
* [Alpha Vantage](https://www.alphavantage.co/) (for stock data)

---

## Contributing

1. Fork the repository
2. Create your feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m "Add new feature"`
4. Push to the branch: `git push origin feature-name`
5. Open a Pull Request


