# SEO Changelog & Technical Architecture — NewGen Events (newgenevents.in)

**Audit & Implementation Date:** October 2026  
**Target Market:** India (`google.co.in`)  
**Canonical Domain:** `https://www.newgenevents.in/`

---

## 1. Executive Summary

A comprehensive technical SEO overhaul and multi-page commercial architecture was implemented for **NewGen Events**, led by CEO & Founder **Prachi Rana**, destination operations director **Sam (Mr. House)**, and lead stage performer **Nick (Mr. Lock)**.

The strategy expands the previous single-page site into a multi-page hub targeting high-intent bridal, groom, couple, sangeet, cost, and destination wedding queries across India (Delhi NCR, Jaipur, Udaipur, and Goa).

---

## 2. Page & URL Inventory

| # | URL Slug | Primary Target Keyword | Title Tag (Length) | Meta Description (Length) | Primary Schema(s) |
|---|---|---|---|---|---|
| 1 | `/` | Wedding entry & choreography India | `Wedding Entry & Choreography in India \| NewGen Events` (55 chars) | `Cinematic wedding entry concepts & choreography across Delhi NCR, Jaipur, Udaipur & Goa by Prachi Rana. 500+ weddings. Book your customized consultation!` (158 chars) | `ProfessionalService`, `FAQPage`, `VideoObject` |
| 2 | `/bride-entry/` | Bridal entry choreography, bride entry ideas | `Bridal Entry Choreography & Concepts \| NewGen Events` (55 chars) | `Explore 12+ royal bridal entry concepts by Prachi Rana. From emotional phoolon ki chadar walks to dramatic dancer-backed entries across India. Book a quote!` (158 chars) | `BreadcrumbList`, `Service`, `FAQPage` |
| 3 | `/groom-entry/` | Royal groom entry ideas, groom choreography | `Royal Groom Entry Ideas & Choreography \| NewGen Events` (55 chars) | `Cinematic groom entry concepts with vintage cars, royal dhol nagada troupes, ATV/horse processions, and dramatic pyro. Tailored by Prachi Rana across India.` (158 chars) | `BreadcrumbList`, `Service`, `FAQPage` |
| 4 | `/couple-entry/` | Grand couple entry ideas, couple choreography | `Grand Couple Entry Ideas & Choreography \| NewGen Events` (55 chars) | `Make your first steps unforgettable with grand couple entries. Flowing fabrics, floral frames, dancers, custom voiceover tracks & stage pyrotechnics. Inquire now!` (160 chars) | `BreadcrumbList`, `Service`, `FAQPage` |
| 5 | `/sangeet-choreography/` | Wedding sangeet choreography India | `Wedding Sangeet Choreography in India \| NewGen Events` (53 chars) | `Award-winning sangeet choreography for couples, families & friends by Prachi Rana. Custom medleys, virtual & in-person rehearsals for non-dancers pan-India.` (158 chars) | `BreadcrumbList`, `Service`, `FAQPage` |
| 6 | `/wedding-entry-cost/` | Wedding entry cost India, choreography price | `Wedding Entry Cost in India (2026 Price Guide) \| NewGen Events` (60 chars) | `Transparent guide to wedding entry costs & choreography prices in India. Packages start from ₹10,000+. Learn what affects troupe, pyro, props & audio pricing.` (160 chars) | `BreadcrumbList`, `Article`, `FAQPage` |
| 7 | `/wedding-choreographer-delhi/` | Wedding choreographer Delhi NCR | `Wedding Choreographer in Delhi NCR \| NewGen Events` (49 chars) | `Premier wedding choreography & entry design in Delhi NCR, Chattarpur, Gurgaon & Noida. Led by Prachi Rana from Civil Lines Delhi. Tailored for non-dancers.` (157 chars) | `BreadcrumbList`, `ProfessionalService`, `FAQPage` |
| 8 | `/wedding-choreographer-jaipur/` | Wedding choreographer Jaipur | `Wedding Choreographer in Jaipur \| NewGen Events` (47 chars) | `Destination wedding choreography & royal entry concepts in Jaipur. Palace entries at Rambagh, Fairmont, Samode & Leela Palace directed by Prachi Rana & Sam.` (158 chars) | `BreadcrumbList`, `ProfessionalService`, `FAQPage` |
| 9 | `/wedding-choreographer-udaipur/` | Wedding choreographer Udaipur | `Wedding Choreographer in Udaipur \| NewGen Events` (48 chars) | `Luxury wedding choreography & royal entries in Udaipur. Lakeside entries at Jagmandir, The Leela, Taj Lake Palace & Raffles. Directed by Prachi Rana & team.` (157 chars) | `BreadcrumbList`, `ProfessionalService`, `FAQPage` |
| 10 | `/wedding-choreographer-goa/` | Wedding choreographer Goa | `Wedding Choreographer in Goa \| NewGen Events` (44 chars) | `Bespoke beach wedding entries & sangeet choreography in Goa. Tropical sunset entries, cold pyro walkways & high-energy beach afterparty acts by Prachi Rana.` (157 chars) | `BreadcrumbList`, `ProfessionalService`, `FAQPage` |
| 11 | `/404.html` | Custom branded error page | `Page Not Found (404) \| NewGen Events` | `The page you are looking for has moved or does not exist. Explore our royal wedding entry concepts and choreography services at NewGen Events.` | `None` (`noindex, follow`) |

