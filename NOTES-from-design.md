# Notes from the design canvas

These are the notes that sit next to the pages on the design canvas.

## DEVELOPER: Areas section (map + local SEO)

1. AREA LINKS: every area chip links to its own page, e.g. /locksmith-stratford, /locksmith-hackney, /locksmith-walthamstow. Each page needs unique local content (not copies with the name swapped), a click-to-call button, a few local reviews or job photos, and links back to /areas and the service pages. 'View all areas we cover' goes to /areas (the hub that lists every area).

2. TITLES: e.g. 'Locksmith in Stratford, E15 | 24/7 | East London Locksmith Ltd'. Area name in the H1 and meta description.

3. SCHEMA (JSON-LD, sitewide): @type Locksmith, name, telephone 07958033395, no street address (service-area business), openingHours Mo-Su 00:00-23:59, areaServed = the six boroughs and the areas listed here.

4. MAP: keep this map image (WebP, width/height set, lazy-loaded) or swap for a live Google Map.
Google Maps Embed API:
<iframe src="https://www.google.com/maps/embed/v1/place?key=YOUR_API_KEY&q=East+London+Locksmith+Ltd" width="100%" height="100%" style="border:0" loading="lazy" referrerpolicy="no-referrer-when-downgrade" title="East London Locksmith Ltd on Google Maps"></iframe>
Load it only when the section scrolls into view, to protect page speed. Restrict the API key to the website's domain.

5. CONSISTENCY: business name, address, phone and areas must match the Google Business Profile exactly. Same on mobile.

## OWNER / DEVELOPER: Instant estimate (homes and businesses)

1. PRICES are Zahid's supplied and fitted starting prices (November 2026). Lockouts, business lockouts, shutters, master key and access control are priced on the phone or after a visit.
Home (inc VAT): Locked out, Lock change, Lock repair, Snapped key, Break-in repair, Anti-snap upgrade. Composite door adds a set amount, Right now adds the out-of-hours amount, Book a time takes a little off.
Business (per door, + VAT): Tenant changeover, Eviction lock change, Business lockout, Shutter or door repair. Master key system, Access control and anything over 20 doors show 'Priced after a site visit' instead of a price.

2. CONFIRM WITH THE OWNER before launch: VAT registered (home prices shown inc VAT, business ex VAT), monthly invoicing on account, PO numbers on invoices, arranging tenant access, key records for master key systems, shutter and access control work. Remove any line that is not true.

3. LEADS: the business form (name and company, email, phone) plus the answers and postcode should be emailed to info@eastlondonlocksmith.co.uk and/or sent to the CRM. Track 'See my price', 'Request written quote' and every tel: click as conversions in GA4 and Google Ads.

4. SEO: H2 'Know the price before we arrive' plus the FAQ 'How much does a locksmith cost in East London?' target price searches. Add FAQPage schema. Build /commercial-locksmith and /landlord-locksmith pages and link the business tab's left-hand list to them. Postcodes outside E, EC, IG and RM should show 'call us to check' instead of a price.

## DEVELOPER: 'Get a free quote' pop-up and postcode checks

1. Every 'Get a free quote' button on the homepage opens the same pop-up form (header, banner result, planned work card, bottom call strip). On the live site use one centred modal fixed to the screen, with focus moved into the form and Esc to close. On the desktop canvas it opens next to the button that was clicked; on the mobile frame it covers the screen.

2. Fields: name, phone, postcode, email (optional), service (Locked out, Lock change, Lock repair, Door repair, Broken key, Lost keys, Boarding up, Eviction, Commercial locksmith, Security upgrade, Something else), when, and a message. Name, phone and postcode are required: show an inline error under any empty field.

3. On submit: email the request to info@eastlondonlocksmith.co.uk and send an instant SMS or WhatsApp alert to the on-call locksmith, so the promise 'One of our locksmiths will call you back in a couple of minutes' is kept. Track the submit as a conversion in GA4 and Google Ads.

