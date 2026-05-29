# Task 2 — The Creative Visionary 🎨
### DecodeLabs Generative AI Internship | Batch 2026

---

## Brand Brief

**Brand Name:** NexCore Tech  
**Aesthetic:** Cyberpunk-Corporate  
**Color Palette:** Deep navy black + electric teal + vivid purple  
**Mood:** Futuristic authority — a corporation that operates at the edge of technology and power  

All 5 images follow a unified visual language: dark backgrounds, neon-outlined geometry, and a cinematic atmosphere that feels both high-tech and high-stakes.

---

## Generated Assets

### Image 1 — Brand Character / Hero Portrait
![Image 1 – Brand Character](./images/image1.jpg)

**Prompt used:**
```
Cyberpunk corporate brand ambassador, silver-haired executive woman in a black suit 
with glowing purple circuit-board lapels, rainy neon-lit city street at night, 
"NEXUS CORPORATION" holographic billboard in background, dramatic rim lighting, 
cinematic realism, photorealistic, 1:1 aspect ratio
```
**Negative prompt:** `no warm colors, no casual clothing, no daytime, no cartoon style`  
**Techniques:** Persona anchoring, negative prompting, lighting direction (rim light), cinematic realism style

---

### Image 2 — Hero Scene / Office Interior
![Image 2 – Hero Scene](./images/image2.jpg)

**Prompt used:**
```
Futuristic corporate office interior, floor-to-ceiling holographic data displays 
showing world maps and analytics, silhouette of executive in black suit, 
electric teal and purple neon color palette, cyberpunk-corporate aesthetic, 
cinematic wide-angle shot, dramatic rim lighting, ultra-detailed, 16:9 aspect ratio
```
**Negative prompt:** `no warm colors, no orange tones, no daylight, no casual clothing`  
**Techniques:** Aspect ratio (16:9), lighting style (cinematic), negative prompting, compositional framing

---

### Image 3 — Logo Concept
![Image 3 – Logo](./images/image3.jpg)

**Prompt used:**
```
Minimalist tech company logo, geometric hexagon shape with circuit board lines inside, 
electric teal and purple neon gradient, dark black background, corporate clean style, 
cyberpunk aesthetic, vector art, flat design, no text, centered composition, 1:1 aspect ratio
```
**Negative prompt:** `no humans, no gradients on background, no realistic textures, no serif fonts`  
**Techniques:** Aspect ratio (1:1), flat vector style, negative prompting, color palette locking

---

### Image 4 — Icon Set
![Image 4 – Icon Set](./images/image4.jpg)

**Prompt used:**
```
Set of 9 flat UI icons on dark navy background: AI chip, neural network, analytics chart, 
security shield, satellite, cloud sync, fingerprint scanner, global network, 
robot head — all outlined in teal-to-purple gradient, cyberpunk corporate icon set, 
consistent line weight, minimalist, 3x3 grid layout, 1:1 aspect ratio
```
**Negative prompt:** `no color fill inside icons, no drop shadows, no realistic style, no text labels`  
**Techniques:** Style-seed phrase for consistency, grid layout instruction, negative prompting, matched line weight

---

### Image 5 — Social Media Banner / Background
![Image 5 – Banner](./images/image5.jpg)

**Prompt used:**
```
Aerial view of a futuristic city built like a circuit board, skyscrapers connected 
by glowing teal data streams and neon grid lines, deep purple stormy sky, 
cyberpunk-corporate aesthetic, cinematic drone shot perspective, ultra-detailed, 
electric teal and violet color palette, 16:9 aspect ratio
```
**Negative prompt:** `no faces, no cars, no organic nature elements, no warm tones, no text`  
**Techniques:** Perspective direction (aerial/drone), aspect ratio (16:9), negative prompting, lighting

---

## Prompting Techniques Demonstrated

| Technique | Where Used | Purpose |
|---|---|---|
| Negative prompting | All 5 images | Eliminated unwanted colors, styles, and elements |
| Aspect ratio control | Images 2, 5 (16:9) and 1, 3, 4 (1:1) | Matched intended use case (banner vs square) |
| Lighting style direction | Images 1, 2 | Cinematic rim lighting for dramatic effect |
| Style seed phrase | All 5 images | Kept Cyberpunk-Corporate aesthetic consistent |
| Compositional instruction | Images 2, 5 | Guided camera angle and subject placement |
| Persona anchoring | Image 1 | Defined a specific brand character with visual identity |

---

## Image-to-Image Consistency Strategy

Since Bing Image Creator (DALL-E 3) does not natively support image uploads for reference, **style consistency was achieved through a repeating "style anchor phrase"** embedded in every prompt:

> *"electric teal and purple neon, dark navy/black background, cyberpunk-corporate aesthetic, consistent line weight"*

This acted as a textual style seed — ensuring the model's output stayed visually coherent across all 5 assets without needing to upload a reference image.

For true image-to-image translation (available in tools like DALL-E via ChatGPT Plus or Stable Diffusion), you would upload Image 1's character and prompt: *"Same character, now seated at a holographic terminal in a dark server room"* — keeping the subject identical while changing the scene.

---

## Tools Used

- **Image generation:** Bing Image Creator (DALL-E 3) — free tier
- **Prompting method:** Advanced text prompting with negative prompts, aspect ratios, lighting descriptors, and style anchoring

---

## Brand Consistency Analysis

All 5 images share:
- ✅ Dark navy / black backgrounds
- ✅ Electric teal + purple neon color palette  
- ✅ Cyberpunk-Corporate visual tone
- ✅ High-contrast cinematic lighting
- ✅ No warm colors (orange, yellow, red) — excluded via negative prompts
- ✅ Professional, corporate subject matter

---

*Submitted as part of the DecodeLabs Generative AI Industrial Training — Batch 2026*
