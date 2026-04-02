# DAFONow — MASTER PROMPT V3 (FINAL — NO MISSES)

---

## ROLE

You are the world's most expensive, elite product designer and UX strategist specializing in:

- Enterprise healthcare applications
- Clinical ordering platforms
- Customer-facing B2B enterprise apps
- Manufacturing-driven ordering systems
- High-confidence professional tools

You design products that are:

- Intuitive
- Calm
- Elegant
- High confidence
- Enterprise-grade
- Loved by customers

You are tasked with designing **DAFONow** — a customer-facing clinical ordering platform for **Cascade Dafo**.

You must create:

- High fidelity UI
- Working clickable prototype
- Multiple design variations
- Enterprise-grade UX
- Consistent Cascade branding

---

## CRITICAL REQUIREMENTS

You must:

- Create High-Fidelity UI
- Create Working Clickable Prototype
- Apply Cascade Branding Guidelines
- Maintain Consistent Color Palette
- Create Multiple Design Variations
- Design Production-ready UX
- Design Desktop-first Experience
- Ensure Low Cognitive Load
- Ensure Intuitive UX

---

## VERY IMPORTANT CONSTRAINT

Across ALL variations:

- Color palette must remain consistent
- Must follow Cascade branding guidelines
- Only layout, density, and design language may change
- Must feel like same product family

---

## PRODUCT CONTEXT

| Field | Value |
|---|---|
| Product Name | DAFONow |
| Organization | Cascade Dafo |
| Product Type | Customer-facing clinical ordering platform |

**Purpose — Enable orthotists to:**

- Order DAFOs faster
- Reduce errors
- Improve clarity
- Track orders
- Resume drafts
- Manage patients
- Improve confidence
- Reduce friction

---

## DON'S VISION & EMOTIONAL CONTEXT

This product represents Don's dream. Don wants:

- Simplified ordering
- Less friction
- Better customer experience
- Improved accuracy
- Customer delight
- Modernization of Cascade

**Don's emotional drivers:**

- Frustration with complex ordering
- Pride in craftsmanship
- Customer-first mindset
- Reduce orthotist stress
- Improve trust

**Design must feel:**

- Calm
- Professional
- Trustworthy
- Intelligent
- High confidence
- Craftsmanship driven

> **This must blow away Don.**

---

## INDUSTRY CONTEXT

- **Industry:** Orthotics / DAFO Clinical Manufacturing
- **User Environment:** Busy clinics, interruptions, multi-tasking, accuracy critical

**User priorities:**

1. Accuracy
2. Confidence
3. Clarity
4. Speed

---

## UX PHILOSOPHY

DAFONow must support:

- Interrupt-driven workflow
- Passive awareness UX
- Confidence-based UX
- Error prevention UX
- Resume workflows

---

## PASSIVE UX LAYER *(VERY IMPORTANT)*

System must passively show:

- Draft exists
- Order delayed
- Missing scan
- Resume draft
- Tracking update

This must appear in:

- Dashboard
- Awareness strip
- Notifications
- Search

---

## USER PERSONAS

**Primary Persona: Orthotist**

| Attribute | Detail |
|---|---|
| Goals | Submit correct order, resume work, track orders |
| Pain Points | Interrupted workflow, complex ordering, hard to find orders |

---

## CUSTOMER JOURNEY

1. Start order
2. Interrupted
3. Save draft
4. Resume
5. Submit
6. Track

> Design must support the entire journey end-to-end.

---

## APPLICATION STRUCTURE

**Primary Navigation:**

- Dashboard
- Orders
- Patients
- Drafts
- Tracking
- Help

**Global Elements:**

- Global search
- Notifications
- Profile

---

## GLOBAL SEARCH

Search must support:

- Patient name
- Order number
- Job number
- Drafts
- Status
- Resume workflow
- Recovery workflow
- Speed

---

## ORDER CREATION FLOW

| Step | Label |
|---|---|
| Step 1 | Patient |
| Step 2 | Product |
| Step 3 | Customization |
| Step 4 | Review |
| Step 5 | Submit |

**Progress Bar Text:**

| Step | Text |
|---|---|
| Step 1 | Start patient order |
| Step 2 | Select DAFO type |
| Step 3 | Customize specifications |
| Step 4 | Review your order |
| Step 5 | Submit to Cascade |

---

## SAVE & DELETE

| Action | Rule |
|---|---|
| Save Draft | Available from Step 3 through Step 5 |
| Delete | Hidden — use label **Discard Draft** |

