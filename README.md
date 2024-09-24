# eBayScrapingBot

eBay Web Scraper with Discord Integration

This Python-based tool scrapes product data from eBay, such as prices, product titles, and locations, and provides a simple interface to request the data through a Discord bot. The bot returns the data in real-time, offering features like filtering by price range and sending notifications.

# Features
Product Scraping: Automatically scrapes eBay for specific products based on user queries.
Price Filtering: Allows users to specify a price range (e.g., lowest or highest price) for the results.
Discord Integration: Users can interact with the bot to request data directly from a Discord server.
Automated Notifications: Sends notifications of product updates directly to a Discord channel.
# Tech Stack
- Python: The core programming language for this tool.
- BeautifulSoup: For parsing HTML and extracting product data.
- Requests: For making HTTP requests to eBay and retrieving web pages.
- Pandas: For processing and filtering the scraped data.
- Discord.py: For integrating the bot with Discord and sending automated messages.
  
# Installation

1. Clone the repository:
```
git clone https://github.com/Rtaibzadah/eBayScrapingBot.git
cd ebay-webscraper-python
```

2. Set up a virtual environment (optional but recommended):
```
python3 -m venv venv
source venv/bin/activate  # For MacOS/Linux
venv\Scripts\activate  # For Windows
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Create a .env file for your Discord bot token:
```
DISCORD_TOKEN=your_discord_bot_token
```
# Changes
You must update the url and Authorizartion variable for the chat API key and the Authorisation key.
# Usage
Start the scraper: The scraper runs through a Python script that fetches the eBay data based on the provided product or location parameters.

Interacting through Discord: Once the bot is online, you can send commands to it in your Discord server, and the bot will reply with the requested information in real-time.

Example Command

```
/search "iphone 13" min_price=300 max_price=600
```

This command will search for iPhone 13 listings on eBay with prices between CA$300 and CA$600 and return the top 10 cheapest results.

Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for any suggestions or bug reports.

# License
There is no license :)
