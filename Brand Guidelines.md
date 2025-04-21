<p align="center">
  <img src="https://github.com/salvium/brand-assets/blob/main/Salvium_assets/wordmark_logo/black/solid/salvium_wordmark_black_1024x1024px_solid.png?raw=true" width="200"/>
</p>

# Salvium Brand Guidelines
Welcome to the Salvium brand guideline. This document defines the visual and stylistic standards that represent the Salvium identity — a privacy-first, regulation-ready, proof-of-work blockchain.
These guidelines ensure that our design language remains consistent and recognizable across all platforms and communication channels.
---
## Typography
Salvium's typographic style reflects clarity, security, and modernism — all key to our brand philosophy.
### Primary Font
**Font Name:** `Poppins`  
**Usage:** Headlines, Subheadings, Emphasis  
**Style:** Bold or Semi-Bold  
**Example:**  
```css
font-family: 'Poppins', sans-serif;
font-weight: 600;
```
### Secondary Font
**Font Name:** `Roboto`  
**Usage:** Body text, UI elements, technical documentation  
**Style:** Regular  
**Example:**  
```css
font-family: 'Roboto', sans-serif;
font-weight: 400;
```
---
## Color Palette
Salvium's color system is designed to convey strength, trust, and innovation — suitable for a protocol that balances privacy and regulatory compliance.

### Website Colors

#### Background Colors
| Color Name        | Variable Name       | Hex       | Usage                      |
|------------------|---------------------|-----------|----------------------------|
| Dark Background   | `--color-bg-dark`   | `#1e1e1e` | Main background            |
| Darker Background | `--color-bg-darker` | `#1e1e1e` | Secondary background       |
| Header Background | `--color-bg-header` | `#1e1e1e` | Navigation headers         |

#### Text Colors
| Color Name      | Variable Name          | Hex       | Usage                      |
|----------------|------------------------|-----------|----------------------------|
| Primary Text    | `--color-text`         | `#e0e0e0` | Main body text             |
| Light Text      | `--color-text-light`   | `#e0e0e0` | Secondary text             |
| Lighter Text    | `--color-text-lighter` | `#b0b0b0` | Tertiary/caption text     |

#### Accent Colors
| Color Name     | Variable Name         | Hex/Value | Usage                      |
|---------------|----------------------|-----------|----------------------------|
| Primary Accent | `--color-accent`      | `#40E0D0` | Buttons, highlights        |
| Light Accent   | `--color-accent-light`| `#80cbc4` | Secondary highlights       |
| Salvium Dot    | (No variable)         | `#0AEB85` | Logo dot, accent highlights|

#### Border Colors
| Color Name     | Variable Name         | Value     | Usage                      |
|---------------|----------------------|-----------|----------------------------|
| Primary Border | `--color-border`      | `rgba(0, 191, 165, 0.15)` | Content dividers |
| Light Border   | `--color-border-light`| `rgba(0, 191, 165, 0.05)` | Subtle separators |

### Color Usage Example (CSS)
```css
body {
  background-color: var(--color-bg-dark);
  color: var(--color-text);
}
a {
  color: var(--color-accent);
}
.border {
  border: 1px solid var(--color-border);
}
.salvium-dot {
  color: #0AEB85;
}
```
---
## Salvium Green Dot
The green dot in our logo is a signature element of the Salvium brand identity. It represents our commitment to privacy, security, and innovation.

### Green Dot Color Specifications

| Format | Value |
|--------|-------|
| HEX | `#0AEB85` |
| RGB | `10, 235, 133` |
| CMYK | `96%, 0%, 43%, 8%` |
| HSL | `151°, 92%, 48%` |
| Pantone | PMS 354 C (closest match) |

### Usage Guidelines
- The green dot must always be displayed in `#0AEB85`
- Never alter the color of the dot, even when using the logo in monochrome contexts
- The dot serves as a recognizable brand element and can be used as a design motif in marketing materials
---
## Logo Usage
Our primary logo is available in multiple formats (SVG, PNG) in the [Salvium Brand Assets GitHub folder](https://github.com/salvium/brand-assets/tree/main/Salvium_assets).

### Guidelines
- **Minimum spacing:** Leave ample padding around the logo — do not crowd it with text or other graphics.
- **Use only** approved variants from the assets folder.
- **Color integrity:** Maintain the exact green dot color (`#0AEB85`) in all applications.

### Variants
- Full logo (with icon and text)
- Icon only (for favicons, app buttons, etc.)
- Dark mode and light mode versions
---
## Tone of Voice
Our voice is:
- **Authoritative** – We lead with confidence and clarity.
- **Transparent** – We explain complex privacy and compliance topics clearly.
- **Progressive** – We use forward-looking, privacy-positive language.
---
## Resources
- Website: [https://salvium.io](https://salvium.io)
- Brand Assets: [GitHub - Salvium Assets](https://github.com/salvium/brand-assets/tree/main/Salvium_assets)
- Litepaper: [Download PDF](https://salvium.io/litepaper.pdf)  
---
For any questions about branding or custom asset requests, contact the Salvium team directly via Discord.
