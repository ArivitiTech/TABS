# Ariviti Brand System — Manifest

Reference list of files organized by the atomic-design tier structure this
system follows. See `Living_Style_Guide/index.html` for the visual version.

**Note on scope:** this reference is not the same taxonomy as any separate "TABS" repository system you may
be running elsewhere — that system has its own `04-molecules.md` build
manifest with its own canonical values. If reconciling the two, treat that
repo's `02-particles.md` as authoritative for any color/type value conflict;
this manifest's tokens were derived independently and are a starting point
for that repo, not a replacement for it.

---

## 01 · Particle (indivisible tokens)

| File |
|---|
| `Palette_Primary.ase`, `Palette_Secondary.ase`, `Palette_Print_CMYK.ase` |
| `tokens_color.json`, `colors.css`, `colors.scss` |
| `colors_accessible_addendum.css` |
| `tokens_typography.json`, `typography.css`, `typography.scss` |
| `Icon_Library.zip` (36 icons × 6 color variants + sprite) |
| `Generate_Palette_Apple_clr.applescript` |
| Logo vector (.ai/.eps/.svg), brand font files (.ttf/.otf) |

## 02 · Atom (smallest composed pieces)

| File |
|---|
| Web Component Library — React ×6, Vue ×6, pixel-identical |
| `Chart_Style_Gallery.pptx` (4 native, editable charts) |
| `Imagery_Guide.zip` (crop ratios, duotone treatment spec) |
| `Figma_Tokens/ariviti.tokens.json` |
| Figma component file (native `.fig`) |

## 03 · Molecule (reusable document/page shells)

| File |
|---|
| `Ariviti_Proposal.potx` (22 layouts, MBB-hybrid) |
| `Ariviti_Presentation.potx`, `Ariviti_Report_POV.potx`, `Ariviti_Internal.potx`, `Ariviti_OnePager.potx`, `Ariviti_Brochure.potx`, `Printable_4x3_Master.potx` |
| `Corporate_Document_Master.dotx`, `Formal_Letterhead_Master.dotx` |
| `Email_Header_Footer_Wrapper.mjml` / `.html` |
| `Email_Signature_Template.html` |
| `Social_Templates.zip` (LinkedIn post, LinkedIn banner, OG image) |
| Business card / stationery die-line |
| `Palette_Print_CMYK.acb` (Adobe Color Book) |

## 04 · Organism (full assemblies)

| File |
|---|
| `Demo_Monthly_Newsletter_Live.html`/`.mjml`, `Demo_Product_Announcement_Email.html`/`.mjml`, `Demo_Landing_Page.html` |
| `Living_Style_Guide/index.html` |

## Governance

| File |
|---|
| `WCAG_Contrast_Audit.md` |
| This manifest |

---

