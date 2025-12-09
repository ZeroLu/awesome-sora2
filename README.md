# Awesome Sora2 🚀

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/) [![GitHub stars](https://img.shields.io/github/stars/ZeroLu/awesome-sora2?style=social)](https://github.com/ZeroLu/awesome-sora2/stargazers)

> A curated collection of the **best Sora 2 prompts**, video generation guides, JSON techniques, and resources for OpenAI's advanced video model.

This repository focuses on **high-fidelity video prompts** sourced from X (Twitter), Discord, and top prompt engineers. Whether you are looking for **cinematic realism**, **character consistency**, or **complex timeline control**, you will find the most effective inputs here to unlock the full potential of **Sora 2**.

### Sponsor: [Sora Watermark Remover](https://thesorawatermarkremover.com)

[<img width="600" height="265" alt="image" src="https://github.com/user-attachments/assets/b087445c-d3ad-4152-8e28-33a5ca49d4b5" />](https://thesorawatermarkremover.com)


---

## 📖 Table of Contents

1. [Cinematic & Photorealism](#1-cinematic--photorealism)
2. [Epic & Historical](#2-epic--historical)
3. [Anime & Animation](#3-anime--animation)
4. [Consistency & Image-to-Video](#4-consistency--image-to-video)
5. [Advanced Techniques (JSON)](#5-advanced-techniques-json)
6. [Tools & Utilities](#6-tools--utilities)

---

## 1. Cinematic & Photorealism

Prompts focused on high-speed action, realistic camera movements, and blending surreal elements with photorealism.

### 1.1. The Pikachu Pursuit
*A perfect example of blending IP characters into realistic settings with high-speed camera dynamics.*

<img width="500" alt="Sora 2 Pikachu Police Chase Prompt Result" src="https://github.com/user-attachments/assets/3b70be58-46ba-45dd-9994-7ebd579a0252" />

**Prompt:**
```text
Realistic body cam footage of a police officer pulling over a red Ferrari with Pikachu driving. pikachu only says "pika pika" and moves the head in fear, It was a serious offence, so the cop is extremely angry and tries to open the door of the car before Pikachu speeds away quickly. Miami, sunny day, palms
```
*Source: [@javilopen](https://x.com/javilopen/status/1973779306074566797?s=20)*

---

## 2. Epic & Historical

Use these prompts to generate large-scale battles, specific film stocks (65mm), and complex sound design descriptions.

### 2.1. Medieval War Trailer
*Demonstrates crowd simulation, specific color grading, and audio cues.*

<img width="500" alt="Sora 2 Medieval Battle Prompt Result" src="https://github.com/user-attachments/assets/cf86669e-2d70-4cc8-be0c-f5249cb0403b" />

**Prompt:**
```text
Epic medieval war trailer set in a storm-swept valley at dawn.
Hundreds of armored soldiers prepare for battle, banners ripple, horses snort, and the ground trembles under their boots.
Shot on 65mm film with cinematic wide shots and drone sweeps through mist.
The clash begins: swords spark on shields, arrows streak across the sky, mud splatters in slow motion.
Camera tracks a lone knight, silver armor, scarred face, determined eyes, as he charges through chaos.
Cinematic lighting: cold blue-gray tone, natural overcast, enhanced with volumetric fog.
Color grading: desaturated steel hues with crimson accents.
Sound design: thundering drums, echoing war horns, clashing steel, and distant chanting.
Ends with a wide shot of the battlefield in smoke and fire.
Voiceover: “In the age of kings and betrayal… one will rise from ashes.”
Title appears in gold embers: “The Last Kingdom Falls.”
```
*Source: [@azed_ai](https://x.com/azed_ai/status/1983488391636570133?s=20)*

---

## 3. Anime & Animation

How to use time-stamped prompts (`[00:00]`) to control scene cuts and narrative flow in animation.

### 3.1. Sci-Fi Cryogenic Awakening
*A big-budget anime style prompt using temporal markers for precise editing.*

<img width="500" alt="Sora 2 Anime Prompt Result" src="https://github.com/user-attachments/assets/0ae580fb-c2a1-488b-a7ec-7684e954a5c3" />

**Prompt:**
```text
Big budget anime movie with clean lines and smooth movements

[00:00]
The woman earring a short hospital gown suddenly wakes up in her cryogenic chamber with cold breath

[00:02]
Cut to she walks away from the cyrochamber looking around the lab with control consoles on the left

[00:04]
Cut to backside of the woman walking down a hallway at the end of the hallway is a black ladder mounted to the wall that leads up a vertical pathway with some light emitting down from led lights on the walls

[00:06]
Cut to Below the woman as she ascends up the black ladder and above her is a manhole cover with four small holes in it that has light shining through them

[00:08]
cut to the woman climbing out of a manhole in the middle of an overgrown forest

[00:10] 
Cut to the woman amazed looking around the beautiful forest with fireflies and deer running past

[00:12]
Cut to wide shot of the large beautiful forest with destroyed city with overgrown plants all around it in the far background
```
*Source: [@EccentrismArt](https://x.com/EccentrismArt/status/1976308355036742044)*

---

## 4. Consistency & Image-to-Video

Techniques for using reference images to maintain character and object consistency across Sora 2 generations.

### 4.1. The "Expensive Dress" Narrative
*Using an establishing shot and character reference to tell a coherent story.*

**Input Reference Image:**
<img width="500" alt="Sora 2 Input Reference Image" src="https://github.com/user-attachments/assets/e42e8960-fbd0-46bf-b209-eac06b54c35f" />

**Prompt:**
```text
[00:00-00:01] establishing donor shot

[00:01-00:03] two characters are walking at the mall, holding hands 

[00:03-00:05] a close up shot of a girl asking the man what he is getting her for birthday

[00:05-00:08] a close up shot of the man's confused and terrified face as he says "a new dress?"

[00:08-00:10] both walk up to the shop window where a fancy pink dress is placed on a mannequin with a price tag "2000$", man check's the price by leaning towards it

[00:10-00:12] man says: "no, not this one" and walks to the opposite side bringing the girl with him
```

**Result:**
<img width="500" alt="Sora 2 Consistent Video Result" src="https://github.com/user-attachments/assets/91af844d-9d9c-4aae-a82f-6cf0a97cfce8" />

*Source: [@0xFramer](https://x.com/0xFramer/status/1975945198992802022)*

### 4.2. Stylized Character Consistency
*Another example of using image references for consistent style.*

**Reference & Result:**
<img width="500" alt="Sora 2 Style Reference" src="https://github.com/user-attachments/assets/11882749-9719-4c1e-acf4-867919a2374f" />
<img width="500" alt="Sora 2 Style Result" src="https://github.com/user-attachments/assets/dde9dddd-afce-478e-a926-8a4854d89555" />

*Source: [@TheoMediaAI](https://x.com/TheoMediaAI/status/1974507496170725808)*

---

## 5. Advanced Techniques (JSON)

For granular control, use structured **JSON-style prompts**. This separates Camera, Audio, FX, and Dialogue into distinct parameters.

### 5.1. The Chaos Supermarket (JSON Structure)
*High-energy editing using structured data for camera angles and sound effects.*

<img width="500" alt="Sora 2 JSON Prompt Example" src="https://github.com/user-attachments/assets/c1bfec9f-51c2-47eb-bb42-7b8deb05515e" />

**Prompt:**
```text
[00:00]
[CAMERA]: handheld close-up, sweat-beaded BUCK FUZZ (cartoonishly drunk, slurring) grips grocery cart, eyes wild and defiant.
[DIALOGUE]: “GO!”
[SND]: airhorn blast, crowd erupts.
[FX]: motion blur, vignette pulse, zoom flare.

[00:01]
[CAMERA]: ultra-wide as doors burst open; mob floods in like a tsunami of carts.
[SUBJECT]: chaos—pajamas, helmets, one on a Roomba.
[SND]: dubstep drop, screaming.
[EDIT]: whip-pans, rapid micro cuts.

[00:02]
[CAMERA]: first-person sprint through aisles, shelves rattling.
[FX]: GoPro shake, ketchup bottles flying.
[DIALOGUE]: “Grab the rotisserie chickens—LEFT SIDE!”

[00:03]
[CAMERA]: slow-motion tackle over TV; groceries explode mid-air.
[SND]: distorted opera over EDM pulse.

[00:04]
[CAMERA]: low-angle under cart rocketing past, sparks flying.
[DIALOGUE]: shopper yelling, “This coupon EXPIRES TODAY!”

[00:05]
[CAMERA]: dutch-angle close-up of BUCK FUZZ chugging energy drink mid-sprint.
[SND]: can crack + gulp echo.
[EDIT]: jump cut to black for comedic beat.

[00:06]
[CAMERA]: drone over produce chaos; people sliding on lettuce.
[FX]: slow-mo apple explosion.
[DIALOGUE]: announcer voice: “Tonight’s savings… are violent.”

[00:07]
[CAMERA]: security-cam view with timestamp overlay.
[SND]: “WORLD STAR!” chant, VHS flicker.

[00:08]
[CAMERA]: close-up of barcode scanner flashing like police lights.
[DIALOGUE]: cashier: “Price check on morality.”

[00:09]
[CAMERA]: montage—carts crash, cereal avalanches, BUCK FUZZ laughing.
[FX]: glitch overlays, speed-ramp bursts.
[SND]: bass rising to overload.

[00:10]
[CAMERA]: overhead freeze as crowd dives for checkout.
[FX]: confetti of receipts, sparks, neon “SALE”
[SND]: music halts, one distant fart.
[DIR]: freeze-frame on BUCK FUZZ screaming “PRICE OF FREEDOM!” as lights die.
```
*Source: [@dustinhollywood](https://x.com/dustinhollywood/status/1974940457173127645/video/1)*

---

## 6. Tools & Utilities

### 6.1. System Prompt Generator
*Use this System Prompt in ChatGPT or Claude to have it act as a "Visionary Creative Director" that writes Sora 2 JSON prompts for you.*

<img width="500" alt="ChatGPT System Prompt for Sora 2" src="https://github.com/user-attachments/assets/9b5c04bc-0af6-428b-a446-2347d8b66587" />

**System Prompt:**
```xml
<role>
You are a visionary creative director specializing in AI video generation and Sora 2's technical capabilities. You translate creative vision into precise video prompts through natural conversation.
</role>
<approach>
Guide users through conversational creative discovery. Ask ONE thoughtful question at a time, building on their answers. Make it feel like exciting collaboration, not interrogation. Listen for hidden ideas and help them discover visual concepts they didn't know they had.
</approach>
<discovery_flow>
Start with an opening question about their video concept. After each response:
- Acknowledge what excites you about their answer
- Ask ONE follow-up exploring: concept, emotional tone, visual style, key moment, camera movement, or specific details (lighting, colors, setting)
- When they seem stuck, offer 2-3 inspiring options to spark imagination
- After 5-7 exchanges with rich context, announce you're ready to craft their prompt 
</discovery_flow>
<output>
Provide brief analysis covering:
- Core Vision: [synthesize central concept]
- Visual Identity: [aesthetic and technical approach]
- Unique Elements: [what makes this distinctive]
Then deliver complete Sora 2 prompt as copy-paste ready ultra-detailed JSON with these fields:
- prompt (detailed 2-4 sentence description)
- style
- camera_movement
- lighting
- duration
- aspect_ratio
- mood
- additional_parameters (motion_intensity, color_palette)
Add 2-3 sentences on why these choices amplify their vision for Sora 2. 
</output>
<critical_rules>
- ONE question per message - never multiple
- No bulleted question lists or survey feel
- Keep questions short (1-2 sentences)
- Use inspiring language: "imagine," "envision," "picture this"
- Celebrate their ideas with enthusiasm
</critical_rules>
Begin with a single question inviting them to share their video concept.
```
*Source: [@dustinhollywood](https://x.com/dustinhollywood/status/1974940457173127645/video/1)*

---

## Contributing

Got a great Sora 2 prompt? Found a new technique? Contributions are welcome! Please read the contribution guidelines first.

1. Fork the repo
2. Create your branch (`git checkout -b feature/amazing-prompt`)
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ZeroLu/awesome-sora2&type=Date)](https://star-history.com/#ZeroLu/awesome-sora2&Date)
```
