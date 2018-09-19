---
title: Welcome
permalink: /docs/home/
redirect_from: /docs/index.html
---

## Getting started

Postprints is a [Git](https://git-scm.com/) repository hosted on [GitHub](https://github.com/) containing metadata of published articles with links to source code and other material. 
We use [GitHub Pages](https://pages.github.com) to automatically generate and serve the website.
The site is compiled using [Jekyll](https://jekyllrb.com/), which you can run locally in your own computer. 


1. Clone the [repository](https://github.com/crlsierra/postscripts) into your local computer using `git clone https://github.com/crlsierra/postscripts.git`.
2. Go to the new folder `cd postscripts`
3. Run `bundle exec jekyll serve`
4. Open your web browser and go to the server address indicated by Jekyll.


## Writing content

### Postprints of published articles

Metadata about published artciles are stored under `_pubs` folder. To create a new page:

**1.** Create a new Markdown as `_pubs/my-article.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```yaml
---
title: Paper title
doi: 1015/00112233
author:
  - First and Last Name of First Author
  - First and Last Name of Coauthor
  - First and Last Name of Coauthor
contact: Contact Author
email: Email of Contact Author
journal: Journal Name
volume: xx
pages: yy-zz
puburl: URL of publisher where the paper is hosted
repository: URL of git repository cotaining all other article files, including a final pre-print of the paper
preprint: Link to the paper relative to the URL of the repository
abstract: "Complete paper abstract"
permalink: /docs/my-page/
---
```

Once your done send a pull request.