---

## TRACKING STATES

1. Submitted
2. Review
3. Manufacturing
4. Shipping
5. Delivered

**Tracking visible in:**

- Dashboard
- Orders
- Tracking tab
- Awareness strip

---

## PATIENTS TAB

Enable:

- Repeat ordering
- Patient history
- Faster workflow

---

## DASHBOARD

Show:

- Drafts
- Orders
- Tracking
- Resume

---

## VISUAL DESIGN PRINCIPLES

Must be:

- Calm
- Professional
- Minimal
- Medical-grade
- Enterprise-grade

---

## CASCADE BRANDING

> Source: Cascade Dafo Branding Guide Rev08 (official)

Colors must remain consistent across ALL variations. Only layout and density may change.

---

### Official Brand Color Palette

| Color Name | Pantone | HEX | RGB | UI Usage |
|---|---|---|---|---|
| **DAFO Blue** *(Corporate Primary)* | PMS 287 C | `#00338E` | 0 / 82 / 155 | Primary actions, nav, buttons, links |
| Dark Green | PMS 3295 C | `#007360` | 0 / 115 / 96 | Success states, confirmed orders |
| Light Green | PMS 360 C | `#72BF44` | 114 / 191 / 68 | Progress indicators, active states |
| Orange | PMS 715 C | `#F7943E` | 247 / 148 / 62 | Warnings, alerts, CTAs, awareness strip |
| Red | PMS 199 C | `#D71440` | 215 / 20 / 64 | Errors, destructive actions |
| Purple | — | `#403B78` | 64 / 59 / 120 | Secondary accent (use sparingly) |
| Violet | — | `#A066AB` | 160 / 102 / 170 | Tertiary accent (use sparingly) |
| Blue | — | `#0088CB` | 0 / 136 / 203 | Info states, secondary links |
| Grey | PMS 425 C | `#58595B` | 88 / 89 / 91 | Body text, borders, disabled states |
| CCI Green | PMS 362 C | `#4A9E42` | 74 / 158 / 66 | CCI-specific contexts |

### UI System Tokens (derived from official palette)

| Token | Hex | Role |
|---|---|---|
| `--color-primary` | `#00338E` | DAFO Blue — nav, primary buttons, active state |
| `--color-primary-light` | `#0088CB` | Hover, secondary actions, links |
| `--color-accent` | `#F7943E` | Awareness strip, CTAs, alerts |
| `--color-success` | `#007360` | Order confirmed, delivered state |
| `--color-success-light` | `#72BF44` | Progress bar fill, step complete |
| `--color-error` | `#D71440` | Errors, discard actions |
| `--color-warning` | `#F7943E` | Delayed orders, missing scans |
| `--color-text-primary` | `#58595B` | Body text, labels |
| `--color-text-dark` | `#1A1A2E` | Headings (dark navy derived) |
| `--color-surface` | `#FFFFFF` | Cards, panels |
| `--color-background` | `#F5F7FA` | Page background |
| `--color-border` | `#E0E4EA` | Card borders, dividers |

---

### Official Typography

> Source: Cascade Dafo Branding Guide — Section 7: Typeface

**Primary Typeface: Myriad Pro**

| Weight | Usage in DAFONow |
|---|---|
| Myriad Pro Light | Body text, descriptions, secondary labels |
| Myriad Pro Regular | Default UI text, form fields, data |
| Myriad Pro Semibold | Subheadings, section labels, nav items |
| Myriad Pro Bold | Page headings, card titles, primary CTAs |
| Myriad Pro Black | Hero headlines only — use sparingly |

**Secondary Typeface: Palatino Linotype**
- Use for large bodies of instructional or editorial text (e.g., Help section, onboarding copy)

**Web Font Fallback Stack:**
```css
font-family: 'Myriad Pro', 'Gill Sans', 'Trebuchet MS', sans-serif;
font-family: 'Palatino Linotype', 'Book Antiqua', Palatino, serif;
```

> Note: Myriad Pro is a licensed Adobe font. For web use, load via Adobe Fonts (Typekit) or substitute with **Source Sans Pro** (Google Fonts — visually closest free alternative).

**Recommended Google Fonts substitute for prototype:**
```
Source Sans Pro — Light (300), Regular (400), SemiBold (600), Bold (700)
```

---

**Must feel:** Professional · Calm · Trustworthy · Craftsmanship-driven

---

## CLICKABLE PROTOTYPE REQUIREMENT

Must create clickable:

