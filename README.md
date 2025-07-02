# Shopify Liquid Snippets

A curated set of Shopify Liquid snippets used across real-world projects like [Blush+Wren](https://blushwren.com) and [Maysama](https://maysama.com).  
These snippets demonstrate custom section builds, advanced metafield logic, and LLMO-friendly schema integration for Shopify product pages.

Jump to → [Custom Colour Builder](#custom-colour-builder) • [LLMO Schema FAQ](#llmo-schema-faq) • 

---

## 🔧 Snippets

### Custom Colour Builder
`1. custom-colour-builder.liquid`

A fully custom step-by-step colour selection section using HTML, CSS, JavaScript, and Liquid. This component uses metafields and conditional logic to guide users through up to three shade selections, plus optional root blends.

**Use cases:**
- Visual product configuration (e.g., hair extensions, bundles, custom kits)
- Multi-step customisers powered by metafields
- Advanced colour/pattern selection tools with conditional logic

**Features:**
- Built-in rules for when root stretch is or isn’t selected
- Dynamic line item property output
- Minimalist, UX-led UI structure with custom styling

---

### LLMO Schema FAQ
`2. llmo-schema-faq-json.liquid`

Custom JSON-LD schema markup for Shopify FAQ blocks, optimised for Google rich results and future-facing LLMO (Large Language Model Optimisation) visibility.

**Note:** This schema is currently under development and structured to be easily expanded in the future.

**Highlights:**
- Injects product metadata from Shopify and metafields (e.g., custom colour codes, lifespan, short description)
- Includes placeholders for reviews and aggregateRating if/when added
- Structured to be lean, compliant, and scalable

---

### Reusable WhatsApp Float (w/ Animation)
`3. whatsapp-float.liquid

Custom reusable whatsapp float to be used across any shopify store and increase customer conversation and conversion.

**Highlights:**
- Fully customisable in theme editor
- Optional pre-populated message on click-through
- Enable/Disable on checkout pages for enhanced UX control


#### Coming Soon

- Custom Mega Menu with Images designed for Shopify 2.0


## 📄 License

MIT – Feel free to use, modify, and build upon these snippets in your own Shopify projects. Attribution appreciated.
