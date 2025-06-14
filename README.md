
# YouTube Channel Scraper

This is a simple Flask web app that uses Selenium to scrape videos from a YouTube channel page (e.g., `https://www.youtube.com/@channelName/videos`).

## Features
- User-friendly web interface
- URL validation using JavaScript
- Loading screen while scraping
- Scrapes video metadata (title, views, posted date, etc.)
- Exports data to CSV (`youtube.csv`)
- Option to download the scraped CSV file

## Screenshot

![Screenshot](screenshot.png)

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask app:
   ```bash
   python app.py
   ```

4. Open your browser and go to: `http://127.0.0.1:5000`

## Dependencies
See `requirements.txt`
