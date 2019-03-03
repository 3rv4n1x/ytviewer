# YTViewer

## Description

**YTViewer** is simple YouTube views bot

## Prerequisites

### Windows

Install Python(3+): https://www.python.org/downloads/

Install required libraries:

```
$ pip install -r requirements.txt
```

Download **ChromeDriver** and move the executable to folder in your PATH: http://chromedriver.chromium.org/downloads

### Linux

```
$ sudo apt update && sudo apt upgrade -y
$ sudo apt install python -y
$ pip install -r requirements.txt
```

Download **ChromeDriver** and move the executable to folder in your PATH: http://chromedriver.chromium.org/downloads

## Installation

Clone this repository:

`$ git clone "https://github.com/DeBos99/ytviewer.git"`

## Usage

Help:

`$ main.py --help`

Run bot on \<url\>:

`$ main.py --url <url>`

Set number of threads (default: 15):

`$ main.py --url <url> --threads <threads>`

Set duration of view in seconds (default: 5 minutes):

`$ main.py --url <url> --duration <duration>`

Set proxies file (default: proxies loaded from web)

`$ main.py --url <url> --proxies <proxies>`

## Authors

* **Michał Wróblewski** - Main Developer - [DeBos99](https://github.com/DeBos99)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
