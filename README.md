# 📖 Dynamic Dictionary Tooltips

This script is a powerful tool that empowers web content. Imagine having any piece of text enriched with definitions in real-time, without needing a separate glossary. That's what this tool achieves. It finds words defined in a given dictionary, highlights them, and then serves the definition right there in the text when hovered over or pressed.

## Features:

- **Dynamic Highlighting:** Words defined in the dictionary are automatically highlighted.
- **Instant Tooltips:** Definitions appear in a tooltip when a user hovers over or taps a highlighted word.
- **Smart Processing:** Avoids highlighting words within links and ensures only full word matches.
- **Optimized Performance:** Debounced event listeners ensure smooth performance even on dense pages.
- **Easy Integration:** Use with your existing web content and fetch dictionary entries from an API endpoint.

## How to use:

1. Source the script on your webpage.
2. Ensure the required class names in your content match the constants defined in the script (`CONTAINER_CLASS_NAME` for content container, etc.).
3. Host your dictionary as a JSON file accessible via an API endpoint, ensuring the word and definition keys match the constants (`WORD_KEY` and `DEFINITION_KEY`).
4. The tool automatically fetches and processes the dictionary on document load. No additional setup is required.

## How it works:
The script highlights words defined in a dictionary and shows their definitions in a tooltip when hovered or pressed. Works on both mobile and desktop.

![tooltips](https://github.com/axelferdinand/Dynamic-Dictionary-Tooltips/assets/10460870/986f8d2b-6653-431c-95b5-822573f9c1f8)

## Demo:

Here is a working demo: [https://codepen.io/prototypen/pen/PoXwWNe](https://codepen.io/prototypen/pen/PoXwWNe)
