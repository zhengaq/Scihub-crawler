# Crawl Data from SCI-HUB

## Descriptions

This Jupyter Notebook is used to crawl data from sci-hub.

## How to install

The script is wrote in Python, and the following guidance works for macOs.
The underlying philosophy is using selenium to manipulate a web-driver, which hosts and controls a chrome web browser. 

To run this stuff:
- install Python 3.6+ (installing with [Anaconda](https://www.anaconda.com/distribution/) is recommended!)
- install jupyter (included in anaconda, so no need to download separately if you've installed anaconda)
- install chrome (practically any version works)
- install [chrome webdriver](https://chromedriver.chromium.org/downloads)
  - download the chrome webdriver and run `sudo cp chromedriver /usr/local/bin/` in command line (terminal)
- install [selenium](https://selenium-python.readthedocs.io/)
  - run `pip install selenium` in command line
- download the `Downloader.ipynb` to a local destination, where you keep the targeted list of article names. Then run `jupyter notebook` in command line under the same destination
- open `downloader` at the pop-up chrome page and start crawling (specific guidance is included in the notebook)
