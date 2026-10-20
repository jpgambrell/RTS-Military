# RTS Game – Concept Art Prompt Library (GPT Image 2.5 Sunburst on Higgsfield)

## Model settings (Higgsfield)
- **Model:** GPT Image 2.5 (`gpt_image_2_5`), **variant: Sunburst**.
- **Quality:** `high` for keepers (use `medium` while exploring; `xhigh`/`max` only for final hero art, since they cost more).
- **Resolution:** `2k` by default, `4k` for final sheets.
- **Aspect ratio:** `16:9` (or `21:9`) for master sheets and lineups; `1:1` for single units; `3:4` for single infantry; `16:9` for turnarounds.
- **Background:** leave unset for studio-gray concept art; set `transparent` when you want a clean cut-out of a unit for in-game icons or placeholders.
- **References:** for every follow-up edit, attach the previous image as an image reference so the design stays consistent. Attach the faction master sheet too when generating a new unit, so it matches the family.

## Shared rules (apply to every prompt)
- **Setting: the 2040s.** Grounded military realism extrapolated about 20 years forward: an evolution of today's equipment, not sci-fi. Think more unmanned and optionally-crewed systems, drone companions, active camouflage panels, integrated sensor fusion, hybrid-electric and electric drivetrains, and faceted low-observable shaping. No energy weapons, mechs, or hover tech.
- The reference look is the first GPT Image 2.5 output (saved in `concept-art/references/`): photoreal hard-surface rendering, olive-tan with dark gray splinter blocks, orange chevron marking.
- Faction palette (Faction A): olive-tan / dark gray-olive base, dark gray accents, small orange faction marking on every unit.
- Opposing faction (Faction B): dark gray-blue base with red markings, same designs.
- Every unit must have a distinct, chunky silhouette readable from a high top-down RTS camera.
- Neutral light-gray studio background, crisp hard-surface rendering, soft studio lighting, light wear.
- No text, no real-world insignia or logos. Describe aircraft by role, not real names (avoids copying real designs).
- GPT Image 2.5 follows long, descriptive sentences closely, including numbered layouts, so keep the full-prose prompts below rather than keyword lists.
- Iterate by editing: attach the image you like as a reference and describe only the change, instead of regenerating from scratch.
- Because GPT Image renders text well, it may add labels or callouts on sheets. Keep "No text, no labels, no logos" in every prompt, and repeat it in edits if text appears.

---

## 1. Ground vehicles

### Master sheet
```
Professional concept art sheet for a modern real-time strategy video game, showing a family of four 2040s military ground vehicles designed by the same fictional faction. Clean, grounded realism extrapolated to the 2040s: angular faceted armor, low-profile silhouettes, modular add-on armor panels, integrated sensor masts, remote weapon stations, and hybrid-electric drivetrains.

Vehicles, arranged left to right on a neutral light-gray studio background:
1. A fast light tactical vehicle (jeep class), open-backed, roll cage, roof-mounted remote machine gun, oversized off-road tires.
2. An 8x8 wheeled armored troop transport with rear ramp, firing ports, slat armor on the sides, and a small turret.
3. A mobile missile launcher on a heavy 6x6 truck chassis with an armored cab and an elevating box launcher holding sealed missile canisters, shown partially raised.
4. A main battle tank with a low unmanned turret, long smoothbore cannon, active protection system launchers, and wide tracks with side skirts.

Each vehicle shown in a three-quarter front view at consistent scale relative to one another. Unified faction color scheme: desaturated olive-tan base with dark gray accents and a small orange faction marking repeated on every vehicle. Readable, chunky shapes that will stay recognizable from a top-down RTS camera. Crisp hard-surface rendering, soft studio lighting, subtle wear and dust on lower hulls. No text, no real-world insignia, no logos.
```

