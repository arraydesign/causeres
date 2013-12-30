# LONG FORM ARTICLES

* 1000+ words;
* Dealing with a specific concept, idea or theme;
* Will be released monthly.

## Structure & Formatting
* Please use either MARKDOWN or TEXTILE for writing the articles;
* The meta data for each article should be set using YAML front-matter;
	- The front-matter must be the first thing in the file and must take the form of valid YAML set between triple-dashed lines;
	- Basic example:

    ---
    title: Article Title
    author: Firstname Lastname
    abstract: Lorem ipsum dolor sit amet, consectetur...	
    categories:
    - Category Name
    - Category Name
    tags: tag1 tag2 tag3 multi-word-tag
    published: false
    date: YYYY-MM-DD HH:mm:ss
    ---

## Published vs Draft Articles
* To separate published & draft articles a specific naming convention will be used for the filenames:
	- The filename of draft articles should be «draft-article-name.md» or «draft-article-name.textile»;
	- The filename of published articles should be «YYYY-MM-DD-published-article-name.md» or «YYYY-MM-DD-published-article-name.textile»;
* In other words draft articles do NOT have the date in their filenames while published articles do;
* Regardless whether the article is a draft or is published the filename must be:
	- lowercase
	- alphanumeric characters only (A – Z, a – z, 0 – 9)
	- dashes instead of spaces

## Examples
* Two examples articles have been provided:
	- «example-draft-article.md»
	- «2013-12-30-example-published-article.textile»