---
layout: "@/layouts/BlogPost"
title: Hello World
publishDate: 9 November 2022
description: Post đầu tiên
tags: ["blog"]
---

## Bên dưới là một vài ví dụ về markdown syntax khi được render bởi Astro

<Image
	src="https://picsum.photos/id/1025/550/460"
	alt="A covered up pug in the woods"
	width={550}
	height={460}
/>

## Using some markdown elements

Here we have a simple js code block.

```js
let string = "JavaScript syntax highlighting";
```

This is styled by Shiki, set via the [config](https://docs.astro.build/en/guides/markdown-content/#syntax-highlighting) for Astro.

You can choose your own theme from this [library](https://github.com/shikijs/shiki/blob/main/docs/themes.md#all-themes), which is currently set to Dracula, in the file `astro.config.mjs`.

Here is a horizontal rule.

---

Here is a list:

- Item number 1
- Item number 2
- Item number 3

And an ordered list:

1. James Madison
2. James Monroe
3. John Quincy Adams

Here is a table:

| Item         | Price | # In stock |
| ------------ | :---: | ---------: |
| Juicy Apples | 1.99  |        739 |
| Bananas      | 1.89  |          6 |

## Tailwind CSS Prose styling

> I'm a simple blockquote.
> I'm styled by Tailwind CSS prose plugin