﻿# Wildcards for NovelAI Diffusion 4.0

> **Turn `__hair__` into `||short bob\|long waves\|straight bangs||` automatically—before your prompt ever reaches NovelAI.**

A lightweight, privacy‑friendly Chrome extension that intercepts **`POST https://image.novelai.net/ai/generate-image`** and expands any `__wildcard__` tokens inside the request body using text files you upload.  
Works like a1111 webui's wildcards extension, and the wildcards txt files for a1111 webui can be used, untouched.

---

## ✨ Features
| | |
|---|---|
| **Wildcard replacement** | Detects `__name__` tokens anywhere in the JSON payload (including Character prompts). |
| **Set your wildcards txt files** | Upload `.txt` wildcards. Files are not sent anywhere, just stored in local storage. Files can be added and deleted at extension menu.|
| **Prompt replacement** | Converts lines to NovelAI’s original dynamic prompting syntax. |
| **Zero external calls** | All data lives in Chrome Storage; nothing ever leaves your browser. |

---

## 🖼️ Screenshot
![ss](https://github.com/user-attachments/assets/3f67ae5c-43e3-48d0-b446-acb3781757c1)
![ss2](https://github.com/user-attachments/assets/763a5d89-c578-47aa-a617-be212cca022a)
