# LONG FORM ARTICLES

* 1000+ words;
* Dealing with a specific concept, idea or theme;
* Will be released monthly.

## Structure & Formatting
* Please use either MARKDOWN or plain text for writing the articles;
* The meta data for each post should be set using the YAML syntax:
	- This must be the first thing in the file and must take the form of a valid YAML set between triple-dashed lines;
	- Basic example:

```
---
title: Article Title
author: Firstname Lastname
abstract: Lorem ipsum dolor sit amet, consectetur...
categories:
- Category Name
- Category Name
tags: tag1 tag2 tag3 multi-word-tag
published: YYYY-MM-DD HH:mm:ss
updated: YYYY-MM-DD HH:mm:ss
---
```

## Published vs Draft Articles
* To separate published & draft articles a specific naming convention will be used for the filenames:
	- The filename of draft articles should be «draft-article-name.md»;
	- The filename of published articles should be «~published-article-name.md»;
* In other words published posts have the ‘~’ character at the beginning of their filenames;
* Regardless whether the article is a draft or is published the filename must be:
	- lowercase
	- alphanumeric characters only (A – Z, a – z, 0 – 9)
	- dashes instead of spaces

## Examples
* Two examples articles have been provided:
	- «example-article-1.md»
	- «~example-article-2.md»
