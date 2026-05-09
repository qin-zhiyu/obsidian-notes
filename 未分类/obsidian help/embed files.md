#   Embed files

Learn how you can embed other notes and media into your notes. By embedding files in your notes, you can reuse content across your vault.

To embed a file in your vault, add an exclamation mark (`!`) in front of an [Internal link](https://help.obsidian.md/links). You can embed files in any of the [Accepted file formats](https://help.obsidian.md/file-formats).

[[Drag and Drop]] embed 

On desktop, you can also [[drag and drop]] supported files directly into your note to embed them automatically.

## Embed a note in another note 

To embed a note:

```md
![[Internal links]]
```

You can also embed links to [headings](https://help.obsidian.md/links#Link%20to%20a%20heading%20in%20a%20note) and [blocks](https://help.obsidian.md/links#Link%20to%20a%20block%20in%20a%20note).

```md
![[Internal links#^b15695]]
```

The text below is an example of an embedded block:

Learn how to link to notes, attachments, and other files from your notes, using _internal links_. By linking notes, you can create a network of knowledge. 

## Embed an image in a note 

To embed an image:

```md
![[Engelbart.jpg]]
```

![Engelbart.jpg > outline](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/Engelbart.jpg)

You can change the image dimensions, by adding `|640x480` to the link destination, where 640 is the width and 480 is the height.

```md
![[Engelbart.jpg|100x145]]
```

If you only specify the width, the image scales according to its original aspect ratio. For example, `![[Engelbart.jpg|100]]`.

![Engelbart.jpg#outline](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/Engelbart.jpg)

You can also embed an externally hosted image by using a markdown link. You can control the width and height the same way as a wikilink. 

```md
![250](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/Engelbart.jpg)
```

![250](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/Engelbart.jpg)

## Embed an audio file in a note 

To embed an audio file:

```md
![[Excerpt from Mother of All Demos (1968).ogg]]
```

## Embed a PDF in a note 

To embed a PDF:

```md
![[Document.pdf]]
```

You can also open a specific page in the PDF, by adding `#page=N` to the link destination, where `N` is the number of the page:

```md
![[Document.pdf#page=3]]
```

You can also specify the height in pixels for the embedded PDF viewer, by adding `#height=[number]` to the link. For example:

```md
![[Document.pdf#height=400]]
```

## Embed a list in a note 

To embed a list from a different note, first add a [block identifier](https://help.obsidian.md/links#Link%20to%20a%20block%20in%20a%20note)to your list:

```md

- list item 1
- list item 2

^my-list-id
```

Then link to the list using the block identifier:

```md
![[My note#^my-list-id]]
```

## Embed search results 

## Embed search results in a note 

To embed search results in a note, add a `query` code block:

````
```query
embed OR search
```
````

[Obsidian Publish](https://help.obsidian.md/publish) doesn't support embedded [search results](https://help.obsidian.md/publish/limitations#Search). To see a live rendered example, use the code block above within your vault.

![search-query-rendered.png](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/search-query-rendered.png)

LINKS TO THIS PAGE

[Accepted file formats](https://help.obsidian.md/file-formats)

[Advanced formatting syntax](https://help.obsidian.md/advanced-syntax)

[Attachments](https://help.obsidian.md/attachments)

[Audio recorder](https://help.obsidian.md/plugins/audio-recorder)

[Basic formatting syntax](https://help.obsidian.md/syntax)

[Callouts](https://help.obsidian.md/callouts)

[Create a base](https://help.obsidian.md/bases/create-base)

[Glossary](https://help.obsidian.md/glossary)

[Internal links](https://help.obsidian.md/links)

[Media files](https://help.obsidian.md/publish/media)

[Note composer](https://help.obsidian.md/plugins/note-composer)

[Obsidian Flavored Markdown](https://help.obsidian.md/obsidian-flavored-markdown)

[Style guide](https://help.obsidian.md/style-guide)

[Views](https://help.obsidian.md/bases/views)