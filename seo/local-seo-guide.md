# Local SEO Playbook — Mesquite Manufacturing

**Business:** Mesquite Manufacturing  
**Primary Service Area:** Mesquite, TX and Dallas–Fort Worth metroplex  
**Target:** Rank in Google local pack for CNC machining searches in DFW

---

## Canonical NAP (Name / Address / Phone)

Use this EXACT format on every directory, citation, and website page:

```
Name:    Mesquite Manufacturing
Address: [Full street address, Mesquite, TX ZIP]
Phone:   [Primary phone number]
Website: https://mesquitemanufacturing.com
```

⚠️ **Critical:** Even minor inconsistencies (abbreviations, suite formatting) confuse Google.
- Always spell out "Street" vs "St" — pick one and stick to it
- Always include same phone format: (XXX) XXX-XXXX or XXX-XXX-XXXX — pick one
- Always use the same suite/unit format if applicable

---

## Google Business Profile — Full Optimization Checklist

### Setup / Basics
- [ ] Claim and verify your GBP listing at business.google.com
- [ ] Business name: **Mesquite Manufacturing** (no keyword stuffing)
- [ ] Category (Primary): **Machine Shop** or **Manufacturing Plant**
- [ ] Additional categories: CNC Machining, Metal Fabricator, 3D Printing Service, Prototype Development
- [ ] Address: Complete and verified
- [ ] Phone: Primary business number
- [ ] Website: https://mesquitemanufacturing.com
- [ ] Service area: Add cities — Mesquite, Dallas, Garland, Plano, Irving, Arlington, Fort Worth, Grand Prairie, Richardson, Frisco

### Hours
- [ ] Set accurate hours (24/7 if genuinely available)
- [ ] Add special hours for holidays
- [ ] Enable "Open 24/7" if accurate to your model

### Description (750 chars)
```
Mesquite Manufacturing is a precision CNC machining and milling company serving the Dallas–Fort Worth area and beyond. We specialize in fourth axis CNC machining, prototype development, custom assembly, and 3D printing — delivering tolerances to ±0.001″ for metals, plastics, and composites. Available 24/7. Free RFQ online at mesquitemanufacturing.com.
```

### Photos (ongoing)
- [ ] Exterior of facility (if applicable)
- [ ] Interior shop floor / machines
- [ ] Finished parts (close-up, clean)
- [ ] Team members working
- [ ] CNC machines in operation
- [ ] Logo image
- [ ] Cover photo (modern, professional)
- Add 2–3 new photos monthly for freshness signals

### Products/Services
Add each service with description:
- Precision CNC Machining & Milling
- Prototype Development
- Custom Assembly
- 3D Printing / Additive Manufacturing

### Posts (ongoing — 1–2x per week)
Use GBP posts for:
- New blog content (share link)
- Completed project spotlights (no confidential client info)
- Industry news relevance
- Seasonal/holiday availability
- RFQ calls to action

### Q&A Section
Pre-populate with your own questions and answers:
- "What materials do you machine?" → Metals, plastics, composites including aluminum, stainless steel, titanium, Delrin, PEEK
- "What tolerances can you hold?" → ±0.001″ on CNC machined parts
- "Do you offer rush turnaround?" → Yes, 24/7 availability
- "What is your RFQ process?" → Submit online, receive response within 24 hours
- "What areas do you serve?" → Mesquite, Dallas, Fort Worth, all of Texas, nationwide

### Reviews Strategy
- [ ] Ask satisfied clients for reviews via email follow-up
- [ ] Add GBP review link to email signature
- [ ] Add "Leave us a review" CTA on website footer
- [ ] Respond to every review (positive and negative) within 48 hours
- [ ] Goal: 10+ reviews at 4.5+ stars within 6 months

---

## Bing Places Optimization

- Sync from GBP (easiest path) or create manually
- Verify via postcard or phone
- Match all NAP data exactly
- Upload same photos as GBP

---

## Apple Maps Connect

- Register at mapsconnect.apple.com
- Often forgotten — iOS Safari users default to Apple Maps
- Add business hours, photos, website, phone

---

## Local Citation Priority List

