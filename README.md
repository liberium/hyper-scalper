# Hyper Scalper 🚀
Hyper Scalper is a professional-grade trading terminal built from the ground up for scalping crypto futures at moments of high volatility. It fuses a high-performance, real-time data visualization frontend with a robust, event-driven backend to provide traders with a critical edge.

This repository contains the full codebase, from the Next.js frontend to the Python-based data ingestion and trading services. The project is architected for future integration of AI-driven analysis and trade automation, aiming to evolve from a powerful manual trading tool into a comprehensive, intelligent trading system.

### Core Features

*   📈 **Multi-Chart Analysis:** Synchronized 1, 5, and 15-minute charts with key indicators (RSI, Volume, VWMA).
*   ⚡ **High-Resolution Market Depth:** A CScalp-inspired UI with a real-time order book (DOM), live ticks, and dynamic volume clusters.
*   📢 **Real-time Signal Ingestion:** A backend service that parses trading signals from Telegram and feeds them directly into the UI.
*   ⌨️ **Rapid Order Execution:** Place orders directly from the chart or DOM using keyboard shortcuts and mouse clicks, with semi-automated risk management.
*   🧠 **AI-Powered Roadmap:** Architected to support future development of:
    *   A high-fidelity **Market Replay Engine** for training.
    *   An **LLM-based Advisor** to analyze trading patterns.
    *   A fully **Automated AI Trader** trained via imitation learning.

### Tech Stack

**Web App:** Next.js, TypeScript, Tailwind CSS, TradingView Lightweight Charts
**Server:** Python, FastAPI, Kafka, TimescaleDB, Telethon, CCXT
