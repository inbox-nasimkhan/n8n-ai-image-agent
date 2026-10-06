# n8n AI Image Agent (Archived Portfolio)

**Status:** 🗂️ This project is **archived** — no longer active on n8n.

## What It Does

A **no-code automation workflow** that searches images from Unsplash API:

- **Input:** Keyword via webhook (`?q=coffee`)
- **Processing:** HTTP request to Unsplash Search API
- **Output:** JSON with 3 image URLs
- **Speed:** ~300ms per request

## How It Works
## Example

**Request:**
**Response:**
```json
{
  "images": [
    "https://images.unsplash.com/photo-...",
    "https://images.unsplash.com/photo-...",
    "https://images.unsplash.com/photo-..."
  ]
}
