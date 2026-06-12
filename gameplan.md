# Fitzgerald's Irish Tavern — Website Gameplan

## Client Info
- **Owner:** Sherry Kuntz
- **Business:** Fitzgerald's Irish Tavern
- **Address:** 5811 Nebraska Ave, New Port Richey, FL 34652
- **Phone:** (727) 816-9092
- **Email:** REMOVED from site per Sherry's request (phone only)
- **Facebook:** facebook.com/fitzgeraldsirishtavern
- **Instagram:** @fitzbar1 (confirm with Sherry — already on demo site)
- **Founded:** 2004
- **Relationship:** 2 blocks from Jake. Longest-running business in downtown NPR. Sherry knows all the other business owners — major referral source.

## Deal Terms
- **Build fee:** $800 (paid on completion, client satisfied)
- **Monthly hosting:** $25/mo (hosting + minor updates via Stripe subscription)
- **Blog automation (optional):** offer after launch — same $125/mo package as other clients
- **Ownership:** Sherry owns her domain and all content after payment in full
- **Agreement:** Written contract required
- **Receipts:** Stripe handles invoicing and receipts automatically

## Domain & Hosting
- **Domain:** fitzgeraldstavern.com (Sherry owns it)
- **Current registrar:** GoDaddy (domaincontrol.com nameservers)
- **Transfer plan:** Transfer domain to Porkbun (Sherry's request — On Point takes possession)
- **Deploy:** Cloudflare Pages (free, fast, global CDN)
- **Current site:** GoDaddy Website Builder 8.0 — 206KB HTML, HTTP/1.1, bloated, typos in headings

## Stack
- Static HTML + Tailwind CDN
- Cloudflare Pages deploy
- Stripe: one-time $800 invoice + $25/mo recurring subscription
- No contact form — phone only per Sherry's request
- Same stack as On Point, CPW, TidyLife, Jenkins sites

## Site Structure

### Pages
- **Home (index.html)** — hero, about teaser, menu highlights, The Fitzperience, events, reviews, contact/hours footer
- **Menu (menu.html)** — full food menu with category navigation (Appetizers, Soups & Salads, Irish Favorites, Sandwiches, Char Grill, Entrees)

### Site Changes Requested by Sherry
- Add top bar with business hours
- Change "Contact" nav link to clickable phone number: (727) 816-9092
- Remove business email from footer (phone only)
- Add "More Reviews" button at bottom of reviews section → Google reviews page
- Menu changes coming (Sherry reviewing and making updates)
- Additional photos TBD (Jake will ask)
- Instagram handle TBD (confirm @fitzbar1 with Sherry)

## What We Have
- **Full demo site built** at onpoint-demos/fitzgeralds/ — dark Irish theme, Celtic knot dividers, parallax hero, bento menu highlights, The Fitzperience gallery, events section, 3 reviews, full menu page
- **Pitch sheet** (pitch-sheet.html) — 3-page print comparison doc used to land the account
- **Custom shamrock logo SVG** — traced and embedded in nav
- **Stock assets** — patio photos, interior shots in assets/ and stock/ folders
- **Hours on site:** Mon-Wed 11AM-12AM, Thu-Sat 11AM-2AM, Sun 11AM-12AM. Kitchen: 10PM Sun-Thu, midnight Fri-Sat

## Waiting on From Sherry
- [ ] Menu changes / updates
- [ ] Additional photos (interior, food, staff — Jake will ask)
- [ ] Design tweaks (Sherry reviewing demo)
- [ ] Instagram handle confirmation (@fitzbar1?)
- [ ] GoDaddy domain login (for transfer to Porkbun)
- [ ] Signed contract

## Checklist — Build Order

### Phase 1: Immediate (can do now)
- [ ] Add top bar with hours (Mon-Wed 11AM-12AM, Thu-Sat 11AM-2AM, Sun 11AM-12AM)
- [ ] Change "Contact" nav button to clickable phone link: (727) 816-9092
- [ ] Remove email from footer contact section
- [ ] Add "Read More Reviews" button below reviews → Google reviews page
- [ ] Create Stripe payment link: $800 one-time (build fee)
- [ ] Verify $25/mo hosting subscription link works (reuse Dan's)
- [ ] Create service agreement/contract
- [ ] Apply same menu.html sticky nav fix from this morning's local-only patch

### Phase 2: Waiting on Sherry
- [ ] Apply menu changes Sherry sends
- [ ] Replace stock photos with real Fitzgerald's photos (if provided)
- [ ] Apply any design tweaks Sherry requests
- [ ] Confirm/update Instagram handle

### Phase 3: Domain & Launch
- [ ] Receive GoDaddy login from Sherry
- [ ] Transfer domain to Porkbun
- [ ] Point DNS to Cloudflare
- [ ] Push site to Cloudflare Pages (GitHub repo)
- [ ] Verify SSL, HTTP/2, global CDN working
- [ ] Mobile-first QA pass
- [ ] Set up GA4
- [ ] Implement schema markup (LocalBusiness, Restaurant)
- [ ] Submit sitemap to Google Search Console

### Phase 4: Post-Launch
- [ ] Final review with Sherry
- [ ] Sherry pays $800 via Stripe
- [ ] $25/mo subscription begins
- [ ] Offer blog automation package ($125/mo)
- [ ] GBP optimization (if applicable)
- [ ] QR code for any print materials

## SEO Keywords
- Irish pub New Port Richey
- downtown New Port Richey restaurant
- Fitzgerald's tavern menu
- best fish and chips New Port Richey
- live music downtown NPR
- sports bar New Port Richey
- Irish tavern Tampa Bay

## Notes
- Strategic account — Sherry knows every business owner in downtown NPR. Her referral = pipeline.
- Negotiated down from $1K to $800 because her network value is worth more than $200
- No contact form — phone calls only. Removes the email, keeps it simple.
- Domain transfer to Porkbun (same registrar as CPW) — clean, no GoDaddy lock-in
- Demo was already built and presented — just needs tweaks, not a ground-up build
