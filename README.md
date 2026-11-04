# East London Locksmith Ltd: website design files for the developer

Design by Laser Me Out, November 2026. Phone on every page: **07958 033395**. Email: info@eastlondonlocksmith.co.uk (see "Before launch").

## What is in this folder

- `desktop/`: every page as designed at 1440px wide.
- `mobile/`: every page as designed at 390px wide.
- `images/`: every image the pages use, already linked.
- `NOTES-from-design.md`: the developer and owner notes from the design canvas.

Open any `.html` file in a browser. Links between pages work. These are static design files: build each page **once, responsively**, using the desktop and mobile files as the two reference widths. Interactive parts (listed below) are shown in their default state.

Live design canvas, with every page side by side: https://claude.ai/artifact/PRMQoqgpjGHNpj5DdDm2q1

## Design basics

- Font: Montserrat (Google Fonts), weights 400 to 900.
- Colours: navy `#0B2D5B` (dark sections `#071A35`, `#08203F`), gold `#E9B62C` / `#F2B824`, body text `#1F2A37` / `#4B5563`, light background `#F4F6FA`, borders `#E3E7EE`.
- Content width 1240px. Buttons 52 to 56px tall, 12px radius. Cards 16 to 22px radius.
- UK English throughout, and no em dashes in any copy.

## Pages, URLs and SEO

Each page has one main keyword. Service pages target the service plus "East London". Area pages own their borough and neighbourhoods, so the two never compete. One self-referencing canonical per page.

### Main and info pages

| File | Suggested URL | Title tag | Meta description |
|---|---|---|---|
| home.html | `/` | Locksmith East London | 24/7, Usually 30 to 60 Minutes | East London Locksmith Ltd | 24/7 locksmith across East London: lockouts, lock changes, repairs and boarding up. All-inclusive prices, MLA member, fully insured. Call 07958 033395. |
| services.html | `/services` | Locksmith Services East London | East London Locksmith Ltd | Every locksmith service we offer across East London, for homes, landlords and businesses. All-inclusive prices agreed first. Call 07958 033395. |
| areas.html | `/areas` | Areas We Cover | Locksmith in East London | Newham, Stratford, Tower Hamlets, Hackney, Waltham Forest, Redbridge, Barking and Dagenham. Check your postcode. Call 07958 033395. |
| pricing.html | `/prices` | Locksmith Prices East London | Supplied and Fitted, No Hidden Extras | All-inclusive supplied and fitted lock prices: 3-star anti-snap cylinders from £130, nightlatches from £75. Confirmed on the call. 07958 033395. |
| about.html | `/about` | About East London Locksmith Ltd | MLA Member Locksmith | A local, fully insured MLA member locksmith covering East London 24 hours a day. |
| contact.html | `/contact` | Contact East London Locksmith Ltd | 07958 033395, 24/7 | Call 07958 033395 any time, or send a quote request and a locksmith will call you back. |
| faqs.html | `/faqs` | Locksmith FAQs | East London Locksmith Ltd | Answers on prices, arrival times, ID checks, insurance-approved locks and more. |
| glossary.html | `/glossary` | Locksmith Glossary: Lock Terms Explained | Euro cylinders, BS 3621, TS007, multipoint locks and more, in plain English. |
| blog.html | `/blog` | Locksmith Advice Blog | East London Locksmith Ltd | Practical advice on locks, security and what to do after a break-in. |
| blog-burgled.html | `/blog/what-to-do-after-a-burglary` | What to Do After a Burglary | East London Locksmith Ltd | Step-by-step advice after a break-in, from the police to your insurer and securing your home. |
| terms.html | `/terms` | Terms and Conditions | East London Locksmith Ltd |  |
| privacy.html | `/privacy-policy` | Privacy Policy | East London Locksmith Ltd |  |
| cookies.html | `/cookies` | Cookie Policy | East London Locksmith Ltd |  |

### Service pages (H1 shown on the page)

