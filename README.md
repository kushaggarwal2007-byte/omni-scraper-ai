# 🕷️ Omni-Scraper-AI

> **High-speed, LLM-powered web intelligence & structured schema extractor built for autonomous agent pipelines.**

[![GitHub stars](https://img.shields.io/github/stars/kushaggarwal2007-byte/omni-scraper-ai?style=for-the-badge&color=ffd700)](https://github.com/kushaggarwal2007-byte/omni-scraper-ai/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Python 3.10+](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kush-aggarwal-52a624450)
[![Instagram](https://img.shields.io/badge/Follow-Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/kushsup)

---

## ⚡ What is Omni-Scraper-AI?

Web scraping in the age of LLMs is broken: raw HTML dumps consume massive token windows, while traditional CSS/XPath parsers break every time a page updates.

**Omni-Scraper-AI** solves this:
- 🧹 **Zero-Noise Content Cleaning**: Strips scripts, SVGs, and clutter down to high-density markdown.
- 🎯 **Strict Schema Enforcement**: Guarantees Pydantic/JSON validation without hallucinated keys.
- ⚡ **Async Batch Engine**: Scrapes and transforms dozens of target URLs concurrently with built-in rate-limiting.
- 🔗 **Agent-Ready**: Seamlessly pipes structured results into autonomous swarms.

---

## 🚀 Quickstart

```bash
git clone https://github.com/kushaggarwal2007-byte/omni-scraper-ai.git
cd omni-scraper-ai
pip install -r requirements.txt
```

```python
import asyncio
from omni_scraper import OmniScraper

async def main():
    scraper = OmniScraper()
    data = await scraper.extract_markdown("https://news.ycombinator.com")
    print(data[:500])

if __name__ == "__main__":
    asyncio.run(main())
```

---

## 👤 Author
Maintained by **Kush Aggarwal** — AI Systems Architect & Founder.
- **LinkedIn:** [Kush Aggarwal](https://www.linkedin.com/in/kush-aggarwal-52a624450)
- **Instagram:** [@kushsup](https://instagram.com/kushsup)
- **GitHub:** [@kushaggarwal2007-byte](https://github.com/kushaggarwal2007-byte)
