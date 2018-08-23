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

### Docs

Docs are [collections](https://jekyllrb.com/docs/collections/) of pages stored under `_docs` folder. To create a new page:

**1.** Create a new Markdown as `_docs/my-page.md` and write [front matter](https://jekyllrb.com/docs/frontmatter/) & content such as:

```
---
title: My Page
permalink: /docs/my-page/
---

Hello World!
```

**2.** Add the pagename to `_data/docs.yml` file in order to list in docs navigation panel:

```
- title: My Group Title
  docs:
  - my-page
```

### Blog posts

Add a new Markdown file such as `2017-05-09-my-post.md` and write the content similar to other post examples.

### Pages

The homepage is located under `index.html` file. You can change the content or design completely different welcome page for your taste. (You can use [bootstrap components](http://getbootstrap.com/components/))

In order to add a new page, create a new `.html` or `.md` (markdown) file under root directory and link it in `_includes/topnav.html`.
