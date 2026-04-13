# Express Junk Removal — Homepage Redesign Spec

## Overview

Redesign the Express Junk Removal homepage to reposition the company as a full-service hauling & delivery company. The site currently focuses solely on junk removal; this redesign adds construction material delivery as an equal service offering. The new homepage must be high-converting, SEO-optimized, and mobile-first.

**Live site:** https://expressjunk-removal.com  
**Current stack:** WordPress + Elementor  
**Phone:** (208) 240-1007  
**Email:** expressjunkremoval208@gmail.com

---

## Business Context

- **New service:** Construction material delivery via dump truck — aggregates (gravel, sand, topsoil, fill dirt) and building materials (lumber, drywall, concrete blocks).
- **Primary audience:** General contractors and construction companies, with accessibility for homeowners doing DIY projects.
- **Service area:** East Idaho — Idaho Falls, Rigby, Pocatello, Rexburg, Shelley, Blackfoot.
- **Key value props:** Same-day/next-day delivery, competitive/transparent pricing, locally owned, free estimates, no hidden fees.
- **Conversion goals:** Phone calls and quote form submissions weighted equally.

---

## Design Direction: "The Professional"

Clean, modern, business-grade. White/light palette with navy and green accents. Balances contractor credibility with homeowner approachability. Borrows local SEO strengths from a community-rooted approach.

---

## Page Structure

### 1. Sticky Header

- **Desktop:** Logo (left), nav center (Home, Services dropdown, About, Contact), phone number + "Get Quote" button (right).
- **Mobile:** Logo (left), tap-to-call phone icon (right), hamburger menu. Sticky on scroll.
- Services dropdown contains: "Construction Material Delivery" and "Junk Removal & Cleanout".

### 2. Hero Section

- **Layout:** Full-width, split. Left side content, right side quote form.
- **Background:** High-quality photo of dump truck / construction delivery scene with dark overlay for text contrast.
- **Left side content:**
  - H1: "East Idaho's Full-Service Hauling & Delivery Company"
  - Subheadline: "Construction material delivery and junk removal across Idaho Falls, Pocatello, Rexburg, and surrounding areas. Same-day service available."
  - Two CTA buttons: "Call (208) 240-1007" (green, primary) and "Get Free Quote" (navy outline, scrolls to form on mobile).
- **Right side form (desktop) / below hero content (mobile):**
  - Fields: Name, Email, Phone Number, Service Area, Desired Service Date, Desired Service Time.
  - Service Type radio buttons: "Construction Delivery" | "Junk Removal" | "Roll Off Dumpster Rental".
  - Image upload field.
  - Submit button: "GET QUOTE NOW!" (green, full-width).
  - Form heading: "Get a Free Quote Today!"

### 3. Trust Bar

- Horizontal strip directly below hero.
- Five items with line icons: "Same-Day Delivery" | "Free Estimates" | "Locally Owned" | "Licensed & Insured" | "No Hidden Fees".
- Light gray background, navy icons and text.
- Mobile: Horizontal scroll or 2x3 grid.

### 4. Services Section

- Section heading H2: "Our Services"
- Two equal cards side by side (stack vertically on mobile).

**Card 1 — Construction Material Delivery:**
- Icon: Dump truck
- H3: "Construction Material Delivery"
- Description: Brief paragraph about delivering aggregates and building materials across East Idaho.
- Bullet points: Gravel & crushed rock, Sand & topsoil, Fill dirt, Lumber & drywall, Concrete blocks & masonry, Same-day & next-day available.
- CTA button: "Request Delivery Quote" (green).

**Card 2 — Junk Removal & Cleanout:**
- Icon: Broom/trash
- H3: "Junk Removal & Cleanout"
- Description: Brief paragraph about full-service junk removal for residential and commercial.
- Bullet points: House, garage & estate cleanouts, Furniture & appliance removal, Commercial junk removal, Construction debris removal, Eco-friendly recycling.
- CTA button: "Request Removal Quote" (green).

### 5. How It Works

- Section heading H2: "How It Works"
- Three numbered steps in a horizontal row (stack on mobile):
  1. "Call or Submit a Quote" — icon: phone/form — "Call us at (208) 240-1007 or fill out our quick quote form."
  2. "We Schedule & Confirm" — icon: calendar — "We confirm your date, time, and provide a transparent price."
  3. "We Deliver or Remove" — icon: truck — "Our crew arrives on time and gets the job done right."

### 6. Service Area Section

- Section heading H2: "Serving East Idaho"
- Visual: Grid of city name badges (navy background, white text, rounded) — no map image needed, keeps it lightweight and SEO-friendly since city names are real text.
- Cities prominently listed: Idaho Falls, Rigby, Pocatello, Rexburg, Shelley, Blackfoot.
- Brief copy: "Proudly serving contractors and homeowners across East Idaho. From Pocatello to Rexburg, we deliver materials and remove junk on your schedule."
- CTA: "See If We Serve Your Area — Call (208) 240-1007"

### 7. Testimonials

- Section heading H2: "What Our Customers Say"
- Carousel with existing reviews:
  - Jared Duncan — "Very Impressed" (5 stars)
  - Leslie Hartley — "Professional" (5 stars)
  - Autumn Roseberg — "Super Fast" (5 stars)
  - Amanda McFarland — "Quick & Efficient" (5 stars)
- Each card shows: Name, review title, excerpt, star rating.

### 8. Footer CTA

