---
title: Margin Notes Demo
date: 2026-02-06
tags:
  - demo
  - features
---

# Margin Notes in Action

This page demonstrates the Quarto-style margin notes feature. Margin notes appear in the right margin on wide screens and inline on mobile devices.

:::{.margin}
This is a **longer** margin note with multiple paragraphs.

It can span several lines and include complex formatting.

Perfect for detailed asides and commentary!
:::

## Basic Usage

The syntax is simple: wrap your margin note content in `:::{.margin}` and `:::` markers.

Here's some main content that flows naturally. :::{.margin}
This is a margin note! It appears in the right margin without disrupting the main text flow.
:::

You can continue writing your main content, and the margin notes will be positioned adjacent to where they're referenced in the markdown.

## Multiple Notes

Margin notes automatically stack to avoid overlapping, even when they're close together in the source text.

This paragraph has a note. :::{.margin}
First note about something important.
:::

This next paragraph also has a note. :::{.margin}
Second note that will automatically adjust its position to avoid overlapping with the first note.
:::

And a third note here! :::{.margin}
Third note showing the smart stacking in action.
:::

## Rich Content in Margin Notes

Margin notes can contain **formatted text**, `code snippets`, and [links](https://example.com).

:::{.margin}
You can include:
- Lists
- **Bold** and *italic* text
- `inline code`
- Even [external links](https://quarto.org)
:::

## Multi-paragraph Notes

You can also create multi-paragraph margin notes by wrapping multiple paragraphs:

:::{.margin}
This is a longer margin note with multiple paragraphs.

It can span several lines and include complex formatting.

Perfect for detailed asides and commentary!
:::

## Use Cases

Margin notes are perfect for:

- **Commentary**: Add context without breaking reading flow :::{.margin}
Like this contextual addition that explains something without interrupting the main argument.
:::

- **Citations & References**: Keep references handy without cluttering inline text

- **Definitions**: Provide quick glossary terms :::{.margin}
**Glossary**: A margin note explaining a technical term inline.
:::

- **Tangential thoughts**: Share related ideas that aren't core to the main narrative

## Responsive Design

On mobile devices (or narrow screens), margin notes automatically convert to inline callout-style boxes to ensure readability on all screen sizes.

Try resizing your browser window to see the responsive behavior in action!

---

**Tip**: For the best experience, view this page on a screen wider than 1400px to see true margin positioning.
