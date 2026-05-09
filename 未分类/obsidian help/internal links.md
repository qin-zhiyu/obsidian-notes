## Link to a block in a note 

A block is a unit of text in your note, such as a paragraph, block quote, or list item.

You can link to a block by adding `#^` at the end of your link destination, followed by a unique block identifier. For example: `[[2023-01-01#^37066d]]`. Fortunately, you don't need to manually find the identifier—when you type the caret (`^`), a list of suggestions will appear, allowing you to select the correct block.

For _simple paragraphs_, place a blank space followed by a caret `^` and the block identifier at the end of the line:

```md
The quick purple gem dashes through the paragraph with blazing speed. Pen in hand and a paperclip in the other, Gemmy works toward her goal of making the world of note-taking a happier place. ^37066d
```

For _structured blocks_ (lists, quotations, callouts, tables), the block identifier should be on a separate line, with a blank line before and after:

```md
> The quick purple gem dashes through the paragraph with blazing speed. Pen in hand and a paperclip in the other, Gemmy works toward her goal of making the world of note-taking a happier place.

^37066f

This is the tale of Gemmy, the Unhelpful assistant.  
```

For _specific lines within a list_, the block identifier can be placed directly on a bullet point:

```mathjax
- Gemmy
    $$Paperclip / Pen$$ 
    ^37006f
- Unhelpful assistant
```

We do not support links to specific parts of quotations, callouts, and tables.

**Searching for blocks across the vault**

You can also search for blocks to link to from across your vault using the `[[^^block]]` syntax. However, more items qualify as blocks compared to [heading links](https://help.obsidian.md/links#Link%20to%20a%20heading%20in%20a%20note), so this list will be much longer.

Screenshot of searching for a block link 

![link-block-heading.png > interface](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/link-block-heading.png)

You can also create human-readable block identifiers by adding a blank space followed by a caret (`^`) and the identifier. Block identifiers can only consist of Latin letters, numbers, and dashes.

For example, add `^quote-of-the-day` at the end of a block:

```md
"You do not rise to the level of your goals. You fall to the level of your systems." by James Clear ^quote-of-the-day
```

Now you can link to the block by typing `[[2023-01-01#^quote-of-the-day]]`.

Interoperability

Block references are specific to Obsidian and not part of the standard Markdown format. Links containing block references won't work outside of Obsidian.