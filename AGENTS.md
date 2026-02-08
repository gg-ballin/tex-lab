---
alwaysApply: true
---

# Role: Senior Mobile & Web Engineer 

## Computers used for development
- **Principal PC:** Mac Mini M2 Pro (Apple Silicon, ARM64)
- **Secondary PC:** MacBook Pro i7 (Intel, x86_64)

## Domain
- **Website: https://texlab.com.ar**
- **Domain purchased in nic.ar**
- **Domain hosted in Cloudflare**
- **Email:** contacto@texlab.com.ar

## Business
- **Business core**: Argentinean small B2B business that sells corporate clothing for small to medium businesses that require branded t-shirts, hoodies and more.
- **Players**: This site is managed by 2 people, Lautaro and Germán (me).
- **Business strategy**: This site is planned for handling email and Whatsapp marketing campaigns
-**Language**: This page and it's contents should be strictly for Argentina's demographics and language. The frontend should be served ALWAYS in spanish. 

## Technical Stack
- **Framework:** Astro 5.x (latest stable).
- **Preferred Package Manager:** NPM.
- **Styling:** Tailwind CSS with the `@tailwindcss/typography` plugin.

## Mobile
- **Mobile structure**: It's mandatory for the app to follow good UX/UI principles that can enhance the experience of possible new customers. When campaigns should roll, the landing page will be open via WhatsApp.

## Marketing
- **Email and WhatsApp**: This website should be our anchor for creating marketing campaigns via e-mail and WhatsApp. This integrations should exist and it's core to the business 

## Implementation Rules
- **SEO:** Ensure semantic HTML (header, main, footer, article) and proper meta tags.

## Version control & Commands
- **Version control mandatory rule:** NEVER add or commit anything.
- **Working directory:** Always assume the current working directory (CWD) is the project root. When suggesting or executing terminal commands (e.g., installations, builds, or development scripts), never prepend them with cd commands or include absolute system paths. Execute all commands directly from the root using relative paths if necessary

## Documentation
- **Dedicated directory:** Everytime you need to create a new `.md`, `.mdc` or `.mdx` file, please, create it under the `/docs/` directory. If something has changed in the requirements of some of the `.md` files, please check them and update them. 
- **Only do new docs upon request of me**

## Theme
- **Colors should be in global.css**

## Prompting rules
- Prompts should be in English.

## Language & Tone
- **Dialect for the web:** Spanish (Argentina).
- **Style:** Use "Voseo" (e.g., "Comprá", "Vení", "Tus remeras") instead of neutral Spanish or "Tú".
- **Tone:** Professional B2B but accessible. Focus on reliability and local presence.

## Assets & Images
- **Storage:** All local images must be in `/src/assets/images/`.
- **Optimization:** Use Astro's `<Image />` component for automatic optimization (WebP/AVIF).
- **Placeholders:** If an image is missing, use a descriptive `<div class="bg-slate-200">` with the aspect ratio instead of broken links.

## Marketing & Conversion
- **Events:** Every WhatsApp/Email CTA must be easily identifiable for future GTM/Pixel integration.
- **Forms:** Use simple validation. Ensure phone inputs are optimized for Argentine formats (+54).

## Development Standards
- **Components:** Favor Small, reusable Astro components in `/src/components/`.
- **Mobile First:** Tailwind classes should prioritize mobile views first (default), then use `md:` or `lg:` for desktop.