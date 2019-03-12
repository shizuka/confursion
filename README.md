# confursion

Knowledgebase wiki for the Confursion universe

Powered by git-wiki

### Filenames
For character sheets, name the file `firstname.md` and set `title` to the same
name in front matter. If the character has a last name, add it to `ititle` in
the infobox, and use `# Firstname Lastname` as the main header for the content.

For documents and articles, name the file `YYYY-MM-DD-article-title-without-spaces.md`
and set the `title`. Keep filenames short for easier linking, a longer article
title can be set for the first header `# Some Long Article Title With Spaces`

For locations, name the file `location-without-spaces.md`, and set front matter
appropriately.

Leave events alone for now, that will be mostly a timeline page.

### Front Matter
Please be sure to add at least this block to the top of every file. Additional
front matter, such as the infobox, goes before the last `---`

```
---
title: Page title
author: yourname
---

# Page Header

...content...
```

If you don't want the page to have a table of contents built (which is put before
the first header of the content), add `notoc: true` to the front matter.

To remove the "Edit" and "Delete" links, for instance when the document is final,
add `noedit: true` to the front matter.

### Infoboxes
To enable the infobox, add the following to front matter. All fields are optional.

```
infobox: true
ititle: Different title from filename, for instance a full character name
subtitle: smaller text under title
image: path to image, either offsite or "/img/file.name" and adding the file
caption: text under the image
info:
  Key: Value
  Born: yesterday
  List:
    - Pay attention
    - to the number
    - of spaces
  Some: fourth thing
```

### Infobox List Standards
Still working on a standard list of info to add for characters, locations, etc

```
info:
  Species: ____
  Gender: ____
  Colors:
    - ____ fur
    - ____ hair
    - ____ eyes
    - etc
  Height: ____
```