### Style line (append to each vehicle prompt)
```
Modern RTS game concept art, grounded 2040s military design, angular faceted armor, olive-tan base with dark gray accents and a small orange faction marking, three-quarter front view on a neutral gray background, crisp hard-surface rendering, soft studio lighting, light dust weathering, silhouette readable from a high top-down camera, no text or real-world insignia.
```

### Jeep / light recon
```
A fast, lightweight 4x4 tactical recon vehicle with an open crew area, tubular roll cage, roof-mounted remote weapon station with a heavy machine gun, spare tire and jerry cans on the rear, long-travel suspension, and a small folding sensor mast.
```

### Troop transport
```
An 8x8 wheeled armored personnel carrier with a sloped wedge-shaped front, rear hydraulic ramp lowered to show bench seating inside, side firing ports, bolt-on slat armor, smoke grenade launchers, and a compact remote turret with an autocannon.
```

### Mobile missile launcher
```
A heavy 6x6 armored truck carrying a long-range missile launcher: an armored blast-proof cab up front, stabilizer outriggers deployed, and a large box launcher on the rear raised to a 45-degree firing angle, holding six sealed missile canisters. A separate small radar unit folds out behind the cab.
```

### Tank
```
A modern main battle tank with a low-profile unmanned turret, long 130mm smoothbore cannon, hard-kill active protection launchers on the turret corners, panoramic sensor sights, wide tracks with segmented side skirts, and a rear hybrid-electric power pack with cooling vents.
```

### Vehicle follow-ups (attach the vehicle image as a reference)
- "Show this exact vehicle from the top-down 45-degree angle an RTS camera would use."
- "Create an orthographic turnaround of this vehicle: front, side, rear, and top views."
- "Recolor this vehicle for an opposing faction: dark gray-blue base with red markings, keep the design identical."
- "Add a damaged variant: scorched armor, missing side skirts, smoke from the engine deck."
- "Create an upgraded tier-2 version with heavier reactive armor and a second weapon."

---

## 2. Aircraft

### Master sheet
```
Professional concept art sheet for a modern real-time strategy video game, showing a family of four 2040s military aircraft designed by the same fictional faction as its ground forces. Grounded realism extrapolated to the 2040s: angular faceted stealth shaping, blended surfaces, internal weapon bays, conformal sensors, and minimal visible seams.

Aircraft, arranged on a neutral light-gray studio background:
1. A long-endurance armed surveillance drone with long thin wings, a bulbous sensor nose with no cockpit, a rear pusher propeller, a V-tail, and precision missiles under the wings.
2. A single-seat stealth fighter jet with a diamond-shaped fuselage, canted twin tails, a gold-tinted canopy, and side intakes.
3. A tandem two-seat attack helicopter with a narrow armored fuselage, stub wings loaded with rocket pods and missiles, a chin-mounted cannon, a mast-mounted radar dome, and a shrouded tail rotor.
4. A large tailless flying-wing stealth bomber with a sawtooth trailing edge, buried engines with shielded exhausts, and an open bomb bay showing its payload.

Each aircraft shown in a three-quarter top-down view at consistent relative scale, with the bomber clearly the largest. Unified faction color scheme: dark gray-olive base with lighter gray accents and a small orange faction marking repeated on every aircraft. Bold, distinct silhouettes that stay recognizable from a high top-down RTS camera. Crisp hard-surface rendering, soft studio lighting, subtle wear on panel edges. No text, no real-world insignia, no logos.
```

### Style line (append to each aircraft prompt)
```
Modern RTS game concept art, grounded 2040s military aircraft design, angular faceted stealth shaping, dark gray-olive base with lighter gray accents and a small orange faction marking, three-quarter top-down view on a neutral gray background, crisp hard-surface rendering, soft studio lighting, light panel-edge wear, silhouette readable from a high top-down camera, no text or real-world insignia.
```

### Armed recon drone
```
A long-endurance unmanned combat drone with very long slender straight wings, a smooth bulbous nose housing satellite antennas, an under-nose rotating sensor turret, a rear pusher propeller, an inverted V-tail, and four precision guided missiles on underwing pylons. No cockpit or windows anywhere.
```

