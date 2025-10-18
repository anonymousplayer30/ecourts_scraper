# ecourts_scraper
🏛️ eCourts Scraper  A Python-based command-line and API tool to fetch court listing information from the eCourts  portal of India. This utility helps you check if a case is listed for hearing today or tomorrow and allows optional downloading of the entire cause list for a selected district.

✨ Features
🔍 Search by CNR number or case details (type, number, year)
📆 Check if the case is listed today or tomorrow
🧾 Fetch serial number and court name for listings
📄 Optionally download the cause list for a district court
💾 Save outputs as structured JSON files
🖥️ Simple CLI interface with Click
🌐 Optional REST API using FastAPI

🛠️ Tech Stack
Python 3.x
Requests & BeautifulSoup (for scraping)
Click (CLI)
FastAPI (optional API)
Selenium (placeholder for dynamic scraping if needed)

Project Structure
ecourts_scraper/
├── main.py            # CLI entry point
├── cli.py             # CLI interface (Click)
├── scraper.py         # Core scraping logic
├── utils.py           # Helper functions
├── api.py             # Optional FastAPI server
├── config.py          # Config constants
├── requirements.txt   # Dependencies
├── data/              # Saved case & cause list data
└── README.md


