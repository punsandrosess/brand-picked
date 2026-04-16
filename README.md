# Sow What · Brand Discovery Tool

**AI-powered brand strategy for cybersecurity founders**

Built by [Kelsey LaBelle](https://kelseylabelle.com) (aka [punsandrosess](https://github.com/punsandrosess)) · *the gardener of cybersecurity marketing*

---

## What It Does

Sow What is a comprehensive brand discovery tool designed specifically for cybersecurity founders. Through 21 strategic questions across 6 sections, it helps technical founders articulate their authentic brand positioning without the typical corporate marketing fluff.

**The tool generates 5 strategic brand outputs:**
1. **Brand Archetype** (with reference links and examples)
2. **Brand Personality Profile** (voice, character, energy)
3. **Positioning Framework** (April Dunford's 5-component system)
4. **Visual Direction Brief** (emotional targets and design metaphors)
5. **Taglines + Voice Lines** (3-5 strategic directions)

## Key Features

### 🎯 **Cybersecurity-Focused Questions**
- Customer goals (explicit vs implicit)
- Best/worst customer stories
- Conviction under pressure moments
- Market pattern recognition
- Anti-patterns and villains

### 🤖 **AI-Agnostic Generation**
- **Anthropic Claude** (recommended)
- **OpenAI GPT** (experimental)
- **Custom API endpoints** (any OpenAI-compatible API)
- **No API key required** (export structured prompts)

### 💰 **Cost Optimization**
- Real-time cost estimation
- Token-efficient prompts (70% reduction)
- **Off-peak scheduling** (30-50% savings)
- **Batch vs Sequential** generation modes

### 📚 **Brand Archetype Reference System**
- **12 complete archetypes** with descriptions and examples
- **Auto-detection** from AI outputs
- **Direct links** to [iconicfox.com.au](https://iconicfox.com.au/brand-archetypes/)
- **Zero API credits** used (hardcoded data)

### 🎨 **GitHub Technical Aesthetic**
- Clean, grid-based design system
- **punsandrosess** branding
- Full light/dark mode support
- Corner bracket styling throughout

### 📤 **Flexible Export Options**
- **.md/.txt** formats with complete answer appendix
- **PDF export** (via print dialog)
- **Structured AI prompts** for any tool

## How It Works

### Path 1: AI Generation
1. **Answer 21 questions** across 6 strategic sections
2. **Upload supporting files** (optional: PDFs, docs, images)
3. **Choose your AI provider** and generation mode
4. **Review and refine** each output (2 refinements per output)
5. **Export final results** in your preferred format

### Path 2: Prompt Export
1. **Answer the questions** (same strategic framework)
2. **Export structured prompt** as markdown file
3. **Use with any AI tool** (Claude.ai, ChatGPT, etc.)
4. **Get the same quality outputs** without API setup

## The Question Framework

### Section 01: Customer Goals
- What customers think they want vs what they actually optimize for
- How you're different (not just better)
- The headline when you succeed
- Wrong-fit customers to avoid

### Section 02: Your Believers  
- Best customer story and why it worked
- Worst prospect story and the misalignment
- Upload zone for customer testimonials/reviews

### Section 03: Belief System + Origin Story
- Conviction under pressure moments
- Industry anti-patterns you won't tolerate
- Turning point customer stories
- Core beliefs and worldview
- Upload zone for blog posts/manifestos

### Section 04: The Problem You Name
- Patterns you keep seeing that others miss
- Cautionary tales from the market
- What disappears if you don't exist
- Upload zone for competitive analysis

### Section 05: Personification
- Your brand as a high school student
- Place metaphor for brand atmosphere  
- Why you started vs why you stay
- Competitor you could beat and how
- Upload zone for current taglines/mood boards

### Section 06: Brand Feeling
- Two critical customer encounter scenes
- Upload zone for company culture docs

## Technical Specifications

### Requirements
- Modern web browser with JavaScript enabled
- No server setup required (runs entirely client-side)
- Optional: AI API key for generation path

### API Support
- **Anthropic Claude Sonnet 4** (primary, fully tested)
- **OpenAI GPT-4** (experimental support)  
- **Custom endpoints** (must accept OpenAI-compatible format)

### Cost Optimization Features
- **Token-efficient prompts** (~70% reduction from verbose versions)
- **Real-time cost estimation** before generation
- **Off-peak scheduling** with timezone support
- **Rate limit protection** with automatic delays
- **Sequential mode** for budget control

### Data Privacy
- **Client-side only** - no data sent to external servers
- **sessionStorage** for API keys (clears on tab close)
- **localStorage** for session persistence
- **File processing** happens in browser
- **No tracking** or analytics

## Brand Archetype Reference System

The tool includes a complete hardcoded reference system with:

- **12 Standard Archetypes**: Innocent, Sage, Explorer, Outlaw, Magician, Hero, Lover, Jester, Everyman, Caregiver, Ruler, Creator
- **Rich Descriptions**: Core traits and characteristics  
- **Brand Examples**: Nike (Hero), Apple (Magician), Google (Sage), etc.
- **Direct Links**: Specific pages on iconicfox.com.au
- **Auto-Detection**: Matches AI outputs to archetype references
- **Zero Credits**: No API calls required for reference data

## File Structure

```
sow-what.html                 # Complete single-file application
├── CSS (embedded)            # GitHub technical design system
├── JavaScript (embedded)    # Full application logic
├── Fonts (Google Fonts)     # Playfair Display, Source Serif 4, Space Mono
└── No dependencies          # Self-contained, no external JS libraries
```

## Usage Examples

### For Cybersecurity Founders
```bash
# Download the HTML file
# Open in any modern browser
# Answer 21 questions about your startup
# Generate brand outputs with your preferred AI
```

### For Brand Consultants
```bash
# Use with clients who need technical credibility
# Export prompts for use in client's preferred AI tools
# Reference system provides educational value
# Professional GitHub aesthetic builds trust
```

### For Marketing Teams
```bash
# Cost-effective alternative to brand consultancy
# Technical founder-friendly language and examples  
# Structured outputs ready for design/copy teams
# Off-peak scheduling reduces API costs
```

## Cost Estimates

### API Generation Path
- **Full session**: ~$0.50-$0.75 USD
- **Single output**: ~$0.10-$0.15 USD
- **Off-peak savings**: 30-50% cost reduction
- **Token efficiency**: 70% reduction from verbose prompts

### No-API Path
- **Completely free** - export structured prompts
- **Use with any AI tool** you already have access to
- **Same strategic framework** and output quality

## Philosophy

> *"You can't outsource conviction."*  
> — Kelsey LaBelle

**Sow What** is built on the belief that authentic brands come from founders who know what they stand for, not from generic positioning exercises. The tool helps technical founders:

- **Find their authentic voice** rather than adopting corporate speak
- **Identify their true differentiators** beyond feature comparisons  
- **Connect with believers** rather than trying to convince skeptics
- **Build conviction-driven brands** that attract the right customers

The questions are designed to surface the founder's genuine beliefs, experiences, and worldview. The AI then helps articulate these insights into professional brand language that maintains the founder's authentic voice.

## Contributing

This is a single-file application designed for simplicity and portability. For suggestions or improvements:

1. **Open issues** for feature requests or bugs
2. **Fork and modify** the single HTML file
3. **Test thoroughly** across different browsers and AI providers
4. **Submit pull requests** with clear descriptions

## License

MIT License - feel free to use, modify, and distribute.

## Credits

**Built by**: [Kelsey LaBelle](https://kelseylabelle.com) (punsandrosess)  
**Archetype Reference**: [Iconic Fox](https://iconicfox.com.au/brand-archetypes/)  
**Positioning Framework**: April Dunford methodology  
**Brand Philosophy**: Roei Deutsch (believer marketing) and Don Jeter (B2B brand building)

---

## Quick Start

1. **Download** `sow-what.html`
2. **Open** in any modern web browser
3. **Choose your path**: AI generation or prompt export
4. **Answer 21 questions** about your cybersecurity startup
5. **Generate or export** your brand strategy
6. **Use the outputs** as foundation for marketing, design, and positioning

**The soil is prepared. The planting is still on you.**
