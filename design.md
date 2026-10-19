# Design System: Ringvitation (The Wedding of Bowo & Maya)

## 1. Visual Theme & Atmosphere

An opulent, deeply atmospheric dark-romance digital wedding invitation tailored for intimate luxury and timeless solemnity. The aesthetic departs sharply from conventional airy pastels, adopting a moody nocturnal canvas dominated by deep petrol navy (`#084259`), abyssal graphite (`#000000`, `#0C0C0C`), and opulent warm champagne golds (`#bc9b64`, `#C4A17E`). 

The composition marries modern architectural containers with sacred, classical romance. Slow ethereal rotations of celestial floral mandalas float in negative space, while delicate arched cathedral silhouettes (`border-radius: 220px 220px 0 0`) frame the matrimonial events. Typography balances ceremonial calligraphic flourishes (`Carattere`) with dignified literary serif typography (`Cardo`) and ultra-clean modern geometric utility labels (`Poppins`). The atmosphere conveys solemn sanctity, royal warmth, and bespoke celebratory grandeur.

- Overall feeling: Moody midnight romance, imperial elegance, liturgical serenity, and bespoke digital luxury.
- Visual density: Measured and expansive; dramatic vertical breathing room accented by intimate nested cards.
- Brand posture: Bespoke celebratory craftsmanship, culturally reverent, and sophisticated.
- Signature motifs: Cathedral-arch containers, slowly rotating 360-degree floral mandalas, dual-tone gold script headings, and textured tribal tree dividers.

### Key Characteristics

- Midnight Petrol & Gold Gradient: Atmospheric backdrop blending intense dark oceanic teal with deep noir.
- Cathedral Arched Cards: Distinctive top-rounded arched event cards (`220px 220px 0 0`) with dual-pixel champagne borders.
- Dual Script & Serif Typography: Expressive `Carattere` cursive script for couple names, anchored by `Cardo` for solemn dates and titles.
- Layered Entrance Choreography: Progressive reveal sequences using slow fade-ins, zoom-ins, and floating background florals.

## 2. Color Palette & Roles

| Role | Semantic Name | Value | Usage |
| --- | --- | --- | --- |
| Primary action | Royal Gold Gradient | `linear-gradient(90deg, #bc9b64 0%, #86672B 100%)` | Main CTA button ("Buka Undangan"), interactive buttons |
| Accent | Champagne Gold | `#bc9b64` | Bride/Groom calligraphic names, calendar highlighted badges |
| Secondary Accent | Warm Sand Gold | `#C4A17E` | Arched container borders, date highlight chips, decorative accents |
| Deep Atmosphere | Midnight Petrol | `#084259` | Central gradient glow, modal atmospheric radial centers |
| Surface | Noir Black | `#0C0C0C` | Nested container backgrounds, modal dialog surface |
| Surface Deep | Translucent Jet | `rgba(0, 0, 0, 0.83)` | Couple profile card backdrop with warm gold border |
| Text Primary | Cream Silk | `#F8F4E7` | Primary headings, subheadings, ceremony names, countdown numbers |
| Text Secondary | Pale Silver | `#C6C6C6` | Parent names, venue addresses, descriptive body copy |
| Text Muted | Ash Gray | `#8D8C8C` | Section eyebrows, divider text, decorative line labels |
| Border | Fine Champagne | `#d8c192` | Subtle profile container boundaries and decorative outlines |

### Primary

- Royal Gold (`#bc9b64`): Expresses celebration and warmth, used on the groom's name and primary invitation trigger.
- Warm Sand Gold (`#C4A17E`): Complements the primary gold on the bride's name, arch frames, and calendar blocks.

### Interactive

- Primary Button: Linear gradient `#bc9b64` to `#86672B` with soft drop shadow `1px 1px 6px rgba(0, 0, 0, 0.26)` and white text.
- Secondary Button: Pale cream `#F8F4E7` fill with slate border `#656565` and sharp rectangular corners.
- Icon Triggers: Enclosed envelope and navigation icons colored in warm cream `#F8F4E7`.

### Neutral Scale

- Cream Silk (`#F8F4E7`): Highest contrast text and numerical display.
- Pure White (`#FFFFFF`): Button text, holy scripture verses, and secondary event subheaders.
- Pale Silver (`#C6C6C6`): Secondary metadata, parental lineage, and event addresses.
- Ash Gray (`#8D8C8C`): Subtle divider separators and formal uppercase headers.
- Midnight Noir (`#000000` / `#0C0C0C`): Deepest background absorption layer.

### Surface & Overlay

- Background Base: Radial gradient `radial-gradient(circle at center, #084259 0%, #0C0C0C 100%)`.
- Card Surface: Semi-opaque black `#000000D4` (`rgba(0, 0, 0, 0.83)`) providing clear readability over background animations.
- Modal Cover Overlay: Full-screen locked takeover overlay in dark petrol gradient with radial bloom.

