# Purchase Object Imagery Test — Reference Data

## Source
- **Consumer Study:** Discover Consumer Insights Rewards Category Image Study (n=500+, 3/17/2023)
- **Sales Data:** Discover MCC Sales Mix (Category Rollup)
- **Spend Sentiment:** McKinsey ConsumerWise Global Sentiment Survey (n=4,008, Feb 2026)
- **Scope:** 12 categories (Digital Wallets excluded from this matrix)
- **Methodology:** Unaided word association, association ratings, forced choice (keywords + images)

---

## Project Status

### Completed
- Sourced and organized object imagery across 12 categories from Miro board
- Built interactive HTML review tool with category navigation, image grid, and lightbox
- Added spend classification (Essential / Semi-discretionary / Discretionary) based on McKinsey Q1 2026 data
- Mapped force choice winners and other top choices from study to image columns
- Winner images prioritized (first in column, column moved to left)
- Added research summary modal with strategic implications
- Deployed to GitHub Pages with password protection (atg2026)
- **Live URL:** https://simonpeterforeman-prog.github.io/ATGImagery/
- **Repo:** https://github.com/simonpeterforeman-prog/ATGImagery (public)

### To Do
- **Seasonal Quarters (Q1–Q4):** Travel category needs seasonal image rotation. Folders exist (Q1, Q2, Q3, Q4) but are not yet wired into the review tool. Imagery suggestions are directional only — no consumer test data exists for Travel.
- **Image selection UI:** Add ability to select/flag preferred images per category for stimulus creation
- **Stimulus generation:** Convert selected images into final stimuli format
- **Empty subcategories:** Some subcategory folders are still empty and need images added

---

## Spend Classification (McKinsey Q1 2026)

| Classification | Categories | Key Insight |
|---|---|---|
| **Essential** | Grocery Stores, Gas & EV, Telecom Utilities | Spending holds steady; consumers maintain essentials through spring |
| **Semi-discretionary** | Walmart, Amazon, Target, Drug Stores, Discount Stores | Mixed signals; some pullback in toys/beauty but mostly stable |
| **Discretionary** | Restaurants, Travel, Department Stores, Home Improvement | Most sensitive to pullback; bright spots in home improvement (+11pts) and domestic flights (+5pts) |

---

## Guiding Principles

1. **Everyday > Aspirational:** Consumers preferred imagery of frequently purchased, everyday products over big-ticket or niche items.
2. **Clothes = Universal Shorthand:** "Clothes" appeared as top-of-mind across Walmart (48%), Target (51%), TJ Maxx (60%), and Amazon (21%).
3. **Category-Core Imagery Wins:** Gas pump (95%), toilet paper (76%), wifi (76%), candy (74%) — the most literal representation dominates.
4. **Seasonal Relevancy:** Study recommends considering seasonal context when selecting product imagery. Travel is the natural rotation candidate.
5. **Avoid Premium/Niche:** Electronics like AirPods and Bluetooth speakers tested poorly for mass-market retailers. Dumplings underperformed for restaurants.

---

## Categories

### Amazon / Walmart / Target
- **MCC Sales Mix:** 14.1% (shared across all three)
- **MCC Rollup:** AMZ/WMT/TGT

#### Walmart
- **Force Choice Winner:** Toilet paper (76%)
- **Top Image Objects:** Clothes, toilet paper
- **Avoid:** AirPods, Bluetooth speaker, watch (all <17% image association)
- **Alt Keywords:** Water bottle (12%), notebook (5%)
- **Top of Mind (unaided):** Clothes (48%), Food (32%), Groceries (29%), Electronics (15%), Toys (14%)
- **Image Test Status:** Images tested (AirPods, speakers, watch — all scored low)
- **Spend:** Semi-discretionary
- **Image Types:** toilet paper, tech, grocery, clothes, toys, walmart box, school, pet, baby

