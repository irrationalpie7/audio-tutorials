---
title: Adding a tutorial
parent: Tutorials
---

# Adding a tutorial

Start by creating a copy of `docs/new-tutorial.md`. Change the file name to be something more appropriate, and change the "title" on line 2 and in the heading to match your new tutorial's title:

```
---
title: Adding a tutorial
parent: Tutorials
---

# Adding a tutorial
```

The .md file type is a "markdown" file, it's basically a plain text file with a few special ways of adding headers, links, and formatting. It's relatively commonly supported, for example Discord supports it for italics, bold, lists, or links in messages. Here's a more complete article on [formatting using Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

Markdown also lets you display an image, though you'll have to upload it to the "images" folder in order to be able to use it here.

An example image:

![Waveform plus spectrogram in audacity of 'The quick brown fox jumped over the lazy dog']({{site.baseurl}}/images/quick-brown-fox.png)

The format for that image:

```
![alt text here]({% raw %}{{site.baseurl}}{% endraw %}/images/FILENAME.png)
```

## You can also have a subheading

And a list:

1. Hi there
2. Hi 2

Or a bulleted list:

- A thing
- Another thing

Doing an audio embed is slightly different:

{% include embed_audio.html src="mp3/fox.mp3" %}

The code for that looks like this:

```
{% raw %} {% include embed_audio.html src="mp3/fox.mp3" %} {% endraw %}
```
