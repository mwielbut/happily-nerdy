# Happily Nerdy

My minimal personal blog built with [Hugo](https://gohugo.io/).

## Quick Start

```bash
# Start development server
hugo server

# Build for production
hugo
```

## Adding Content

Create a new project post:

```bash
hugo new projects/my-project.md
```

Then edit the file and set the front matter:

```yaml
---
title: 'My Project'
date: 2024-01-15
draft: false
category: 'Project'
---

Your content here...
```

## Project Structure

```
├── hugo.toml                    # Site configuration
├── content/projects/            # Blog posts
├── themes/happily-nerdy/
│   ├── assets/css/style.css     # Styling
│   └── layouts/                 # Templates
```

## Configuration

Edit `hugo.toml` to update:

- `baseURL` - Your production URL
- `params.author` - Your name
- `params.bio` - About text
- `params.github` - GitHub username
- `params.linkedin` - LinkedIn username

## Deployment

Deployment happens automatically via Github actions in Github pages.
https://gohugo.io/host-and-deploy/host-on-github-pages/
