---
tags: [markdown, frontmatter, blogging, yaml]
---

# Frontmatter Basics

Frontmatter is YAML metadata at the top of markdown files. It's wrapped in triple dashes and lets you add structured data to your content.

```yaml
---
title: My Post
tags: [web, javascript]
draft: false
---

# Your content starts here
```

## Common uses:
- **Tags** - organize content by topic
- **Drafts** - hide work-in-progress posts
- **Metadata** - titles, dates, descriptions

## This file's frontmatter:
```yaml
---
tags: [markdown, frontmatter, blogging, yaml]
---
```

Yep, using frontmatter to explain frontmatter.

Modern frameworks support it natively: Astro has built-in frontmatter with type-safe content collections, Next.js uses it with MDX (via `next-mdx-remote`), and Remix handles it for content routing. The `gray-matter` library handles parsing in Node.js. Simple concept, very useful for content management.