- Full-width section with contrasting background (navy).
- Heading: "Ready to Get Started?"
- Subtext: "Call for a free estimate or submit a quote request online."
- Two buttons: "Call (208) 240-1007" (green) and "Get Free Quote" (white outline).

### 9. Footer

- Three columns (stack on mobile):
  - **Column 1:** Logo, brief company description, social media links.
  - **Column 2:** Quick links (Home, About, Services, Contact) + service links (Construction Delivery, Junk Removal).
  - **Column 3:** Contact info — phone, email, service area cities listed (for SEO).
- Bottom bar: Copyright, locally owned badge.

### 10. Mobile Sticky Bottom Bar

- Appears on scroll (after hero passes out of view).
- Two buttons side by side: "Call Now" (tap-to-call) and "Get Quote" (scrolls to form).
- Semi-transparent background, fixed to bottom of viewport.

---

## Visual Design

### Color Palette

| Role | Color | Hex |
|------|-------|-----|
| Primary (navy) | Dark navy blue | #1B3A5C |
| Accent (green) | CTA green | #2ECC71 |
| Secondary accent | Urgency orange | #E67E22 |
| Background | Light gray | #F8F9FA |
| Surface | White | #FFFFFF |
| Text | Dark charcoal | #1A1A2E |
| Muted text | Medium gray | #6C757D |

### Typography

- **Font family:** Inter or Poppins (Google Fonts, sans-serif).
- **H1:** 48px / bold (desktop), 32px (mobile).
- **H2:** 36px / bold (desktop), 28px (mobile).
- **H3:** 24px / semibold (desktop), 20px (mobile).
- **Body:** 16px / regular, line-height 1.6.
- **CTA buttons:** 16-18px / uppercase / bold / letter-spacing 0.5px.

### Buttons

- **Primary CTA:** Green (#2ECC71), white text, rounded (8px), min height 48px, hover darkens to #27AE60.
- **Secondary CTA:** Navy (#1B3A5C) outline, navy text, same dimensions, hover fills navy with white text.
- **Phone number:** Orange (#E67E22) text in header, always tappable on mobile.

### Layout & Spacing

- Max content width: 1200px, centered.
- Section padding: 80px top/bottom (desktop), 48px (mobile).
- Cards: White background, soft box-shadow (0 2px 12px rgba(0,0,0,0.08)), border-radius 8px, padding 32px.
- Sections alternate between white and #F8F9FA backgrounds.
- Generous whitespace between all elements.

### Imagery

- **Hero:** Stock photo of dump truck delivering materials at a construction site, dark overlay (rgba(0,0,0,0.55)) for text readability.
- **Service cards:** Simple line icons or flat illustrations (truck for delivery, broom/bin for removal).
- **Trust bar:** Line icons (clock, handshake, map-pin, shield, tag).
- **Format:** WebP with JPEG fallback. Hero compressed to under 200KB.

---

## SEO Optimization

### Meta Tags

- **Title:** "Construction Material Delivery & Junk Removal | Idaho Falls, East Idaho | Express Junk Removal"
- **Meta description:** "Same-day construction delivery and junk removal in Idaho Falls, Pocatello, Rexburg, Rigby, Shelley & Blackfoot. Free estimates, no hidden fees. Call (208) 240-1007."
- **Canonical:** https://expressjunk-removal.com/

### Heading Hierarchy

- H1: "East Idaho's Full-Service Hauling & Delivery Company" (one per page)
- H2: "Our Services", "How It Works", "Serving East Idaho", "What Our Customers Say", "Ready to Get Started?"
- H3: "Construction Material Delivery", "Junk Removal & Cleanout" (within service cards)

### Target Keywords

- Primary: "construction delivery Idaho Falls", "junk removal East Idaho"
- Secondary: "gravel delivery Pocatello", "sand delivery Rexburg", "building material delivery Idaho", "dump truck delivery East Idaho", "topsoil delivery Idaho Falls"
- Long-tail: "same day construction delivery Idaho Falls", "affordable junk removal Pocatello", "construction material delivery near me"

### Local SEO

- All six city names appear in: service area section, footer, and naturally in body copy.
- NAP (Name, Address, Phone) consistent in header and footer.
- Schema markup: LocalBusiness type with service area, AggregateRating, and Service schemas for both service types.

### Structured Data (JSON-LD)

- **LocalBusiness** schema with: name, phone, email, service area (all six cities), aggregate rating.
- **Service** schema (x2): one for construction delivery, one for junk removal.
- **BreadcrumbList** schema for navigation.

---

## Performance & Technical

- **Mobile-first responsive:** Built from mobile breakpoint up. Breakpoints: 768px (tablet), 1024px (desktop).
- **Lazy loading:** All images below the fold use `loading="lazy"`.
- **Critical CSS:** Inline above-the-fold styles to eliminate render-blocking.
- **Image optimization:** Hero image in WebP (JPEG fallback), compressed under 200KB. All other images optimized.
- **Minimal JavaScript:** Only for mobile menu toggle, testimonial carousel, sticky bottom bar show/hide, and form validation.
- **Target:** 90+ Lighthouse performance score on mobile.
- **Accessibility:** Semantic HTML, ARIA labels on interactive elements, sufficient color contrast (WCAG AA), focus states on all interactive elements.
- **Form:** Maintains current form submission backend (keeps existing hidden fields and form handler).

---

## Deliverable

A single standalone HTML file with embedded CSS and minimal JS that can be used as a reference implementation or directly integrated into the WordPress/Elementor site. The file will be fully functional, responsive, and contain all sections described above.