| File | Suggested URL | Title tag | Meta description | Featured snippet question |
|---|---|---|---|---|
| service-emergency.html | `/services/emergency-locksmith` | Emergency Locksmith East London | 24/7, Usually 30 to 60 Minutes | 24/7 emergency locksmith across East London. Lockouts, snapped keys and break-ins. Price agreed on the phone first. MLA member. Call 07958 033395. | How much does an emergency locksmith cost in East London? |
| service-lockouts.html | `/services/locked-out-lost-keys` | Locked Out or Lost Keys? Locksmith East London | 24/7 | Locked out or lost your keys in East London? We get you in, usually without damage, and change the locks only if you need to. Call 07958 033395. | Do I need to change my locks if I lose my keys? |
| service-locked-inside.html | `/services/locked-inside` | Locked Inside? Emergency Locksmith East London | 24/7 | Stuck inside your home with a door that will not open? Call 999 if anyone is at risk. Otherwise call 07958 033395, 24/7, East London. | What should I do if I am locked inside my home? |
| service-boarding-up.html | `/services/boarding-up` | Emergency Boarding Up East London | 24/7 After a Break-In | Smashed window or forced door? Emergency boarding up across East London, 24/7, with photos and a report for your insurer. Call 07958 033395. | Will my insurance pay for boarding up? |
| service-after-burglary.html | `/services/burglary-repairs` | Burglary Repairs East London | Same-Day Locks and Doors | Burgled? Same-day lock changes, door repairs and boarding across East London, with an itemised invoice for your insurer. Call 07958 033395. | What should I do straight after a burglary? |
| service-repairs.html | `/services/lock-repairs` | Lock Repairs East London | Repair First, Same Day | Stiff, jammed or broken lock? We find the fault and repair it first, with the price agreed before we start. Lock repairs across East London. Call 07958 033395. | Is it cheaper to repair a lock or replace it? |
| service-replacements.html | `/services/lock-changes` | Lock Change East London | Anti-Snap and BS 3621 Locks | Lock changes across East London: anti-snap cylinders, BS 3621 mortice locks and keyed-alike sets, with the price agreed first. Call 07958 033395. | Do I need a new lock or just a new cylinder? |
| service-door-repairs.html | `/services/door-repairs` | Door Repairs East London | Doors That Stick or Will Not Lock | Door dropped, sticking or will not lock? We adjust hinges, keeps and frames across East London, with the price agreed first. Call 07958 033395. | Why will my door only lock when I lift the handle hard? |
| service-upvc.html | `/services/upvc-door-lock-repair` | uPVC Door Lock Repair East London | Gearboxes and Multipoints | uPVC or composite door will not lock? We repair gearboxes, multipoint locks and handles across East London, usually without a new lock. Call 07958 033395. | Why will my uPVC door not lock? |
| service-security.html | `/services/security-upgrades` | Home Security Upgrades East London | Anti-Snap Locks and More | Anti-snap cylinders, BS 3621 locks, door viewers, chains and letterbox guards fitted across East London. Price agreed first. Call 07958 033395. | What is the best way to make my front door more secure? |
| service-security-survey.html | `/services/security-survey` | Home and Business Security Survey East London | A check of every door, window and lock, with a priority and a price for each item. Homes, landlords and businesses in East London. Call 07958 033395. | What is checked in a home security survey? |
| service-safes.html | `/services/safe-opening` | Safe Opening and Repairs East London | Non-Destructive First | Forgotten the code, lost the key or keypad not working? Safe opening and repairs across East London, non-destructive first. Call 07958 033395. | Can a locksmith open a safe without damaging it? |
| service-landlords.html | `/services/landlords-evictions` | Landlord and Eviction Locksmith East London | Bailiffs and HCEOs | Tenancy changeovers, eviction lock changes with bailiffs and HCEOs, and HMO locks across East London. Invoices with your reference. Call 07958 033395. | Can a landlord change the locks on a tenant? |
| service-commercial.html | `/services/commercial-locksmith` | Commercial Locksmith East London | Shops, Offices, Shutters | Commercial locksmith for East London shops and offices: lockouts, master key systems, shutters and fire exit hardware, out of hours if you need. Call 07958 033395. | What does a commercial locksmith do? |

### Area pages

| File | Suggested URL | Title tag | Meta description | Leaves to other pages |
|---|---|---|---|---|
| area-newham.html | `/areas/newham` | Locksmith in Newham | East Ham, Forest Gate, Canning Town | Local Newham locksmith for East Ham, Forest Gate, Plaistow, Manor Park and Canning Town. Usually with you in 30 to 60 minutes, 24/7. Call 07958 033395. | Stratford, Maryland, West Ham, E15, E20 (Stratford page) |
| area-stratford.html | `/areas/newham/stratford` | Locksmith in Stratford, E15 and E20 | East Village, 24/7 | Lockouts and lock changes in Stratford, East Village, the Olympic Park and Maryland. Usually with you in 30 to 60 minutes, day or night. Call 07958 033395. | East Ham, Forest Gate, Canning Town (Newham page) |
| area-tower-hamlets.html | `/areas/tower-hamlets` | Locksmith in Tower Hamlets | Bow, Bethnal Green, Canary Wharf | Lockouts, lock changes and fire door locks in Bow, Bethnal Green, Whitechapel, Wapping and Canary Wharf. Usually 30 to 60 minutes, 24/7. Call 07958 033395. | Haggerston and Shoreditch (Hackney page) |
| area-hackney.html | `/areas/hackney` | Locksmith in Hackney | Dalston, Clapton, Shoreditch, 24/7 | Lockouts, lock changes and shutter repairs in Dalston, Clapton, Stoke Newington and Shoreditch. Usually 30 to 60 minutes. Call 07958 033395. | Bethnal Green (Tower Hamlets page) |
| area-waltham-forest.html | `/areas/waltham-forest` | Locksmith in Waltham Forest | Walthamstow, Leyton, Chingford | Lockouts and lock changes in Walthamstow, Leyton, Leytonstone, Highams Park and Chingford. Usually 30 to 60 minutes. Call 07958 033395. | Wanstead (Redbridge page) |
| area-redbridge.html | `/areas/redbridge` | Locksmith in Redbridge | Ilford, Gants Hill, Woodford, 24/7 | Lockouts, uPVC door repairs and lock changes in Ilford, Gants Hill, Barkingside, Wanstead and Woodford. Usually 30 to 60 minutes. Call 07958 033395. | Leytonstone (Waltham Forest page), Barking IG11 (Barking and Dagenham page) |
| area-barking-dagenham.html | `/areas/barking-dagenham` | Locksmith in Barking and Dagenham | Becontree, Chadwell Heath | Lockouts, anti-snap lock upgrades and shutter repairs in Barking, Dagenham, Becontree, Chadwell Heath and Barking Riverside. Call 07958 033395. | Ilford and Goodmayes (Redbridge page) |

