# Animation Menu

> Animation patterns organized by quality tier for quick reference.

## How to Use

When proposing to users, present options across tiers:
- **Standard** — Reliable, professional, non-distracting
- **Enhanced** — Polished, engaging, memorable
- **Cinematic** — Dramatic, eye-catching, "wow" factor

---

## Entrance Animations

Making elements appear.

### Fade-Based Entrances

#### Standard: Simple Fade Up
**Visual:** "Gently rises into view like it's floating up"
**Feel:** Clean, professional, gets out of the way
**Use for:** Business presentations, when content is the star
**Timing:** 0.5s, smooth spring

**User description:**
> "Fades up smoothly as the scene loads. Professional and subtle."

---

#### Enhanced: Fade Up with Scale
**Visual:** "Rises while growing from slightly smaller to full size"
**Feel:** Polished, has presence, still professional
**Use for:** Product launches, marketing, when element matters
**Timing:** 0.6s, smooth spring

**User description:**
> "Floats up while subtly growing. More presence than simple fade, 
> still polished and professional."

---

#### Cinematic: Dramatic Entrance
**Visual:** "Sweeps in from the side with a subtle glow that settles"
**Feel:** Grand arrival, this moment is important
**Use for:** Hero elements, key announcements, intro moments
**Timing:** 0.8s, slight overshoot, glow fades after 0.3s

**User description:**
> "Makes an entrance—slides in with a brief glow that fades. 
> Says 'this is important.'"

---

### Scale-Based Entrances

#### Standard: Gentle Scale
**Visual:** "Grows from 90% to full size while fading in"
**Feel:** Elegant, restrained
**Use for:** Images, when you want presence without motion
**Timing:** 0.5s, smooth

**User description:**
> "Fades in while gently growing to full size. Elegant and restrained."

---

#### Enhanced: Pop with Settle
**Visual:** "Pops in slightly oversized, then settles into place"
**Feel:** Friendly, alive, welcoming
**Use for:** CTAs, announcements, engaging content
**Timing:** 0.4s, bouncy spring (damping: 15)

**User description:**
> "Pops in with a little overshoot, like it's excited to be here. 
> Friendly and attention-grabbing."

---

#### Cinematic: The Grand Entrance
**Visual:** "Spins in from zero while scaling up, landing with impact"
**Feel:** Dramatic, celebratory, unforgettable
**Use for:** Launch moments, celebrations, viral content intros
**Timing:** 0.7s, rotation + scale, bouncy settle

**User description:**
> "Makes a grand entrance—spins and scales in dramatically. 
> Perfect for moments that need to feel special."

---

### Text-Specific Entrances

#### Standard: Fade Up
**Visual:** "Rises smoothly from below while becoming visible"
**Feel:** Clean typography, readable
**Use for:** Body text, supporting content

---

#### Enhanced: Word-by-Word
**Visual:** "Words appear one after another like someone speaking them"
**Feel:** Narrative, rhythmic, engaging
**Use for:** Headlines, short impactful phrases (< 10 words)

---

#### Cinematic: Kinetic Typography
**Visual:** "Letters animate with dramatic timing—some slide, some rotate, all coordinated"
**Feel:** Artistic, high-energy, memorable
**Use for:** Opening titles, brand statements

---

## Sequence Animations

Multiple elements appearing together.

### Standard: Staggered Fade
**Visual:** "Items appear one by one, calm and orderly"
**Feel:** Organized, easy to follow
**Use for:** Feature lists, team members, navigation
**Pattern:** 0.1s delay between items, fade up

**User description:**
> "Items fade up one by one, like a well-organized presentation."

---

### Enhanced: The Cascade
**Visual:** "Each item finishes its animation before the next starts"
**Feel:** Building momentum, deliberate
**Use for:** Step-by-step processes, building anticipation
**Pattern:** Item N finishes, then Item N+1 starts

