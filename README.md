# NIPS-2025-abstract
Titles, authors, and abstracts of all NeurIPS 2025 papers.
I attempted to download NeurIPS 2025 papers using the openreview_downloader tool:

```bash
pip install openreview_downloader
ordl accepted --venue-id NeurIPS.cc/2025/Conference
```

openreview_downloader fetched 5,287 accepted submissions. However, the official page (https://nips.cc/virtual/2025/loc/san-diego/papers.html) displays "showing 400 of 5858 papers."

Due to this discrepancy in the total count, I re-scraped the NeurIPS 2025 titles and abstracts using a custom web crawler.
