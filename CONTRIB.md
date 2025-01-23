# Contribution guidelines

In addition to audio tutorials, the site also has a how-to for adding a tutorial to the site.

## Building the website locally

First, you may need to [install Jekyll](https://jekyllrb.com/docs/installation/#guides).

If you have that working, then from the `docs/` directory, run:

```
bundle install
```

and

```
bundle exec jekyll serve
```

Alternatively, provided you're on the main branch, any changes you commit should be live at https://irrationalpie7.github.io/audio-tutorials/ within a few minutes.

## A note on formatting

I have prettier running on all the markdown files, which is honestly really nice, but does break some of the kramdown markup things, like inserting a table of contents or excluding a header from the table of contents.
For the moment, I think I'd rather keep the formatting and skip the ability to have a table of contents, but at some point it might be nice to investigate if there's any workarounds (say, an alternate formatter, or possibly the ability to include a toc the way we include `<audio>` elements)
