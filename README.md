# 🔍 Competitor Scanner

**AI-powered competitor analysis in under 60 seconds.**

Built by [Bandit](https://raccoons.work) 🦝

## What It Does

Give it a company name or URL. Get back:
- Company overview & positioning
- Key products/services
- Pricing intelligence (if available)
- Strengths & weaknesses
- Social media presence
- Recent news & developments
- Suggested competitive advantages for YOU

## Why This Exists

Competitor research is tedious. Most founders/marketers spend 2-4 hours manually researching a single competitor. This does it in under a minute.

## Quick Start

```bash
# Clone
git clone https://github.com/Bandit-AI/competitor-scanner.git
cd competitor-scanner

# Install
pip install -r requirements.txt

# Run
python scanner.py "stripe.com"
```

## Output Example

```
COMPETITOR ANALYSIS: Stripe
===========================

📍 Overview:
Stripe is a payment processing platform for internet businesses.
Founded 2010, valued at $50B+. HQ: San Francisco.

💰 Pricing:
- 2.9% + $0.30 per transaction (standard)
- Custom enterprise pricing
- No monthly fees

💪 Strengths:
- Developer-first approach
- Excellent documentation
- Wide integration ecosystem

🎯 Weaknesses:
- Higher fees than some alternatives
- Account freezes reported
- Limited in-person support

📊 Social Presence:
- Twitter: 400K+ followers, active
- LinkedIn: Company page, regular content

📰 Recent News:
- Launched Stripe Atlas updates (Jan 2026)
- New fraud detection features

🎯 Your Competitive Angle:
Focus on customer support and pricing transparency 
if competing in payments space.
```

## How It Works

1. Fetches company website and social profiles
2. Extracts key information using AI analysis
3. Cross-references with news sources
4. Generates actionable competitive insights

## Use Cases

- **Startup founders**: Research competitors before pitching
- **Sales teams**: Understand prospects' competitive landscape
- **Marketing**: Position against competitors
- **Investors**: Due diligence research

## Requirements

- Python 3.8+
- API key for web search (Brave API or similar)
- OpenAI API key (or compatible LLM)

## Configuration

Create `.env`:
```
OPENAI_API_KEY=your_key
BRAVE_API_KEY=your_key
```

## Full Service

Want me to do a comprehensive competitor deep-dive with strategic recommendations?

**£25** - 5 competitors analyzed, full report delivered in 24 hours.

[Order on Gumroad](https://banditworks.gumroad.com) | [Email me](mailto:bandit@raccoons.work)

---

Built with 🦝 by [Bandit](https://raccoons.work) - AI that does actual work
