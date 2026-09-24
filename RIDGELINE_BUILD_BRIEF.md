# Ridgeline Roofing Services — Rebuild Brief

## Goal

Rebuild Ridgeline Roofing Services with the premium editorial structure, rounded card framing, large typography, smooth scrolling, loader, clip-mask reveals, parallax hero and polished interactions from the supplied Baseline reference, but make the content and visual identity completely Ridgeline.

The source reference describes the desired experience as a full-bleed hero, oversized animated typography, stacked light/dark sections, in-view reveals, hover micro-interactions, parallax, responsive scaling, a fullscreen menu and modal interaction. The Ridgeline version should use those interaction/layout ideas without retaining tennis content.

## Brand rules

Use the branding from the existing Ridgeline website:

- Primary orange: #FF6700
- Dark charcoal: #333333
- Near black: #222222
- Body text: #666666
- Light accent: #FECB8B
- White: #FFFFFF
- Light surface: #F9F9F9
- Current logo: https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/07/Logo-1-light.svg
- Font in this implementation: Onest, weights 400/500/600

Do not introduce blue, green or another unrelated brand colour.

## Business details

- Ridgeline Roofing Services
- Phone: 07455 083369
- Email: info@ridgelineroofingservices.uk
- Location: Romiley, Stockport
- Coverage: North West UK
- Emergency service: 24-hour / 24-7 emergency call-out

## Services

1. New Roof Installation
2. Roof Repairs
3. Flat Roofing
4. Pitched Roofing
5. Solar Panel Installation
6. Guttering

Use the existing site's wording as the content source. Do not invent awards, accreditations, review scores, years in business or project counts unless they are supplied later.

## Page structure

1. Loader
2. Hero with current Ridgeline logo, existing roofing image, oversized "Roofing Built To Last" headline, 24/7 emergency card and quote CTA
3. Brand/trust intro
4. Services list
5. Our Work section using the existing portfolio photography
6. Dark "Why Ridgeline" / key facts band
7. Three-step process: Consultation & Assessment / Planning & Execution / Final Inspection
8. Footer with contact details and quote CTA
9. Fullscreen menu
10. Quote modal
11. Image lightbox for portfolio images

## Quote form

Fields:
- Full name
- Phone
- Email
- Postcode
- Service
- Message
- Optional photo upload

The version committed here is a front-end interaction stub only. It validates and shows success but intentionally does not send data to a server. Connect it to the production email/CRM/backend before launch.

## Existing image assets used

Homepage / about:
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/07/shutterstock_2046407060.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/07/shutterstock_2054847506.jpg

Portfolio:
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/354565611_106580782478620_3151367569541272717_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/354925485_106515099151855_4244123283829798250_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/354986580_106580905811941_1687924455913572781_n-e1691743838776.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/355290779_106580769145288_1803309526030841986_n-e1691743805664.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/355604450_110125972124101_4399586774712217159_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/355703205_116656734804358_1458824357233049642_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/356449772_116656788137686_5919322236421555518_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/357016368_118152621321436_9203323998518767892_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/352230490_106580889145276_4707778456031590155_n.jpg
- https://www.ridgelineroofingservices.uk/wp-content/uploads/sites/5/2023/08/354455139_106515129151852_2736004676469268718_n.jpg

## Responsive / interaction requirements

- No horizontal scrollbar at any breakpoint.
- Mobile layout must be deliberately designed, not a desktop squeeze.
- Smooth scroll through Lenis.
- Loader must release scroll correctly.
- Hero background should parallax without revealing an empty edge.
- Headings reveal from clipped masks.
- Cards reveal once when entering view.
- Hover effects should remain subtle and never cause layout shift.
- Escape closes modal/menu/lightbox.
- Focus states must remain visible.
- Respect prefers-reduced-motion.
- Keep the page as a single self-contained index.html for this first version.
