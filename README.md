# 🤖 TDS Virtual Teaching Assistant

This project is a FastAPI-based virtual TA that automatically answers student questions using:

- Course logic from Tools in Data Science (TDS Jan 2025)
- TDS Discourse discussion threads
- Rule-based responses for key student queries

## 🚀 Features

✅ Deployed on Hugging Face Spaces  
✅ Handles real student questions  
✅ Returns helpful answers and direct Discourse links  
✅ Returns JSON responses in required format  
✅ Accepts optional images (base64) — placeholder logic

## 📬 API Endpoint

Live API: [https://zairarahman24-tds-virtual-ta.hf.space/api/](https://zairarahman24-tds-virtual-ta.hf.space/api/)  
Interactive Swagger Docs: [https://zairarahman24-tds-virtual-ta.hf.space/docs](https://zairarahman24-tds-virtual-ta.hf.space/docs)

## 🧠 Supported Questions

- Should I use `gpt-3.5-turbo-0125` or `gpt-4o-mini`?
- GA4 bonus score visibility
- Docker vs Podman
- TDS Sep 2025 end-term date
- ...and more!

## 🛠 Bonus: Discourse Scraper Script

File: `scrape_discourse.py`  
Scrapes Discourse topics using a date/page range.

```bash
python scrape_discourse.py --start 1 --end 3
