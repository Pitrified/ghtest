---
title: Github pages test deploy
---

# Deploy

This file is in the `ghpages` folder in the `main` branch.

To update the site, the modifications must be pushed on the `gh-pages` branch:

```bash
git subtree push --prefix ghpages origin gh-pages
```

Thanks to [this](https://gist.github.com/cobyism/4730490) gist.

# Markdown mini cheat-sheet

Markdown is a lightweight and easy-to-use syntax for styling your writing.
It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see
[GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles
from the Jekyll theme you have selected in your
[repository settings](https://github.com/Pitrified/packaging-example/settings).
The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages?
Check out our
[documentation](https://docs.github.com/categories/github-pages-basics/)
or
[contact support](https://support.github.com/contact)
and we’ll help you sort it out.
