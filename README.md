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

### 🤖 **Multi-AI Provider Support**
- **Anthropic Claude** (recommended for brand work)
- **OpenAI GPT-4** (widely available)
- **Perplexity** (Llama 3.1 Sonar with web access)
- **Custom API endpoints** (any OpenAI-compatible API)
- **No API key required** (export structured prompts)

### 💰 **Advanced Cost Optimization**
- Real-time cost estimation with provider comparison
- Token-efficient prompts (70% reduction from verbose versions)
- **Off-peak scheduling** (30-50% savings with timezone support)
- **Multiple generation modes**: Batch, Sequential, Scheduled
- **Rate limit protection** with automatic delays

### 📚 **Brand Archetype Reference System**
- **12 complete archetypes** with descriptions and examples
- **Auto-detection** from AI outputs with smart keyword matching
- **Direct links** to [iconicfox.com.au](https://iconicfox.com.au/brand-archetypes/) 
- **Zero API credits** used (hardcoded reference data)
- **Professional examples**: Nike (Hero), Apple (Magician), Google (Sage)

### 🎨 **GitHub Technical Aesthetic**
- Clean, grid-based design system with corner bracket styling
- **punsandrosess** branding with kelseylabelle.com integration
- **Full light/dark mode** support with perfect contrast
- **Dynamic UI elements** that adapt to selected AI provider

### 📤 **Comprehensive Export Options**
- **.md/.txt** formats with complete answer appendix
- **PDF export** for both results and prompts (via print dialog)
- **Structured AI prompts** for use in any tool
- **Professional formatting** optimized for sharing

### 🔧 **User Experience Enhancements**
- **File upload & deletion** (× buttons, multiple formats supported)
- **Auto-save** with session persistence across browser restarts
- **Smart error handling** with actionable guidance
- **Dynamic form elements** that update based on selections

## How It Works

### Path 1: AI Generation
1. **Answer 21 questions** across 6 strategic sections
2. **Upload supporting files** (optional: PDFs, docs, images, any format)
3. **Choose your AI provider** from 4 supported options
4. **Select generation mode** (Batch, Sequential, or Off-peak Scheduled)
5. **Review and refine** each output (2 refinements per output max)
6. **Export final results** in your preferred format (.md, .txt, or PDF)

### Path 2: Prompt Export
1. **Answer the questions** (same strategic framework)
2. **Export structured prompt** as markdown or PDF
3. **Use with any AI tool** (Claude.ai, ChatGPT, Perplexity, etc.)
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

## AI Provider Comparison

| Provider | Model | Strengths | Cost (Est.) | API Key Format |
|----------|-------|-----------|-------------|----------------|
| **Anthropic** | Claude 3.5 Sonnet | Best for brand work, nuanced understanding | $0.50-0.75 | sk-ant-api03-... |
| **OpenAI** | GPT-4 | Widely available, consistent quality | $0.30-0.50 | sk-... |
| **Perplexity** | Llama 3.1 Sonar | Web-connected, latest information | $0.20-0.40 | pplx-... |
| **Custom** | Your choice | Self-hosted models, full control | Varies | Any format |

## Technical Specifications

### Requirements
- Modern web browser with JavaScript enabled
- No server setup required (runs entirely client-side)
- Optional: AI API key for generation path

### Cost Optimization Features
- **Token-efficient prompts** (~70% reduction from verbose versions)
- **Real-time cost estimation** with provider comparison
- **Off-peak scheduling** with intelligent timezone detection
- **Rate limit protection** with automatic retry logic
- **Multiple generation modes** for different budget needs

### Data Privacy & Security
- **Client-side only** - no data sent to external servers except chosen AI provider
- **sessionStorage** for API keys (clears on tab close)
- **localStorage** for session persistence and auto-save
- **File processing** happens entirely in browser
- **No tracking** or analytics of any kind

### Smart Error Handling
```
Network connection failed. Check CORS settings and internet connection.
Rate limit exceeded. Try sequential mode or wait a few minutes.
Invalid API key. Please check your key and try again.
```

## Brand Archetype Reference System

The tool includes a complete hardcoded reference system with:

- **12 Standard Archetypes**: Innocent, Sage, Explorer, Outlaw, Magician, Hero, Lover, Jester, Everyman, Caregiver, Ruler, Creator
- **Rich Descriptions**: Core traits and characteristics with emotional resonance
- **Brand Examples**: Nike (Hero), Apple (Magician), Google (Sage), IKEA (Everyman), etc.
- **Direct Links**: Specific archetype pages on iconicfox.com.au with detailed explanations
- **Auto-Detection**: Smart keyword matching and explicit mention recognition
- **Zero Credits**: No API calls required for reference data
- **Educational Value**: Helps founders understand their archetype in context

## File Structure

```
sow-what.html                 # Complete single-file application (420KB)
├── CSS (embedded)            # GitHub technical design system
├── JavaScript (embedded)    # Full application logic with multi-provider support
├── Fonts (Google Fonts)     # Playfair Display, Source Serif 4, Space Mono
└── No dependencies          # Self-contained, no external JS libraries
```

## Usage Examples

### For Cybersecurity Founders
```bash
# Download the HTML file
# Open in any modern browser
# Choose your preferred AI provider
# Answer 21 questions about your startup
# Generate brand outputs with cost optimization
# Export results as PDF, markdown, or text
```

### For Brand Consultants
```bash
# Use with clients who need technical credibility
# Export prompts for use in client's preferred AI tools
# Reference system provides educational value without billable hours
# Professional GitHub aesthetic builds trust with technical founders
```

### For Marketing Teams
```bash
# Cost-effective alternative to brand consultancy ($0.20-$0.75 per session)
# Technical founder-friendly language and examples  
# Structured outputs ready for design/copy teams
# Off-peak scheduling reduces costs by 30-50%
# Multiple export formats for different team workflows
```

## Cost Estimates (Updated)

### AI Generation Path
- **Anthropic Claude**: $0.50-$0.75 per full session (recommended quality)
- **OpenAI GPT-4**: $0.30-$0.50 per full session (good balance)
- **Perplexity**: $0.20-$0.40 per full session (most economical)
- **Off-peak savings**: 30-50% cost reduction across all providers
- **Token efficiency**: 70% reduction from verbose prompts
- **Sequential mode**: Review each output before continuing (cheapest option)

### No-API Path
- **Completely free** - export structured prompts as markdown or PDF
- **Use with any AI tool** you already have access to
- **Same strategic framework** and output quality
- **Professional formatting** for easy copy/paste

## Recent Updates (v1.3)

### 🔌 **Enhanced AI Provider Support**
- Added **Perplexity API** with Llama 3.1 Sonar model
- **Dynamic API key labels** that update based on selected provider
- **Smart placeholder text** showing correct key format (sk-ant-, pplx-, etc.)
- **Provider-specific help links** to get API keys

### 🎨 **UI/UX Improvements**
- **Fixed dark mode visibility** issues with better contrast
- **File deletion capability** with × buttons next to uploaded files
- **PDF export functionality** working on final results page
- **Better error messages** with actionable guidance

### 📄 **Export Enhancements**
- **PDF export for prompts** on the API key selection screen
- **Improved PDF formatting** with better typography and spacing
- **Professional layouts** optimized for printing and sharing
- **Popup handling** with graceful fallbacks

### 🧠 **Smart Features**
- **Brand archetype auto-detection** with links to educational resources
- **Cost estimation** that adapts to selected AI provider
- **Intelligent error handling** for common API issues
- **Session persistence** across browser restarts

## Philosophy

> *"You can't outsource conviction."*  
> — Kelsey LaBelle

**Sow What** is built on the belief that authentic brands come from founders who know what they stand for, not from generic positioning exercises. The tool helps technical founders:

- **Find their authentic voice** rather than adopting corporate speak
- **Identify their true differentiators** beyond feature comparisons  
- **Connect with believers** rather than trying to convince skeptics
- **Build conviction-driven brands** that attract the right customers
- **Access professional brand strategy** without expensive consultancy fees

The questions are designed to surface the founder's genuine beliefs, experiences, and worldview. The AI then helps articulate these insights into professional brand language that maintains the founder's authentic voice.

## Getting Started

### Quick Start (5 minutes)
1. **Download** `sow-what.html` (420KB single file)
2. **Open** in any modern web browser
3. **Choose your path**: 
   - **AI Generation**: Select provider, enter API key, generate outputs
   - **Prompt Export**: Skip API, export structured prompts for any AI tool
4. **Answer 21 questions** about your cybersecurity startup (auto-saves progress)
5. **Generate or export** your brand strategy
6. **Use the outputs** as foundation for marketing, design, and positioning

### For Best Results
- **Be specific** in your answers - generic responses yield generic outputs
- **Upload relevant files** (testimonials, blog posts, competitive analysis)
- **Use off-peak scheduling** for significant cost savings
- **Try different AI providers** to find your preferred output style
- **Refine outputs** using the built-in refinement system (2 per output)

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
**AI Providers**: Anthropic, OpenAI, Perplexity  

---

**The soil is prepared. The planting is still on you.**

*Ready to discover your authentic cybersecurity brand? Download Sow What and start digging.*