**User description:**
> "Each item fully appears before the next begins. 
> Creates momentum and anticipation."

---

### Cinematic: The Wave
**Visual:** "Ripples through items diagonally like water spreading"
**Feel:** Dynamic, fluid, alive
**Use for:** Grids, portfolios, impressive showcases
**Pattern:** Diagonal offset based on position

**User description:**
> "Ripples through like a wave—diagonal and dynamic. 
> Visually impressive for grids."

---

## Emphasis Animations

Drawing attention to visible elements.

### Standard: Subtle Pulse
**Visual:** "Breathes gently, expanding and contracting softly"
**Feel:** Alive, inviting, not demanding
**Use for:** CTAs waiting for interaction, status indicators
**Pattern:** Scale 1→1.02→1, 2s cycle, infinite

**User description:**
> "Breathes softly—gentle expansion that catches the eye 
> without demanding attention."

---

### Enhanced: The Highlight
**Visual:** "A glow appears and fades, like a spotlight passing over"
**Feel:** Important, selected, worthy of notice
**Use for:** Key points, selected items, emphasis moments
**Pattern:** Box-shadow glow in and out, 0.4s

**User description:**
> "A soft glow passes over, like a spotlight momentarily highlighting it."

---

### Cinematic: Dramatic Pulse
**Visual:** "Pulses with scale bounce and color shift, impossible to ignore"
**Feel:** Urgent, exciting, celebration
**Use for:** Sale notifications, achievements, critical CTAs
**Pattern:** Scale + color + glow, all coordinated

**User description:**
> "Pulses dramatically—scales, changes color, glows. 
> Impossible to ignore."

---

## Data Visualization Animations

### Standard: Grow from Bottom
**Visual:** "Bars rise up from baseline like buildings being constructed"
**Feel:** Clear, honest, straightforward
**Use for:** Business charts, reports

---

### Enhanced: Liquid Fill
**Visual:** "Fills upward like liquid in a container"
**Feel:** Organic, modern, polished
**Use for:** Creative presentations, dashboards

---

### Cinematic: The Counter Reveal
**Visual:** "Numbers count up rapidly while bars grow to meet them"
**Feel:** Impressive, data-driven, exciting
**Use for:** Key metrics, achievements, launches

---

## Transition Animations

### Standard: Crossfade
**Visual:** "One scene fades out as the next fades in"
**Feel:** Seamless, gentle
**Use for:** Most scene changes

---

### Enhanced: Directional Slide
**Visual:** "New scene pushes in from a direction"
**Feel:** Movement, progression, flow
**Use for:** Sequential content, storytelling

---

### Cinematic: The Zoom
**Visual:** "Dramatic scale into or out of a detail"
**Feel:** Focus shift, important moment
**Use for:** Reveals, emphasis, cinematic flow

---

## Quick Decision Guide

| Content | Standard | Enhanced | Cinematic |
|---------|----------|----------|-----------|
| Headline | Fade up | Word-by-word | Kinetic type |
| Product image | Fade + scale | Pop with settle | Spin + scale |
| Feature list | Staggered fade | Cascade | Wave |
| CTA | Gentle pulse | Bounce entrance | Dramatic pulse |
| Chart | Grow from bottom | Liquid fill | Counter reveal |
| Scene change | Crossfade | Slide | Zoom |

---

## User Descriptions Cheat Sheet

| Technical Concept | User-Facing Description |
|-------------------|------------------------|
| Spring with damping: 200 | "Smooth settle" |
| Spring with damping: 15 | "Bouncy pop" |
| 0.05s stagger | "Quick rhythm, almost together" |
| 0.1s stagger | "Comfortable one-by-one" |
| 0.2s stagger | "Dramatic pause between each" |
| Overshoot | "Pops a bit past then settles" |
| Glow | "Soft light that appears" |
| Clip-path wipe | "Unveiled like a curtain" |
| Counter | "Numbers roll up like slot machine" |
