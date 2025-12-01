# Capital One Shopping Scraper

![Capital One Shopping Scraper](https://i.ibb.co/FT0gqKQ/Capital-One-Shopping-Cover.png)

**Capital One Shopping Scraper** is a powerful Apify actor built to extract trending deals and product listings from [capitaloneshopping.com](https://capitaloneshopping.com/). Whether you're tracking discounts, analyzing e-commerce trends, or collecting product data, this actor is a reliable solution for your scraping needs.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/DevbkY3adMTBuoECt-actor-Q4V3vlgzaItY5SUMG-eHGASMXdhF-images-7.png" alt="Capitaloneshopping.com Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/capital-one-shopping" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


---


## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.4` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `capital-one-shopping` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---


## ✨ Key Features

- **Trending Offers Scraper** – Scrape popular deals, price drops, rewards offers, and coupons.
- **Product Page Scraper** – Scrape individual products or listings by keyword, category, or direct URL.
- **Multi-Source Input** – Start from trends, product search, category pages, or specific product URLs.
- **Flexible Filtering** – Search by keyword, filter trends, or target specific categories.

---

## 📌 Why Use This Actor?

Capital One Shopping is a competitive e-commerce engine known for surfacing deals and coupon-based discounts. Extracting this data lets you:

- Monitor pricing strategies and product trends
- Analyze competitive positioning
- Track consumer-focused deals and offers
- Enrich your product comparison or affiliate marketing databases

---

## 👥 Who Is This Actor For?

- 🧠 **E-commerce analysts** researching market pricing
- 🛒 **Deal aggregator platforms** collecting top promotions
- 📈 **Marketers** looking for coupon or discount trends
- 🧱 **Developers & startups** building consumer tools
- 📊 **Researchers** studying price evolution and availability

---

## ENUMs

### "model" input

| Enum    | Enum Title     |
| ------- | -------------- |
| PRODUCT | Product        |
| TREND   | Trending Offer |

### "trendFilters" input

| Enum             | Enum Title       |
| ---------------- | ---------------- |
| Popular Deals    | Popular Deals    |
| Price Drops      | Price Drops      |
| Rewards Offers   | Rewards Offers   |
| Trending Coupons | Trending Coupons |

### "category" input

| Enum                        | Enum Title                             |
| --------------------------- | -------------------------------------- |
| appliances                  | Appliances                             |
| arts-crafts-sewing-supplies | Arts, Crafts & Sewing Supplies         |
| car-parts                   | Automotive Supplies & Car Parts        |
| baby-products               | Baby Products                          |
| beauty-supplies             | Beauty & Personal Care Supplies        |
| books                       | Books                                  |
| cds-vinyl-records           | CDs & Vinyl Records                    |
| clothes                     | Clothing, Shoes & Jewelry              |
| electronics                 | Electronics                            |
| groceries                   | Groceries & Gourmet Foods              |
| health-household            | Health & Household                     |
| kitchen-supplies            | Home & Kitchen Supplies                |
| industrial-equipment        | Industrial & Scientific Equipment      |
| movies-tv                   | Movies & TV on Blu-Ray & DVD           |
| musical-instruments         | Musical Instruments                    |
| office-products             | Office Products                        |
| patio-lawn-garden-supplies  | Patio, Lawn & Garden Supplies          |
| pet-supplies                | Pet Supplies                           |
| phones                      | Smartphones, Cell Phones & Accessories |
| software                    | Software                               |
| sports-outdoor-supplies     | Sports & Outdoor Supplies              |
| tools-home-improvement      | Tools & Home Improvement               |
| toys-games                  | Toys & Games                           |
| video-games                 | Video Games                            |

## Input Schema

### 💡 Side Note

This actor intelligently adapts to the type of input provided:

- If `model` is set to `"TREND"`, the scraper focuses on trending offers only.
- If `startUrls` are defined, those URLs will be scraped directly, regardless of keyword or category.
- If neither of the above is set, the actor falls back to searching by keyword or browsing category pages.

This hierarchy ensures that your scraping logic remains clean and predictable.

### 1. Trending Deals Mode

```json
{
  "model": "TREND",
  "trendFilters": [
    "Popular Deals",
    "Price Drops",
    "Rewards Offers",
    "Trending Coupons"
  ],
  "keyword": "Nike",
  "maxItems": 20
}
```

### 2. Start URLs Mode

```json
{
  "model": "PRODUCT",
  "startUrls": [
    {
      "url": "https://capitaloneshopping.com/p/eufy-security-s-220-solo-cam-sol/7JQMLB5VXG"
    },
    { "url": "https://capitaloneshopping.com/search?q=Camera" },
    {
      "url": "https://capitaloneshopping.com/c/arts-crafts-sewing-supplies/QDZYZ455"
    }
  ],
  "maxItems": 20
}
```

### 3. Keyword & Category Mode

```json
{
  "model": "PRODUCT",
  "keyword": "Nike",
  "category": "appliances",
  "maxItems": 20
}
```

## Output Schema

### 1. TREND Model Output

```json
{
  "id": "760cc093-bf42-4d6d-bcb4-1bdfb112c27d",
  "title": "Men's Nike Air Force 1 Low Jewel Casual Shoes",
  "url": "https://capitaloneshopping.com/api/v1/redirectV2?autoRedirect=true&clickEvent=mirageTrackClick&credits=true&destDomain=finishline.com&destUrl=https%3A%2F%2Fwww.finishline.com%2Fstore%2Fproduct%2Fmens-nike-air-force-1-low-jewel-casual-shoes-%2Fprod2792889&experience=capitaloneshopping.com&redirectId=__WBCLICKID__&singleUseCoupon=false&subExperience=best_on_web&userId=4c7d7b63-75ac-5db2-a2ae-bc0588279d68&vendorMetaId=6f339faf-abc9-414f-ba71-9cad541f628b",
  "primaryImageUrl": "https://i.capitaloneshopping.com/150,fit,ifjpeg,q90,srII4FSwy6QaeWwIwRiwocI5lJpxSgOfVB0tJzr4Z8xA/https://media.finishline.com/s/finishline/null_null?$Grid$",
  "secondaryImageUrl": "https://images.capitaloneshopping.com/api/v1/logos?domain=finishline.com&width=400&type=cropped&fallback=true",
  "createdAt": null,
  "type": "great_popular_deal",
  "filterLabel": "Price Drops",
  "pill": {
    "text": "Price Drop",
    "backgroundColor": "objectCriticalEmphasisHigh",
    "textColor": "textInverse"
  },
  "merchantName": "Finish Line",
  "stats": {
    "priceHistory": [
      {
        "date": "2025-04-03",
        "list_price": 40
      },
      {
        "date": "2025-03-04",
        "list_price": 130
      }
    ],
    "viewHistory": [
      {
        "date": "2025-04-04",
        "views": 73
      },
      {
        "date": "2025-04-08",
        "views": 1855
      }
    ],
    "newPrice": "$40",
    "oldPrice": "$130",
    "percentOff": "69%",
    "productPopularity": 1453,
    "viewRatioVsAvg": 11.6850395,
    "exclusionsText": "Not eligible for purchases of adidas Yeezy products.",
    "cashback": "12%",
    "priceAfterRewards": "$35.20",
    "cashbackAmount": "$4.80"
  },
  "__mirage": {
    "trackProps": {
      "contentId": "760cc093-bf42-4d6d-bcb4-1bdfb112c27d",
      "contentRequestId": "3dcc7c0f-d788-4a98-be0d-67221eca45c7",
      "contentInstanceId": "f2bd30b7-2196-4929-82df-7cb84d4b4e1c",
      "feed": "best-on-web",
      "tld": "finishline.com",
      "dataType": "great_popular_deal",
      "feedItemId": "great_popular_deal:https://www.finishline.com/store/product/mens-nike-air-force-1-low-jewel-casual-shoes-/prod2792889",
      "brand": "NIKE",
      "displayInfo": "{\"primaryImage\":\"https://i.capitaloneshopping.com/150,fit,ifjpeg,q90,srII4FSwy6QaeWwIwRiwocI5lJpxSgOfVB0tJzr4Z8xA/https://media.finishline.com/s/finishline/null_null?$Grid$\",\"secondaryImage\":\"https://images.capitaloneshopping.com/api/v1/logos?domain=finishline.com&width=400&type=cropped&fallback=true\",\"primaryText\":\"Men's Nike Air Force 1 Low Jewel Casual Shoes\",\"stats\":{\"newPrice\":\"$40\",\"oldPrice\":\"$130\",\"percentOff\":\"69%\",\"productPopularity\":1453,\"viewRatioVsAvg\":11.6850395,\"exclusionsText\":\"Not eligible for purchases of adidas Yeezy products.\"},\"sortingData\":{\"actualPopularityScore\":0.024358654394745827,\"timesPreviouslyViewed\":0}}",
      "mirageFeatures": "[\"ext_homepage_feed_service_migration\",\"financial_product_cof_link\",\"financial_products_control\",\"homepage_feed_enhanced_filters_no_search\",\"homepage_feed_ftc_disclosure_first_item_on\",\"homepage_feed_generic_merchants_by_country\",\"homepage_feed_generic_tile_all_merchants\",\"homepage_feed_max_retargeting_age_30\",\"homepage_feed_merchant_logo_in_generic_event_tile\",\"homepage_feed_mobile_all_types\",\"homepage_feed_new_expiring_offers_on\",\"homepage_feed_paginate_head_response\",\"homepage_feed_service_migration\",\"mobile_ext_homepage_feed_service_migration\",\"wb_mobile_homepage_feed_service_migration\"]",
      "page": ""
    }
  },
  "hasVisitedDomain": false
}
```

### 2. PRODUCT Model Output

```json
{
  "id": "F6K7XGSNWR",
  "title": "Whirlpool W10165294RB 15-Inch Plastic Compactor Ba, Pack of 60",
  "description": "",
  "url": "https://capitaloneshopping.com/p/whirlpool-w-10165294-rb-15-inch-/F6K7XGSNWR",
  "createdAt": "2025-05-02T03:53:38.099Z",
  "userHasPrime": false,
  "originTotal": 4800,
  "originSubtotal": 4434,
  "originTax": 366,
  "originShipping": 0,
  "matchTotal": null,
  "savings": 0,
  "primaryImageUrl": "https://i.capitaloneshopping.com/czRlNmI5ZkZhTTdCMUE0NXkxam5Ib3Vyb1JzLVdTb1VwYV...",
  "images": [
    "https://i.capitaloneshopping.com/czRlNmI5ZkZhTTdCMUE0NXkxam5Ib3Vyb1J...",
    "https://i.capitaloneshopping.com/c3VPazhaMml4RDB4OUk3MVh1YkFoa1VmY..."
  ],
  "brand": "Whirlpool",
  "categories": [
    {
      "isRoot": true,
      "name": "Appliances",
      "id": "QDZE5755",
      "slug": "appliances"
    }
  ],
  "stats": {
    "viewCount": 56,
    "viewCount30": 238
  },
  "specs": [
    {
      "name": "Batteries Required?",
      "value": "No",
      "section": "Product information"
    },
    {
      "name": "Color",
      "value": "white",
      "section": "Product information"
    },
    {
      "name": "Item Package Quantity",
      "value": "1",
      "section": "Product information"
    }
  ],
  "vendor": {
    "sku": "B001U0OJ7O",
    "vendor": "amazon.com",
    "vendorName": "Amazon",
    "url": "https://amazon.com/dp/B001U0OJ7O"
  },
  "variants": {
    "select": null,
    "images": [
      {
        "cpid": "5RDC2SJLDR",
        "id": "5RDC2SJLDR",
        "asin": "B001U0OJ8I",
        "url": "/p/whirlpool-w-10165296-bu-18-inch-/5RDC2SJLDR",
        "count": 1,
        "azOrderCount": 0,
        "runId": "3a4f8602-4a7e-4462-8247-a0a0578cf092",
        "product": {
          "title": "Whirlpool W10165296BU 18-Inch Plastic Compactor Bags with Odor Remover, 180-Pack",
          "image": "https://i.capitaloneshopping.com/czJXTjVPWDFkY1VmR043SkE5UzRLcEliZmstaXp",
          "options": [
            {
              "key": "Color",
              "value": "white"
            },
            {
              "key": "Size",
              "value": "180 Bags"
            }
          ],
          "breadcrumb": [
            {
              "isRoot": true,
              "name": "Appliances",
              "id": "QDZE5755",
              "slug": "appliances"
            }
          ],
          "brand": "Whirlpool",
          "sku": "B001U0OJ8I",
          "url": "https://amazon.com/dp/B001U0OJ8I",
          "vendor": "amazon.com",
          "wbpid": "amazon.com_B001U0OJ8I",
          "vendorCategory": "home improvement > major home appliances"
        },
        "savings": 4000,
        "receivedAt": "2019-10-28T00:26:53.146Z",
        "originPricing": {
          "subtotal": 19999,
          "total": 19999
        },
        "matchPricing": {
          "total": 15999
        },
        "stats": {
          "viewCount": 1,
          "viewCount30": 4
        },
        "amzFirstAvailable": "2009-03-11",
        "firstAvailableDay": "2009-03-11"
      }
    ]
  }
}
```

## Need to scrape more products?

👉 Scrape Alibaba with [Alibaba Scraper](https://apify.com/lexis-solutions/alibaba-scraper)

👉 Scrape Michaels.com with [Michaels.com Scraper](https://apify.com/lexis-solutions/michaels-scraper)

👉 Scrape BizBuySell with [BizBuySell Scraper](https://apify.com/lexis-solutions/bizubuysell)

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: https://capitaloneshopping.com/
