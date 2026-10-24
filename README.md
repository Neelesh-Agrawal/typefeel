# Typefeel — Ship69 Day 64

Interactive typography playground with AI analysis. Pick a font, type anything, manipulate size, weight, tracking, leading, skew, and opacity in real time. Hit "Analyse feel" to get a mood breakdown, use cases, font pairings, and what to avoid.

## Features
- 16 Google Fonts across serif, display, sans, and handwritten styles
- 6 type controls: size, weight, letter spacing, line height, skew, opacity
- 5 presets: Display, Editorial, Minimal, Loud, Elegant
- 4 backgrounds: Dark, Light, Black, Cream
- 12 colour swatches
- AI analysis via Groq: mood, tags, best use cases, font pairings, avoid

## Stack
- Vanilla HTML/CSS/JS
- Vercel serverless function
- Groq API (openai/gpt-oss-120b)
- Google Fonts

## Deploy to Vercel
1. Push to GitHub
2. Import in Vercel
3. Add env variable: `GROQ_API_KEY`
4. Deploy

## Project structure
```
typefeel/
├── index.html
├── api/
│   └── typefeel.js
├── vercel.json
├── .gitignore
└── README.md
```
