# Introduction

Welcome to the Dictionary Tool, an elegant JavaScript library built to enhance reading experiences on the web. With this tool, words from a defined dictionary get dynamically highlighted in your content. And what's more, readers can simply hover or tap on these highlighted words to view their definitions through a friendly tooltip.

By seamlessly integrating a dictionary into your content, we aim to enrich comprehension, deepen engagement, and provide readers with a more immersive reading environment. Whether it's a technical article, an educational portal, or a literary blog, the Dictionary Tool makes understanding complex or unfamiliar terms just a hover away.

## Features:

- **Dynamic Highlighting:** Words defined in the dictionary are automatically highlighted.
- **Instant Tooltips:** Definitions appear in a tooltip when a user hovers over or taps a highlighted word.
- **Smart Processing:** Avoids highlighting words within links and ensures only full word matches.
- **Optimized Performance:** Debounced event listeners ensure smooth performance even on dense pages.
- **Easy Integration:** Use with your existing web content and fetch dictionary entries from an API endpoint.

## How to Use:

1. Ensure the required class names in your content match the constants defined in the script (`CONTAINER_CLASS_NAME` for content container, etc.).
2. Source the script on your webpage.
3. Host your dictionary as a JSON file accessible via an API endpoint, ensuring the word and definition keys match the constants (`WORD_KEY` and `DEFINITION_KEY`).
4. The tool automatically fetches and processes the dictionary on document load. No additional setup is required.