---

## 3. Technical SEO Enhancements

### 3.1 Metadata & Indexing Directives
- **Language declaration:** Updated from generic `<html lang="en">` to regional semantic `<html lang="en-IN">` on all pages.
- **Title tags:** Standardized to the 40–60 character sweet spot for mobile & desktop SERP rendering on Google India. Diluting sub-branding removed.
- **Meta descriptions:** Calibrated strictly between 150–160 characters, with primary target keywords, proof points, and action triggers.
- **Canonical tags:** Absolute `<link rel="canonical" href="https://www.newgenevents.in/[path]/">` added across every single page.
- **OpenGraph & Twitter Cards:** Full protocol tags declared on all pages (`og:site_name`, `og:type`, `og:title`, `og:description`, `og:url`, `og:image`, `og:locale="en_IN"`, `twitter:card="summary_large_image"`).

### 3.2 Crawling & Sitemaps
- **`robots.txt`**: Created at root, granting crawling access to all search engines and referencing the XML sitemap.
- **`sitemap.xml`**: Built using standard Sitemaps 0.9 protocol containing all 10 canonical URLs, `lastmod` timestamps, and priority tiers (1.0 for Homepage, 0.9 for core service pages, 0.85 for city hubs and cost guide).

### 3.3 Structured Data (JSON-LD)
- **`ProfessionalService` / `LocalBusiness`**: Declared with official brand name (`NewGen Events`), CEO & Founder (`Prachi Rana`), key personnel (`Sam Mr. House`, `Nick Mr. Lock`), registered address (`J-4, Khyber Pass, Civil Lines S.O, Civil Lines, Delhi 110054`), geo-coordinates (`28.6814, 77.2228`), price range (`₹₹`), telephone (`+91-9654344858`), email (`prachir426@gmail.com`), and coverage areas (`Delhi NCR`, `Jaipur`, `Udaipur`, `Goa`, `India`).
- **`FAQPage`**: Implemented on all pages matching visible on-page accordion questions and answers verbatim.
- **`VideoObject`**: Implemented on homepage for live vertical reels (`reel_1.mp4`, `reel_2.mp4`, `reel_3.mp4`).
- **`BreadcrumbList`**: Implemented on all subpages for rich snippet breadcrumb navigation in Google SERPs.

### 3.4 Image Optimization & Accessibility
- Audited all 31 images across `index.html`.
- Replaced generic alt texts with natural, descriptive keyword phrasing.
- Implemented `loading="lazy"` on all below-the-fold assets to preserve core web vitals and fast initial paint.

### 3.5 Internal Linking Architecture
- Header mega-menu Group 7 (ENTERTAINMENT) and CHOREOGRAPHY & GALLERY dropdowns linked directly to money pages.
- Nav bar BUDGET link updated to point to `/wedding-entry-cost/`.
- Site footer structured with dedicated columns: Wedding Entries, Destination Cities, and Direct Contact details.
