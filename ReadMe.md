# Obsidian-Config

This repository aims to provide a quick way to configure Obsidian's appearance and plugins.

## What it Contains

+ All JSON files to costomize Obsidian's look
+ Two `Community Plugin`s : `Advanced Tables` and `Number Headings`
+ Two CSS snippets written by me : `main` and `tableNoBorder`, which are in `/snippets`

## What it Does

It applies the Light theme and new interface font(Courier New).

`Advanved Tables` provides a convenient envirenment to type tables.

`Number Headings` automatically count the headings.

All the `Community Plugin`s are pre-configured by me, with no change to the core source code.

`main`.css can:

+ Center H1 headings
+ Set font family for bold and italic font
+ Center pictures and restrict their maximum width to 80% of the interface
+ Center tables

`tableNoBorder.css` can:

+ Eliminate borders of tables, useful for organizing elements

**You can use, modify and distribute my CSS snippets**

## How to Use

1. Delete your original `.obsidian` folder
2. Clone this repo and replace it:

```bash
git clone https://github.com/14983/obsidian-config.git
mv obsidian-config .obsidian
```