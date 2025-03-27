# Web Scraping Projects

This repository serves as a collection of different web scraping projects, each designed to extract data from specific sources using various scraping techniques. Each project is structured as an independent submodule to maintain modularity and allow easy cloning and updates.

## 📌 Projects in This Repository

### 1. [AiEstateScraper: Apartment Data Scraper](https://github.com/nazzal5448/AiEstateScraper)
- Scrapes property listings from **apartments.com**.
- Uses **Playwright** for browser automation.
- Parses and extracts data using **Selectolax**.
- Enhances extracted data with **LLM integration**.
- Outputs structured results in **JSON format**.

#### 🔧 Installation & Usage:
```bash
# Clone the project separately
git clone https://github.com/nazzal5448/AiEstateScraper.git
cd AiEstateScraper
pip install -r requirements.txt
playwright install
python main.py
```

---

### 2. [Stream Site Scraper](https://github.com/nazzal5448/stream-scraper)
- Scrapes game details from an online **streaming site**.
- Extracts **games on sale** with relevant details.
- Uses **Playwright** and **Selectolax** for scraping.
- Outputs results in **JSON format**.

#### 🔧 Installation & Usage:
```bash
# Clone the project separately
git clone https://github.com/nazzal5448/stream-scraper.git
cd stream-scraper
pip install -r requirements.txt
playwright install
python main.py
```

---

## 🛠 Cloning This Repository with Submodules
Since each project is stored as a **Git submodule**, use the following command to clone everything properly:

```bash
git clone --recurse-submodules https://github.com/nazzal5448/WebScrapingProjects.git
```

If you’ve already cloned it without submodules, run:
```bash
git submodule update --init --recursive
```

## 📌 Updating Submodules
To update any submodule to its latest version:
```bash
git submodule update --remote --merge
```

## 📜 License
Each project in this repository is independently licensed under the **MIT License**.

---

This repository is structured to help manage multiple web scraping projects efficiently while keeping them modular and maintainable. 🚀

