# Designs by Brodhead — New Website/Platform Goal

## Vision
Build a modern, conversion-focused website and ecommerce platform for **Designs by Brodhead** that showcases custom 3D printing capabilities, sells ready-made products/STLs, and captures qualified custom-order leads.

## Business Outcomes (90–180 days)
1. Increase direct online sales through a streamlined storefront and checkout.
2. Increase custom quote requests with clear service pages and instant quote intake.
3. Improve trust and repeat business using social proof, portfolio depth, and automated customer communication.
4. Reduce manual admin overhead with order workflow automation (quote → payment → production → delivery).

## Primary User Types
- **Retail buyers**: want finished products quickly and securely.
- **Maker buyers**: want digital STL files with instant delivery.
- **Custom clients (B2C/B2B)**: need design help, material guidance, and production quotes.
- **Returning customers**: want reorder speed and status transparency.

## Core Platform Features

### 1) Marketing Website
- Homepage with clear value proposition, featured categories, and CTA split:
  - "Shop Products"
  - "Get a Custom Quote"
- About/Process pages to explain quality standards and turnaround times.
- Portfolio/gallery filtered by use case (cosplay, prototypes, gifts, replacement parts, etc.).
- SEO landing pages for local + niche intent (e.g., custom 3D printing in region, cosplay prop printing).

### 2) Ecommerce Store
- Product catalog with variants (material, color, size, finish).
- Inventory states (made-to-order, in-stock, backorder).
- Secure checkout (card, wallet options, tax/shipping automation).
- Discount codes, bundles, and upsell modules.
- Digital product support for STL sales and automatic file delivery.

### 3) Quote & Custom Order System
- Guided quote form (file upload, dimensions, material, quantity, deadline, budget).
- Auto-estimate logic for common print/material combinations.
- CRM pipeline status: New → Reviewing → Quoted → Approved → In Production → Shipped.
- Customer portal for messages, revisions, and progress updates.

### 4) Operations Layer
- Admin dashboard for orders, quotes, production queue, and fulfillment status.
- Email/SMS notifications (order confirmations, quote updates, shipping events).
- Basic analytics for revenue, conversion rate, top products, quote close rate.
- Integration-ready architecture for shipping and label providers.

## Recommended MVP Scope (Phase 1)
Deliver in 6–8 weeks:
1. New brand-consistent website with homepage, about, services, portfolio, contact.
2. Ecommerce for physical products + one digital category (STLs).
3. Quote request flow with file upload and admin email notifications.
4. Foundational SEO, analytics, and conversion tracking.

## Phase 2 Enhancements
- Customer account area with order history and reorder.
- Advanced quoting calculator with geometry/material heuristics.
- Subscription or membership for maker files.
- B2B portal (bulk pricing, PO workflow, repeat manufacturing jobs).
- AI-assisted support/chat for common pre-sales questions.

## Information Architecture (Sitemap)
- Home
- Shop
  - Categories
  - Product Detail
  - Cart/Checkout
- Custom 3D Printing
  - How It Works
  - Materials
  - Quote Form
- Portfolio
- Reviews
- FAQ
- About
- Contact
- Policies (Shipping, Returns, Terms, Privacy)

## Conversion & UX Requirements
- Mobile-first design and <2.5s LCP target on primary pages.
- Sticky quote CTA for service-intent visitors.
- Trust elements above fold: ratings, turnaround guarantees, secure checkout badges.
- Persistent cart + abandoned cart recovery.
- Frictionless quote flow (save progress + drag/drop file upload).

## Technical Direction (Suggested)
- **Frontend**: Next.js (SEO, performance, scalable component architecture).
- **Commerce**: Shopify (headless or themed), or WooCommerce if WordPress-first preference.
- **CMS**: Sanity/Contentful or Shopify CMS fields for editable marketing content.
- **Forms/Uploads**: UploadThing/Cloudinary + server validation.
- **Analytics**: GA4 + Meta Pixel + server-side event tracking.
- **Hosting**: Vercel (frontend) + managed backend services.

## SEO & Content Strategy
- Keyword clusters:
  - Custom 3D printing service terms
  - Niche product categories
  - Educational content (materials, tolerances, print prep)
- Content cadence: 2 optimized posts/month plus new product pages.
- Structured data for Product, FAQ, and Review snippets.

## KPIs to Track
- Ecommerce conversion rate.
- Revenue per visitor.
- Quote submission rate.
- Quote-to-order close rate.
- Average order value.
- Repeat purchase rate.
- Organic search impressions/clicks.

## Launch Checklist
- Brand system finalized (logo usage, colors, typography, imagery style).
- Product data cleanup (titles, photos, attributes, SKUs).
- Shipping/tax/payment configuration verified.
- Legal policies published.
- 301 redirects from old URLs mapped.
- Analytics + conversion events QA'd.
- Backup/rollback plan documented.

## Immediate Next Steps
1. Confirm platform stack (Shopify headless, Shopify theme, or WordPress/WooCommerce).
2. Prioritize top 20 SKUs + top 5 custom service funnels.
3. Approve wireframes for Home, Product, Quote, and Portfolio pages.
4. Begin MVP implementation sprint with weekly demo cadence.
