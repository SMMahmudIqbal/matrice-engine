# MATRICE · Nutritional Specification Engine & FDA Claim Studio

An interactive, high-precision food engineering and nutrition intelligence suite. Built strictly against the United States Food and Drug Administration (FDA) modernized 2016 label guidelines (**21 CFR § 101.9**) and statutory nutrient content claim regulations (**21 CFR § 101 Subpart D**).

🌐 **Live Deployment:** [https://fda-nutrition-label-generator.vercel.app](https://fda-nutrition-label-generator.vercel.app)  
📦 **GitHub Repository:** [https://github.com/SMMahmudIqbal/matrice-engine](https://github.com/SMMahmudIqbal/matrice-engine)

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

2. **Target Nutrition Inverse Solver (Simplex / Goal-Seek R&D Engine):**
   - Declare target nutritional outcomes per serving (e.g. Target Protein ≥ 20g, Max Added Sugar ≤ 4g, Target Energy = 230 kcal).
   - Fast coordinate-descent optimization algorithm dynamically solves for the exact ingredient gram adjustments to hit targets with minimal variance.
   - Interactive live comparison table displaying baseline vs. optimized nutritional deltas and batch weight changes.
   - One-click recipe deck synchronization.

3. **Automated FDA Ingredients Statement Generator (21 CFR § 101.4):**
   - Automatically sorts all ingredients in strict descending order of predominance by batch weight.
   - Expands compound sub-ingredients according to statutory guidelines (e.g., `Dark Chocolate (Cacao Mass, Cane Sugar, Cocoa Butter, Vanilla Extract)`).
   - Generates the statutory bold allergen statement (`CONTAINS: MILK, TREE NUTS (ALMOND)`) under FALCPA and the FASTER Act.
   - One-click legal text copying for packaging designers.

4. **Pixel-Perfect FDA 2016 Label Standard:**
   - Accurate 2016 formatting with prominent calorie typography.
   - Dual-column Daily Values (`% DV`) based on updated 2,000 kcal diet benchmarks.
   - Mandated modern micronutrient reporting: Vitamin D (mcg), Calcium (mg), Iron (mg), and Potassium (mg).
   - Indented lines for Saturated Fat, Trans Fat, Dietary Fiber, and Added Sugars.

5. **21 CFR Regulatory Claim Intelligence Engine:**
   - **Protein Claims (21 CFR § 101.54):** Evaluates "Excellent source of Protein" (≥ 20% DV) vs. "Good source of Protein" (10–19% DV).
   - **Fiber Claims (21 CFR § 101.54):** Evaluates "High Fiber" (≥ 20% DV) vs. "Good source of Fiber" (10–19% DV).
   - **Sodium Claims (21 CFR § 101.61):** Flags "Sodium Free" (< 5mg), "Very Low Sodium" (≤ 35mg), and "Low Sodium" (≤ 140mg per RACC).
   - **Fat & Saturated Fat (21 CFR § 101.62):** Flags "Fat Free" (< 0.5g), "Low Fat" (≤ 3g), and "Low Saturated Fat".
   - **Sugars (21 CFR § 101.60):** Verifies "No Added Sugars" and "Sugar Free".
   - **Disqualifying Nutrient Disclosures (21 CFR § 101.13(h)):** Automatically flags if positive marketing claims trigger mandatory front-of-pack disclosure statements due to high sodium, saturated fat, or cholesterol.

6. **525+ Verified Food Ingredients Database (FCTB / INFS DU / USDA FoodData):**
   - **Comprehensive Bangladeshi Food Composition Table (FCTB):** Over 400 verified local Bangladeshi ingredients sourced from the Institute of Nutrition and Food Science (INFS, University of Dhaka) and FAO.
     - *Freshwater & Marine Fishes:* Padma Ilish (fresh, fried, fish roe/caviar), Rui, Katla, Mrigal, Pabda, Chital, Shing, Magur, Deshi Koi, Tengra, Gulsha, Puti, Chanda, Batashi, Baim, Kholisha, Ayre, Boal, Roopchanda, Bagda & Galda Chingri, Shutki (Chepa, Loitta, Chhuri).
     - *Traditional Shaks & Greens:* Lal Shak, Palong Shak, Pui Shak, Kalmi Shak, Kochu Shak, Dheki Shak, Helencha, Pat Shak, Notey Shak, Shorshe Shak, Methi Shak, Mula Shak, Bathua Shak, Kochur Loti.
     - *Deshi Vegetables (Shobji):* Lau (Bottle Gourd), Chal Kumra, Potol, Jhinga, Chichinga, Korola, Deshi Uchhe, Dherosh (Okra), Round & Long Begun, Sheem & Sheem Bichi, Kochur Mukhi, Ol Kochu, Maan Kochu.
     - *Local Heritage Grains & Dals:* Chinigura Polao Rice, Kalijira, Najirshail, Miniket, Balam, Deshi Moshur Dal (Red Lentil), Roasted Moong Dal, Khesari Dal, Chhola (Deshi Chickpea), Mashkalai.
     - *Dairy, Sweets & Traditional Preparations:* Bogurar Shahi Mishti Doi, Traditional Tok Doi, Chhana, Roshogolla, Sandesh, Porabarir Chamcham, Cumillar Roshmalai, Deshi Cow Ghee (Baghabari / Pabna), Cold-Pressed Kachi Ghani Mustard Oil.
   - **Modern Global Functional Ingredients:** Whey Protein Isolate 90%, Micellar Casein, Pea Protein Isolate, Hydrolyzed Collagen, Spirulina, Ceremonial Matcha, Dutch Cocoa, Raw Cacao Nibs, MCT Oil Powder, Psyllium Husk, Allulose, Stevia Reb-A.
   - **Bilingual Fast-Search Modal:** Instant search across English and Bengali (বাংলা) script and transliteration, category filtering pills, and live per-100g nutrient inspector.

7. **1-Click Industrial & Traditional Presets:**
   - *Clean-Label Protein Energy Bar*
   - *Padma Ilish & Chinigura Khichuri Feast* (Traditional Bangladeshi Staple)
   - *Bogurar Shahi Mishti Doi* (Authentic Caramelized Sweet Yogurt)
   - *Botanical Low-Sodium Bone Broth*
   - *Wild Blueberry & Flax Clusters*
   - *Keto Avocado Green Elixir*

8. **Export Ready:**
   - High-resolution PNG and JPG export of the FDA label only (via html2canvas) — saves the label as an image file at 3x packaging-grade DPI.
   - 1-click copy of plain-text nutrition summary and FDA legal ingredient statements.

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
