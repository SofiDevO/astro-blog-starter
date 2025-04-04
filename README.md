
# Astro Blog Starter 🌟

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Astro](https://img.shields.io/badge/Astro-5.5.5-FF5D01.svg?logo=astro)](https://astro.build)


## Key Components 🔑

### Atomic Design Implementation
- **Atoms**:
  `ToggleTheme.astro` (+ CSS) | `HamburgerButton.astro` | `FormattedDate.astro`
- **Molecules**:
  `Blogcards.astro` (Post grids)
- **Organisms**:
  `Header.astro` (Responsive nav with dropdowns)

### Content Management
```astro
// Example blog post (content/blog/post.md)
---
title: "My First Post"
date: 2024-01-01
---

Article content...
```







## Core Structure 🌐

```
src/
├── components/
│   ├── atoms/
│   │   ├── CardBlog/           # Blog post cards
│   │   ├── HamburgerButton/    # Mobile menu toggle
│   │   ├── Icons/              # Iconify wrapper
│   │   ├── ToggleTheme/        # Dark/light switcher (+ CSS)
│   │   └── utilsComponents/    # Date formatter
│   ├── molecules/
│   │   └── Blogcards/          # Blog post grid system
│   └── organisms/
│       ┗── Header/             # Navigation with dropdowns
├── content/
│   ├── blog/                   # Markdown posts
│   └── config.ts               # Content collection config
├── data/
│   └── menuElements.js         # Navigation items
├── layouts/
│   ├── Layout.astro            # Default layout
│   └── LayoutBlogPost.astro    # Article template
├── pages/
│   ├── blog/
│   │   ├── [...slug].astro     # Dynamic blog routes
│   │   └── index.astro         # Blog archive
│   └── index.astro             # Homepage
└── styles/
    └── global.css              # Base styles
```


## Support Development ☕
[![GitHub Sponsors](https://img.shields.io/badge/Sponsor-%E2%9D%A4%EF%B8%8F-ea4aaa?logo=githubsponsors)](https://github.com/sponsors/SofiDevO?o=esb)
[![Ko-fi](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ff5e5b?logo=kofi)](https://ko-fi.com/sofidev)

---

**MIT Licensed** | Optimized for Astro v5+ | [Full Documentation](https://github.com/SofiDevO/astro-blog-starter)
