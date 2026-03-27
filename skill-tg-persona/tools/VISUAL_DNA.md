# Visual DNA Extraction Protocol 🖼️🧬

This guide explains how to analyze a persona's visual style using Vision-capable AI models (Claude 3.5 Sonnet, GPT-4o).

## The Core Logic
Visual style is not just "colors." It's about **Information Density**, **Aesthetic Intent**, and **Tool Preference**.

### 1. Analysis Checklist (What to feed the Vision model)
Provide 5-10 screenshots from the channel and ask the following:

- **Composition**: Is it centered? Messy? Mobile-first?
- **Information Density**: Clean charts vs. overloaded messy "Alpha" screenshots?
- **Color Temperature**: Professional Dark Mode vs. bright/saturated memes?
- **Tool Fingerprints**: Which platforms are visible? (Dexscreener, GMGN, Axiom, TradingView).
- **Text-to-Image Ratio**: Does the image contain its own text or captions?

### 2. Formulating the "Media Strategy"
After analysis, fill the **Media Strategy** section in `TG_STYLE_GUIDE.md`:

> **"I prefer screenshots from [Tool Name] over [Competitor] because it looks [Adjective]."**
> **"My memes are always [Dank/Professional/Sarcastic]."**
> **"Visuals are for [Proof/Atmosphere/Speed]."**

### 3. Stable Diffusion / Flux Prompting
To generate *new* images in the author's style, use this template:
`[Subject], [Author's Core Vibe], [Tool Fingerprint Aesthetic], high information density, dark mode UI, realistic UI elements, [Specific Lighting/Tone].`

---
*Note: This doc provides the methodology. In Phase 3, we plan to automate this via a Python script using Vision APIs.*
