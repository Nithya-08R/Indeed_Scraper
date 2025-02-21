A Python script to scrape job listings from Indeed using the Apify API and save them to a CSV file.

📌 Features
✅ Scrapes job details (title, company, job type, rating, apply link)
✅ Saves data in output.csv
✅ Configurable job position, location, and max items

🚀 Usage
1️⃣ Install dependencies:

sh
Copy
Edit
pip install apify-client
2️⃣ Run the script:

sh
Copy
Edit
python indeed.py
3️⃣ Customize search: Edit run_input in indeed.py to change job title, location, etc.

📁 Output Format
The results are saved in output.csv with columns:
Job Title | Company | Job Type | Rating | Apply Link

⚠️ Disclaimer
Replace ApifyClient("your_api_key") with your Apify API key.
Follow Indeed’s terms of service when scraping.
