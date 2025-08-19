# Websites-Source-Extraction
A Python website grabber that downloads static &amp; dynamic HTML plus assets (JS, CSS, images, media). Uses requests + BeautifulSoup for static and Selenium for JS-rendered pages. Saves content locally for offline use or analysis.
# Website Grabber

A Python tool to download **static & dynamic HTML** along with assets (JS, CSS, images, media) from a website.  
Uses `requests` + `BeautifulSoup` for static content and `Selenium` for JavaScript-rendered pages.

---

## 🔧 Install
```bash
pip install requests beautifulsoup4 selenium webdriver-manager
▶️ Usage
python website_grabber.py


Enter the target website URL when prompted.
📂 Output

Static HTML → index.html

Dynamic (JS-rendered) HTML → rendered_index.html

Assets (CSS/JS/images/media) → saved in website_grab/

⚠️ Disclaimer

This tool is for educational and archival purposes only.
Do not use it to scrape or clone websites without permission.