#### Amazon
- **Force Choice Winner:** Cell phone charger (32%)
- **Top Image Objects:** Clothes, cell phone charger, headphones
- **Avoid:** Stand mixer (8% force choice, 30% image association)
- **Alt Keywords:** Headphones (31%), robot vacuum (29%)
- **Top of Mind (unaided):** Clothes (21%), Electronics (13%), Toys (13%), Shoes (11%)
- **Image Test Status:** Images tested (robot vacuum 42% vs stand mixer 30%)
- **Spend:** Semi-discretionary
- **Image Types:** electronics, clothes, box, groceries, toys, beauty, amazon products

#### Target
- **Force Choice Winner:** Dish soap (35%)
- **Top Image Objects:** Clothes, dish soap
- **Avoid:** N/A (all options viable)
- **Alt Keywords:** Shoes (27%), stand mixer (20%), purse (18%)
- **Top of Mind (unaided):** Clothes (51%), Food/Groceries (38%), Toys (16%), Electronics (14%), Shoes (7%)
- **Image Test Status:** Images tested (dish soap 45%, stand mixer 33%, purse 32%)
- **Spend:** Semi-discretionary
- **Image Types:** cleaning, clothing, home decor, grocery, kitchen, pet

---

### Restaurants
- **MCC Sales Mix:** 9.2%
- **MCC Rollup:** Total Retail
- **Force Choice Winner:** Burger (51%)
- **Top Image Objects:** Burger, salad, sandwich & soda
- **Avoid:** Dumplings (5% force choice, 38% image association)
- **Alt Keywords:** Salad (23%), chicken wings (11%), chicken sandwich (6%), tacos (5%)
- **Spend:** Discretionary
- **Image Types:** fast casual, salad bowls, drinks, table setting, sit down, sweets, coffee matcha, pizza, trendy

---

### Grocery Stores (Supermarkets)
- **MCC Sales Mix:** 9.0%
- **MCC Rollup:** Total Everyday
- **Force Choice Winner:** Milk (54%)
- **Top Image Objects:** Milk, grocery bag, produce items (oranges, avocado)
- **Avoid:** Breakfast sandwich (16% image association, 1% force choice)
- **Alt Keywords:** Grocery bag (40%), oranges (2%), avocados (2%)
- **Spend:** Essential
- **Image Types:** dairy, grocery bag, produce, meat, paper products, detergent, baby

---

### Travel
- **MCC Sales Mix:** 6.0%
- **MCC Rollup:** Travel (standalone)
- **Force Choice Winner:** Not tested
- **Top Image Objects (directional):**
  - Q1 (Jan–Mar): Ski gear, winter travel, cold-weather accessories
  - Q2 (Apr–Jun): Beach gear, summer travel, sunglasses
  - Q3 (Jul–Sep): Back-to-school travel, fall getaways
  - Q4 (Oct–Dec): Holiday travel, gift-wrapped luggage, winter destinations
- **Avoid:** TBD — no consumer test data
- **Spend:** Discretionary
- **Image Types:** suitcase, passport, plane tickets, summer vacation, winter vacation, backpack, car keys, camera
- **Status:** Seasonal Q1–Q4 folders exist but are NOT yet wired into the review tool. Needs implementation.

---

### Gas & EV (formerly Gas Stations)
- **MCC Sales Mix:** 4.5%
- **MCC Rollup:** Total Everyday
- **Force Choice Winner:** Gas pump (95%)
- **Top Image Objects:** Gas pump, fuel gauge
- **Avoid:** N/A (car tire only 22% image association)
- **Alt Keywords:** Fuel gauge (2%), coffee, car tire (1%)
- **Spend:** Essential
- **Image Types:** nozzle charger, signifiers, snacks, drinks
- **Note:** Renamed from "Gas Stations" to "Gas & EV". Subcategories split: nozzle/charger (gas pump + EV charger) and signifiers (fuel gauge, keys).

---

