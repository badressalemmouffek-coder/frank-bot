# 🤖 frank-bot - Ask Your Docs, Get Clear Answers

[![Download frank-bot](https://img.shields.io/badge/Download-frank--bot-blue?style=for-the-badge)](https://github.com/badressalemmouffek-coder/frank-bot)

## 🚀 What frank-bot does

frank-bot is a desktop-style AI assistant for business use. It helps you ask questions about your files, policies, notes, and other company documents.

It uses your documents as the source of truth, so you can get answers that match your own content. It is built with ChromaDB and Claude, which helps it search text and reply in plain language.

Use frank-bot to:

- Ask questions about company documents
- Find facts in long files without manual searching
- Help HR teams answer common staff questions
- Build a private knowledge base for your business
- Keep answers tied to your own documents

## 📥 Download frank-bot

Visit this page to download and run the app:

[https://github.com/badressalemmouffek-coder/frank-bot](https://github.com/badressalemmouffek-coder/frank-bot)

## 🪟 Windows setup

Follow these steps on Windows:

1. Open the download link above in your browser.
2. Download the latest release or app file from the repository page.
3. If the file comes in a ZIP folder, right-click it and choose **Extract All**.
4. Open the extracted folder.
5. Find the app file and double-click it to run.
6. If Windows asks for permission, choose **Run anyway** if you trust the source.
7. Wait for Frank Bot to start.

If the app opens in a browser window or a local web page, keep that window open while you use it.

## 🧭 First-time setup

When you open frank-bot for the first time, you may need to set up a few things:

- Add your Claude API key
- Choose the folder with your documents
- Let the app build its search index
- Wait for the first scan to finish

If you do not have an API key yet, create one from your Anthropic account before you start. Keep it private and paste it into the app when asked.

## 📚 How to add your documents

frank-bot works best when you give it clear, text-based files.

Good file types include:

- PDF
- DOCX
- TXT
- Markdown files
- Internal notes
- Policy docs
- Employee handbooks
- Help center articles

To add documents:

1. Open frank-bot.
2. Choose the folder or files you want to use.
3. Start the import or scan step.
4. Wait until the documents finish processing.
5. Ask a question about the content.

For best results, use files with clean text and simple headings.

## 💬 How to ask questions

Type a question in normal language, just like you would ask a coworker.

Examples:

- What is our leave policy?
- How do I request access to the sales folder?
- What does the employee handbook say about remote work?
- Which document explains our onboarding steps?
- What is the refund policy for enterprise plans?

Ask one clear question at a time. If you want a better answer, include the document name or topic in your question.

## 🧠 How frank-bot works

frank-bot follows a simple flow:

1. It reads your uploaded documents.
2. It stores the text in ChromaDB.
3. It looks for the most relevant passages when you ask a question.
4. It sends those passages to Claude.
5. Claude writes a response based on your content.

This setup helps the app give answers that stay close to your source files.

## 🔍 Best use cases

frank-bot fits teams that need fast answers from internal documents.

Common use cases:

- HR policy Q&A
- Employee onboarding help
- IT support docs
- Sales playbook lookup
- Operations manual search
- Client service knowledge base
- Private business document search

If your team keeps answers in scattered files, frank-bot gives you one place to ask for them.

## 🖥️ System needs

For smooth use on Windows, use a recent computer with:

- Windows 10 or Windows 11
- 8 GB RAM or more
- A stable internet connection
- Enough space for your documents and search index
- Access to the Claude API

For large document sets, a faster machine will handle indexing and search better.

## 🛠️ Common tasks

### Add new documents

When your files change, add the new versions to frank-bot and re-scan them. This keeps answers current.

### Remove old content

Delete outdated files from the source folder, then rebuild the index so Frank stops using old text.

### Improve answer quality

To get cleaner answers:

- Use clear file names
- Keep documents well organized
- Avoid scanned images with no text
- Split very large files into smaller topics
- Write questions with enough detail

## 🔐 Privacy and control

frank-bot is self-hosted, so you keep control of your documents on your own setup.

That makes it a good fit for teams that want:

- Local document control
- Private internal search
- A simple setup for staff
- Fewer manual support questions

Your document content stays tied to your own environment and API setup.

## 🧩 Topics covered

This project relates to:

- anthropic
- document-qa
- enterprise-ai
- flask
- hr-automation
- llm
- python
- rag
- self-hosted

## ❓ Troubleshooting

### The app does not open

- Check that the file finished downloading
- Make sure you extracted the ZIP folder first
- Try running the app again as an administrator
- Check that your antivirus did not block the file

### Frank cannot answer questions

- Confirm your Claude API key is correct
- Make sure your documents finished indexing
- Check that the files contain readable text
- Try asking a shorter question

### The answers look weak

- Use clearer source documents
- Add headings to long files
- Remove duplicate or outdated files
- Ask more direct questions

### Document import is slow

- Start with a smaller folder
- Use fewer large files at once
- Close other heavy apps on your computer
- Make sure your internet connection is stable

## 📝 Suggested folder setup

A simple folder structure can help:

- HR
  - Benefits
  - Leave Policy
  - Onboarding
- IT
  - Access Requests
  - Device Setup
- Sales
  - Pricing
  - Objections
- Operations
  - SOPs
  - Vendor Rules

This makes it easier for Frank Bot to find the right text.

## 📌 File tips

Use documents that are:

- Easy to read
- Based on facts
- Up to date
- Clearly named
- Focused on one topic

Avoid files that are:

- Full of images with no text
- Mixed with unrelated topics
- Very old or duplicate copies
- Hard to read because of scans

## 🔗 Project link

Primary download and project page:

[https://github.com/badressalemmouffek-coder/frank-bot](https://github.com/badressalemmouffek-coder/frank-bot)

## 📄 License

Check the repository page for license details before use in your team or business setup