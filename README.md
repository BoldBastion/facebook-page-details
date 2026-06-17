[Facebook Page Details](https://apify.com/data-slayer/facebook-page-details?fpr=data)

Extract comprehensive Facebook page data without logging in or managing cookies. This cookieless scraper enables sales intelligence teams to build rich lead databases by capturing verified business information, follower counts, contact details, and more from public Facebook pages.

## 📺 Video Tutorial: How it Works

[Video](https://www.youtube.com/embed/9M87r2AInGs?enablejsapi=1&rel=0)

---

## Key Features

🔒 **Cookieless / No Login Required** - Access public Facebook page data without authentication, eliminating account management overhead and reducing the risk of blocks or restrictions.

📈 **Scalable Architecture** - Process multiple page URLs efficiently to build comprehensive lead databases at scale for B2B prospecting campaigns.

✅ **Rich Profile Data** - Capture essential business intelligence including page names, follower counts, verification status, categories, contact information (phone, email, website), addresses, ratings, and profile images.

⚡ **Fast & Reliable** - Optimized extraction engine delivers consistent results with minimal latency, ensuring your prospecting workflows stay on schedule.

📊 **Export-Ready Formats** - Download data in JSON, CSV, or Excel formats for immediate integration with CRM systems, marketing automation platforms, and analytics tools.

## Use Cases

**Sales Intelligence Professionals**: Build targeted B2B lead lists by extracting verified business pages with contact details, follower metrics, and category classifications to prioritize high-value prospects.

**Market Research Analysts**: Gather competitive intelligence by analyzing page categories, follower growth patterns, verification status, and business information across industry segments.

**Marketing Teams**: Enrich existing customer databases with social proof metrics, website URLs, and business classifications to personalize outreach campaigns and improve conversion rates.

## Inputs

| Field | Type | Description |
| --- | --- | --- |
| pageUrl | String | The full Facebook page URL to scrape (e.g., [https://www.facebook.com/facebook](https://www.facebook.com/facebook)) |

## Outputs

**Formats**: JSON, CSV, Excel

**Fields**: Each extracted page record includes:

- `name` - Page display name
- `page_id` - Unique Facebook page identifier
- `url` - Full page URL
- `followers` - Total follower count
- `verified` - Verification status (true/false)
- `categories` - Business category classifications
- `website` - Associated website URL
- `phone` - Contact phone number
- `email` - Contact email address
- `address` - Physical business address
- `rating` - Page rating score
- `image` - Profile image URL
- `cover_image` - Cover photo URL
- `intro` - Page introduction text
- `services` - Listed services
- `price_range` - Price range indicator
- `other_accounts` - Connected social accounts
- `delegate_page` - Delegate page information

## How to Use

**Step 1**: Enter the target Facebook page URL in the `pageUrl` field (e.g., [https://www.facebook.com/yourcompany](https://www.facebook.com/yourcompany)).

**Step 2**: Click "Start" to begin the extraction process.

**Step 3**: Once complete, download your data in JSON, CSV, or Excel format and import directly into your CRM or analytics platform.

## Sample Output

```
{
  "name": "TechCorp Solutions",
  "type": "page",
  "page_id": "100012345678901",
  "url": "https://www.facebook.com/techcorpsolutions",
  "image": "https://scontent.example.com/profile.jpg",
  "followers": 45000,
  "categories": [
    "Software Company",
    "Technology Company"
  ],
  "phone": "+1-555-0123",
  "email": "contact@techcorp.com",
  "address": "123 Innovation Drive, San Francisco, CA 94105",
  "website": "https://www.techcorp.com",
  "verified": true,
  "rating": 4.7,
  "cover_image": "https://scontent.example.com/cover.jpg"
}
```

## 🧩 Other Facebook Actors by Data Slayer

| Actor | What it does | Link |
| --- | --- | --- |
| Facebook Reviews Scraper | Extract customer reviews from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-reviews) |
| Facebook Posts Scraper | Extract posts from any Facebook page | [Try it](https://apify.com/data-slayer/facebook-page-posts) |
| Facebook Group Posts Scraper | Extract posts from any public Facebook group | [Try it](https://apify.com/data-slayer/facebook-group-posts) |
| Facebook Page Search Scraper | Search and discover Facebook pages by keyword | [Try it](https://apify.com/data-slayer/facebook-search-pages) |
| Facebook People Search Scraper | Search and find Facebook profiles by keyword | [Try it](https://apify.com/data-slayer/facebook-search-people) |
| Facebook Events Scraper | Discover Facebook events by keyword search | [Try it](https://apify.com/data-slayer/facebook-search-events) |
| Facebook Marketplace Listing Scraper | Extract detailed listing data from Facebook Marketplace | [Try it](https://apify.com/data-slayer/facebook-marketplace-details) |

**Powerful workflow:** Use [Facebook Page Search Scraper](https://apify.com/data-slayer/facebook-search-pages) to discover pages by keyword → feed those page URLs into this actor to get full business profiles with contact details.

## 💬 Feedback and Support

We actively maintain this actor and ship improvements based on user feedback. If you run into any issues or have ideas for new features:

- Create an issue on the Actor's **Issues tab** in Apify Console
- Rate the actor if it helped you — it helps others find it too
We typically respond within 24 hours.