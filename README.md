# Sow What · Brand Discovery Tool

> **Your brand starts with what you believe.**

A brand discovery tool for cybersecurity founders. Twenty-one questions across six sections, designed to surface the convictions, beliefs, and strategic instincts that make your company yours, before a single campaign runs.

## Overview

Sow What is a thoughtfully designed single-page application that guides cybersecurity founders through a structured brand discovery process. The tool generates five key brand outputs using AI: Brand Archetype, Personality Profile, Positioning, Visual Direction Brief, and Taglines & Voice Lines.

### Key Features

- **21 Strategic Questions** across 6 sections covering customer goals, competitive positioning, beliefs, and brand personality
- **Tab Navigation** with clickable horizontal tabs showing your progress across all sections
- **File Upload Support** for existing brand materials, competitor research, and voice examples
- **AI Integration** with Anthropic Claude, OpenAI GPT, and Perplexity for brand output generation
- **Dark/Light Theme Toggle** with full accessibility support and theme-aware color variables
- **Export Options** - Download as Markdown, TXT, or printer-friendly PDF formats
- **Session Persistence** - Answers automatically saved in browser
- **Clear All Functionality** with confirmation for starting over (preserves theme preference)

## Technical Implementation

### Architecture
- **Single-page application** - No external dependencies, fully self-contained
- **Vanilla JavaScript** - Clean, performant, framework-free implementation
- **CSS Custom Properties** - Full theming system with dark/light mode support using `body.light` class toggle
- **Web APIs** - Direct integration with AI providers via fetch API
- **Local Storage** - Client-side session persistence

### Design System
- **Typography**: Playfair Display (headlines), Source Serif 4 (body), Space Mono (accents)
- **Color Palette**: Forest green system with botanical accents and terracotta highlights
- **Component Library**: Consistent buttons, cards, modals, and form elements
- **Responsive Layout**: Mobile-first design with flexible breakpoints

### AI Integration
- **Anthropic Claude** (Recommended) - Claude Sonnet 4 (`claude-sonnet-4-6`) for brand strategy
- **OpenAI GPT** - GPT-4o for alternative generation approach
- **Perplexity** - Llama 3.1 Sonar for research-enhanced, web-connected outputs
- **Rate Limiting** - Built-in 3-second delays and batch processing options
- **Error Handling** - Comprehensive API error management with provider-specific messages
- **Key Validation** - Provider-aware validation (sk-ant- for Anthropic, sk- for OpenAI, pplx- for Perplexity)

## Usage

### Getting Started
1. Open the application in a modern web browser
2. Toggle between light/dark modes using the theme button
3. Begin the brand discovery process with "Let's dig in"

### The Discovery Process

#### Section 1: Customer & Goals
- Explicit vs implicit customer goals
- Better vs different value proposition
- Target customer identification
- Wrong customer avoidance

#### Section 2: Competition & Market
- Competitive landscape mapping
- Status quo alternatives
- Market position clarity
- Unique value identification

#### Section 3: Beliefs & Convictions
- Core belief system
- Industry patterns and insights
- Mission-critical convictions
- Worldview articulation

#### Section 4: Voice & Personality
- Brand personality traits
- Communication style
- Voice and tone guidelines
- High school student explanation test

#### Section 5: Metaphors & Imagery
- Place metaphors for brand feeling
- Founder energy and approach
- Visual direction guidance
- Atmospheric brand qualities

#### Section 6: Lines & Messaging
- Tagline and messaging uploads
- Brand encounter scenarios
- Product moment descriptions
- Voice line development

### Export Options

#### AI Generation Path
1. **API Key Setup** - Enter your AI provider API key (provider-specific validation)
2. **Generation Mode** - Choose batch (slower, safer), sequential (one at a time), or off-peak (scheduled for lower cost)
3. **Output Review** - Approve or refine each of 5 brand outputs
4. **Final Export** - Download completed brand strategy as MD, TXT, or PDF

#### Manual Export Path
1. **Markdown Prompt** - Export formatted AI prompt for any tool
2. **PDF Export** - Download questions and answers for review (printer-friendly layout)
3. **Session Data** - All answers preserved in browser storage

## Brand Outputs Generated

### 1. Brand Archetype
Primary archetype identification from the standard 12, with supporting evidence from responses.

### 2. Brand Personality Profile
- **Voice and Tone** - How the brand speaks and what it avoids
- **Character Sketch** - Brand's unique worldview and positioning angle  
- **Tone and Energy** - Specific descriptors earned from responses

### 3. Positioning (April Dunford Framework)
- **Who This Is For** - Specific target customer definition
- **The Promise** - Value proposition through "so what" test
- **The Voice** - Communication approach and style
- **Competitive Alternatives** - Real alternatives customers consider
- **Market Gap** - White space opportunity identification

