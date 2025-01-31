<IMG SRC="blocked-scraper-detect-logo.png" ALT="Detect blocked browser pages" />

# Blocked Scraper Detector

For detecting when your scraper is blocked - This project does not much on its own but it is designed to be integrated with your scraper / page fetcher.

**But what problem does it solve?** - Many CDN's and other anti-robot services will report a "Sorry you are blocked" 
page response, BUT the actual reply from the server will still be code `200` "Standard response for successful HTTP requests.".

It is beneficial to know for example, if the price that you're scraping for is missing, OR if the page request was blocked.

**How to help**

Increase the detection surface area - Please submit PR's at https://github.com/dgtlmoon/blocked-scraper-detect when you have some specific regex, text, HTML etc to match.


## Usage

### Python 

We include a python module interface
@todo

### JS
@todo




