[Facebook Page Details](https://apify.com/iron-crawler/facebook-page-details?fpr=data)

"# Facebook Page Details Scraper (Cookieless)

## What does Facebook Page Details Scraper (Cookieless) do?

This tool extracts comprehensive page information from Facebook pages without requiring any login credentials or cookies. Built with a cookieless architecture, it allows sales intelligence professionals, marketers, and researchers to gather public Facebook page data efficiently and at scale. You can access page details, engagement metrics, and profile information without authentication barriers, making it ideal for building lead databases and competitive intelligence workflows.

**Key Features:**

- Extract page details without Facebook login or cookies
- Scrape page names, descriptions, categories, and verification status
- Capture follower counts, likes, and engagement metrics
- Export data to JSON, CSV, or Excel formats
- Process multiple pages in a single run
- Access public page information compliantly

## Why scrape Facebook page data?

Sales intelligence professionals need detailed page information to build comprehensive lead databases and accelerate B2B prospecting efforts. Facebook pages contain valuable business signals including company size indicators, industry categories, contact information, and engagement levels that help qualify leads and prioritize outreach. This data transforms social profiles into actionable sales intelligence.

**Primary Use Cases:**

- **Lead Generation:** Build targeted prospect lists by extracting business pages matching your ideal customer profile, including industry, location, and follower count criteria
- **Market Research:** Analyze competitor pages, track brand presence across regions, and identify emerging players in your target markets
- **Sales Enrichment:** Enhance existing CRM records with social proof metrics, engagement data, and updated business information from Facebook pages

## How to scrape Facebook using this tool?

**Step 1:** Locate the Facebook page URL you want to scrape. Navigate to the target page and copy the full URL from your browser (e.g., [https://www.facebook.com/facebook](https://www.facebook.com/facebook)).

**Step 2:** Configure your input parameters by pasting the page URL into the `pageUrl` field. You can process multiple pages by adding additional URLs. **1 page ≈ 1 Facebook page profile** with all available public details.

**Step 3:** Run the scraper and wait for extraction to complete. Once finished, download your data in JSON, CSV, or Excel format directly from the Apify platform.

## What are the input parameters?

| Field | Type | Description |
| --- | --- | --- |
| `pageUrl` | String (URL) | The full Facebook page URL you want to scrape (e.g., [https://www.facebook.com/facebook](https://www.facebook.com/facebook)). Accepts standard Facebook page URLs. |

## What data can you extract?

You can download the following data in JSON, CSV, or Excel formats:

```
{
  ""page_url"": ""https://www.facebook.com/apify"",
  ""title"": ""Apify - Web Scraping and Automation Platform"",
  ""meta_description"": ""Apify is a platform that enables developers to build, run, and share web scraping and automation tools. Extract data from any website."",
  ""last_modified"": ""2025-12-17T14:22:18Z"",
  ""word_count"": 2341,
  ""author"": ""Apify Team"",
  ""read_time_minutes"": 12,
  ""social_shares"": 1847
}
```

**Extracted Fields:**

- `page_url`: The complete Facebook page URL
- `title`: Page name and headline
- `meta_description`: Page description and about section
- `last_modified`: Timestamp of last page update
- `word_count`: Total word count from page content
- `author`: Page administrator or author information
- `read_time_minutes`: Estimated reading time for page content
- `social_shares`: Total engagement and share count

---

This web scraping tool serves as a powerful data extraction tool for professionals who need to export website data from Facebook at scale. Whether you're building a product data scraper workflow, conducting lead generation scraping, or creating a price data scraper for competitive analysis, this web scraper delivers reliable Facebook page intelligence without authentication complexity."