### Theme Modes

#### Dark Mode (Native & Primary)

- Background: Radial gradient `#084259` to `#000000` / `#151414`.
- Surface: `#0C1F28` / `#000000D4` with `#d8c192` border.
- Text: `#F8F4E7` (Cream) and `#C6C6C6` (Silver).
- Accent: `#bc9b64` & `#C4A17E` (Gold dual-tone).
- Notes: This design system is natively designed for an immersive dark luxury experience.

#### Light Mode (Secondary / Card Contrast Variant)

- Background: Pale cream `#f5f5f5` to `#f2f5f7`.
- Surface: `#ffffff` with subtle gray shadow `0 10px 30px rgba(0,0,0,0.05)`.
- Text: `#3a3a3a` / `#4b4f58`.
- Accent: `#0170b9` (Astra default fallback) or `#bc9b64` (Theme accent).
- Notes: Used when embedded in neutral article or blog wrappers.

### Shadows & Depth

- Elevation Card: `box-shadow: 0px 0px 21px 0px rgba(0, 0, 0, 0.3)` on couple profile cards.
- Cathedral Arch Glow: `box-shadow: 0px 0px 13px 0px rgba(0, 0, 0, 0.24)`.
- Section Separation: Heavy drop shadow `0px 0px 28px 0px rgba(0, 0, 0, 0.51)` on full-width transition blocks.
- Text Shadow: Subtle depth `1px 1px 1px rgba(0, 0, 0, 0.3)` on display cursive script.

## 3. Typography Rules

### Font Family

- Primary Script: `"Carattere", cursive` (Google Fonts) – ceremonial calligraphy for names & "&" connector.
- Editorial Serif: `"Cardo", serif` (Google Fonts) – formal event titles, dates, and liturgical markers.
- Modern Sans: `"Poppins", sans-serif` (Google Fonts) – clean geometric utility, labels, and verses.
- Secondary Sans: `"Roboto", sans-serif` – system fallbacks and input elements.
- Monospace: `"Roboto Mono", monospace` – technical fallbacks.

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
| --- | --- | --- | --- | --- | --- | --- |
| Hero Couple Names | Carattere | 4.0em - 5.0rem | 500 | 1.1 | 0.02em | Gold `#bc9b64` & `#C4A17E` with text shadow |
| Couple Connector ("&") | Carattere | 5.0rem | 400 | 1.0 | normal | Pale gray `#A8A8A8` or `#DADADA` |
| Section Headline | Cardo | 2.5rem - 3.0rem | 400 | 1.2 | 0.05em | Italic styling for "Akad", "Resepsi", and "Event" |
| Date Mega Number | Cardo | 55px | 600 | 1.0 | normal | Displayed on gold badge box `#C4A17E` |
| Section Eyebrow | Poppins | 0.8rem - 1.0rem | 400 | 1.4 | 0.2em | Uppercase, cream `#F8F4E7` ("SAVE THE DATE", "THE WEDDING OF") |
| Body / Verses | Poppins | 16px | 400 | 1.7 | normal | Italicized scripture quotes, white `#FFFFFF` |
| Metadata / Lineage | Poppins | 14px | 400 | 1.6 | normal | Parental details and locations in silver `#C6C6C6` |
| Countdown Numbers | Poppins | 2.0rem | 400 | 1.0 | normal | Framed in hollow bordered countdown units |

### Principles

- Dignified Contrast: Pair emotive hand-lettered script (`Carattere`) with strict, symmetrical Roman serif capitals (`Cardo`).
- Breathing Room: Large display sizes offset by generous margin blocks preventing visual crowding.
- Golden Ratio Accentuation: Primary human names receive warm reflective metallic tones; procedural titles remain neutral cream.

## 4. Component Stylings

### Buttons and Links

- Primary CTA ("Buka Undangan"):
  - Height: `44px` - `48px`, padding `10px 28px`.
  - Background: Gradient `linear-gradient(90deg, #bc9b64 0%, #86672B 100%)`.
  - Border: None; border-radius: `30px` (pill).
  - Text: White `#FFFFFF`, `Poppins` 14px, medium weight (`500`).
  - Leading Icon: FontAwesome envelope icon (`far fa-envelope`).
- Secondary Action ("Lokasi Acara", "Kirim Ucapan"):
  - Height: `38px`, padding `8px 20px`.
  - Background: Cream `#F8F4E7`, border `1px solid #656565`.
  - Border Radius: Sharp `0px` or subtle micro `4px`.
  - Text: Dark slate `#656565`, font weight `600`.

### Cards and Containers

