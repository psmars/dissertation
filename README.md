# dissertation

Environment for the preparation of dissertations with markdown

## Software

Some software tools are necessary to take advantage of the present framework.
The easiest, may be to use the docker image absps/md2pdf.
But tools can also be installed on your favorite OS.

- pandoc (to convert Markdown to pdf)
- latex (to process latex, intermediary step between Markdown and pdf)
- gs (to reduce the size of pdf)
- GNU Make (to automatise the process)

## Initialisation

- Go to the utils directory and do a 'make' it will ensure that the location of the utility files are known.
- If you want to use a remote git directory for you project, you will need to change the url of '\[remote: \"origin\"\]' in .git/config
