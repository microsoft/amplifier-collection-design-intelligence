# Design Intelligence Collection

> Transform raw design ideas into refined solutions through collaborative intelligence

---

## What This Provides

The **Design Intelligence** collection equips Amplifier with comprehensive design capabilities through:

- **7 specialized design agents** - Each expert in their domain
- **Design philosophy framework** - 9 Dimensions, 5 Pillars, 4 Layers
- **Design knowledge base** - Color theory, typography, animation, accessibility
- **Established protocols** - Component creation, checklists, wireframes, anti-patterns

### The Three-Part Goal

Every design output achieves ALL THREE:

1. ✅ **Looks Good** - Meets 9.5/10 quality standard
2. ✅ **Feels Theirs** - User recognizes their vision in the result
3. ✅ **Beyond Imagination** - Refined in ways they never thought possible

```
User's spark → Design philosophy + craft → Their expression, elevated
```

---

## Quick Start

### Installation

```bash
# Install the collection (requires foundation collection)
amplifier collection add git+https://github.com/microsoft/amplifier-collection-design-intelligence@main

# Verify installation
amplifier collection show design-intelligence
```

### Usage

```bash
# Use the designer profile
amplifier profile use design-intelligence:designer

# Start a design session
amplifier run "Design a notification toast that feels warm and inviting"

# The session has access to all 7 design specialists:
# - design-system-architect
# - component-designer
# - animation-choreographer
# - layout-architect
# - art-director
# - responsive-strategist
# - voice-strategist
```

---

## Resources

### Profile

- **designer** - Full design intelligence configuration with all agents and extended thinking

### Agents (7 specialists)

| Agent                       | Expertise                                  | Keywords                                   |
| --------------------------- | ------------------------------------------ | ------------------------------------------ |
| **design-system-architect** | System-wide patterns, tokens, architecture | system, tokens, foundation, palette, theme |
| **component-designer**      | Individual components, props, variants     | component, button, modal, form, card       |
| **animation-choreographer** | Motion sequences, easing, choreography     | animate, motion, transition, timing        |
| **layout-architect**        | Page layout, IA, grid systems              | layout, IA, grid, structure, hierarchy     |
| **art-director**            | Aesthetic strategy, visual coherence       | art-direction, aesthetic, brand, style     |
| **responsive-strategist**   | Responsive strategy, breakpoints           | responsive, mobile, tablet, breakpoint     |
| **voice-strategist**        | Tone, messaging, content strategy          | voice, tone, messaging, microcopy          |

### Context

**Philosophy** (4 documents):

- `DESIGN-PHILOSOPHY.md` - Five Pillars of design thinking
- `DESIGN-PRINCIPLES.md` - Quick reference principles
- `DESIGN-FRAMEWORK.md` - 9 Dimensions + 4 Layers framework
- `DESIGN-VISION.md` - Design beyond the artifact

**Knowledge Base** (4 documents):

- `color-theory.md` - Color systems, psychology, accessibility
- `typography.md` - Type systems, hierarchy, readability
- `animation-principles.md` - Motion design, timing, choreography
- `accessibility.md` - WCAG guidelines, inclusive design

**Protocols** (5 documents):

- `COMPONENT-CREATION-PROTOCOL.md` - Step-by-step component design
- `DESIGN-CHECKLIST.md` - Quality assurance checklist
- `REQUIREMENTS-TEMPLATE.md` - Design requirements capture
- `WIREFRAME-STANDARDS.md` - Wireframing guidelines
- `ANTI-PATTERNS.md` - Common mistakes to avoid

---

## Working Approach

The design intelligence system follows a collaborative transformation process:

### 1. Receive the Spark

Welcome **any** input:

- Rough ideas: "I want it to feel premium but not cold"
- Vibes: "Like Sunday morning coffee"
- References: [screenshot], "like Stripe but warmer"
- Feelings: "I don't know how to describe it..."

### 2. Collaborative Interpretation

Reflect back understanding:

