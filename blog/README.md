# BLOG POSTS

* Under 500 words;
* Thoughts, questions, comments, etc;
* Will be released once or twice a week.

## Structure & Formatting
* Please use either MARKDOWN or TEXTILE for writing the posts;
* The meta data for each post should be set using YAML front-matter;
	- The front-matter must be the first thing in the file and must take the form of valid YAML set between triple-dashed lines;
	- Basic example:

    ---
    title: Post Title
    author: Firstname Lastname
    categories:
    - Category Name
    - Category Name
    tags: tag1 tag2 tag3 multi-word-tag
    published: false
    date: YYYY-MM-DD HH:mm:ss
    ---

## Published vs Draft Posts
* To separate published & draft posts a specific naming convention will be used for the filenames:
	- The filename of draft posts should be «draft-post-name.md» or «draft-post-name.textile»;
	- The filename of published posts should be «YYYY-MM-DD-published-post-name.md» or «YYYY-MM-DD-published-post-name.textile»;
* In other words draft posts do NOT have the date in their filenames while published posts do;
* Regardless whether the post is a draft or is published the filename must be:
	- lowercase
	- alphanumeric characters only (A – Z, a – z, 0 – 9)
	- dashes instead of spaces

## Examples
* Two examples posts have been provided:
	- «example-draft-post.md»
	- «2013-12-30-example-published-post.textile»