### 4. Visual Direction Brief
- **Emotional Target** - Specific scenes and feelings to evoke
- **Should Feel Like** - Atmospheric direction from place metaphors
- **Suggested Metaphors** - Visual and verbal anchors for design

### 5. Taglines & Voice Lines
- **Multiple Directions** - 3-5 distinct strategic approaches
- **Complete Line Sets** - Hero, belief, kicker lines for each direction
- **Strategic Reasoning** - Why each direction works for the brand

## File Structure

```
sow-what-v5.html
├── CSS Styles
│   ├── Theme System (CSS Custom Properties, body.light toggle)
│   ├── Tab Navigation (sticky, clickable section tabs)
│   ├── Component Styles (Buttons, Cards, Modals)
│   ├── Layout System (Responsive Grid)
│   └── Dark/Light Mode Overrides (body:not(.light) selectors)
├── HTML Structure  
│   ├── Header (Punsandrosess branding, Theme Toggle, Clear All)
│   ├── Tab Navigation Bar (dynamic, section-aware)
│   ├── Welcome Screen
│   ├── Question Sections (Dynamically Rendered)
│   ├── API Configuration Screen (Radio buttons for provider selection)
│   ├── Generation & Review Screens
│   ├── Summary & Export Screen
│   └── Footer
└── JavaScript Application
    ├── Data Layer (Sections, Questions, State)
    ├── Tab Navigation (render, update, click handling)
    ├── UI Rendering (Screen Management, Form Handling)
    ├── AI Integration (Anthropic, OpenAI, Perplexity)
    ├── Export System (MD, TXT, Printer-friendly PDF)
    ├── Theme Management
    └── Local Storage Persistence
```

## Development Notes

### Recent Updates
- **API Models**: Updated to `claude-sonnet-4-6` (Anthropic) and `gpt-4o` (OpenAI)
- **Tab Navigation**: Added clickable horizontal tab bar for section navigation with completion indicators
- **Dark Mode**: Fixed theme system to use consistent `body.light` / `body:not(.light)` selectors; replaced broken `[data-theme="dark"]` rules; added proper dark-mode color variables for `--botanical-faint`, `--botanical-pale`, and `--terracotta-pale`
- **Radio Buttons**: Added `accent-color` styling for visibility in both themes
- **AI Provider Selection**: Replaced duplicate dropdown+radio UI with clean radio button group
- **Key Validation**: Now provider-aware (validates correct prefix per provider)
- **Clear All**: Fixed to preserve theme preference and reset all state properties correctly
- **PDF Export**: Printer-friendly margins (0.6in/0.7in), tighter spacing, `@media print` rules
- **Branding**: Header updated to Punsandrosess with GitHub link; terracotta accent in dark mode
- **Bug Fixes**: Removed duplicate `callAI()` and `generateWithKey()` function definitions; restored OpenAI provider support; cleaned up dead custom provider code

### Browser Compatibility
- **Modern Browsers**: Chrome 80+, Firefox 75+, Safari 13+, Edge 80+
- **ES6 Features**: Uses modern JavaScript (async/await, template literals, destructuring)
- **CSS Features**: Custom properties, CSS Grid, Flexbox
- **Web APIs**: Fetch API, Local Storage, Blob/URL APIs

### Security Considerations
- **API Keys**: Processed client-side only, never stored or transmitted to third parties
- **CORS Headers**: Handles cross-origin API requests with proper headers
- **Input Validation**: Sanitizes user input in exports and displays
- **XSS Prevention**: Escapes HTML content in dynamic rendering

## Philosophy & Approach

### Design Principles
- **Conviction-Driven**: Focus on beliefs and authentic positioning over tactics
- **Founder-Centric**: Built specifically for cybersecurity startup founders
- **Trust-Based**: No manipulation or FUD-based marketing approaches
- **Thoughtful Questioning**: Each question designed to surface genuine insights
- **AI-Augmented**: Technology enhances human insight rather than replacing it

### Brand Voice Guidelines
- **Warm & Editorial**: Conversational but authoritative tone
- **Direct Communication**: Say the quiet part out loud
- **No Corporate Jargon**: Plain language over business-speak
- **Evidence-Based**: Quote actual responses as supporting evidence
- **Starting Point Focus**: Directionally true, not finished - meant for reaction and refinement

## Credits & Attribution

**Built by [Punsandrosess](https://github.com/punsandrosess)**

### Methodology Influences
- **April Dunford** - Positioning framework and competitive alternative thinking
- **Don Jeter** - Brand personality and character-driven B2B approaches  
- **Roei Deutsch** - Believer marketing and conviction-based messaging
- **The Jolt Effect** - Decision-making psychology and customer indecision patterns

### Technical Implementation
- **Single-file Architecture** for simplicity and portability
- **No External Dependencies** for reliability and speed
- **Progressive Enhancement** for accessibility and performance
- **Thoughtful UX** prioritizing founder experience over technical complexity

---

*Sow What prepares the soil. The planting is still on you.*
