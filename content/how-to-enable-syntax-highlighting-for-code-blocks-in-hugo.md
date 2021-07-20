---
title: "How to Enable Syntax Highlighting for Code Blocks in Hugo"
date: 2021-07-20T13:32:00-05:00
draft: false
---

Code blocks were highlighted when I was developing locally with `hugo server`, but when I would deploy the built site, the syntax highlighting was gone.

To fix it, add these two lines to your `config.toml`:

```toml
pygmentsCodeFences = true
pygmentsUseClasses = false
```
