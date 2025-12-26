# AI-powered-brochure-generator-that-scrapes-and-navigates-company-websites-intelligently

This project is a simple business-oriented solution that automatically creates a company brochure from a public website.

Given a company name and its primary website, the system:

Scrapes the landing page and all internal links

Uses an LLM to decide which pages are relevant for a brochure

Fetches and cleans the content from those pages

Generates a short, readable brochure in markdown

Instead of relying on fixed rules, the model is used to understand which links and content matter, such as company background, culture, customers, and careers. This makes the approach work across many different websites with minimal changes.

The project also demonstrates:

One-shot prompting with structured JSON outputs

Prompt design for business writing

Streaming responses for a better user experience

A clean separation between scraping logic and LLM reasoning

This is intended as a practical example of how LLMs can be applied to real business problems like marketing content creation, investor materials, and recruitment summaries.
