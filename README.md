
# PugnaPorcorum
This project aims to produce a transcription and translation of the Latin poem, _The Battle of the Pigs_.

For general information about this project, please visit the [GitClassics site](http://gitclassics.github.io).

## How to Get Started (The Workflow)

* First, fork the repository to get a copy of the text files on your own computer.
* Take a look at the PDF and pick a page that you'd like to work on transcribing. Once you've found a page to work on, head over to the [Issues](https://github.com/GitClassics/PugnaPorcorum/issues) page and post a message to announce your work on that page.
	* Check open issues to see if someone is already working on your page.
	* By posting a message we can avoid multiple people working on the same page at the same time.
* Remember that you need to type out Latin in a text editor, not a word processor. **Do not use Microsoft Word.** You can use your computer's default text editor like Notepad (Windows) or TextEdit (Mac), or you can download a more powerful text editor like [Notepad++](http://www.notepad-plus-plus.org/).
* When you've finished your section, submit a pull request. I'll review your submission and merge your contribution with the rest of the text.

## Some Formatting Guidelines

I decided to use [Kramdown](http://kramdown.gettalong.org/) for this project since the text has some footnotes. If you're new to Markdown, you might want to read a good introduction to it [here](http://whatismarkdown.com/).

Since the _Pugna Porcorum_ document includes both prose and poetry, it's important to format your text correctly depending on what you're transcribing.

* If you're transcribing poetry, please **leave three blank spaces at the end of each line**. By including these spaces at the end of the lines, you will guarantee that our files will keep every line of hexameter separate. If you don't leave these spaces at the end of line, Markdown will understand lines of hexameter as one continuous prose paragraph. 
* The _Pugna_ includes footnotes. If your line has a footnote, you should write the line using the following format. You'll notice that we're putting footnotes at the **end** of the line (even though the original text includes them at the beginning). You should use square brackets at the end of the line. Include a caret (^) after the first bracket, enter the number of the footnote, and then close with the second square bracket. Then place the footnote definition at the end.   
	Plaudite porcelli, porcorum pigra propago.[^1]   
  [^1]: Processus porcorum ponitur.   
* For an example of what your text should look like, check out Page9.md, which I have already finished. You can also read the [Kramdown documentation on footnotes](http://kramdown.gettalong.org/quickref.html#footnotes).

## What about Translations?

We'll start translating once we're done with the transcription of the Latin text.

## Questions?

If you have questions about some Latin---maybe some text is blurry or you just find a word that seems out of place---head over to the Issues page and ask!
