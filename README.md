# SPXcondors
SPX CONDORs Tools
# 🦅 SPX Iron Condor Scanner

A zero-latency scanner and strategy suite for **same-day SPX Iron Condors**, tuned for positive theta and sentiment overlays. Designed for tactical intraday execution and rapid backtesting.

> ⏱️ Beat the clock. 🎯 Nail the setup. ⚡ Deploy with confidence.

---

## 🔍 Features

- **📊 Signal Intelligence**: Real-time SPX scanner for high-probability condor entries
- **🧠 Sentiment Overlay**: Market bias insights from volume flow and option chain deltas
- **🚀 0DTE Ready**: Built for same-day expiry trading — every tick counts
- **💼 Strategy Templates**: Multi-layered Iron Condors with preconfigured wings
- **📈 Backtest Harness**: Replay signals against historical cycles
- **🔐 Local Deployment**: Run inside your Trusted Execution Environment (TEE) for secure inference

---

## 🛠️ Installation

```bash
git clone https://github.com/HONEYPOTZ-AI/SPXcondors.git
cd SPXcondors
streamlit run app.py
```

- Requires Python 3.9+
- All packages auto-installed via `requirements.txt`

---

## 🌐 Demo

Watch it live on [Streamlit](https://ironcondor.tools) *(Coming Soon)*  
Or preview the core logic inside `/scanner/` and `/strategies/`

---

## 🧠 How It Works

SPXcondors blends sentiment overlays, intraday price action, and statistical edge zones to detect momentary inefficiencies.  
Each Condor setup outputs:

| Field          | Description                                       |
|----------------|---------------------------------------------------|
| 📉 Short Strikes | Near ATM with volume-weighted deltas             |
| 📈 Long Wings   | Far OTM to cap risk and neutralize volatility     |
| ⏱️ Expiry       | Today’s 0DTE SPX chain                            |
| 🧠 Bias         | Bull/Bear sentiment meter from custom indicators |

---

## 📁 Repo Structure

```plaintext
SPXcondors/
├── scanner/           # Real-time signal engine
├── strategies/        # Condor templates + analytics
├── streamlit/         # UI components for live deployment
├── assets/            # SVG, favicon, teaser GIF
├── LICENSE
├── README.md
```

---

## 🙌 Contributing

Pull requests welcome!  
See [`CONTRIBUTING.md`](./CONTRIBUTING.md) for ideas, templates, and testing flows.

---

## 📢 Launch Badges

Add these to your product thread or landing page:

![GitHub stars](https://img.shields.io/github/stars/HONEYPOTZ-AI/SPXcondors?style=social)
![GitHub forks](https://img.shields.io/github/forks/HONEYPOTZ-AI/SPXcondors?style=social)

---

## 🧑‍💻 Built by [HONEYPOTZ Inc.](https://honeypotz.ai)  
Secure AI. Tactical Deployment.  
Need a custom scanner? DM us.
