* New web site

Static web site that uses Github pages, and embodies the coolness and futuristic possibilities of an AI integrated virtual world. 

Feature scrolling code, neon 3D geometric shapes.

# Content

 * 4 Main pages with top navbar
 * Scrollable Home Page shows "Features" section with 5 key features. Also A section "Stack" that shows the main stack components OpenSimulator, OpenCode, libremetaverse and the Custom MCP Servers and Bot Client
 * "Get It" - Shows main pre-requisites section (just "Docker Compose" and an OpenSimulator viewer - link to a couple), then a section "Composee" with a link to release docker compose and the docker compose lines to start and start. Then finally a section that lists the mounts and the required (OPENSIM_HOSTNAMEE) and most likely to be changed environment variables
 * "Play It" - 2 Sections. First section "Login" with quick login instructions. 
 * "Share It" - Basic instructions on open ports and joining the hypergrid.

# Appearance

Very dark background, Kinda cyberish with high contrast neon colours. Can we mix the following three frameworks.

 * TailwindCSS
 * Template https://www.tailawesome.com/resources/cool-docs/demo
 * DaisyUI

## DaisyUI theme CSS

```
@plugin "daisyui/theme" {
  name: "night";
  default: false;
  prefersdark: false;
  color-scheme: "dark";
  --color-base-100: oklch(13% 0.028 261.692);
  --color-base-200: oklch(21% 0.034 264.665);
  --color-base-300: oklch(27% 0.033 256.848);
  --color-base-content: oklch(96% 0.003 264.542);
  --color-primary: oklch(51% 0.262 276.966);
  --color-primary-content: oklch(96% 0.018 272.314);
  --color-secondary: oklch(55% 0.288 302.321);
  --color-secondary-content: oklch(97% 0.014 308.299);
  --color-accent: oklch(60% 0.118 184.704);
  --color-accent-content: oklch(98% 0.014 180.72);
  --color-neutral: oklch(44% 0.03 256.802);
  --color-neutral-content: oklch(98% 0.002 247.839);
  --color-info: oklch(71% 0.143 215.221);
  --color-info-content: oklch(98% 0.019 200.873);
  --color-success: oklch(70% 0.14 182.503);
  --color-success-content: oklch(98% 0.014 180.72);
  --color-warning: oklch(70% 0.213 47.604);
  --color-warning-content: oklch(98% 0.016 73.684);
  --color-error: oklch(64% 0.246 16.439);
  --color-error-content: oklch(96% 0.015 12.422);
  --radius-selector: 0.5rem;
  --radius-field: 0.5rem;
  --radius-box: 0.5rem;
  --size-selector: 0.25rem;
  --size-field: 0.25rem;
  --border: 1px;
  --depth: 0;
  --noise: 0;
}
```
