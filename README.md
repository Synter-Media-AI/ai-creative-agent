# AI Creative Generator MCP Starter Kit — Generate Ad Images & Videos with AI

[![MCP Compatible](https://img.shields.io/badge/MCP-compatible-blue)](https://modelcontextprotocol.io)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform: AI Creative](https://img.shields.io/badge/Platform-AI%20Creative-F59E0B)](https://syntermedia.ai)

**Generate ad-ready images and videos without a design team.** Open this repo in Amp, Cursor, or VS Code and create platform-optimized ad creatives with AI — Imagen 4 for images, Veo for video, with automatic sizing for Google, Meta, LinkedIn, TikTok, and more.

---

## Why AI Creative Generation?

The #1 bottleneck in advertising isn't targeting or bidding — it's creative. Every campaign needs images and videos in platform-specific sizes. Every A/B test needs variants. Every week, creative fatigues and needs refreshing.

Hiring designers, coordinating creative briefs, and waiting 3-5 days for deliverables doesn't scale. AI creative generation produces ad-ready assets in seconds: product shots, lifestyle images, banner ads, and short-form video — all sized for each platform's requirements.

This doesn't replace your design team. It fills the gap when you need 5 image variants for an A/B test by tomorrow, or a new display banner because your current creative fatigued, or a dozen product shots for a Google PMax campaign.

**Best for:** Teams without designers, rapid A/B testing, filling creative gaps, generating platform-specific sizes, prototyping ad concepts before investing in professional production.

---

## Quick Start (30 Seconds)

### Amp / Cursor / VS Code (Copilot)

1. **Get a free API key** at [syntermedia.ai/developer](https://syntermedia.ai/developer)
2. **Set the key:**
   ```bash
   export SYNTER_API_KEY=syn_your_key_here
   ```
3. **Open this repo** in your editor
4. **Start chatting** — MCP tools are pre-configured in `.mcp.json`

### Claude Desktop

Copy `claude_desktop_config.json` to your Claude config directory and replace the API key:

- **macOS:** `~/Library/Application Support/Claude/claude_desktop_config.json`
- **Windows:** `%APPDATA%\Claude\claude_desktop_config.json`

---

## What You Can Do

| Capability | Example |
|-----------|---------|
| **Product Images** | "Generate a product shot of a coffee mug on a clean white background" |
| **Lifestyle Images** | "Create a lifestyle image of someone using a laptop at a coffee shop" |
| **Display Banners** | "Generate a 1200x628 display banner for our SaaS product" |
| **Social Media Ads** | "Create a 1080x1080 Instagram ad for our skincare launch" |
| **Video Ads** | "Generate an 8-second product reveal video for TikTok" |
| **Multi-Size Export** | "Create the same ad in Google Display, Meta Feed, and LinkedIn sizes" |
| **A/B Test Variants** | "Generate 5 image variants with different backgrounds for testing" |
| **Competitor-Inspired** | "Analyze Meta Ads Library for our competitor and create a similar style" |
| **Brand-Consistent** | "Generate creatives matching our brand colors (navy + gold)" |
| **Platform-Specific** | "Make this image work as both a landscape (Google) and square (Instagram)" |

---

## Example Conversations

### 1. Multi-Platform Creative in One Go

> **You:** I need ad images for a new sneaker launch. I'm advertising on Google, Meta, and LinkedIn.
>
> **Agent:** I'll generate platform-optimized creatives. Here's what each platform needs:
>
> | Platform | Size | Format | Style |
> |---|---|---|---|
> | Google Display | 1200x628 | Landscape | Product-focused, clean background |
> | Google PMax | 1200x628 + 1200x1200 | Both | Product + lifestyle mix |
> | Meta Feed | 1080x1080 | Square | Lifestyle, vibrant colors |
> | Meta Stories | 1080x1920 | Vertical | Full-screen, bold text overlay |
> | LinkedIn Feed | 1200x627 | Landscape | Professional, minimal |
>
> **Image generation plan:**
> 1. Hero shot: Sneaker on white background, 45° angle, dramatic lighting (for Google)
> 2. Lifestyle shot: Person walking in urban setting wearing the sneakers (for Meta)
> 3. Flat lay: Sneakers with complementary accessories (for Instagram)
> 4. Professional/clean: Sneaker with minimal copy overlay (for LinkedIn)
>
> Each image auto-exported in all required sizes. Total assets: 12 images (4 concepts × 3 sizes each).
>
> **You:** Generate all 4 concepts. Make the lifestyle shot look like a NYC street style photo.
>
> **Agent:** Generating with Imagen 4... 
>
> Done. 12 images generated and saved to your artifact store. Here's a preview:
> - Hero shot: Clean, studio-quality product image ✅
> - NYC street style: Urban setting, natural lighting, authentic feel ✅
> - Flat lay: Overhead arrangement with laces, socks, shoehorn ✅
> - LinkedIn professional: Minimal, high-contrast with subtle brand gradient ✅
>
> All images are ready for upload. Want me to create campaigns on Google, Meta, and LinkedIn with these creatives?

### 2. A/B Test Creative Variants

> **You:** My current ad is performing okay but I want to test variations. Generate 5 versions with different backgrounds.
>
> **Agent:** I'll create 5 variants of your product image, each with a distinct background:
>
> | Variant | Background | Hypothesis |
> |---|---|---|
> | A (control) | Solid white | Clean, product-focused (your current) |
> | B | Gradient (navy → teal) | Brand colors, modern SaaS feel |
> | C | Lifestyle desk scene | Contextual — shows the product "in use" |
> | D | Abstract geometric pattern | Eye-catching, stops the scroll |
> | E | Bold solid color (coral) | High contrast, emotional appeal |
>
> **How to run the test:**
> - Create a Meta A/B test with all 5 variants
> - Equal budget split ($20/day per variant = $100/day total)
> - Run for 7 days minimum (need statistical significance)
> - Primary metric: CTR (for top-of-funnel) or CPA (for bottom-of-funnel)
>
> **What typically wins:** In ecommerce, lifestyle backgrounds (C) usually beat solid colors. In SaaS, gradient backgrounds (B) outperform. But the data will tell you — that's why we test.
>
> Generating all 5 variants now...

### 3. Video Ad Generation for TikTok

> **You:** I need a short video ad for TikTok. Something that feels like an organic TikTok, not a commercial.
>
> **Agent:** For TikTok, the ad should feel native — UGC-style, vertical (9:16), and hook-first. Here's what I'll generate:
>
> **Video concept: Product reveal with text overlay**
> - **Duration:** 8 seconds (TikTok sweet spot)
> - **Aspect ratio:** 9:16 (full screen vertical)
> - **Structure:**
>   - Seconds 0-2: Hook — "Wait, this actually works?" (text on screen, product partially visible)
>   - Seconds 2-5: Reveal — Product in action, satisfying visual
>   - Seconds 5-7: Benefit — "No more [problem]" text overlay
>   - Seconds 7-8: CTA — "Link in bio" or shop button
>
> **Generation options:**
> | Provider | Speed | Quality | Best For |
> |---|---|---|---|
> | Veo (Google) | 60-90 sec | Highest | Realistic product shots, cinematic feel |
> | Runway | 30-45 sec | High | Stylized, creative transitions |
> | Luma | 20-30 sec | Good | Quick iterations, experimental |
>
> **You:** Use Veo. Make it look like someone unboxing the product at home.
>
> **Agent:** Generating 8-second UGC-style unboxing video with Veo...
>
> Done. Video saved to your artifact store. Key details:
> - Format: MP4, 9:16, 1080x1920
> - Duration: 8.2 seconds
> - Style: Hands opening a box, revealing product, natural lighting
> - Ready for TikTok upload or Spark Ad conversion

### 4. Competitor-Inspired Creative

> **You:** Our competitor's Meta ads look amazing. Can you analyze what they're doing and create something similar for us?
>
> **Agent:** I'll scrape their Meta Ads Library and reverse-engineer their creative strategy.
>
> **Competitor analysis complete:**
>
> **Creative patterns found:**
> | Pattern | Frequency | Performance Signal |
> |---|---|---|
> | Before/After split image | 40% of ads | Longest running = highest performer |
> | User testimonial with product | 25% | Second longest running |
> | Lifestyle overhead flat lay | 20% | Medium duration |
> | Bold text over solid background | 15% | Shortest duration (likely worst) |
>
> **Color palette:** Soft pastels (blush, sage, cream) — very D2C aesthetic
> **Typography:** Clean sans-serif, large headline, minimal body copy
> **Layout:** Product always visible, never hidden behind text
>
> **What I'll create for YOUR brand:**
> 1. Before/After split image (their top pattern) adapted with YOUR product + YOUR brand colors
> 2. Testimonial-style image with your product and a realistic quote
> 3. Lifestyle flat lay matching your product category
>
> **Important:** I'm creating *inspired* work, not copies. Same structural patterns (split layout, flat lay) but your brand identity, your products, your messaging.
>
> Shall I generate these?

### 5. Brand-Consistent Creative System

> **You:** I need all my ads to look cohesive. Our brand colors are navy (#1a1a4e) and gold (#d4a429). How do I make AI creative stay on-brand?
>
> **Agent:** I'll set up a brand-consistent creative system. Here's how:
>
> **Brand parameters I'll lock in:**
> - Primary: Navy #1a1a4e (backgrounds, headers)
> - Accent: Gold #d4a429 (CTAs, highlights, borders)
> - Background: Off-white #f5f3ef (clean negative space)
> - Text: White on dark, navy on light
> - Style keywords: "Premium," "Minimalist," "High-end"
>
> **I'll generate a creative kit:**
> 1. **Display banner template** — navy gradient background, gold CTA button, product centered
> 2. **Social media template** — product on off-white, navy text, gold accent line
> 3. **Stories template** — full-bleed navy, gold title text, product hero
> 4. **Video intro/outro** — navy background with gold logo reveal
>
> Each future generation will use these brand parameters as constraints. When you say "generate a new product ad," it'll automatically use navy/gold without you specifying.
>
> **Consistency rules I'll enforce:**
> - Logo always in the same position (top-left or bottom-right)
> - CTA always in gold (#d4a429) with white text
> - Product images never cropped below 50% of frame
> - Never use more than 2 colors beyond brand palette

---

## AI Creative Tips

1. **Generate platform-specific sizes in one go.** One concept, many sizes. A 1080x1080 Instagram ad, 1200x628 Google Display, and 1080x1920 Stories version should all exist.
2. **Always A/B test AI creative vs human creative.** AI creative is great for volume and speed, but test it against professional work. Sometimes AI wins — especially for variants and iterations.
3. **UGC-style outperforms polished on TikTok and Meta.** For video ads, "phone-quality" generated content often beats studio production. Match the platform's native aesthetic.
4. **Refresh creative every 2-3 weeks.** AI makes this possible. Generate new variants before your current creative fatigues, not after.
5. **Imagen 4 for photorealistic products, Flux for artistic styles.** Match the AI model to your creative need. Product shots need photorealism. Brand imagery can be more artistic.
6. **Background matters more than you think.** A product on a lifestyle background can outperform the same product on white by 2-3x on social platforms.
7. **Always include a CTA in the image.** Display ads with a visual "Shop Now" or "Learn More" button outperform those with product-only imagery by 20-30%.

---

## FAQ

### Is there an MCP for AI ad creative generation?
Yes — this repo. It connects to Imagen 4, Veo, Flux, and other models for generating ad images and videos through conversation.

### What AI models are available?
Images: Imagen 4 (photorealistic), Flux (artistic), SDXL (general). Video: Veo (cinematic), Runway (stylized), Luma (fast iterations).

### Can AI-generated images be used in Google Ads?
Yes. Google, Meta, LinkedIn, TikTok, and all major platforms accept AI-generated creative. There are no specific policies against AI-created ad images.

### How much does image generation cost?
Image generation uses Synter credits. Imagen 4 costs ~80 credits per image. At the base credit price, that's approximately $0.08 per image. Video generation costs more (100-1100 credits depending on the model).

### Can the AI match my brand colors?
Yes. Provide your brand colors (hex codes), fonts, and style guidelines, and the agent will constrain all generations to your brand identity.

---

## Related Repos

- [google-ads-agent](https://github.com/Synter-Media-AI/google-ads-agent) — Use generated images in Google Display & PMax
- [meta-ads-agent](https://github.com/Synter-Media-AI/meta-ads-agent) — Upload to Meta ad campaigns
- [tiktok-ads-agent](https://github.com/Synter-Media-AI/tiktok-ads-agent) — TikTok video ads
- [linkedin-ads-agent](https://github.com/Synter-Media-AI/linkedin-ads-agent) — LinkedIn Sponsored Content images
- [cross-platform-ads-agent](https://github.com/Synter-Media-AI/cross-platform-ads-agent) — Multi-platform campaign launch
- [shopify-agent](https://github.com/Synter-Media-AI/shopify-agent) — Product images for shopping ads

---

## License

MIT — see [LICENSE](LICENSE) for details.

Built by [Synter](https://syntermedia.ai) · [Get API Key](https://syntermedia.ai/developer) · [Documentation](https://syntermedia.ai/docs)