- "By 'premium', I understand: sophisticated shadows, refined motion, subtle depth - is that right?"
- "Premium can mean minimal OR luxurious - which resonates with your vision?"

### 3. Systematic Transformation

Apply frameworks to YOUR vision:

- **Nine Dimensions** - Style, Motion, Voice, Space, Color, Typography, Proportion, Texture, Body
- **Five Pillars** - Purpose, Craft, Constraints, Incompleteness, Humans
- **Technical Standards** - Accessibility, performance, maintainability

### 4. Refined Output

Deliver your vision, elevated to 9.5/10 quality.

### 5. Iterative Refinement

"Close, but the shadow feels too heavy" → Adjust while preserving ownership.

**Goal:** You say "That's MY vision, done better than I imagined."

---

## Design Frameworks

### Nine Dimensions

The design intelligence system evaluates designs across nine dimensions:

1. **Style** - Visual language, aesthetic decisions
2. **Motion** - Animation, transitions, timing
3. **Voice** - Tone, messaging, personality
4. **Space** - Layout, whitespace, rhythm
5. **Color** - Palette, contrast, meaning
6. **Typography** - Type system, hierarchy, readability
7. **Proportion** - Scale, size relationships
8. **Texture** - Depth, layers, materials
9. **Body** - Components, patterns, systems

### Five Pillars

Every design decision considers:

1. **Purpose** - Why does this exist?
2. **Craft** - Is it well-made?
3. **Constraints** - What limitations shape it?
4. **Incompleteness** - What's intentionally left open?
5. **Humans** - Who experiences this and how?

### Four Layers

Design work operates at four levels:

1. **Product Layer** - What is the product?
2. **Interaction Layer** - How do users interact?
3. **Interface Layer** - What do users see and touch?
4. **Visual Layer** - How does it look and feel?

---

## Example Sessions

### Design a Button Component

```bash
amplifier profile use design-intelligence:designer
amplifier run "Design a primary button that feels confident but not aggressive"

# The system will:
# 1. Interpret your vision ("confident but not aggressive")
# 2. Apply component-designer agent expertise
# 3. Reference design system patterns
# 4. Deliver button spec with:
#    - Visual design (colors, shadows, typography)
#    - States (default, hover, active, disabled)
#    - Motion (transitions, feedback)
#    - Accessibility (contrast, focus states)
#    - Code (props API, variants)
```

### Create a Design System

```bash
amplifier run "Create a design system for a healthcare product that feels trustworthy and calm"

# The system will:
# 1. Route to design-system-architect
# 2. Apply color theory and psychology
# 3. Define token architecture
# 4. Create comprehensive system including:
#    - Color tokens (primary, secondary, semantic)
#    - Typography scale
#    - Spacing system
#    - Motion timing tokens
#    - Component patterns
```

### Design an Animation

```bash
amplifier run "Create a drawer slide-in animation that feels smooth and natural"

# The system will:
# 1. Route to animation-choreographer
# 2. Apply animation principles
# 3. Deliver animation spec with:
#    - Easing curves
#    - Timing values
#    - Choreography sequence
#    - CSS/code implementation
```

---

## Philosophy Alignment

The design intelligence collection follows Amplifier's core principles:

- **Mechanism, not policy** - Provides design frameworks and agents; your choices determine outcomes
- **Ruthless simplicity** - Clear, focused expertise per agent; no over-complicated abstractions
- **Convention over configuration** - Standard directory structure; no complex manifests
- **Text-first** - All design knowledge in markdown; inspectable and versionable

---

## Dependencies

- **foundation** collection (^1.0.0) - Required for base profiles and shared context

---

## Contributing

> [!NOTE]
> This project is not currently accepting external contributions, but we're actively working toward opening this up. We value community input and look forward to collaborating in the future. For now, feel free to fork and experiment!

Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit [Contributor License Agreements](https://cla.opensource.microsoft.com).

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft
trademarks or logos is subject to and must follow
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
