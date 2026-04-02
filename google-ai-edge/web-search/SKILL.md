---
name: web-search
description: A skill to search the web for information, news, images, and answers to questions. Perfect for finding current events, product reviews, tutorials, and any factual information.
---

# Web Search

## Instructions

You MUST use the `run_js` tool with the following exact parameters:

- **data**: A JSON string with the following fields:
  - **query**: String, Required. The search query to look up on the web (e.g., "latest AI news", "how to cook pasta", "weather in Sao Paulo").
  - **type**: String, Optional. The type of search: "web" (default), "news", or "image".

The tool will return search results with titles, URLs, and snippets.
