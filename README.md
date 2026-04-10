# Remotion Director — Claude Skill

> Your creative director for Remotion video animations. A Claude skill that guides you from vague animation wishes to concrete, implementable specifications.

[![Made for Remotion](https://img.shields.io/badge/Made%20for-Remotion-blue)](https://remotion.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

**Transform vague animation wishes into concrete, choosable options.**

When you want to animate your Remotion video but find yourself saying things like:
- ":sparkles: Make it look nice"
- ":sparkles: Something smooth"
- ":sparkles: I want it to pop"

...this skill guides you from uncertainty to a precise animation specification.

---

## What This Skill Does

### The Problem

Building programmatic video with [Remotion](https://github.com/remotion-dev/remotion) is powerful, but deciding on animation is hard:

- **What's possible?** — You don't know what animations Remotion can do
- **What fits?** — You don't know which animation matches your content
- **How to describe?** — You can't articulate what you want in precise terms

### The Solution

**Remotion Director** acts as your creative director:

1. **Analyze** — You share your scene/component
2. **Propose** — We show you 2-4 concrete animation directions
3. **Choose** — You react ("yes that" or "more like X")
4. **Specify** — We deliver a precise animation specification
5. **Implement** — Hand off to [remotion-best-practices](https://github.com/remotion-dev/skills/tree/main/skills/remotion) for the code

---

## How It Works

### Three Tiers of Animation

For every element, we propose options across these quality levels:

| Tier | Description | Best For |
|------|-------------|----------|
| **Standard** | Clean, smooth, professional | Business videos, tutorials, data |
| **Enhanced** | Polished, engaging, memorable | Marketing, demos, products |
| **Cinematic** | Dramatic, eye-catching, "wow" | Launches, viral content, intros |

### Visual Language

Instead of technical jargon, we describe what you'll see:

| What We Say | What It Means |
|-------------|---------------|
| "Fades up like it's floating" | Opacity 0→1 + translateY 30px→0 |
| "Pops in excited to be here" | Spring scale with overshoot |
| "Unveiled like a curtain" | Clip-path wipe reveal |
| "Breathes softly" | Continuous gentle pulse |

---

## Example Conversation

### You Have a Product Card

```tsx
<div>
  <img src="product.png" />
  <h1>SuperWidget Pro</h1>
  <p>The best widget ever</p>
  <button>Buy Now</button>
</div>
```

### You Say
> "Make it animated nicely"

### We Respond

---

**Option A: Clean & Professional** (Standard)

Product fades in while gently scaling, text follows smoothly. Like a well-designed store shelf—organized, trustworthy.

**Option B: Polished Impact** (Enhanced) :star: Recommended

Product slides in with soft shadow, button pops with bounce. Like unboxing something exciting—builds toward action.

**Option C: Cinematic Reveal** (Cinematic)

Product spins and scales dramatically, title words appear one-by-one. Like a movie trailer—maximum impact.

---

**B hits the sweet spot** for most product videos. Want to go with that?

### Next Steps

- :white_check_mark: **Ready to implement?** Say "ready" and we'll hand off to `remotion-best-practices`
- :wrench: **Want adjustments?** Tell us what to tweak
- :bulb: **Curious about alternatives?** Ask about specific patterns

---

## Installation

### Option 1: Project-specific (Recommended)

```bash
# In your project root
mkdir -p .agent/skills
cp -r remotion-director .agent/skills/
```

### Option 2: Global (Claude Code)

```bash
# In your home directory
mkdir -p ~/.claude/skills
cp -r remotion-director ~/.claude/skills/
```

### Option 3: Import `.skill` file

Import the `.skill` file directly into Claude.

---

## Usage

Once installed, simply tell Claude about your animation needs:

- "I want to animate this hero section"
- "Make my chart look impressive"
- "What animations work for a testimonial?"
- "I need something smooth for the intro"

The skill will automatically trigger and guide you through the process.

---

## Workflow

```
You: "Animate my product page"
    ↓
Director: Analyzes your layout
    ↓
Director: Proposes A/B/C with visual descriptions
    ↓
You: "B feels right, but slower"
    ↓
Director: Refines timing
    ↓
You: "Perfect!"
    ↓
Director: Generates specification
    ↓
Director: Hands off to remotion-best-practices for code
```

---

## Documentation

- **[SKILL.md](SKILL.md)** — Complete skill guidance for Claude
- **[references/animation-menu.md](references/animation-menu.md)** — Animation pattern catalog
- **[references/scene-patterns.md](references/scene-patterns.md)** — Common video structures

---

## Related

- [Remotion](https://github.com/remotion-dev/remotion) — The React video framework
- [remotion-best-practices](https://github.com/remotion-dev/skills) — Implementation guidance and code patterns

This skill is **complementary** to `remotion-best-practices`:
- **This skill** (`remotion-director`) — Deciding WHAT to animate
- **That skill** (`remotion-best-practices`) — Implementing HOW to animate

---

## Why Not Just Ask Claude?

Without this skill, Claude typically either:

1. **Gives code immediately** — But you didn't know if that animation was the best choice
2. **Asks what you want** — But you didn't know the options

**With this skill**, Claude shows you concrete options with visual descriptions, helps you choose, and only then implements.

---

## Contributing

Contributions welcome! Areas to expand:

- New animation patterns
- Additional scene templates
- More visual descriptions
- Industry-specific recommendations

Please read our [Contributing Guide](CONTRIBUTING.md) (TODO).

---

## License

MIT — See [LICENSE](LICENSE) for details.

---

<p align="center">
  Built with :heart: for the Remotion community
</p>