4. The postcode check in the areas section answers in place (covered or just outside) and never scrolls the page. Same rule as the banner checker: E, EC, IG and RM postcodes are covered; anything else shows 'just outside our usual area' with the phone number.

## OWNER / DEVELOPER: Clearpay and Klarna

1. Shown in: the homepage strip under the banner ('Pay your way'), the footer ('We accept'), and an FAQ on the homepage and Services page.

2. Both need an active merchant account before launch. Swap the coloured text labels for the official Clearpay and Klarna badges from each merchant portal, and use their approved wording.

3. Keep the line '18+, T&Cs apply.' next to any mention of paying later, as both providers require a credit warning. Do not promise a specific number of payments until the account terms are confirmed (Clearpay is usually 4, Klarna usually 3).

4. If pay-later is only offered above a minimum job value, add it to the FAQ answer.

## OWNER: About and Contact pages

1. MLA: the About page links to the MLA 'Find a locksmith' directory. Replace it with the direct link to your own MLA listing, and add the official MLA logo.
2. Name and photo: add the locksmith's name and a real photo to the 'You speak to the locksmith' card if you are happy to.
3. Contact form: same as the quote pop-up. Requests go to info@eastlondonlocksmith.co.uk plus an instant text to the on-call locksmith, so the 'call you back in a couple of minutes' promise is kept.
4. Contact details must match Google Business Profile exactly: East London Locksmith Ltd, 07958 033395, info@eastlondonlocksmith.co.uk, no street address (service-area business).

## OWNER: what will make this look like a real business

1. PHOTOS. Replace the rendered images with real ones: Zahid at work, his tools, a few finished jobs. There is no van, so the van photos have been replaced with a locksmith at work and a map of the area we cover. The current gold lock render looks generated, and the small door photos are too low resolution for the Services page. Real photos are the biggest single change you can make.

2. A NAME AND A FACE. Customers already name Zahid in their Google reviews. With his OK, add his name and a real photo to the About page and the 'You speak to the locksmith' card.

3. ACCREDITATIONS. MLA membership is now shown (homepage strip, footer). Send the MLA membership number and link it to the MLA 'Find a locksmith' listing; use the official MLA logo from the member pack. Add DBS, Checkatrade or Which? only if held.

4. REVIEWS. Removed, because we have no access to the old Google account. Once the new Google Business Profile has reviews, add them back with a live widget.

5. NO SHOP ADDRESS. The Stratford shop has closed, so the site no longer shows a street address, directions or a workshop pin. Set the Google Business Profile 'East London Locksmith Ltd' up as a service-area business (address hidden, the six boroughs as service areas) so the website and Google match. The About text still says 'our own workshop in E12': keep it only if that workshop is real and open.

6. KEEP IT CONSISTENT. Same phone number (07958 033395) and the same 30 to 60 minute promise on every page and listing.

## HOW THE SERVICE PAGES WORK (BUILT FROM RESEARCH INTO 86 UK LOCKSMITH PAGES)

1. FAULT FINDER: what you notice, the usual cause, what we do. The best uPVC and repair pages lead with symptoms, and customers search by symptom.
2. QUICK ANSWER: the main question each page should win in Google, answered in two or three sentences near the top.
3. A GUIDE ONLY THAT PAGE HAS: ID checklist (emergency), new keys vs cylinder vs lock (lockouts), stuck inside (locked inside), insurance pack (boarding up), the first hour (after burglary), lock care (repairs), 30-second front door check (lock changes), door or lock repair (door repairs), how to measure a cylinder (uPVC), viewer, chain or limiter (security), sample report (survey), keypad fixes (safes), eviction day (landlords), master key systems (commercial).
4. MORE FAQs aimed at Google's 'People also ask', plus a checked-by line and sources (Secured by Design, Victim Support, police, GOV.UK, MLA).
5. KEYWORDS: service pages target the service plus 'East London'. Borough names belong to the area pages, so the two never compete.

