# Termux Proxy Scraper by shinn 🚀

Fast fresh free public proxy scraper for Termux with beautiful green interactive menu. Scrapes HTTP, HTTPS, SOCKS4, SOCKS5 from top sources (updated every 5 minutes!).

### Features
- Super fresh proxies (Proxifly every 5 mins, ProxyScrape every second, TheSpeedX daily).
- Interactive green menu: [1] Start Scraping, [2] Download Results (with sub-menu for ALLRESULTS.txt, SOCKS4.txt, etc.), [3] Remove All Results.
- Downloads to phone's **Download** folder with CAPITAL file names.
- Formatted ALLRESULTS.txt: "RESULTS [count]" + grouped sections (SOCKS4, SOCKS5, HTTP, HTTPS) with blank lines.
- No duplicates, fast parallel fetches.
- Note: Free public proxies only (not authenticated/HQ residential). Run often for fresh ones!

They have 2 options to install MANUAL INSTALL & QUICK INSTALL 

MANUAL INSTALL
pkg install curl

git clone https://github.com/shinn30/termux-proxy-scraper.git

chmod +x proxy_scraper
./proxy_scraper

### Quick Install & Run (One Command)
In Termux, run this to clone, set up, and start:
```bash
pkg install git curl && git clone https://github.com/YourUsername/termux-proxy-scraper.git && cd termux-proxy-scraper && chmod +x proxy_scraper && ./proxy_scraper


