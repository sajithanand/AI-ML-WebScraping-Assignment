 The objective was to scrape 5-10 universities and at least 5 courses for each, ensuring that the data is clean, structured, and maintains relational integrity through unique identifiers.Key FeaturesDynamic Scraping: Utilizes BeautifulSoup and Requests to fetch live data from official university websites.Relational Database Structure: Data is organized into two linked Excel sheets: Universities (Parent) and Courses (Child).Unique Identifiers: Implements a custom ID system (university_id and course_id) to ensure data integrity and prevent duplicates.Professional Data Cleaning: Handles missing values appropriately and strips whitespace for a readable final output.📂 Repository Structurescraper.py: The main Python script containing the scraping logic.University_Course_Data.xlsx: The final output file with two relational sheets.requirements.txt: List of Python libraries required to run the script.🛠️ Technical StackLanguage: Python 3.x Libraries: * requests: For handling HTTP requests and bypassing basic bot protection.beautifulsoup4: For parsing HTML and extracting metadata.pandas: For data structuring and Excel manipulation.openpyxl: The engine used to generate the .xlsx file.

 How to Run the Project
Clone the Repository:

git clone https://github.com/YOUR_USERNAME/AI-ML-WebScraping-Assignment.git
cd AI-ML-WebScraping-Assignment

Install Dependencies:
pip install -r requirements.txt

Execute the Scraper:
python scraper.py
