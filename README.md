# Napier Coursework Article Latex Template

## Example 1

A fully integrated example that demonstrates many of the things you can include in your report. Everything is incorporated into a single file called report.tex

## Example 2

This has a slightly simpler structure and doesn't contain all of the examples, e.g. using source-code or diagrams that were shown in example 1. Instead, this example has the parts for you to edit in their own separate files. You can now put your personal details into author.tex and write your report content into content.tex and ignore all of the settings that are in report.tex

To rebuild the PDF, make your edits, then:

        $ pdflatex report
        $ bibtex report
        $ pdflatex report
        $ pdflatex report
