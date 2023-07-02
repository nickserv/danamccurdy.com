# [Dana McCurdy's Website](https://danamccurdy.com)

&copy; [Dana McCurdy](https://danamccurdy.com/) & [Nick McCurdy](https://nickmccurdy.com/)

## Authoring
This site's content is stored in Markdown syntax, edited in Prose, and generated into a full site with Jekyll.

### Using Prose
Before you author any content, you should log in to [Prose](https://prose.io/) (using your GitHub account) and visit [this project](https://prose.io/#danamcc/danamcc.github.io). Check out [Prose's Getting Started Guide](https://github.com/prose/prose/wiki/Getting-Started) to learn more.

**Note:** Text in **bold** represents sidebar buttons and text. If you can't find the right button, mouse over them to see their names.

1. Open the appropriate file according to [file locations](#file-locations). If you're creating a post, go to [`_posts`](https://prose.io/#danamcc/danamcc.github.io/tree/main/_posts) and click **NEW FILE**.
2. Make modifications to the file's content and **Meta Data** (optional) as needed.
3. If you're renaming a post, modify its title (above the content). If you have already shared links to the post, you must also open **Settings** for the post and change its **File Path** back to the original file name, otherwise your links will break.
4. If you're creating a post, don't forget to delete the example Markdown content, add a title (it doesn't have to be unique), and optionally adjust categories or other fields in **Meta Data**.
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
| Pages | [`*.html,md`](.) (based on page name) | Page titles, excerpts, and navbar positions can be edited in Prose's **Meta Data** section. |
| Posts | [`_posts`](_posts) |
| Includes | [`_includes`](_includes) |

### Markdown (`*.md` files)
Refer to [Kramdown's quick reference](https://kramdown.gettalong.org/quickref.html) to learn the Markdown syntax supported in this site.

Please note that the [`hard_wrap` option](https://kramdown.gettalong.org/options.html#option-hard-wrap) is enabled, so returning to the next line will insert a line break without requiring you to append spaces or backslashes to the previous line. Additionally, Prose does not support this option nor some of the other extra features in Kramdown's version of the Markdown syntax, so Prose's Markdown preview may behave differently from the actual site.

## Developing
1. Install [Ruby](https://www.ruby-lang.org/).
2. Install Bundler with `gem install bundler`.
3. Install dependencies with `bundle`.
4. Run Jekyll with `bundle exec jekyll serve`.
5. If you need to access the server from other devices, use `--host 0.0.0.0`.

## Private Resources

### [Namecheap](https://ap.www.namecheap.com/domains/domaincontrolpanel/danamccurdy.com)

Our domain registrar (where we bought [danamccurdy.com](https://danamccurdy.com)).

### [Google Analytics](https://analytics.google.com/analytics/web/#/p316222955/reports/intelligenthome)

Statistics about the website’s visitors.

### [Google Search Console](https://search.google.com/search-console?resource_id=sc-domain%3Adanamccurdy.com)

Information, tools, and suggestions for controlling Google Search for the website.

### [Figma](https://www.figma.com/file/UhYwxVc4gvTo41am3bNcti/Dana-McCurdy)

Designs and prototypes for the website.
