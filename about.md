---
layout: post
permalink: /about
title: Style Demo
description: This is a demonstration of some elements in CSS.
image: assets/images/blue.jpg
---
## Article

This is an `article` showing some basic styling.

<article>
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
<hr>
<p><b>Bold</b></p>
<p><i>Italic</i></p>
<p><small>Small</small></p>
<p><s>Strikethrough</s></p>
<p>Subscript: H<sub>2</sub>O</p>
<p>Superscript<sup>1</sup></p>
<p><u>Underlined</u></p>
<p><a href="https://example.com" target="_blank">URL</a></p>
<p><abbr title="Uniform Resource Locator">URL</abbr> Abbreviated</p>
<p><mark>Highlighted</mark></p>
<p><mark>Highlighted <a href="https://example.com" target="_blank">URL</a></mark></p>
<p>Keyboard: <kbd>Cmd</kbd></p>
</article>

## Aside

This is an `aside` which floats to the right.

<aside>
<p><b>Lorem Ipsum</b></p>
<p><i>Lorem ipsum dolor sit amet, consectetur adipiscing elit</i></p>
</aside>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Blockquote

This is a `blockquote` with a `cite`.

> Lorem ipsum dolor sit amet
>
> <cite>Anonymous</cite>

## Code Block

This can display a block of `code` using `pre`.

```
body {
  background: var(--bg);
  color: var(--text);
  font-size: 1rem;
  line-height: 1.5;
  margin: 0;
}
```

<pre>Here is some pre-formatted text that does not wrap.</pre>

## Details/Summary

The `details` of this element are hidden behind a `summary`.

<details>
  <summary>Summary</summary>
  Some text
</details>

## Lists

<p><u>Description</u></p>
<dl>
  <dt>Item</dt>
  <dd>Description</dd>
  <dt>Item</dt>
  <dd>Description</dd>
</dl> 

<p><u>Ordered</u></p>
1. Item
2. Item
    1. Item
    2. Item
        1. Item
        2. Item

<p><u>Unordered</u></p>
* Item
* Item
  * Item
  * Item
    * Item
    * Item

## Media

This is an image inside a `figure` with `figcaption`.

<figure>
  <img src="https://placekitten.com/800/800" alt="Photo of kitten(s)">
  <figcaption>Here is a caption for the photo.</figcaption>
</figure>

## Table

This is a `table` with overflow contained in a `figure`.

<figure>
  <table>
    <caption>Table Title</caption>
	  <thead>
	    <tr>
		    <th>Table Heading 1</th>
			  <th>Table Heading 2</th>
			  <th>Table Heading 3</th>
			  <th>Table Heading 4</th>
			  <th>Table Heading 5</th>
		  </tr>
	  </thead>
	  <tbody>
	    <tr>
		    <td>Table Cell 1</td>
			  <td>Table Cell 2</td>
			  <td>Table Cell 3</td>
			  <td>Table Cell 4</td>
			  <td>Table Cell 5</td>
		  </tr>
	    <tr>
		    <td>Table Cell 1</td>
			  <td>Table Cell 2</td>
			  <td>Table Cell 3</td>
			  <td>Table Cell 4</td>
			  <td>Table Cell 5</td>
		  </tr>
	    <tr>
		    <td>Table Cell 1</td>
			  <td>Table Cell 2</td>
			  <td>Table Cell 3</td>
			  <td>Table Cell 4</td>
			  <td>Table Cell 5</td>
		  </tr>
	    <tr>
		    <td>Table Cell 1</td>
			  <td>Table Cell 2</td>
			  <td>Table Cell 3</td>
			  <td>Table Cell 4</td>
			  <td>Table Cell 5</td>
		  </tr>
	  </tbody>
  </table>
  <figcaption>Table Caption</figcaption>
</figure>