### Fighter jet
```
A single-seat stealth air-superiority fighter with a flat diamond-shaped fuselage, sharply swept trapezoidal wings, outward-canted twin vertical tails, a frameless gold-tinted canopy, angular side air intakes, thrust-vectoring nozzles, and one internal weapons bay open to show air-to-air missiles.
```

### Attack helicopter
```
A heavily armed tandem two-seat attack helicopter with a narrow faceted armored fuselage, stepped cockpits, a five-blade main rotor with a radar dome on top of the mast, a shrouded fan-style tail rotor, stub wings carrying rocket pods and anti-tank missiles, and a chin-mounted rotary cannon.
```

### Stealth bomber
```
A massive tailless flying-wing stealth bomber with a smooth blended center body, a sawtooth trailing edge, engines buried inside the wing with intakes on top and flattened shielded exhausts, a small faceted cockpit window strip, and its central bomb bay doors open to show a rotary launcher loaded with large guided bombs.
```

### Aircraft follow-ups (attach the aircraft image as a reference)
- "Show this aircraft in flight from a high RTS camera angle, with its ground shadow visible below."
- "Create top, side, and front orthographic views of this aircraft."
- "Show the attack helicopter in a low hover kicking up dust, rotors blurred."
- "Show the bomber from directly below during a bombing run, bomb bay open."
- "Recolor for the opposing faction: dark gray-blue base with red markings, same design."
- Combined lineup (attach both master sheets as references, 21:9): "Combine these two images into a single faction lineup with ground vehicles in front and aircraft behind, consistent scale."

---

## 3. Infantry

### Master sheet
```
Professional character concept art sheet for a modern real-time strategy video game, showing four infantry soldiers from the same fictional faction as its armored vehicles and aircraft. Grounded military realism extrapolated to the 2040s: modular plate carriers, ballistic helmets with mounted night-vision and comms headsets, knee pads, gloves, tactical pouches, and integrated helmet cameras.

Soldiers, arranged left to right in dynamic combat poses on a neutral light-gray studio background:
1. A rifleman advancing in a firing stance, shouldering a compact bullpup assault rifle with an optic and suppressor.
2. A heavy gunner braced and firing a belt-fed heavy machine gun from the hip, with an ammo backpack feeding the belt, bulkier armor, and a wider stance.
3. A sniper kneeling and aiming a long bolt-action rifle with a large scope and bipod, wearing a light ghillie wrap over the shoulders.
4. An anti-armor specialist kneeling and aiming a shoulder-fired rocket launcher, with spare rockets on the back and a grenade launcher on the hip.

Full body, consistent scale. Unified faction look: olive-tan uniforms and gear with dark gray armor plates and a small orange faction patch on each shoulder. Each soldier must have a distinct, exaggerated silhouette defined by their weapon so they remain identifiable from a high top-down RTS camera. Crisp, painterly-realistic rendering, soft studio lighting, light dust and wear on gear. Faces partially covered by goggles or balaclavas. No blood, no text, no real-world insignia or logos.
```

### Style line (append to each soldier prompt)
```
Modern RTS game character concept art, grounded 2040s infantry, full body, olive-tan uniform with dark gray armor plates and a small orange faction shoulder patch, ballistic helmet with night-vision mount, neutral gray background, crisp painterly-realistic rendering, soft studio lighting, light dust wear, silhouette clearly identifiable from a high top-down camera, no blood, no text or real-world insignia.
```

### Rifleman
```
An agile infantry rifleman mid-stride advancing in a combat crouch, shouldering a compact bullpup assault rifle with a holographic optic, suppressor, and foregrip. Light plate carrier with magazine pouches, a sidearm on the thigh, and a small radio antenna on the back.
```

