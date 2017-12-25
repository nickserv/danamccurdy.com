# [Dana McCurdy's Website](http://danamccurdy.com)

&copy; [Dana McCurdy](http://danamccurdy.com/)

Website by [Nick McCurdy](http://nickmccurdy.com/)

## Authoring
This site's content is stored in Markdown syntax, edited in Prose, and generated into a full site with Jekyll.

### Using Prose
Before you author any content, you should log in to [Prose](http://prose.io/) (using your GitHub account) and visit [this project](http://prose.io/#danamcc/danamcc.github.io). Check out [Prose's Getting Started Guide](https://github.com/prose/prose/wiki/Getting-Started) to learn more.

**Note:** Text in **bold** represents sidebar buttons and text. If you can't find the right button, mouse over them to see their names.

1. Open the appropriate file according to [file locations](#file-locations). If you're creating a poem, go to [`_posts`](http://prose.io/#danamcc/danamcc.github.io/tree/master/_posts) and click **NEW FILE**.
2. Make modifications to the file's content and **Meta Data** (optional) as needed.
3. If you're renaming a poem, modify its title (above the content). If you have already shared links to the poem, you must also open **Settings** for the poem and change its **File Path** back to the original file name, otherwise your links will break.
4. If you're creating a poem, don't forget to delete the example Markdown content, add a title (it doesn't have to be unique), and optionally adjust categories or other fields in **Meta Data**.
5. If you're editing a Markdown file, check its **Preview**.
6. Click **Changes to Save**.
7. If you're changing an existing file, write a brief commit message under **Describe your Changes** (for future reference).
8. Click **COMMIT** to save the file.

### Updating Facebook Shares
Facebook caches metadata about a page when its link is shared, so you may notice a share has outdated content after the page is changed. You will need to ask Facebook to refresh its copy of a page if you change the page after sharing its link.

1. Copy the specific link you want to share or have already shared.
2. Paste the link into the [Facebook Sharing Debugger](https://developers.facebook.com/tools/debug/sharing/), click `Debug`, and inspect the link preview section. If the preview seems to be out of date or the scrape time is too old, click `Scrape Again`.
3. If you already have shared the link through a Facebook post, click on the post's chevron menu (upper right) and select `Refresh share attachment`. The post should now display the same preview as the Sharing Debugger.

### File Locations
**Note**: `*` represents a [wildcard](https://en.wikipedia.org/wiki/Wildcard_character).

| Content | Location | Note |
| --- | --- | --- |
| Site metadata | [`_config.yml`](_config.yml) | Includes preview data for social networks and search engines, along with additional configuration for Jekyll and Prose. |
| Pages | [`*.md`](.) (based on page name) | Page titles, excerpts, and navbar positions can be edited in Prose's **Meta Data** section. |
| Home intro | [`_includes/home_*.md`](_includes) | Includes the home page's heading, portrait photo, and nearby text. |
| Drum circle photos |  [`_data/drum_circle_photos.yml`](_data/drum_circle_photos.yml) | A list of photo files included at the top of the Drum Circles page, and a second list of photo files displayed in the carousel at the bottom of the page. |
| Poems intro | [`_includes/poems_intro.md`](includes/poems_intro.md) | Displayed at the top of both categories (life and love). |
| Poems | [`_posts`](_posts) |
| This readme | [`README.md`](README.md) | Displayed on GitHub and Prose only, but you can edit it like any other Markdown file in this site. |

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
