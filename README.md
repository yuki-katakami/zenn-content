# zenn-content

Articles published on [Zenn](https://zenn.dev/yuki-katakami) — managed via the
[Zenn CLI](https://zenn.dev/zenn/articles/zenn-cli-guide) and synchronised
automatically through GitHub integration.

## Local development

```bash
# Install dependencies (Zenn CLI)
npm install

# Preview articles locally
npx zenn preview

# Create a new article
npx zenn new:article

# List existing articles
npx zenn list:articles
```

## Publishing flow

1. Write or edit articles under `articles/`.
2. Set `published: true` in the front-matter when ready.
3. Commit and push to `main`.
4. Zenn automatically detects the change and publishes / updates the article.

## Topics

I write mostly about:

- AI workflow engineering with Claude Code
- Operations & automation
- Self-tracking and time management as a knowledge worker
