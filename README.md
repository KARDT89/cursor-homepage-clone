# Cursor Homepage Clone

A recreation of the Cursor homepage with custom styling and layout.

## Live Demo

Visit the hosted website: [https://kardt89.github.io/cursor-homepage-clone/](https://kardt89.github.io/cursor-homepage-clone/)

![Cursor Homepage Clone Screenshot](./assets/screenshot.png)

## Sections Recreated

### Navigation Header

- Sticky navigation bar with Cursor logo
- Navigation menu (Features, Enterprise, Pricing, Resources)
- Sign in and Download buttons

### Hero Section

- Main headline: "Built to make you extraordinarily productive, Cursor is the best way to code with AI."
- Call-to-action button (Download for Windows)
- Hero image display

### Company Logos / Trust Section

- "Trusted every day by millions of professional developers"
- 8-column grid of company logos (Stripe, OpenAI, Liner, Datadog, Nvidia, Figma, Ramp, Adobe)

### Features Section (3 Main Features)

1. **Agent** - "turns ideas into code" with detailed description
2. **Tab** - "Magically accurate autocomplete" with model prediction details
3. **Everywhere** - "software gets built" covering integration points

Each feature includes an image and learn more link.

### Research Team Section

- "Cursor is an applied research team focused on building features of software development"
- Call-to-action: "Join us"
- Feature image

### Testimonials Section

- Headline: "The new way to build software"
- 6 testimonial cards from industry leaders:
    - Diana Hu (Y Combinator General Partner)
    - shadcn (Creator of shadcn/ui)
    - Andrej Karpathy (CEO, Eureka Labs)
    - Patrick Collison (Co-Founder & CEO, Stripe)
    - ThePrimeagen
    - Greg Brockman (President, OpenAI)

Each testimonial includes author photo and title.

### Use Cases Section ("Stay on the Frontier")

- 3-column grid of use cases:
    1. **Access the best models** - Choose from OpenAI, Anthropic, Gemini, xAI
    2. **Complete codebase understanding** - Semantic search capabilities
    3. **Develop enduring software** - Enterprise trust and scale

Each includes description and action link with images.

### Changelog Section

- Recent updates with version numbers and dates:
    - Version 2.4 (Jan 22, 2026): Subagents, Skills, Image Generation
    - Jan 16, 2026: CLI Agent Modes and Cloud Handoff
    - Jan 8, 2026: New CLI Features and Performance
    - Version 2.3 (Dec 22, 2025): Layout Customization

### Recent Highlights

Updated three highlight cards with real content:

1. **Towards self-driving codebases** - Research · Feb 5, 2026
2. **Salesforce ships higher-quality code** - Customers · Jan 21, 2026
3. **Best practices for coding with agents** - Product · Jan 9, 2026

Each card includes a title, description, and category with date.

### Call-to-Action Section

- Large headline: "Try Cursor now"
- Download button

### Footer

The footer was completely restructured with a multi-column layout:

- **Product Column**: Agents, Enterprise, Code Review, Tab, CLI, Cloud Agents, Pricing
- **Resources Column**: Download, Changelog, Docs, Forum, Status
- **Company Column**: Careers, Blog, Community, Students, Brand, Anysphere
- **Legal Column**: Terms of Service, Privacy Policy, Data Use, Security
- **Connect Column**: X, LinkedIn, YouTube

Bottom footer bar includes:

- Copyright notice and SOC 2 Certified badge
- Icon buttons (keyboard, light mode, dark mode)
- Language selector (English)

## Design System

### Fonts

- **Primary Font**: Cursor Gothic (custom font family: `cursor`)
    - Source: `./assets/CursorGothic-Regular.woff2`
    - Weight: 400 (Regular)
    - Style: Normal

### Color Palette

| Variable                       | Hex Code    | Purpose                          |
| ------------------------------ | ----------- | -------------------------------- |
| `--background-color`           | `#14120B`   | Main dark background             |
| `--light-bg`                   | `#1B1913`   | Lighter background sections      |
| `--text-color`                 | `#ECECEC`   | Primary text color               |
| `--ghost-bg`                   | `#ECECEC`   | Light button/element backgrounds |
| `--ghost-text`                 | `#14120B`   | Dark text on light backgrounds   |
| `--light-inner-color`          | `#201E18`   | Inner section backgrounds        |
| `--secondary-background-color` | `#1b1913`   | Card/box backgrounds             |
| `--secondary-text-color`       | `#f75712`   | Accent color (orange/red)        |
| `--muted-text-color`           | `#fffefe86` | Faded/secondary text             |

### Typography

- **Body text**: 0.9rem default
- **Primary headings**: 4.5rem (CTA section)
- **Section headings**: 2rem
- **Feature headings**: 1.4rem - 1.625rem
- **UI text**: 0.875rem

All text uses line-height: 1.5 and the Cursor Gothic font family.
