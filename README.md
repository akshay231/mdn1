# mdn1
Assessment: Marking up a letter: is my first commit to github on html and css projects. It will be followed by a lot more.
About this project: (source: https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Marking_up_a_letter)
Starting point
To get this assessment started, you should go and grab the raw text you need to mark up, and the CSS you need to include in your HTML. Create a new .html file using your text editor to do your work in (or alternatively use a site like JSBin or Thimble to do your assessment.)

Project brief
For this project, your task is to mark up a letter that needs to be hosted on a university intranet. The letter is a reponse from a research fellow to a prospective PhD student concerning their application to work at the university.

Block/structural semantics:

You should structure the overall document with an appropriate structure including doctype, and <html>, <head> and <body> elements.
The letter in general should be marked up with a structure of paragraphs and headings, with the exception of the below points. There is one top level heading (the "Re:" line) and three second level headings.
The semester start dates, study subjects and exotic dances should be marked up using an appropriate list type.
The two addresses can just be put inside paragraphs,or you could use the address element appropriately; each line of the address should sit on a new line, but not be in a new paragraph.
Inline semantics:

You should mark up the contents of the body with appropriate elements:
The names of the sender and receiver (and "Tel" and "Email") should be marked up with strong importance.
The four dates in the document should be given appropriate elements containing machine-readable dates.
The first address and first date in the letter should be given a class attribute value of "receiver-column"; the CSS you'll add later will then cause these to be right aligned, as should be the case in a classic letter layout.
The five acronyms/abbreviations in the main text of the letter should be marked up to provide expansions of each acronym/abbreviation.
The six sub/superscripts should be marked up appropriately.
The degree symbols, greater than symbol and multiply symbols should be marked up using appropriate entity references.
Try to mark up at least two appropriate words in the text with strong importance/emphasis.
There are two places where a hyperlink should be added; add appropriate links with titles. For the location that the links point to, just use http://example.com.
The university motto quote and citation should be marked up with appropriate elements.
The head of the document:

The character set of the document should be specified as utf-8 using an appropriate meta tag.
The author of the letter should be specified in an appropriate meta tag.
The provided CSS should be included inside an appropriate tag.
Hints and tips
Use the W3C HTML validator to validate your HTML; you'll get bonus points if it validates.
You don't need to know any CSS to do this assessment; you just need to put the provided CSS inside an HTML element.