### Heavy machine gunner
```
A large, heavily armored machine gunner braced in a wide stance firing a belt-fed heavy machine gun from the hip, the ammunition belt running from a large backpack ammo drum. Thick shoulder and groin armor, a heat-resistant sleeve on the gun barrel, and spent casings flying from the ejection port.
```

### Sniper
```
A sniper in a low kneeling firing position aiming a long-barreled bolt-action precision rifle with a large scope, bipod, and suppressor. Lighter gear, a camouflage ghillie wrap draped over the shoulders and helmet, a rangefinder on the chest, and a muted, stealthy profile.
```

### Grenade / rocket launcher
```
An anti-armor specialist kneeling and aiming a large shoulder-fired rocket launcher with a fold-down sight, a visible backblast cone of smoke behind them. Two spare rockets strapped to the back and a compact six-round revolver grenade launcher holstered on the hip.
```

### Infantry follow-ups (attach the soldier image as a reference)
- "Show this soldier from a high top-down RTS camera angle at small scale."
- "Create a front, side, and back character turnaround in a neutral A-pose, holding the weapon."
- "Show this soldier in four poses: idle, moving, firing, and taking cover."
- "Show a four-soldier squad of this type moving together in formation."
- "Recolor for the opposing faction: dark gray-blue uniforms with red patches, same gear."
- Weapon fix: generate a clean weapon alone first, then attach both the soldier and the weapon as references: "Give this soldier this exact weapon, held correctly with both hands."

---

## 4. Per-asset variant sheets (one asset per sheet)

Use these to explore four design options for a single unit, then pick one and refine it with the follow-ups above. Settings: GPT Image 2.5, Sunburst, quality `high`, `2k`, `16:9`. First run (2026-10-20), also in your Higgsfield library:

- [Recon jeep](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175914_ba2d73e3-0404-406a-b71e-fab5c30c93b0.png)
- [Troop transport (APC)](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175915_dac78c92-301f-4037-b4e2-e2070d0e5b99.png)
- [Mobile missile launcher](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175914_89a9b110-2ce7-4fa6-adfd-85a8bef34c6a.png)
- [Main battle tank](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175917_9e49766e-316d-4db1-b40d-adde1e290d52.png)
- [Armed recon drone](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175915_c3032e2c-3182-4886-b921-0e253b735030.png)
- [Stealth fighter](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175914_d242d45c-5878-4bf8-83ca-2f5ac632ae91.png)
- [Attack helicopter](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175916_6ddf3a87-92c2-432e-8bd3-cd53d0f79181.png)
- [Stealth bomber](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175916_4c6714e5-e2aa-460b-bc75-224c3b44a1a2.png)
- [Rifleman](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175916_5e9a693c-b7be-48c6-b758-a902f909220b.png)
- [Heavy machine gunner](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175917_c02a8dfe-a6b4-4c31-84ae-e7d9f33df82e.png)
- [Sniper](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175918_33a68ea7-e01c-4d32-8ed5-c7099fe8d84d.png)
- [Rocket specialist](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_175916_bd0e184c-9d24-4384-9e20-fb79fe21a9d5.png)

### Template
```
Concept art variation sheet for a real-time strategy video game: four distinct design variations of the same unit, a 2040s [UNIT], arranged in a single row left to right at consistent scale, evenly spaced with clear gaps. [UNIT DESCRIPTION FROM ABOVE] The four options should explore different design directions for this one role (for example different proportions, armor layout, weapon fit and sensor placement) while clearly belonging to the same faction. [FACTION LOOK BLOCK] Setting: the 2040s, grounded military realism extrapolated about twenty years from today's equipment, not science fiction: unmanned and optionally-crewed systems, sensor fusion, hybrid-electric drives, faceted low-observable shaping. No energy weapons, no mechs. Each variation must have a clearly different, chunky silhouette that stays readable from a high top-down RTS camera. No text, no labels, no numbers, no logos, no real-world insignia.
```

