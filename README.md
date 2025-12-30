# termux-proxy-scraper by shinn

    # Termux Proxy Scraper By Shinn 🚀

Fast and fresh free public proxy scraper for Termux with interactive menu.

### Features
- main menu
- [1] Start Scraping → Gets **super fresh** proxies (sources update every 5 minutes!)
- [2] Download Results → Sub-menu to save files to your phone's **Download** folder (ALLRESULTS.txt, SOCKS4.txt, etc.)
- Formatted ALLRESULTS.txt exactly as requested (RESULTS count + grouped sections with blank lines)
- [3] Remove All Results → Cleans everything
- No duplicates, fast parallel downloads
- All file names in **CAPITAL LETTERS**

**Important**: These are free public proxies (not HQ residential or authenticated). Many die quickly — run often for fresh ones!

### Installation & Run

```bash

pkg install curl
nano proxy_scraper_menu.sh   # Paste the script code here
chmod +x proxy_scraper_menu.sh
./proxy_scraper_menu.sh