### Department Stores (formerly Clothing Department Stores)
- **MCC Sales Mix:** 4.5%
- **MCC Rollup:** Total Retail
- **Force Choice Winner:** Clothes (89%) — tested under TJ Maxx
- **Top Image Objects:** Clothes (universal winner across multiple categories)
- **Avoid:** N/A
- **Alt Keywords:** Candles (7%), photo frames (3%)
- **Spend:** Discretionary
- **Image Types:** clothes, candles, accessories, photo frames
- **Note:** Renamed from "Clothing Department Stores". TJ Maxx was the proxy category in the study. Includes HomeGoods/Marshalls/Ross.

---

### Telecom & Utilities
- **MCC Sales Mix:** 4.4%
- **MCC Rollup:** Total Services
- **Force Choice Winner:** Wifi (76%)
- **Top Image Objects:** TV, wifi symbol/router
- **Avoid:** Laptop (weaker association, 4% force choice)
- **Alt Keywords:** TV (20%), laptop (4%)
- **Spend:** Essential
- **Image Types:** wifi, tv, electric, bills, electronics

---

### Home Improvement
- **MCC Sales Mix:** 2.9%
- **MCC Rollup:** Total Retail
- **Force Choice Winner:** Paint (41%)
- **Top Image Objects:** Paint, toolbox
- **Avoid:** N/A (all options strong: 73–87% association)
- **Alt Keywords:** Toolbox (30%), hammer (16%), drill (12%)
- **Spend:** Discretionary
- **Image Types:** paint, tools, wood, gardening

---

### Discount Stores
- **MCC Sales Mix:** 2.1%
- **MCC Rollup:** Total Everyday (Drug & Discount Stores combined with Dollar Stores)
- **Force Choice Winner:** Candy (74%) — tested under Dollar Stores
- **Top Image Objects:** Candy, snacks, pens
- **Avoid:** Hand sanitizer (weakest association)
- **Alt Keywords:** Pens (16%), hand sanitizer (10%)
- **Spend:** Semi-discretionary
- **Image Types:** snacks, toys, school, party, electronics

---

### Drug Stores
- **MCC Sales Mix:** 2.1%
- **Force Choice Winner:** N/A
- **Spend:** Semi-discretionary
- **Image Types:** pharmacy, groceries, snacks, skin care
- **Note:** Not directly tested in the original study. Drug Stores category was added based on MCC codes.

---

## Data Gaps & Notes

| Gap | Detail |
|-----|--------|
| Travel | No consumer test data at all. Seasonal rotation suggestions are directional. Q1–Q4 folders need to be wired into review tool. |
| Clothing Stores | Keyword-only testing via TJ Maxx proxy. No image-level validation. |
| Telecom & Utilities | Keyword-only testing. No images tested. |
| Home Improvement | Keyword-only testing. No images tested. |
| Discount Stores | Keyword-only testing via Dollar Stores proxy. No images tested. |
| Drug Stores | Not tested in original study. |
| Hard Lines (8.5% mix) | Not covered in the image study. No test data. |
| Other Retailers (8.1% mix) | Not covered in the image study. No test data. |
| Other Services (10.0% mix) | Not covered in the image study. No test data. |
| Wholesale Clubs (1.4% mix) | Not covered in the image study. No test data. |

## Folder Structure
```
ATG Imagery/
├── index.html              ← Review tool (GitHub Pages)
├── purchase-object-imagery-reference.md
├── purchase_object_imagery_matrix.xlsx
├── Walmart/
│   ├── toilet paper/
│   ├── tech/
│   ├── grocery/
│   ├── clothes/
│   ├── toys/
│   ├── walmart box/
│   ├── school/
│   ├── pet/
│   └── baby/
├── Amazon/
├── Target/
├── Restaurants/
├── Grocery Stores/
├── Travel/
├── Gas & EV/
├── Department Stores/
├── Telecom Utilities/
├── Home Improvement/
├── Discount Stores/
├── Drug Stores/
├── Q1/ (seasonal — not yet wired)
├── Q2/ (seasonal — not yet wired)
├── Q3/ (seasonal — not yet wired)
└── Q4/ (seasonal — not yet wired)
```