### Faction look blocks (describe the reference images in words)
- **Vehicles:** Photorealistic hard-surface 3D render, like a high-end game cinematic asset. Faction scheme: desaturated olive-tan base with dark charcoal-gray angular splinter camouflage blocks, a small orange chevron faction emblem on each vehicle, dust and mud weathering on lower hulls, small white LED running lights. Seamless neutral light-gray studio backdrop, soft even studio lighting, soft contact shadows. Three-quarter front view.
- **Aircraft:** Photorealistic hard-surface 3D render, like a high-end game cinematic asset. Faction scheme: dark charcoal gray-olive base with lighter gray angular panel blocks, small orange chevron faction emblems, gold-tinted canopies, light panel-edge wear. Seamless neutral light-gray studio backdrop, soft even studio lighting, soft shadows. Three-quarter top-down view.
- **Infantry:** Photorealistic 3D character render, like a high-end game cinematic asset. Faction look: olive-tan and dark gray mottled camouflage uniforms, dark gray modular armor plates, ballistic helmets with sensor mounts, amber-tinted goggles and balaclavas covering faces, a small orange triangle faction patch on the shoulder, dust and mud on boots and knees. Seamless neutral light-gray studio backdrop, soft even studio lighting. Full body.

### Picking a winner
"Isolate variation [1-4, counting from the left] from this sheet as a single hero image on the same background, same design, same paint." Attach the sheet as a reference.

---

## 5. Single-asset images from the reference sheets

One image per unit, made with the original GPT Image sheets attached as references (vehicles, aircraft, infantry). The references are in the repo at `concept-art/references/` on the `claude/project-thread-6ds582` branch.

### Template (attach the matching reference sheet)
```
Using the attached image as the style and design reference, create a single hero concept art image of one unit for a real-time strategy video game: [WHICH UNIT IN THE REFERENCE, e.g. "the main battle tank on the far right of the reference"], [three-quarter front view / three-quarter top-down view / full body]. Keep the exact rendering style, paint scheme, camouflage pattern, orange faction emblem, weathering, lighting and seamless light-gray studio backdrop of the reference image. Update the design subtly to the 2040s: grounded military realism about twenty years beyond today's equipment, with more integrated sensors, drone integration, cleaner faceted armor and hybrid-electric details, but no science fiction, no energy weapons, no mechs. Chunky silhouette readable from a high top-down RTS camera. One unit only, centered, fully in frame. No text, no labels, no logos, no real-world insignia.
```
Settings: `16:9` for vehicles and aircraft, `3:4` for infantry.

### Results (2026-10-20)
- [Recon jeep](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191819_112baca2-01f4-445f-acf0-b8f808da371f.png)
- [Troop transport (APC)](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191817_448df0ab-744c-4932-94a3-3b4cb27634c5.png)
- [Mobile missile launcher](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191816_43058b19-0ff2-48f3-b68d-d2f8d865b191.png)
- [Main battle tank](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191819_67860efe-4061-4fe1-98de-34cad2e2b35a.png)
- [Armed recon drone](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191816_615327d1-6110-4914-aef8-4ec19e088c74.png)
- [Stealth fighter](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191817_a3455338-419a-4edb-aff3-d787327fec84.png)
- [Attack helicopter](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191818_4b54e78a-e1bd-4554-9faa-37afc7ef8c33.png)
- [Stealth bomber](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191820_7012dd65-5f26-4c39-888f-835dacab7ab5.png)
- [Rifleman](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191818_c787fcf6-742d-471c-b5ea-6f1d5187c987.png)
- [Heavy machine gunner](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191816_061808d3-49e5-4a07-91b0-f2685c0cba93.png)
- [Sniper](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191818_2a164df6-94bd-4065-ac1b-28cda6a388f5.png)
- [Rocket specialist](https://d8j0ntlcm91z4.cloudfront.net/user_3I0dEBG9dbak9S2KQlNqbxzSONm/hf_20261020_191817_ada073f5-a0a6-4905-8518-0f0fdefb0d7c.png)
