# AI Video Prompt Library — UGC & Product Videos

A collection of tested prompts for generating AI UGC ads and e-commerce product videos using models like **Veo 3.1**, **Runway**, **Kling**, and **Grok**.

Built for marketers, Shopify/e-commerce sellers, and indie developers who want a starting point instead of staring at a blank prompt box.

## Contents

- [UGC Ad Prompts](#ugc-ad-prompts)
- [Product Video Prompts](#product-video-prompts)
- [Prompt Structure Tips](#prompt-structure-tips)
- [Where to Run These](#where-to-run-these)
- [Contributing](#contributing)

---

## UGC Ad Prompts

Prompts for generating talking-head / testimonial-style AI personas for TikTok and Facebook ad creatives.

### 1. Casual Testimonial
```
A young woman in her 20s sitting in a bright, casual living room, talking 
directly to camera in a natural, slightly excited tone. She's holding up a 
[PRODUCT] and gesturing as she explains why she loves it. Handheld phone 
camera feel, natural lighting, casual outfit, authentic UGC style — not 
overly polished.
```

### 2. Before/After Reaction
```
A person filming themselves in a bathroom mirror, reacting with surprise and 
excitement after using [PRODUCT]. Quick cut style, energetic, slightly shaky 
handheld camera, bright bathroom lighting, genuine reaction shot — looks like 
a real customer video, not a commercial.
```

### 3. Unboxing Style
```
Close-up shot of hands unboxing [PRODUCT] on a wooden table, soft natural 
light from a window, calm and satisfying pacing, slight ASMR feel, 
shallow depth of field, vertical 9:16 format for TikTok/Reels.
```

### 4. "Day in My Life" Integration
```
A person going about their morning routine — making coffee, getting ready — 
and naturally using [PRODUCT] as part of the routine. Warm, cozy apartment 
lighting, lifestyle vlog aesthetic, casual pacing, vertical format.
```

---

## Product Video Prompts

Prompts for turning static product photos into cinematic video ads — common for Shopify/WooCommerce listings.

### 5. Slow Rotation / Hero Shot
```
A [PRODUCT] sitting on a minimalist pedestal, slowly rotating 360 degrees 
against a soft gradient background. Studio lighting with subtle reflections, 
clean and premium feel, smooth camera orbit, 4-5 second loop, suitable for 
product page hero video.
```

### 6. Lifestyle Context Shot
```
A [PRODUCT] placed on a clean kitchen counter near a window, with soft 
morning light moving across the scene. Subtle steam/condensation details if 
applicable, calm and aspirational mood, slow push-in camera movement.
```

### 7. Macro Detail Shot
```
Extreme close-up macro shot of [PRODUCT] showing texture and material detail, 
slow camera movement revealing craftsmanship, soft directional lighting, 
shallow depth of field, premium and tactile feel.
```

### 8. Action/Use-Case Demo
```
A pair of hands demonstrating how [PRODUCT] works in real use — opening, 
applying, adjusting, etc. Bright and clean setting, smooth and confident 
movements, close-up framing, instructional but visually appealing pacing.
```

---

## Prompt Structure Tips

A few patterns that tend to produce more consistent results across models:

- **Be specific about camera behavior** — "slow push-in," "360 orbit," "handheld shake" all produce noticeably different results than leaving it unspecified.
- **Specify aspect ratio explicitly** for social formats — "vertical 9:16" matters more than you'd think.
- **Describe lighting in concrete terms** — "soft window light," "studio softbox," "golden hour" rather than just "good lighting."
- **For UGC specifically**, explicitly request "not overly polished" / "authentic" — models otherwise tend to default to overly cinematic output.
- **Keep product placeholders generic** (`[PRODUCT]`) and replace with a short, concrete description of your actual item — "a matte black ceramic mug" works better than just "mug."

## Where to Run These

These prompts are model-agnostic and should work across most text/image-to-video tools. If you want to test a few quickly without setting up API access or committing to a subscription, [PayPerVideo](https://paypervideo.online/) lets you run prompts against Veo 3.1, Runway, Kling, or Grok on a pay-per-generation basis — useful for comparing how the same prompt performs across different models.

## Contributing

Found a prompt that consistently works well? PRs welcome:

- Add it under the relevant category
- Note which model(s) you tested it on, if known
- Keep placeholders generic (`[PRODUCT]`, `[BRAND]`, etc.) so others can adapt it

## License

[CC0](https://creativecommons.org/publicdomain/zero/1.0/) — public domain. Use freely.
