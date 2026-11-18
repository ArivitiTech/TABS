# 03 · Molecules
*Tracks: .potx · .dotx · .css · .jsx · .mjml · .json*

- [Download Derived Logos](/03_MOLECULE_Logo_Derivatives)

- [Download Core Templates](/03_MOLECULE_Templates)

## What This File Is (and Isn't)

Molecules are reusable template and code files. This document does not restate brand rules; it links each file to the upstream document that governs its implementation. Build every molecule strictly from the Strings, Particles, and Atoms documents — never re-derive it from memory or vibes.

Read the "Governed By" column first. That document is the specification for the file.

## Template Manifest

| File                         | Purpose                                                                        | Governed By                                                                   | Owner                   |
| ---------------------------- | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------- | ----------------------- |
| **`ariviti-brand.potx`**     | Locked PowerPoint master — theme colors, slide masters, and layouts            | Particles (Color, Type Scale) + Compounds → Slide Deck Template               | Brand owner             |
| **`ariviti-brand.dotx`**     | Locked Word master — styles for headings, body, case study/one-pager structure | Particles (Typography) + Compounds → Case Study & One-Pager Templates         | Brand owner             |
| **`ariviti-tokens.css`**     | CSS custom properties for every color and type value                           | Particles → Color Swatches "File Formats to Maintain"; Particles → Typography | Web/product engineering |
| **`ariviti-components.jsx`** | React component library implementing the Component Library                     | Strings → Atomic Design Methodology, "Component Library — Minimum Viable Set" | Web/product engineering |
| **`ariviti-signature.mjml`** | Responsive email-signature markup (replaces raw inline-HTML draft)             | Compounds → Email Signatures                                                  | IT / Marketing ops      |
| **`ariviti-tokens.json`**    | Design-token export (colors, type scale) for Figma/pipeline consumption        | Particles doc, in full                                                        | Brand owner             |

## Build Principles (apply to every molecule above)

1. **No molecule invents a new value.** If a `.jsx` button component needs a color not in Particles → Color Swatches, that's a token-level decision — it escalates per the Decision Rights Table (Strings → Implementation & Governance), it does not get quietly added in code.
2. **No molecule skips accessibility.** Every component in `ariviti-components.jsx` must pass the Fragility Score (Particles → Accessibility) before merge — this includes contrast, alt text props, and keyboard focus states.
3. **Molecules are versioned with the system, not independently.** A `.css` token file that drifts from the Particles doc is a bug, not a style choice — see Version Control (Strings → Implementation & Governance).
4. **MJML over raw HTML for anything email-bound.** The current signature spec (Compounds doc) is written as a plain HTML table for readability; the actual production file should be MJML, which compiles to more reliable cross-client HTML than hand-written tables.

