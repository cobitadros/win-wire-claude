# Win Wire Generator
### Powered by Claude API

A browser-based tool that transforms raw Salesforce deal payloads (JSON) into formatted, slide-style win wire assets using the Anthropic Claude API.

---

## What it does

- Accepts a JSON payload containing opportunity and account data
- Sends it to Claude (`claude-sonnet-4-20250514`) with a structured prompt engineering approach
- Returns a clean, branded win wire slide with key metrics, outcomes, competitive displacement, and customer quotes

## Why I built it

I architected a production version of this pipeline in my current role. This is a rebuild of the core intelligence layer using the Claude API directly — stripping away the orchestration to demonstrate the underlying architecture pattern.

## To run

Download `win_wire_generator.html`, open in any browser, enter your Anthropic API key, paste a deal payload, generate.