## Things to build (interactive)

1. **Get a free quote pop-up**: every "Get a free quote" button opens one form (name, phone, postcode required; email, service, when, message optional). On submit: email info@ and send an instant SMS or WhatsApp to the on-call locksmith. Track as a conversion in GA4 and Google Ads.
2. **Postcode checker** (hero of home and area pages): E, EC, IG and RM postcodes, plus N1, N1C, N4 and N16, show "we cover you"; anything else shows "just outside our usual area, call us".
3. **Price tool** on the homepage: shows Zahid's starting prices (supplied and fitted). Lockouts, business lockouts, shutters, master key and access control show "priced on the phone" or "after a visit". Prices are in the price table below.
4. **Mobile menu**, **FAQ accordions** and **fault finder accordions** (native `<details>` in the files).
5. Every phone number is a `tel:07958033395` link. Track taps as conversions.

## Prices (all-inclusive, supplied and fitted)

| Job | Price |
|---|---|
| Euro cylinders: Kitemarked 1-star cylinder, usually with 5 keys | from £95 |
| Euro cylinders: Kitemarked 3-star anti-snap cylinder | from £130 |
| Nightlatches: Nightlatch barrel (5-pin) replacement | from £75 |
| Nightlatches: Nightlatch replacement | £90 |
| Nightlatches: New nightlatch fitted | £130 |
| Mortice deadlocks: Mortice deadlock replacement | from £120 |
| Mortice deadlocks: New mortice deadlock fitted | £150 |
| uPVC doors: Opening a door with a failed mechanism | from £120 |
| uPVC doors: uPVC door alignment | from £90 |
| uPVC doors: Mechanism replacement | Priced on the call |

Lockouts and uPVC mechanism replacements are priced on the call. Every price is confirmed on the phone before the locksmith comes out.

## Schema (JSON-LD)

- Sitewide `Locksmith` (LocalBusiness): name East London Locksmith Ltd, telephone 07958033395, **no street address** (service-area business), openingHours Mo-Su 00:00-23:59, areaServed = Newham, Tower Hamlets, Hackney, Waltham Forest, Redbridge, Barking and Dagenham.
- Service pages: `Service` + `FAQPage` + `BreadcrumbList`. Area pages: `FAQPage` + `BreadcrumbList`.
- Do **not** add review or rating markup: there are no reviews on the site for now.

## Images

- Most photos are placeholders or renders. Replace with real photos of Zahid at work, his tools and finished jobs before launch. There is **no van**, so do not use van photos.
- Serve as WebP with width and height set, and lazy-load everything below the first screen. Borough maps contain OS and OpenStreetMap data, so keep the attribution line.

## Before launch (confirm with the owner)

- **Domain and email:** eastlondonlocksmith.co.uk appears to be used by a different company ("East London Locksmith Services Ltd", other phone numbers). Confirm which domain and email the business owns before going live.
- **Reviews:** removed, as there is no access to the old Google account. Add a live Google reviews widget in the "Quality locks, not cheap imports" section once the new profile has reviews.
- **Terms:** the up to £89 cancellation charge, the 6-month vs 1-year guarantee, and the payment methods need a decision.
- Emergency: we check ID inside if documents are locked in, and accept a landlord or agent confirming the tenant.
- Boarding up: photos before and after, a written job report and a quote for the permanent repair (already on the site, please confirm).
- Security upgrades: door limiters and letterbox guards are fitted.
- Security survey: a written report with a priority and price for each item, usually under an hour.
- Safes: we ask for proof of ownership. Confirm safe work is still offered.
- Landlords: attending evictions with bailiffs and HCEOs, logging keys, PO numbers and agent invoicing.
- Commercial: master key systems, panic bars and fire exit hardware, business accounts.
- Repairs: common parts carried in the van, old parts shown to the customer.
