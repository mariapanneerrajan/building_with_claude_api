# Building with Claude API

Accompanying code for the **"Building with Claude API"** series on YouTube.

📺 **YouTube playlist:** [Building with Claude API](https://youtube.com/playlist?list=PLq7RUKeig7yaCJ8pTVmNuODFffUmu2tBH&si=0GbYePJcUgLyWuTC)

This content is heavily based on Anthropic Academy's official course:
🎓 **[Claude with the Anthropic API](https://anthropic.skilljar.com/claude-with-the-anthropic-api)**

These notebooks walk through the fundamentals of building applications with the Anthropic Python SDK, one concept at a time.

## Notebooks

| Notebook | Topic |
|----------|-------|
| [01.ipynb](01.ipynb) | First API call, the `Message` object, multi-turn conversations, and tracking token cost |
| [02.ipynb](02.ipynb) | System prompts — steering Claude's role and behavior |
| [03.ipynb](03.ipynb) | Conversation state and the `temperature` parameter |
| [04.ipynb](04.ipynb) | Streaming responses |
| [05.ipynb](05.ipynb) | Controlling output — response prefilling, stop sequences, and JSON output |
| [06_.ipynb](06_.ipynb) | Structured data extraction with reusable helper functions |

## Getting started

1. **Install dependencies**

   ```bash
   pip install anthropic python-dotenv
   ```

2. **Set your API key.** Create a `.env` file in the project root:

   ```
   ANTHROPIC_API_KEY=your_key_here
   ```

   > The `.env` file is git-ignored and is **never** committed. Get a key from the [Anthropic Console](https://console.anthropic.com/).

3. **Open the notebooks** in Jupyter / VS Code and run the cells in order.

## Disclaimer

This is independent, educational content created to accompany the YouTube series. It is not affiliated with or endorsed by Anthropic. Please refer to the [official course](https://anthropic.skilljar.com/claude-with-the-anthropic-api) and [Anthropic documentation](https://docs.anthropic.com/) for authoritative material.
