# Ahmed Reyad — Portfolio & Writing

A Next.js site: portfolio sections (experience, projects, skills, contact) plus a blog
powered by plain Markdown files. No database, no admin login — publishing is just a
Git commit.

## Publish a new article

1. Open the repo on GitHub.
2. Go to `content/posts/`.
3. Click **Add file → Create new file**, name it e.g. `my-article.md`.
4. Paste this at the top, then write the article underneath in Markdown:

   ```
   ---
   title: "Article Title"
   date: "2026-09-12"
   summary: "One or two sentence summary shown in the list."
   tags: ["SOC", "DFIR"]
   ---

   Article content starts here.
   ```

5. Commit to `main`. Vercel rebuilds and republishes automatically — usually live
   within a minute or two.

To edit or remove a post, edit or delete its `.md` file the same way.

## Local development (optional)

```
npm install
npm run dev
```

## Deploy

This project auto-deploys on every push once the GitHub repo is linked to Vercel
(Vercel → Add New Project → import this repo).
