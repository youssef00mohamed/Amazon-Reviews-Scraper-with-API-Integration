# Amazon Reviews Scraper and Sentiment Analysis

Automate the extraction of Amazon product reviews using Selenium WebDriver, store them in a Pandas DataFrame, and integrate with an API for sentiment analysis.

## Overview

This project provides a solution to scrape Amazon product reviews, store them locally, and optionally perform sentiment analysis using an external API. It leverages web automation with Selenium to navigate through product review pages and interact with elements dynamically.

### Key Features

- **Automated Review Scraping:** Uses Selenium WebDriver to navigate Amazon pages, click on review buttons, and extract product reviews.
- **Data Storage:** Saves scraped reviews into a CSV file using Pandas DataFrame for further analysis or storage.
- **API Integration:** Sends extracted reviews to an API endpoint for sentiment analysis using HTTP POST requests.
- **Error Handling:** Implements robust error handling to manage exceptions during scraping and API interactions.

## Technologies Used

- **Python Libraries:** `Pandas`, `Selenium`, `Requests`
- **Web Technologies:** `HTML`, `HTTP`

## Installation

1. **Clone the repository:**

   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. **Install dependencies:**

   ```bash
   pip install -r requirements.txt

3. **Setup**

   - Ensure you have Chrome installed.
   - Download ChromeDriver and set `chromedriver_path` variable in `scrape_reviews` function to its path.

4. **Sentiment Analysis (Optional)**

   - Send reviews to API
  
## Contributions

Contributions to this repository are welcome! If you have suggestions for improvements, additional compression algorithms, or enhancements to the GUI application, please feel free to open an issue or pull request. Ensure that your contributions align with the project's objectives and maintain code quality and documentation standards.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
