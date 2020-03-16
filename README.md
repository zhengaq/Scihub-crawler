# Crawl Data from SCI-HUB

## Descriptions

This Jupyter Notebook is used to crawl data from sci-hub.

## How it works

The script is wrote in Python. 
It uses selenium to manipulate a web-driver, which hosts and controls a chrome web browser. 
To run this stuff:
- you need to install Python 3.6+ (installing with [Anaconda](https://www.anaconda.com/distribution/) is recommended!)
- you need to install jupyter (included in anaconda)
- you need to install chrome (almost any version works)
- you need to install [chrome webdriver](https://chromedriver.chromium.org/downloads) (w.r.t. the corresponding chrome version)
- you need to install [selenium](https://selenium-python.readthedocs.io/), run `pip install selenium`
- download the `Downloader.ipynb` to a local destination, and run `jupyter notebook` in command line under the same destination. Then open `downloader` at the pop-up chrome page and then start crawling (specific guidance is included in the notebook)
