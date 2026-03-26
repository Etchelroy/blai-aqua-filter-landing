# LANDING PAGE RESEARCH: WATER FILTER COMPANY

## SUMMARY
A shareholder-ready landing page combining professional design, trust-building messaging, and conversion optimization for a B2B/B2C water filtration company using blue/white branding.

---

## APPROACH

**Technical Stack:**
- Next.js 14+ (App Router) — enterprise-grade React with built-in SEO, image optimization, static generation
- Tailwind CSS + shadcn/ui components — consistent design system, rapid professional styling
- Framer Motion for micro-interactions — subtle animations that signal polish without distraction
- Vercel deployment — zero-config, CDN-global, shareholder-friendly uptime metrics
- EmailJS or Formspree for lead capture — no backend maintenance
- Open Graph + structured schema markup — professional social sharing and search visibility

**Why this stack:** Fast-loading, SEO-optimized, scalable, minimal maintenance overhead, and suitable for investor presentations.

---

## REQUIREMENTS

### HERO SECTION (Above fold)
- Full-bleed background image or gradient (water droplet/filtration close-up with blue overlay)
- Headline emphasizing problem/solution (e.g., "Industry-Leading Water Purification for 500K+ Households")
- Subheadline with specific value prop (measurable benefit: cost savings, health impact, or environmental stat)
- Primary CTA button ("Request Demo" or "Get Started") + secondary CTA ("Watch 2-min video")
- Trust badge row: certifications (NSF, FDA), customer count, years established
- Navigation bar: sticky, minimalist (Home, Products, Sustainability, About, Contact)

### MESSAGING & CREDIBILITY SECTION
- 3-column feature blocks with icons: quality/certification, cost efficiency, environmental impact
- Real customer metrics displayed (e.g., "2.5M gallons purified," "47% cost reduction")
- Certification carousel or grid: NSF Mark, WQA, EPA, ISO compliance badges

### PRODUCTS/SOLUTIONS SECTION
- 2-3 hero product cards in grid (e.g., residential, commercial, industrial variants)
- Each card: product image, key specs, starting price, "Learn More" link
- Clean comparison table (filtration stages, flow rate, maintenance interval, warranty) — collapsible on mobile

### SOCIAL PROOF & TESTIMONIALS
- 4-6 testimonial cards with customer headshots, company name, role, quote
- Star ratings (5-star average prominently displayed)
- Customer logos grid (15-20 recognizable company names/logos if available)
- Press mentions: "Featured in Forbes," "TechCrunch," etc.

### IMPACT/SUSTAINABILITY SECTION
- Stat carousel or infographic: "X tons of plastic diverted," "Y gallons saved per customer"
- Video embed (YouTube): 60-90 sec product demo or company mission video
- Linked white paper or case study PDF download (lead magnet)

### CONTACT/CTA SECTION
- Dual-column layout: contact form on left, company info + map on right
- Form fields: name, email, company, filtration need, message
- Optional: Calendly embed for "Schedule a Demo" CTA
- Footer with social links, privacy policy, sitemap

### RESPONSIVE DESIGN
- Mobile-first layout (320px+)
- Hero text scales appropriately
- Testimonials/products stack to single column
- Forms reflow gracefully
- Touch-friendly buttons (48px minimum height)

---

## CONSTRAINTS

**Performance:**
- Lighthouse score target: 90+ (SEO, Performance, Accessibility, Best Practices)
- First Contentful Paint (FCP) < 1.5s
- Largest Contentful Paint (LCP) < 2.5s
- Image optimization: WebP format, lazy loading, responsive srcsets
- Total bundle size < 200KB (gzipped)

**Browser/Device Support:**
- Chrome, Safari, Firefox, Edge (latest 2 versions)
- iOS 12+, Android 8+
- No JavaScript required for core content (progressive enhancement)

**SEO/Analytics:**
- Google Analytics 4 event tracking for CTA clicks, form submissions
- hreflang tags if multilingual
- XML sitemap, robots.txt
- Meta descriptions, OG tags for all pages

**Accessibility (WCAG 2.1 AA):**
- Semantic HTML (nav, main, section, article)
- ARIA labels for icons and interactive elements
- Color contrast minimum 4.5:1 for text
- Keyboard navigation fully supported
- Alt text on all images

**Email/Form Handling:**
- GDPR/CCPA compliance: privacy checkboxes, data retention policy
- Form validation (client-side) before submission
- Spam protection (honeypot field or reCAPTCHA v3)
- Confirmation email to user, admin notification to company

---

## NOTES

**Design Best Practices:**
- Use blue as primary (#0066CC or #0052A3), white as background, accent with a complementary teal or navy
- Whitespace-heavy layout (generous padding/margins) signals premium positioning
- Typography: sans-serif (Inter, Poppins, or similar) for body; slightly heavier weight (600-700) for headlines
- Consistent shadow/depth system (subtle, professional — avoid dark shadows)

**Copywriting:**
- Lead with measurable outcomes, not features ("Save 40% on water costs" not "Advanced 7-stage filtration")
- Use active voice and urgency sparingly (avoid "act now" unless time-sensitive promotion exists)
- Shareholder deck tone: confidence without hyperbole, data-driven claims

**Conversion Optimization:**
- Test 2 CTA labels (A/B): "Request Demo" vs. "Get Quote" vs. "Start Free Trial"
- Heat mapping (Hotjar/Mouseflow) to identify drop-off points
- Form field optimization: ask for minimum info on first step (email only), progressive profiling
- Sticky footer CTA on mobile (low friction)

**Edge Cases:**
- Ensure testimonials load images without breaking layout (use aspect-ratio CSS, fixed containers)
- Handle long product names/specs gracefully in cards
- Video auto-play muted (browser policy compliance)
- Fallback content if JavaScript disabled (form still submits via POST)
- RTL language support (if international expansion planned)

**Content Assets Needed:**
- 1 hero background image (2560x1440px minimum, optimized)
- 3-5 product photography (high-res, consistent styling)
- 4-6 customer testimonial headshots (200x200px, circular crop)
- 10-15 company/press logos (SVG preferred)
- Feature icons (6 SVGs, consistent stroke weight and size)
- Certification badges/seals (PNG, 200x200px)
- 1 demo/explainer video (YouTube or self-hosted, <100MB)

**Maintenance/Handoff:**
- Component-based structure (reusable cards, buttons, sections) for easy future updates
- Environment variables for API endpoints, form handlers
- CMS consideration if frequent content updates needed (Contentful, Sanity, or simple admin panel)