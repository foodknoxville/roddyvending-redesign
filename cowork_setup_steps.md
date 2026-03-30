# COWORK SETUP — RODDY VENDING REDESIGN

## Steps to Set Up the Project in Cowork

1. **Open Cowork** — separate from your Table & Ledger project chat

2. **Create a new project folder** on your desktop or wherever you keep working files:
   - Name it something like `roddy-redesign`
   - This is where the output HTML file will land

3. **Point Cowork at that folder** — when Cowork asks for a working directory, give it the `roddy-redesign` folder

4. **Paste the prompt** — copy the entire contents of the `roddy_vending_redesign_prompt.md` file into Cowork as your opening message. That prompt has everything Claude needs: design direction, copy, structure, technical specs, image placeholder instructions, competitive context

5. **Let it build** — Cowork should generate the full index.html in one pass. If it splits into multiple messages, let it finish before intervening

6. **Review the output** — open the index.html in your browser locally. Check:
   - Does the layout look right on desktop?
   - Pull up phone view (browser dev tools or just resize the window narrow)
   - Are all six service sections there?
   - Are the image placeholders clearly visible and descriptive?
   - Does the copy feel right or does it need your edit pass?

7. **Iterate in Cowork** — if sections need adjustment, just tell Cowork what to change. "Make the hero section taller." "Change the accent color to copper." "Rewrite the About section to emphasize the commissary more." Cowork will edit the file in place.

## Image Generation (Separate Step)

Once the HTML skeleton is solid:

1. **Pick your image tool** — Midjourney ($10/mo), Leonardo.ai (free tier available), DALL-E via ChatGPT (you already have access), or Ideogram
2. **Use the placeholder descriptions as your prompts** — they are written to work as image generation prompts with minimal editing
3. **Target 16:9 aspect ratio**, high quality/resolution
4. **For exploded views specifically**, prompt something like: "Exploded technical view of modern vending machine, components separated showing snack trays, cashless payment terminal, wireless monitoring sensor, refrigeration unit, clean white background, product photography style, 4K"
5. **Save images** into the same `roddy-redesign` folder
6. **Tell Cowork to swap them in** — "Replace the hero placeholder with hero.png" etc.

## Deployment Options

When it is ready to show Jim:

- **Quickest:** Just open the HTML file on your laptop and show him in person
- **Shareable link:** Push to a free Cloudflare Pages project (separate from tableandledger), or use GitHub Pages, or Netlify drop (just drag the folder). Any of these give you a live URL in under 5 minutes
- **Do NOT touch roddyvending.com yet** — this is a demo/pitch, not a deployment. Jim decides if/when it goes live

## What NOT to Do

- Don't overcomplicate this. One HTML file. One evening. That is the power of the demo.
- Don't get sucked into building a multi-page site. Single page. If Jim wants more pages later, that is a paid engagement.
- Don't use the Roddy Vending logo from the current site without checking the resolution — it is probably a tiny JPEG. You may need to recreate it or just use clean text for the demo.
- Don't spend more than a couple hours total. The speed IS the point.
