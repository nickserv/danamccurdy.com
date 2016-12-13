# [Dana McCurdy's Website](http://danamccurdy.com)

Site content and poems: &copy; 2016 [Dana McCurdy](http://danamccurdy.com/)

Other source code: &copy; 2016 [Nick McCurdy](http://nickmccurdy.com/)

## Authoring
This site's content is stored in Markdown syntax, edited in Prose, and generated into a full site with Jekyll.

### Using Prose
Before you author any content, you should log in to [Prose](http://prose.io/) (using your GitHub account) and visit [this project](http://prose.io/#danamcc/danamcc.github.io). Check out [Prose's Getting Started Guide](https://github.com/prose/prose/wiki/Getting-Started) to learn more.

**Note:** Text in **bold** represents sidebar buttons and text. If you can't find the right button, mouse over them to see their names.

1. Open the appropriate file according to [file locations](#file-locations). If you're creating a poem, go to [`_posts`](http://prose.io/#danamcc/danamcc.github.io/tree/master/_posts) and click **NEW FILE**.
2. Make modifications to the file's content, title (above the content), **Meta Data**, and filename (under **Settings**) as needed.
3. If you're creating a poem, don't forget to delete the example Markdown content, add a title (it doesn't have to be unique), and give it at least one category under **Meta Data**.
4. If you're editing a Markdown file, check its **Preview**.
5. Click **Changes to Save**.
6. If you're making a non-trivial change to an existing file, write a brief commit message under **Describe your Changes** (for future reference).
7. Click **COMMIT** to save the file.
8. By default, saving a new poem will leave it unpublished, meaning that you will not see it on the website. To publish a poem, click `Unpublished` in the toolbar, then save the poem.

### File Locations
**Note**: `*` represents a [wildcard](https://en.wikipedia.org/wiki/Wildcard_character).

| Content | Location | Note |
| --- | --- | --- |
| Site title and SEO data | [`_config.yml`](_config.yml) | Includes open graph data (for social networks) and linked data |
| Home page jumbotron | [`_includes/home_*.md`](_includes) | Includes site intro |
| Main page content | [`*.md`](.) (based on page name) | Excluding Home and Poems pages |
| Page excerpts, icons, and ordering | Not available in Prose yet | Displayed in the navigation and home page |
| Poems | [`_posts`](_posts) |
| Poems listing intro | [`_includes/poems_intro.md`](includes/poems_intro.md) | Displayed at the top of both categories (life and love) |
| This readme | [`README.md`](README.md) |

### Syntax

#### Markdown Files (`*.md`)
Refer to [Kramdown's quick reference](http://kramdown.gettalong.org/quickref.html) to learn the Markdown syntax supported in this site.

Please note that the [`hard_wrap` option](http://kramdown.gettalong.org/options.html#option-hard-wrap) is enabled, so returning to the next line will insert a line break without requiring you to append spaces or backslashes to the previous line. Additionally, Prose does not support this option nor some of the other extra features in Kramdown's version of the Markdown syntax, so Prose's Markdown preview may behave differently from the actual site.

#### Jekyll Config (`_config.yml`)
Refer to links in the file itself to learn about its configuration options, and [Learn yaml in Y minutes](https://learnxinyminutes.com/docs/yaml/) to learn the YAML syntax used in the file.

## Developing
1. Install [Ruby](https://www.ruby-lang.org/).
2. Install Bundler with `gem install bundler`.
3. Install dependencies with `bundle`.
4. Run Jekyll with `bundle exec jekyll serve`.
5. If you need to access the server from other devices, use `--host 0.0.0.0`.

## Private Resources
- [Google Analytics](https://analytics.google.com/analytics/web/#report/defaultid/a51703743w83996550p87034958/)
- [Google Search Console](https://www.google.com/webmasters/tools/dashboard?siteUrl=http%3A%2F%2Fdanamccurdy.com%2F)
