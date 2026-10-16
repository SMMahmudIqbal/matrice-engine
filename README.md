# MATRICE · Nutritional Specification Engine & FDA Claim Studio

An interactive, high-precision food engineering and nutrition intelligence suite. Built strictly against the United States Food and Drug Administration (FDA) modernized 2016 label guidelines (**21 CFR § 101.9**) and statutory nutrient content claim regulations (**21 CFR § 101 Subpart D**).

Designed with the **Premium Fluidity / Organic Intelligence** design system, combining editorial elegance (*Playfair Display*), technical precision (*JetBrains Mono*), and legible structure (*Inter*).

---

## Key Features

1. **Live Overview & Formulation Intelligence Cockpit (Real-time Analytics):**
   - **Atwater Caloric Energy Split Meter:** Live segmented progress visualization showing % of calories and exact kcal contributions from Protein (4 kcal/g), Fat (9 kcal/g), and Carbohydrates (4 kcal/g).
   - **Protein-to-Calorie Satiety Density:** Real-time calculation of grams of protein per 100 kcal, categorized into High Performance, Balanced, or Low Protein.
   - **Net Carbohydrates Tracker:** Calculates `Total Carbs - Dietary Fiber` per serving instantly.
   - **Added Sugar Caloric Share:** Tracks % of total calories coming from Added Sugars against the WHO & FDA <10% benchmark.
   - **FDA FASTER Act Major 9 Allergen Radar:** Automatically audits every ingredient in your recipe deck against Milk, Eggs, Peanuts, Tree Nuts, Fish, Crustacean Shellfish, Wheat, Soy, and Sesame.
   - **Primary Nutritional Drivers (Top Contributors):** Interactive toggle pills (`[Calories]`, `[Protein]`, `[Sodium]`, `[Sugars]`) showing live ranked bars of which ingredients drive each nutrient.

2. **Pixel-Perfect FDA 2016 Label Standard:**
   - Accurate 2016 formatting with prominent calorie typography.
   - Dual-column Daily Values (`% DV`) based on updated 2,000 kcal diet benchmarks.
   - Mandated modern micronutrient reporting: Vitamin D (mcg), Calcium (mg), Iron (mg), and Potassium (mg).
   - Indented lines for Saturated Fat, Trans Fat, Dietary Fiber, and Added Sugars.

2. **21 CFR Regulatory Claim Intelligence Engine:**
   - **Protein Claims (21 CFR § 101.54):** Evaluates "Excellent source of Protein" (≥ 20% DV) vs. "Good source of Protein" (10–19% DV).
   - **Fiber Claims (21 CFR § 101.54):** Evaluates "High Fiber" (≥ 20% DV) vs. "Good source of Fiber" (10–19% DV).
   - **Sodium Claims (21 CFR § 101.61):** Flags "Sodium Free" (< 5mg), "Very Low Sodium" (≤ 35mg), and "Low Sodium" (≤ 140mg per RACC).
   - **Fat & Saturated Fat (21 CFR § 101.62):** Flags "Fat Free" (< 0.5g), "Low Fat" (≤ 3g), and "Low Saturated Fat".
   - **Sugars (21 CFR § 101.60):** Verifies "No Added Sugars" and "Sugar Free".
   - **Disqualifying Nutrient Disclosures (21 CFR § 101.13(h)):** Automatically flags if positive marketing claims trigger mandatory front-of-pack disclosure statements due to high sodium, saturated fat, or cholesterol.

3. **USDA FoodData Verified Ingredients & Real-time Bill of Materials:**
   - Pre-loaded with staple food ingredients (Rolled Oats, Pea Protein, Whey Isolate, Almond Butter, Chia Seeds, Medjool Dates, Spinach Powder, Blueberries, Olive Oil, etc.).
   - Instant calculation of batch yields, serving counts, and caloric density (kcal/100g).

4. **1-Click Industrial Presets:**
   - *Clean-Label Protein Energy Bar*
   - *Botanical Low-Sodium Bone Broth*
   - *Wild Blueberry & Flax Clusters*
   - *Keto Avocado Green Elixir*

5. **Print & Export Ready:**
   - Instant print-to-PDF stylesheet formatting for clean packaging proof sheets.

---

## Quick Start

Open `index.html` in any modern web browser:

```bash
# On Windows PowerShell:
Start-Process "index.html"
```

No dependencies, build steps, or server installations required.

---

*Developed by S. M. Mahmud Iqbal*
