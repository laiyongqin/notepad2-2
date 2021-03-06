# Notepad2
This is a simple [Jekyll](https://jekyllrb.com/) theme for a team blog, with search and multiple authors, intended to be hosted on [Github Pages](https://pages.github.com/) without Jekyll plugins.

This repo can be viewed at http://capgemini.github.io/notepad2/

Forked from [Notepad by Hossain Mohd. Faysal](https://github.com/hmfaysal/Notepad), incorporating improvements made by the [Capgemini engineering team for their blog](http://capgemini.github.io/).

## Features
 * Category and tag index
 * Multiple authors
 * Search
 * Separate category feeds
 * Responsive videos
 * Print stylesheet shows all links as footnotes using [jquery-footnote-links](https://github.com/dompuiu/jquery-footnote-links)

## Development

### JavaScript
Javascript files are concatenated to reduce HTTP requests. To include a script, edit assets/js/scripts.js

### Feeds
By default there is an RSS feed at feed.xml. To create category-separated feeds, copy feed.category.xml to a new file, and change the category assignment to your own preference.