- Cathedral Arched Container (Ceremony & Reception Cards):
  - Border Radius: `220px 220px 0px 0px` (architectural arched top).
  - Border: `2px solid #C4A17E`.
  - Background: Radial gradient `#084259 0%` to `#030303 100%`.
  - Padding: `70px 20px 50px 20px`.
  - Elevation: Soft shadow `0px 0px 13px 0px rgba(0, 0, 0, 0.24)`.
- Profile Couple Container:
  - Border: `2px solid #d8c192`.
  - Border Radius: `2px` (nearly rectangular sharp frame).
  - Background: `rgba(0, 0, 0, 0.83)`.
  - Padding: `40px 20px`.
- Holy Verse Block:
  - Border: None.
  - Background: Radial gradient `#084259 41%` to `#000000 140%`.
  - Shadow: Floating depth `0px 0px 28px 0px rgba(0, 0, 0, 0.51)`.

### Inputs and Interactive Controls

- Guest Name Gatekeeper:
  - Input auto-fill via query parameter (`?untuk=NamaTamu`).
  - Dynamic display inside guest badge: `"Kepada Yth. Bapak/Ibu/Saudara/i [Nama]"`.
- Countdown Widget:
  - 4 inline modules (Days, Hours, Minutes, Seconds).
  - Border: `1px solid #F8F4E7`.
  - Background: Transparent with rounded borders.
  - Number: 2rem `Poppins`, Label: 0.7rem uppercase `Poppins`.

### Navigation

- Floating Action Widget:
  - Floating circular audio toggle button at the bottom/side corner.
  - Auto-plays romantic instrumental soundtrack upon tapping "Buka Undangan".
  - Iconography: Music disk animation or volume wave icon.

### Image Treatment

- Rotating Mandala Ornament:
  - PNG floral ring (`hjjhu78hjh-1-1.png`) positioned absolutely at corners and edges.
  - CSS Animation: Continuous rotation `rotate-360 animated-slow` (360 degrees infinitely).
- Couple Portraits:
  - Dimensions: Approx `320px` width.
  - Asymmetric Box Shadow: Groom portrait uses `20px 20px 0px 0px rgba(212, 212, 212, 0.19)`; Bride portrait uses `-20px 20px 0px 0px rgba(212, 212, 212, 0.19)`.
  - Border Radius: `0px` (crisp editorial photograph crops).

### Distinctive Components

- Tribal Tree / Decorative Divider:
  - Centered SVG patterned flourish with embedded organic curves or laurel leaf dividers (`--divider-pattern-url`).
  - Color: Cream `#FFFFFF` or Ash `#8D8C8C`, width `50%`.
- Calendar Badge Block:
  - Triple stack container: Month (top bordered), Day (solid gold filled square with large 55px number), Year (bottom bordered).

## 5. Layout Principles

### Spacing System

- Base unit: `8px`.
- Repeated spacing values: `8px`, `16px`, `24px`, `32px`, `48px`, `70px`.

### Grid & Container

- Grid logic: Single-column centered stream optimized for vertical mobile scrolling.
- Max content width: `100%` on mobile, constrained to `480px` - `600px` on desktop viewport to preserve intimate phone-invitation ratio.
- Section spacing: `40px` to `70px` vertical padding between matrimonial chapters.

### Whitespace Philosophy

- Concentric Density: High breathing room around royal headings; compact, deliberate density inside the cathedral event arch.
- Center-aligned balance: Strict central axis alignment across all textual and ornamental elements.

### Border Radius Scale

- Micro: `2px` (profile photo boxes, formal borders).
- Standard: `8px` - `12px` (inputs and secondary containers).
- Arched: `220px 220px 0px 0px` (signature ceremony arch cards).
- Pill: `999px` (opening CTA button).

## 6. Depth & Elevation

| Level | Treatment | Use |
| --- | --- | --- |
| Flat | `background: transparent; border: none;` | Headline titles, floating couple names |
| Soft Glow | `radial-gradient(circle at center, #084259 40%, transparent 80%)` | Atmospheric backdrop glow |
| Raised Card | `background: #000000D4; box-shadow: 0px 0px 21px rgba(0,0,0,0.3); border: 2px solid #d8c192;` | Couple biographical cards |
| Arch Elevated | `box-shadow: 0px 0px 13px rgba(0,0,0,0.24); border: 2px solid #C4A17E;` | Ceremony & Reception arch cards |
| Overlay Gate | `position: fixed; inset: 0; z-index: 9999; backdrop-filter: blur(8px);` | Opening gate modal before invitation unlock |

### Depth Principles

- Light-Emitting Backgrounds: Dark surfaces appear recessed because the backdrop radiates an eerie teal luminescence (`#084259`).
- Rim Lighting: Borders rendered in champagne gold `#d8c192` simulate physical foil edge gilding.

## 7. Do's and Don'ts

### Do