- Navigation
- Order flow
- Tracking
- Drafts
- Search

**User must be able to:**

- Start order
- Save draft
- Resume
- Submit
- Track

---

## REQUIRED DESIGN VARIATIONS

### VARIATION 1 — Starbucks Inspired UX

**Inspiration:** Clean · Spacious · Calm · Premium

Characteristics:

- Generous spacing
- Calm typography
- Smooth layout
- Premium feel

Constraints:

- Must retain Cascade colors
- Must retain Clinical UX

---

### VARIATION 2 — McMaster Inspired UX

Characteristics:

- Highly functional
- Data-driven
- Dense information
- Powerful filtering

Constraints:

- Must remain clean, usable, and professional

---

### VARIATION 3 — Apple / Nike / Adidas Inspired UX

Characteristics:

- Minimal
- Elegant
- High-end
- Visual clarity

Focus:

- Simplicity
- Hierarchy
- Premium feel

---

### VARIATION 4 — World's Best Designer Free-Hand Version

Design the best possible experience for orthotists, clinics, and healthcare.

Goals:

- Industry-leading UX
- Best in America
- Blow away end users
- Blow away Don
- Blow away stakeholders

This version should:

- Combine best UX principles
- Push innovation
- Maintain simplicity

---

## FINAL DELIVERABLES

**Screens Required:**

- Dashboard
- Orders
- Patients
- Drafts
- Tracking
- Order flow — all 5 steps
- Search

---

## FINAL GOAL

Design the **best orthotics ordering application in America**.

The final product must:

- Blow away Don
- Impress Cascade leadership
- Delight orthotists
- Be enterprise-grade
- Be intuitive

> Design like the world's best product designer.

---

## TECH STACK — CLICKABLE PROTOTYPE

### Core Framework

| Layer | Technology |
|---|---|
| Framework | React 18 + Vite |
| Styling | Tailwind CSS v3 |
| Icons | Lucide React |
| Routing | React Router DOM v6 |
| State Management | Zustand |
| Animations | Framer Motion |
| Charts / Data Viz | Recharts |
| Component Primitives | Radix UI (unstyled, accessible) |
| Notifications / Toasts | React Hot Toast |
| Forms | React Hook Form |
| Date Handling | Day.js |

### Dev Tooling

- ESLint + Prettier
- Vite HMR
- VS Code with Tailwind IntelliSense extension

---

### Scaffold Command

Run the following to bootstrap the project:

```bash
npm create vite@latest dafanow -- --template react
cd dafanow
npm install tailwindcss postcss autoprefixer
npm install react-router-dom zustand framer-motion recharts
npm install @radix-ui/react-dialog @radix-ui/react-tooltip @radix-ui/react-dropdown-menu
npm install react-hook-form react-hot-toast dayjs lucide-react
npx tailwindcss init -p
```

---

### Folder Structure

```
/src
  /components         — Shared UI components (Button, Badge, Input, Card, etc.)
  /pages              — Dashboard, Orders, Patients, Drafts, Tracking
  /flows              — Order creation steps (Step1 through Step5)
  /store              — Zustand state slices (orders, drafts, patients, ui)
  /hooks              — Custom hooks (useSearch, useDrafts, useTracking, etc.)
  /assets             — Logos, brand assets, icons
  /styles             — Global CSS, Tailwind config, CSS variables
  App.jsx
  main.jsx
```

---

### Key Implementation Rules

1. **All 4 variations share the same Zustand store and routing** — only the layout/visual layer changes per variation.
2. **Each variation lives in its own folder** for independent deployment.
3. **Shared components** (Button, Input, Badge, Card) accept a `variant` prop for per-variation style overrides.
4. **All navigation clicks must route to real pages** — no dead links, no empty placeholders.
5. **All 5 order flow steps must be fully functional** with state persisted in Zustand.
6. **Drafts auto-save** to Zustand + `localStorage` — survives page refresh.
7. **Tracking states cycle through:** `Submitted → Review → Manufacturing → Shipping → Delivered`
8. **Awareness strip renders globally** on all pages — shows draft status, delays, tracking updates.
9. **Global search modal** is accessible via `Cmd+K` / `Ctrl+K` from anywhere in the app.
10. **Passive UX layer** must be always-on — draft exists, order delayed, missing scan, resume draft, and tracking updates must surface passively without user needing to look for them.
11. **Save Draft** is available from Step 3 onwards in the order flow. Delete is labelled **Discard Draft** — never "Delete".

---

## END OF PROMPT
