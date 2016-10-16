# [Dana McCurdy's Website](http://danamccurdy.com)

Site content and poems: &copy; 2016 [Dana McCurdy](http://danamccurdy.com/)

Other source code: &copy; 2016 [Nick McCurdy](http://nickmccurdy.com/)

## Authoring
This site's content is stored in Markdown syntax, edited in Prose, and generated into a full site with Jekyll.

### Prose
Before you author any content, you should log in to [Prose](http://prose.io/) (using your GitHub account), visit [this project](http://prose.io/#danamcc/danamcc.github.io), and find the right file(s) to edit with the [file locations table](#file-locations). Check out [Prose's Getting Started Guide](https://github.com/prose/prose/wiki/Getting-Started) to learn more.

### File Locations
**Note**: `*` represents a [wildcard](https://en.wikipedia.org/wiki/Wildcard_character).

| Content | Location | Note |
| --- | --- | --- |
| Site title and SEO data | [_config.yml](_config.yml) | Includes open graph data (for social networks) and linked data |
| Home page jumbotron | [\_includes/home\_*.md](_includes) | Includes site intro |
| Main page content | [*.md](.) (based on page name) | Excluding Home and Poems pages |
| Page excerpts, icons, and ordering | Not available in Prose yet | Displayed in the navigation and home page |
| Poems | [_posts](_posts) |
| Poems listing intro | [_includes/poems_intro.md](includes/poems_intro.md) | Displayed at the top of both categories (life and love) |
| This readme | [README.md](README.md) |

### Syntax

#### Markdown Files (`*.md`)
Refer to [Kramdown's quick reference](http://kramdown.gettalong.org/quickref.html) to learn the Markdown syntax supported in this site.

Please note that the [`hard_wrap` option](http://kramdown.gettalong.org/options.html#option-hard-wrap) is enabled, so returning to the next line will insert a line break without requiring you to append spaces or backslashes to the previous line. Additionally, Prose does not support this option nor some of the other extra features in Kramdown's version of the Markdown syntax, so Prose's Markdown preview may behave differently from the actual site.

#### Jekyll Config (`_config.yml`)
Refer to links in the file itself to learn about its configuration options, and [Learn yaml in Y minutes](https://learnxinyminutes.com/docs/yaml/) to learn the YAML syntax used in the file.

### Creating/Editing Posts
1. Open [`_posts` in Prose](http://prose.io/#danamcc/danamcc.github.io/tree/master/_posts).
2. Click on "NEW FILE" to create a post or on an existing post to edit it.
3. Modify the title if you are creating a new post (where it says "Untitled").
4. Author the post in Markdown. The default text when creating a post is just for reference, remove it all before starting a new post.
5. The default category for all posts is "Life". If you want to change it to the other category ("Love"), go to metadata from the sidebar and select it in the dropdown menu.
6. In the sidebar, click save. You can then click "COMMIT" to save the post. If you are modifying an existing post, you should add a commit message explaining why you changed the post (for future reference).
7. By default, saving a new post will leave it unpublished, meaning that you will not see it on the website. To publish a post, click "Unpublished" in the toolbar, then save the post.

## Private Resources
- [Trello Board](https://trello.com/b/hK0hhEDy/dana-s-website)
- [Google Analytics](https://analytics.google.com/analytics/web/#report/defaultid/a51703743w83996550p87034958/)
- [Google Search Console](https://www.google.com/webmasters/tools/dashboard?siteUrl=http%3A%2F%2Fdanamccurdy.com%2F)
