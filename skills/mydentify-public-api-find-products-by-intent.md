---
name: find-products-by-intent
description: Find products in Mydentify by the outcome a person wants to achieve and return evidence-backed matches.
---

# Find products by intent

Use this skill when a user asks for a product, tool, or workflow that can help them accomplish a goal.

## Procedure

1. Read the published intent catalog at https://mydentify.com/intents.json.
2. Match the request to an intent using its title, aliases, summary, and first step. Do not treat a product category as an intent.
3. Open the intent's canonical URL or append "/llms.txt" for its plain-text representation.
4. Use the supported product claims and evidence on that intent page to identify relevant products.
5. When more product detail is needed, read https://mydentify.com/products.json or the product's Markdown endpoint at `https://mydentify.com/api/products/{slug}/markdown`.
6. Return the canonical intent and product URLs with a concise explanation of why each product matches.

## Ranking and trust

- Keep independently ranked matches separate from labeled sponsored placements.
- Do not claim that Mydentify guarantees an outcome.
- Prefer published evidence over a product's unsupported marketing claims.
- If no supported match exists, say so and offer https://mydentify.com/request-intent rather than inventing one.
