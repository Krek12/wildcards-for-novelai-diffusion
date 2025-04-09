# Wildcards for NovelAI Diffusion 4.0

> **Turn `__hair__` into `||short bob\|long waves\|straight bangs||` automatically—before your prompt ever reaches NovelAI.**

A lightweight, privacy‑friendly Chrome extension that intercepts **`POST https://image.novelai.net/ai/generate-image`** and expands any `__wildcard__` tokens inside the request body using text files you upload.  
Works like a1111 webui's wildcards extension, and the wildcards txt files for a1111 webui can be used, untouched.

---

## ✨ Features
| | |
|---|---|
| **Wildcard replacement** | Detects `__name__` tokens anywhere in the JSON payload (including Character prompts). |
| **Upload your wildcards txt files** | Upload unlimited `.txt` files; each line becomes a choice. |
| **Prompt replacement** | Converts lines to NovelAI’s OR syntax: `||item1\|item2\|…||`. |
| **Zero external calls** | All data lives in Chrome Storage; nothing ever leaves your browser. |

---

## 🖼️ Screenshot
