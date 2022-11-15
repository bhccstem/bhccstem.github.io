## Features overview

- Sass/Coffeescript support using Jekyll 2.0
- All the SEO goodies come built-in
- Markdown blogging
- Supports [Pullquotes](https://reverie-jekyll.netlify.app/pullquotes/)
- Syntax highlighting using Pygments
    - [Dracula syntax theme](https://draculatheme.com/) included
- Disqus commenting
- Google Analytics integration
- Supports [Google Analytics 4](https://support.google.com/analytics/answer/10089681?hl=en)
- Fuzzy search across blog posts
- Blog with pagination
- Categorize posts out-of-the box
- Built-in sitemap

## Using Reverie on GitHub Pages

### 3. Publish your first blog post

Delete all files from `_posts`directory and create a new file called `/_posts/2019-2-13-Hello-World.md` to publish your first blog post. That's all you need to do to publish your first blog post! This [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) might come in handy while writing the posts.

> You can add additional posts in the browser on GitHub.com too! Just hit the <kbd>Create new file</kbd> button in `/_posts/` to create new content. Just make sure to include the [front-matter](http://jekyllrb.com/docs/frontmatter/) block at the top of each new blog post and make sure the post's filename is in this format: year-month-day-title.md

## Using Categories in Reverie

You can categorize your content based on `categories` in Reverie. For this, you just need to add `categories` in front matter like below:

For adding single category:

```md
categories: JavaScript
```

For adding multiple categories:

```md
categories: [PHP, Laravel]
```

The categorized content can be shown over this URL: <https://yourgithubusername.github.io/categories/>

## Pagination

Pagination of posts in Reverie works out-of-the-box. You only need to specify the number of posts you want on a single page in `_config.yml` and Reverie will take care of the rest.

```yml
paginate: 6
```

## Sitemap

The generated sitemap of your blog can be found at <https://yourgithubusername.github.io/sitemap.xml>. You can see the example sitemap feed over [here](https://reverie-jekyll.netlify.app/sitemap.xml).
