# 🐾 Devlynx

Devlynx is an AI‑powered code review and developer workflow assistant built with **Bun**, **Prisma**, and **Inngest**. It automates pull request analysis, generates structured reviews, and integrates seamlessly with GitHub.

---

## 🚀 Features
- Automated PR review generation using AI (Gemini via `ai-sdk`).
- Context retrieval from your codebase for smarter reviews.
- Persistent storage of reviews with Prisma ORM.
- Event‑driven workflows powered by Inngest.
- Modern developer experience with Bun runtime.

---

## 📸 Screenshots

### Inngest Server
![Inngest](https://github.com/kylanalicia/devlynx/blob/3727ce4b3bd8dfb8ef847948759dcfe785f13d24/Screenshot%20from%202025-12-22%2019-11-50.png)

### Website Preview
![Website Webcam](https://github.com/user-attachments/assets/3e16dc6f-e8e6-4dd9-9fec-dba4591ff6a8)

---

## 🛠️ Getting Started

Clone the repository:

``` bash
git clone https://github.com/kylanalicia/devlynx.git
cd devlynx
```

# 📦 Install dependencies
```
bun install
```

# ⚡ Run the Inngest server
```
bun run inngest dev
```

# 🌐 Expose local server with ngrok
```
ngrok http 3000
```

# 🗄️ Open Prisma Studio
```
bunx prisma studio
```

# 💻 Run the website locally
```
bun run dev
```

## 📂 Project Structure
app/api/ → Next.js  App Router API endpoints

inngest/functions/ → Event‑driven workflows

module/github/ → GitHub integration helpers

module/ai/ → AI context + review generation

prisma/schema.prisma → Database schema

## 🌐 Tech Stack
Runtime: Bun

Database: Prisma

Events: Inngest

AI: Gemini via ai-sdk

Frontend: Next.js  (App Router)

## 📖 Description
Devlynx automates the code review process by combining AI‑powered analysis with event‑driven workflows. It listens for pull request events, retrieves context, generates reviews, and posts them back to GitHub — saving developers time and ensuring consistent, constructive feedback.

## 🤝 Contributing
Pull requests are welcome! Please open an issue first to discuss major changes.

## 📜 License
MIT © 2025 Alicia Kimani
