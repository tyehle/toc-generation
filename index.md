---
layout: default
---

This page is an example of what the automatic table of contents generation would look like in practice.

## Side Note

This header is just here as an example of what an H2 would look like in the ToC if it appeared before any H1 headers. Note the section header does not appear in the ToC even though it is an H2.

## Sections

{% include toc.html tags="H1,H2" ignore="#sections" %}

-------

Details
=======

This is the main part of the post.

## Part A

Here is a sub section.

### Part A Details

This section does not appear in the ToC because it is an H3 and we specified `tags="H1,H2"`

## Part B

Here is another sub section.

-----------

Conclusions
===========

This is another H1 header.

## Example

With a nested H2.

Here

is

some

text

to

make

the

page

longer

so

the

links

to

the

sections

are

more

obvious.
