HtmlCleaner
=================================================

For this homework, you will clean HTML by removing all of the HTML entities, tags and elements.

Eventually, we want to be able to crawl the web and parse web pages into plain text words. As such, we must be able to remove all of the HTML code from that web page. This assignment is a step towards this functionality. This homework is broken into the following classes:

  - `HttpsFetcher.java`: This is a general HTTP(S) fetcher and is the same as the lecture code.

  - `HtmlCleaner.java`: This is a class dedicated to removing HTML tags from a webpage, leaving only the raw text. There are several methods here you must implement.

*Note:* Before using these classes with project 4, you will need to make some modifications. Specifically, you will eventually need to make your `LinkParser` and `HtmlCleaner` work together so that you parse links after stripping block elements, but before stripping tags and entities. (This is not required for the homework, however.)

## Hints ##

We do not explicitly cover HTML in this class. However, there are many helpful resources on the web for more about this simple markup language. Some resources include:

* [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3C Markup Validation](https://validator.w3.org/)
* [Web Design Group](https://htmlhelp.com/)

## Requirements ##

See the Javadoc and `TODO` comments in the template code in the `src/main/java` directory for additional details. You must pass the tests provided in the `src/test/java` directory. Do not modify any of the files in the `src/test` directory.

See the [Homework Guides](https://usf-cs212-fall2020.github.io/guides/homework/) for additional details on homework requirements and submission.
