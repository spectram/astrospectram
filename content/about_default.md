---
title: About Me
subtitle: This is a short page about me and my work
img_path: images/about.jpg
sitemap_ignore: true
seo:
  metatitle: About Me
  description: A page about me and my work
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: About Me
      keyName: property
    - name: 'og:description'
      value: A page about me and my work
      keyName: property
    - name: 'og:image'
      value: images/about.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: About Me
    - name: 'twitter:description'
      value: A page about me and my work
    - name: 'twitter:image'
      value: images/about.jpg
      relativeUrl: true
layout: page
---

**This is a paragraph**. Paragraphs are usually represented in visual media as blocks of text separated from adjacent blocks by blank lines and/or first-line [indentation](https://en.wikipedia.org/wiki/Indentation_(typesetting)), but <abbr title="HyperText Markup Language">HTML</abbr> paragraphs can be any structural grouping of related content, such as images or form fields.

The HTML &lt;h1&gt;–&lt;h6&gt; elements represent six levels of section headings. &lt;h1&gt; is the highest section level and &lt;h6&gt; is the lowest.

# This is an H1

## This is an H2

### This is an H3

#### This is an H4

##### This is an H5

###### This is an H6

Avoid using heading tags to resize text. Instead, use the CSS font-size property. Headings use size to indicate their relative importance, but CSS is preferred for general-purpose resizing.

## Quoting

The HTML blockquote element defines a long block quotation in the HTML document from another source.

>“Creativity is allowing yourself to make mistakes. Design is knowing which ones to keep.” <cite>― Scott Adams</cite>

A URL for the source of the quotation may be given using the cite attribute, while a text representation of the source can be given using the &lt;cite&gt; element.

<hr />

## Unordered Lists

Groups a collection of items that do not have a numerical ordering, and their order in the list is meaningless.

+ Donec non tortor in arcu mollis feugiat
+ Lorem ipsum dolor sit amet, consectetuer adipiscing elit
+ Donec id eros eget quam aliquam gravida
+ Vivamus convallis urna id felis
+ Nulla porta tempus sapien

## Ordered Lists

Represents a list of items. The only difference from the unordered list is taht the order of the items is meaningful.

1. Donec non tortor in arcu mollis feugiat
2. Lorem ipsum dolor sit amet, consectetuer adipiscing elit
3. Donec id eros eget quam aliquam gravida
4. Vivamus convallis urna id felis
5. Nulla porta tempus sapien

## Code Blocks

<pre>/* Some example CSS code */
body {
  color:red;
}
</pre>

## Tables

<table>
  <caption>Simple table with caption and header</caption>
  <tr>
    <th>First name</th>
    <th>Last name</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Doe</td>
  </tr>
</table>
