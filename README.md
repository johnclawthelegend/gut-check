# 🍴 Feasting with Frank

**Check food labels, dodge reflux and IBS triggers, and cook with what you have.**

Live app: **https://johnclawthelegend.github.io/feasting-with-frank/**

## What it does

- **🔥 Acid Reflux (GERD) section** — flags ingredients that commonly trigger reflux (tomato, citrus, chocolate, mint, caffeine, alcohol, garlic/onion, spicy peppers, vinegar, high-fat ingredients, carbonation) with an explanation for each, plus a quick eat/avoid guide and reflux-friendly recipes.
- **🌀 IBS section** — a separate checker based on high-FODMAP ingredients and common gut irritants (onion, garlic, wheat, lactose, honey/HFCS, sugar alcohols, inulin/chicory root, certain fruits, legumes, cashews…), plus a low-FODMAP eat/avoid guide and low-FODMAP recipes.
- **🧺 Cook from what you have** — type the ingredients in your kitchen and get condition-safe recipes ranked by how many of your ingredients they use, with anything you're missing listed. Recipes you can make right now are marked 🏆.
- **🍽️ Recipes** — 7 gentle, trigger-free recipes per condition so you know what you *can* cook, not just what to skip.

Each ingredient is rated **Avoid / Caution / Likely OK** with a one-line reason. Sub-ingredients in parentheses are checked too.

## How it works

Pure static HTML/CSS/JS — no build step, no backend, no tracking. All analysis happens in your browser; nothing you paste ever leaves your device.

## Run locally

Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8080
# → http://localhost:8080
```

## Disclaimer

This is an educational tool, **not medical advice**. Trigger lists reflect *commonly* reported triggers (and Monash-style FODMAP categories for IBS), but individual tolerance and portion size vary a lot, and umbrella terms like "natural flavors" can hide triggers. Talk to a doctor or registered dietitian before making major dietary changes.
