# AdVantage Gen - AI Ad Creative Generator

Automated Social Media Campaign Studio that generates complete ad campaigns (images + copy) from a single prompt.

## Features

- **Multi-Modal Generation**: Parallel image and text generation for minimal latency
- **Template Overlay & Compositing**: Automatic logo and CTA button overlay
- **Brand Voice Tuning**: Generate copy in multiple tones (Witty, Professional, Urgent, Inspirational)

## Project Structure

```
├── server/          # Express backend
├── client/          # React frontend
└── README.md
```

## Setup

1. Install dependencies:
```bash
npm run install-all
```

2. Set up environment variables:
- Copy `server/env.example` to `server/.env`
- Add your API keys (Hugging Face, Gemini)

3. Run development servers:
```bash
npm run dev
```

## Development Roadmap

- **Week 1**: Image Generation Engine (Hugging Face API integration)
- **Week 2**: Copywriting & Branding (LLM integration, Sharp compositing)
- **Week 3**: Studio UI & Editor (React frontend with Fabric.js)
- **Week 4**: Scaling & History (MongoDB/Cloudinary, Remix feature)

