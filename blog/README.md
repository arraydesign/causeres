# BLOG POSTS

* Under 500 words;
* Thoughts, questions, comments, etc;
* Posts should be published once or twice a week / 4 – 5 times a month / 50 – 60 times a year.

## Structure & Formatting
* Please use MARKDOWN for writing posts;
* The meta data for each post should be set using the YAML syntax:
	- This must be the first thing in the file and must take the form of a valid YAML set between triple-dashed lines;
	- Basic example:

```
---
title: Post Title
author: Firstname Lastname
categories:
- Category Name
- Category Name
tags: tag1 tag2 tag3 multi-word-tag
published: YYYY-MM-DD HH:mm:ss
updated: YYYY-MM-DD HH:mm:ss
---
```

## Published vs Draft Posts
* To separate published & draft posts a specific naming convention will be used for the filenames:
	- The filename of draft posts should be «draft-post-name.md»;
	- The filename of published posts should be «~published-post-name.md»;
* In other words published posts have the ‘~’ character at the beginning of their filenames;
* Regardless whether the post is a draft or is published the filename must be:
	- lowercase
	- alphanumeric characters only (A – Z, a – z, 0 – 9)
	- dashes instead of spaces

## Examples
* Two examples posts have been provided:
	- «example-post-1.md»
	- «~example-post-2.md»
