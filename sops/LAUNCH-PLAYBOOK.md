# Product Launch Playbook
## How to launch a new product from scratch

This is the step-by-step process to go from factory visit to live website.
Follow this every time. Same steps. Same structure.

---

## Step 1 — Capture Product Knowledge

Talk to AI about the product. Just talk. AI writes the file.

Cover:
- What is the product?
- Main applications (what do buyers use it for?)
- Construction and materials
- Available sizes, thicknesses, dimensions
- Key advantages
- Known limitations
- Typical quality requirements
- Packaging
- Certifications available (FSC, PEFC, CE, etc.)
- Comparison with alternatives
- Target market for this launch

Save as: `knowledge/products/[product-name].md`

---

## Step 2 — Capture Factory or Company Info

Talk to AI about who is behind this product for this launch.

Cover:
- Factory name or your own company name
- Location (country, city)
- Years in business
- Production capacity
- Key certifications
- Contact person and details
- What makes this factory trustworthy
- Any limitations to mention

Save as: `products/[product-market]/brief.md`

---

## Step 3 — Define the Launch

Tell AI:
- Target market (e.g. European Union, Germany, Netherlands)
- Target buyer (e.g. kitchen manufacturers, importers, DIY retailers)
- Main application to lead with (e.g. kitchen countertops)
- Domain name (if known)
- Language (English, German, French, etc.)
- Commission or direct trade?

---

## Step 4 — Generate the Website

Ask AI:
> "Generate the product website using the knowledge file and brief."

AI produces: `products/[product-market]/index.html`

Review it. Request changes if needed.

---

## Step 5 — Deploy

1. Open GitHub Desktop
2. Review changed files
3. Write commit message (e.g. "Launch rubberwood EU site")
4. Click Commit
5. Click Push
6. Cloudflare deploys automatically

**Site is live.**

---

## Step 6 — Optional Outputs

After the website is live, ask AI to generate:
- [ ] Product brochure (PDF)
- [ ] Datasheet (1 page)
- [ ] Intro email to buyers
- [ ] Product description for directories

---

## Folder Structure Per Launch

```
products/
  [product-market]/
    brief.md        ← factory/company info + launch definition
    index.html      ← generated website
    brochure.pdf    ← optional
    datasheet.pdf   ← optional
```

---

## The Rule

One product. One market. One folder. One website.

Keep it focused. A serious buyer should feel they found a specialist.
