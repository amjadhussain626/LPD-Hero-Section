
LPD Hero Section — Shopify Custom Hero Component

A flexible, responsive Hero Section for Shopify themes featuring:

Top announcement ticker (scrolling)

Main hero with rating, headline, description, CTA

Media panel supporting image or video (YouTube / Vimeo / MP4)

Bottom scrolling marquee for promotions or features

Mobile-first responsive behavior and simple schema-driven customization

🔑 Key Features

Announcement Ticker — top blue bar with repeating scrolling announcements (multiple items supported).

Hero Content — rating (stars), headline, rich description, and CTA button with custom link/text.

Media Support — choose image or video; supports YouTube, Vimeo, or direct MP4; separate responsive layout.

Bottom Marquee — repeating promotional texts that scroll across the bottom (desktop + mobile variants).

Responsive — mobile layout stacks media above/below content and scales typography for readability.

Theme Editor Settings — change headline, description, CTA, media type, media items, rating and review count, and add announcement/marquee blocks.

🧩 Tech Stack

Shopify Liquid (schema + blocks)

HTML5 & CSS3

No external JS libraries required (pure CSS animations & Liquid)

Supports iframe embeds for YouTube/Vimeo or native <video> tags for MP4

📁 Included File

lpd-hero-section.liquid — complete section code (markup, styles, and schema)

⚙️ Installation

In Shopify Admin go to Online Store → Themes → Actions → Edit code

Open the Sections folder.

Click Add new section and name it lpd-hero-section (or lpd-hero-section.liquid).

Paste the contents of lpd-hero-section.liquid into the new file.

Save.

Go to Customize theme, add the Hero Section to the page, and configure settings & blocks.

🛠 Theme Editor (Settings & Blocks)

Section Settings

headline — main hero text

description — rich description HTML

media_type — image or video

hero_image — image picker

video_url — url (YouTube/Vimeo/MP4)

cta_label / cta_url — button label and link

rating_text — rating display (stars or text)

review_count — review count text

Blocks

announcement_ticker — top announcement text (limit configurable in schema)

hero_section — bottom marquee item text (promotional items)

📱 Responsive Notes & Best Practices

On screens ≤ 768px the layout becomes stacked: media often moves above text for better visual flow.

Use high-resolution images (at least 1200px wide) for crisp hero imagery; set object-fit: cover for consistent cropping.

For videos use YouTube / Vimeo embed URLs for best cross-browser compatibility; for MP4 provide a CDN-hosted file for fast loading.

🔁 Behavior & Accessibility

Announcement and marquee use CSS keyframe animations (continuous scrolling).

If using video, ensure captions or fallback images exist for accessibility.

CTA uses descriptive link text; change cta_label to reflect action (e.g., “Shop Now”, “Get Olive Oil”).

✅ Use Cases

E-commerce landing pages (product launches / seasonal promos)

Food & beverage hero for brands (e.g., olive oil)

Promotional banners with rotating highlights

Any store needing a visually-strong hero with CTA + social proof

💡 Tips for Customization

Keep headline short and punchy (max ~6–8 words).

Use 1–3 marquee/ticker items for clarity; long lists can be duplicated for smooth scroll.

Pair CTA color with brand primary color for better conversions.

Use review count and rating to boost trust (e.g., “★★★★★ — 6,548 reviews”).

License

MIT — feel free to use and adapt for commercial or personal projects. (Add your own license file if required.)

Tags / Topics

Shopify Liquid Hero Section Marquee Responsive Landing Page LPD Components
