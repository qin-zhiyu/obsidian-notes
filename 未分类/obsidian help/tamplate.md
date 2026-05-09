#   Templates

Templates is a [core plugin](https://help.obsidian.md/plugins) that lets you insert pre-defined snippets of text into your active note.

## Set your template folder 

1. In the bottom-left corner, click **[Settings](https://help.obsidian.md/settings)** ( ![lucide-cog.svg > icon](https://publish-01.obsidian.md/access/f786db9fac45774fa4f0d8112e232d67/Attachments/icons/lucide-cog.svg) ).
2. Under **Core plugins → Templates → Template folder location**, enter the folder containing your templates.

## Template variables 

You can add dynamic information to your templates, using _template variables_. When you insert a template containing a template variable, Templates replaces it with its corresponding value.

|Variable|Description|
|---|---|
|`{{title}}`|Title of the active note.|
|`{{date}}`|Today's date. **Default format:** `YYYY-MM-DD`.|
|`{{time}}`|Current time. **Default format:** `HH:mm`.|

Both `{{date}}` and `{{time}}` allow you to change the default format using a _format string_.

To set a format string, add a colon (`:`) followed by a string of [Moment.js format tokens](https://momentjs.com/docs/#/displaying/format/), for example `{{date:YYYY-MM-DD}}`.

You can use `{{date}}` and `{{time}}` interchangeably with format strings, for example `{{time:YYYY-MM-DD}}`.

You can change the default date and time formats under **[Settings](https://help.obsidian.md/settings) → Templates → Date format** and **[Settings](https://help.obsidian.md/settings) → Templates → Time format**.

Tip

You can also use the `{{date}}` and `{{time}}` template variables in the [Daily notes](https://help.obsidian.md/plugins/daily-notes) and [Unique note creator](https://help.obsidian.md/plugins/unique-note) plugins.

## Create a template 

In the [template folder](https://help.obsidian.md/plugins/templates#Set%20your%20template%20folder), [create a note](https://help.obsidian.md/manage-notes#Create%20a%20new%20note) containing the text you want to appear when you use the template. You can use [template variables](https://help.obsidian.md/plugins/templates#Template%20variables) for dynamic text like the current date.

For example, here's a template for study notes:

```markdown
---
topic: 
date: "{{date}}"
course: 
tags:
  - studies
---

# {{title}}

## Key Concepts


## Important Details


## Examples


## Questions
- 

## Summary


## Related Topics
- [[]]
```

## Insert a template into the active note 

**Important:** To insert a template, you need to first [Set your template folder](https://help.obsidian.md/plugins/templates#Set%20your%20template%20folder).

1. In the ribbon, click **Insert template**.
2. Select the template to insert at the cursor position in the active note.

## Template properties 

When you insert a template into the active note, all the properties from the template will be added to the note. Obsidian will also merge any properties that exist in your note with properties in the template. 
