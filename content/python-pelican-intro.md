Title: Introduction to Python & Pelican - A Static Site Generator
Date: 2025-02-03
Category: Python
Slug: python-pelican-intro
Authors: Sachin Arora
Summary: Learn what Pelican is, why it's useful, and how it leverages Python to generate static sites.

## 🚀 What is Pelican?
Pelican is a static site generator written in **Python**. Unlike WordPress or Django, Pelican generates HTML pages **before deployment**, making sites blazing fast. 

### ✅ **Why Use Pelican?**
1. **Speed**: Since it's static, there’s no backend latency.
2. **Security**: No database means fewer vulnerabilities.
3. **Markdown Support**: Write posts using simple Markdown.
4. **Hosted on GitHub Pages**: Free & easy deployment.

### 📌 **How Pelican Works**
Pelican takes your **Markdown files (`.md`)** and converts them into HTML pages using Jinja2 templates.

```sh
pelican content