FOR THE OWNER TO CONFIRM BEFORE LAUNCH
- Emergency: we check ID inside if documents are locked in, and accept a landlord or agent confirming the tenant.
- Boarding up: photos before and after, a written job report and a quote for the permanent repair (already on the site, please confirm).
- Security upgrades: door limiters and letterbox guards are fitted.
- Security survey: a written report with a priority and price for each item, usually under an hour.
- Safes: we ask for proof of ownership. Confirm safe work is still offered.
- Landlords: attending evictions with bailiffs and HCEOs, logging keys, PO numbers and agent invoicing.
- Commercial: master key systems, panic bars and fire exit hardware, business accounts.
- Repairs: common parts carried in the van, old parts shown to the customer.
- Reviews and the Google rating have been removed: we do not have access to that Google account. When the new Google Business Profile has reviews, add a live reviews widget in place of the 'Quality locks, not cheap imports' section.
- Prices are Zahid's all-inclusive supplied and fitted prices (November 2026). There is no van, so there are no van photos or van mentions.
- IMPORTANT: research found eastlondonlocksmith.co.uk trading as 'East London Locksmith Services Ltd' with different phone numbers. Check who owns that domain before using info@eastlondonlocksmith.co.uk on the site.

DEVELOPER: URLs /services/<name>. Use the title and meta from each yellow note. Add Service, FAQPage and BreadcrumbList schema. Keep the 'Checked' date current.

## HOW THE AREA PAGES WORK (NO KEYWORD CANNIBALISATION)

1. One keyword per page. Each page targets "locksmith in" its own area and only its own neighbourhoods. No two area pages claim the same place. The yellow note under each page has its keyword, title tag and meta description.
2. Shared postcodes are split by neighbourhood: E15 and E20 belong to Stratford (the Newham page links to it), Bethnal Green (E2) to Tower Hamlets and Haggerston to Hackney, Leytonstone (E11) to Waltham Forest and Wanstead to Redbridge.
3. Every page has its own local guide: shared houses (Newham), fire doors in blocks (Tower Hamlets), converted houses (Hackney), Warner homes and conservation areas (Waltham Forest), whole-house security (Redbridge), Becontree and Barking Riverside (Barking and Dagenham), new-build flats (Stratford). Plus its own FAQs, the jobs that area calls us for most, service order and the council's licensing rules. Reviews are removed until the new Google profile has its own.
4. Service pages should target the service only, with no borough in the title. The homepage targets "locksmith East London". Area pages link to services but do not try to rank for them.
5. Stratford is the template for neighbourhood pages. Only add another (Forest Gate, Walthamstow, Bow) when there are local reviews and jobs for it, and then take that place out of its borough page's title and intro, as we did for Stratford.
6. Sources: Census 2021 (Newham renting, Tower Hamlets flats, Stratford ward), Fire Safety (England) Regulations 2022, RIBA on Becontree, Barking Riverside planning permission (March 2026), Waltham Forest Council Article 4 directions.

DEVELOPER: URLs /areas/newham, /areas/newham/stratford. Use the title and meta description from each yellow note. Each page's canonical points at itself. Keep the business name and phone the same as the Google Business Profile.

## FOR THE OWNER TO CONFIRM

1. PRICES: Zahid's all-inclusive supplied and fitted prices (November 2026). Lockouts and uPVC mechanism replacements are priced on the call.
2. TERMS: these follow the current website's terms. Three points clash with other pages and need a decision: the call-out charge of up to £89 if a job is cancelled (the old site also says 'no call-out fee'), the 6-month guarantee (the old service pages say 1 year), and payment (the old terms say cash and bank transfer, the new site says card, cash, Clearpay and Klarna).
3. PRIVACY AND COOKIES: written for East London Locksmith Ltd. Ask whoever builds the site to list the real cookies, and have the owner check both pages before launch.
4. BLOG: the seven titles are the current blog's. One article is designed as the template; the other six use the same layout.
5. SAFES: the current website offers safe opening. Confirm it is still a service before this page goes live.