### Tier 1 — Do First (biggest impact)
1. Google Business Profile ← #1 priority
2. Bing Places
3. Apple Maps Connect
4. Yelp for Business
5. Facebook Business Page
6. Foursquare for Business (powers many other aggregators)
7. LinkedIn Company Page

### Tier 2 — Core Citations
8. Yellow Pages (yp.com)
9. Manta
10. Hotfrog
11. Superpages
12. MapQuest

### Tier 3 — Industry-Specific
13. ThomasNet
14. Mfg.com
15. Maker's Row
16. IndustryNet

### Tier 4 — Local Texas
17. Mesquite Chamber of Commerce
18. Dallas Regional Chamber
19. Dallas BBB

---

## Review Acquisition Strategy

### The Ask (timing is everything)
- Ask immediately after: project delivery, positive client feedback, repeat order
- Don't ask during disputes or delays

### Email Template — Review Request
```
Subject: How did we do? (1-minute)

Hi [Name],

Thanks for choosing Mesquite Manufacturing for your recent [project]. We hope the parts met your expectations.

If you have a moment, we'd love an honest review on Google — it helps other engineers and buyers find us when they need precision machining.

[LEAVE A GOOGLE REVIEW →]  ← link directly to GBP review form

Takes about 60 seconds. No account needed if you have Gmail.

Thanks again,
[Your name]
Mesquite Manufacturing
```

### Incentive (careful — Google TOS)
- Never offer discounts/gifts for reviews (Google ToS violation)
- You CAN say "it means a lot to us" — purely genuine ask

---

## Geo-Targeted Content Suggestions

Create location-specific service pages to rank for city-level searches:

### Pages to Create
- `/locations/dallas-cnc-machining` — "CNC Machining in Dallas, TX"
- `/locations/fort-worth-cnc-machining` — "CNC Machining Near Fort Worth, TX"
- `/locations/plano-cnc-machining` — "CNC Machining Services for Plano, TX Companies"
- `/locations/irving-cnc-machining`
- `/locations/garland-cnc-machining`
- `/texas-cnc-machining` — State-level hub page

### Location Page Template
- H1: "[Service] in [City], TX | Mesquite Manufacturing"
- 300–500 words of genuinely unique content per city
- Mention DFW area, proximity to the city
- Include map embed (GBP map)
- Same RFQ CTA

---

## Competitor Analysis Approach

### Find Top Local Competitors
Search: `CNC machine shop Dallas`, `CNC machining Texas`, `precision machining Mesquite TX`

### For Each Competitor, Check
1. **GBP listing** — how many reviews? What categories?
2. **Backlinks** — use Ahrefs/Semrush (or free: Google "site:competitor.com")
3. **Directory listings** — where are they listed that you're not?
4. **Content** — what blog posts rank? Can you do better?
5. **Keywords** — what queries send them traffic?

### Free Tools for Research
- Google Search Console (your own site)
- Google Keyword Planner (keyword volumes)
- Ubersuggest (free tier — basic competitor data)
- Ahrefs Webmaster Tools (free for your own domain)
- MozBar browser extension (quick DA checks)

---

## Local Schema Additions

Add to homepage `<head>` (see schema-markup-additions.json for full code):

```json
{
  "@type": "ManufacturingBusiness",
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": "[your lat]",
    "longitude": "[your lng]"
  },
  "areaServed": [
    {"@type": "City", "name": "Mesquite", "sameAs": "https://en.wikipedia.org/wiki/Mesquite,_Texas"},
    {"@type": "City", "name": "Dallas"},
    {"@type": "City", "name": "Fort Worth"},
    {"@type": "State", "name": "Texas"}
  ],
  "priceRange": "$$"
}
```

---

## 30-Day Local SEO Sprint

| Week | Actions |
|---|---|
| Week 1 | Claim GBP, fully optimize it. Claim Bing Places, Apple Maps, Yelp, LinkedIn. |
| Week 2 | Submit to ThomasNet, Mfg.com, Maker's Row. Add Foursquare, Yellow Pages, Manta, Hotfrog. |
| Week 3 | Join Mesquite Chamber. Submit to Dallas BBB. Begin review request emails to past clients. |
| Week 4 | Publish first blog post. Set up Google Search Console. Start tracking rankings weekly. |
