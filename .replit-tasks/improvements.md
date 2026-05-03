# my-crawl4ai-project — Replit Import Notes

## What This Is
Go client for the Crawl4AI Cloud SDK — crawls URLs and returns clean markdown.

## Setup
```bash
export CRAWL4AI_API_KEY=your-key-here
go mod tidy
go run main.go
```

## Current State
- SDK: `crawl4ai-cloud-sdk/go v0.5.0`
- `main.go` created 2026-05-02 — demonstrates basic Crawl + markdown extraction

## Improvements Roadmap
- [ ] Add batch crawling (multiple URLs concurrently)
- [ ] Add structured extraction example (LLM-based schema extraction)
- [ ] Add CLI flags for URL, output format, timeout
- [ ] Check for SDK updates: github.com/unclecode/crawl4ai-cloud-sdk
