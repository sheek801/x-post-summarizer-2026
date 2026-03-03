# x-post-summarizer-2026

This repository summarizes a public figure's 2026 X posts using AI.

## Account Analyzed
- Handle: @llm_wizard

## Project Overview
This project was built using a LangGraph agent with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## How to Replicate
1. Set up your X API Bearer Token as an environment variable:

```bash
export X_BEARER_TOKEN="your_bearer_token_here"
```

2. Install Python dependencies:

```bash
pip install requests
```

3. Run the search script to fetch recent posts:

```bash
python x_search.py <twitter_handle>
```

Replace `<twitter_handle>` with the desired X account handle.

The script will save the results to `posts.json`.

---

AI-generated summary and metadata files are included in this repository for reference.