- Do use the dual gold tones (`#bc9b64` and `#C4A17E`) exclusively for names, main buttons, and arched structural outlines.
- Do keep body text strictly legible in soft cream `#F8F4E7` or silver `#C6C6C6` against the deep midnight background.
- Do preserve the architectural `220px 220px 0 0` top radius for event cards; it is the visual signature of the design.
- Do maintain centered alignment across all ceremonial typography.

### Don't

- Don't use bright neon blues, stark primary greens, or flat pastel pinks.
- Don't use heavy drop-shadows with sharp black offsets; keep shadows diffuse, radial, and velvety.
- Don't use playful rounded fonts (like Comic Sans, Bubblegum, or Inter); maintain the solemn trio of `Carattere`, `Cardo`, and `Poppins`.
- Don't stretch content wider than 640px on desktop; keep it in an elegant portrait card frame.

## 8. Responsive Behavior

### Breakpoints

| Name | Width | Key Changes |
| --- | --- | --- |
| Mobile (Primary) | `< 768px` | Full width padding (15px - 20px), couple names stack comfortably at 3.5rem - 4.0rem |
| Tablet | `768px - 1024px` | Content bounded in 540px centered column; ornaments scale down |
| Desktop | `> 1024px` | Frame invitation as a centered smartphone mockup stage (`max-width: 480px`) with blurred atmospheric background |

### Touch Targets

- Minimum button hit area: `44px` height with full tap target padding.
- Sticky audio toggle: `50px x 50px` floating circle in bottom corner with `12px` screen offset.

### Collapsing Strategy

- Single column flow by default. No multi-column table wraps needed.
- Couple profiles stack vertically with romantic script separator `-&-` positioned between bride and groom.

## 9. Agent Prompt Guide

### Quick Color Reference

- Primary CTA: `linear-gradient(90deg, #bc9b64 0%, #86672B 100%)`
- Background: `radial-gradient(at center center, #084259 0%, #0C0C0C 100%)`
- Heading text: `#F8F4E7` (Cream) & `#bc9b64` (Gold)
- Body text: `#C6C6C6` (Silver) & `#FFFFFF` (White)
- Border or ring: `#C4A17E` & `#d8c192`
- Accent: `#bc9b64`

### Quick Summary

A midnight petrol and gilded champagne digital wedding invitation system. It combines cathedral arch containers, slow-rotating mandalas, dual-tone gold script typography (`Carattere`), formal Roman serifs (`Cardo`), and modern geometric details (`Poppins`) over a luminous radial dark teal background.

### Example Component Prompts

- Hero: "Create a full-height centered invitation cover with a radial background from `#084259` to `#000000`. Include an uppercase eyebrow 'The Wedding Of', large dual-tone gold cursive names 'Bowo & Maya' in `Carattere`, a recipient badge for 'Lubabah', and a pill-shaped gold button 'Buka Undangan'."
- Card: "Build an event schedule card with an arched top `border-radius: 220px 220px 0 0`, framed in a 2px `#C4A17E` gold border. Include an italic serif heading 'Akad', a laurel divider, a 3-part calendar badge with '20' in 55px serif on gold background, and an address in soft silver."
- Navigation: "Render a discreet floating circular music toggle button in the bottom right corner with a gold ring border and a rotating disc icon."

### Ready-to-Use Prompt

"Build a luxury dark wedding invitation page inspired by Ringvitation using a midnight navy radial backdrop (`#084259` to `#000000`). Use Google Fonts 'Carattere' for romantic script names in warm champagne gold (`#bc9b64`), 'Cardo' for ceremonial section titles, and 'Poppins' for clean cream text (`#F8F4E7`). Feature an arched cathedral card with `220px 220px 0 0` border radius for the wedding events, complete with a countdown timer, gold badge calendar date, and subtle floral rotations."

### Iteration Guide

1. Start by setting up the dark atmospheric radial background and importing `Carattere`, `Cardo`, and `Poppins` from Google Fonts.
2. Build the opening guest gatekeeper with recipient name tag and gold pill button.
3. Construct the cathedral arched card (`border-radius: 220px 220px 0 0`) for Akad and Reception details.
4. Add the couple profile card with the `-&-` separator and parent lineage in pale silver.

## Optional Appendix: Interaction Patterns

- Scroll behavior: Smooth sequential reveal with soft fade-in-up animations.
- Hover behavior: Subtle button brightness increase and scale effect (1.02x).
- Click behavior: Tapping 'Buka Undangan' unlocks the document, initiates background instrumental music, and smooth-scrolls into the hero section.
- Animation tone: Ceremonial, slow, and cinematic (`animated-slow`, 1.5s - 2s durations).

## Optional Appendix: Observed Pages

- `https://inv.ringvitation.my.id/bowo-maya/?untuk=Lubabah`: Sourced real elementor CSS rules, custom gradient radial backgrounds, typography families, arched card geometry, and guest token logic.
