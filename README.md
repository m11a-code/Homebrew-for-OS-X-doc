Homebrew for OS X doc
=====================

A document I created as a walk-through for `Homebrew` -- the missing package manager for OS X -- using pandoc and markdown.

Generally aimed towards users new to `Homebrew` with at least basic knowledge of bash (meaning you can navigate around and know at least some of the basic commands).

Community contributions are welcomed and encouraged.

My goal for this document is to simply make the lives of others starting with `Homebrew` easier by providing an entertaining and educational guide through some of the many aspects of `Homebrew` so that time isn't spent looking around various parts of the internet for information but rather, that time be spent getting what you need out of `Homebrew` so users can go make amazing things and change the world. If that goal is achieved for at least one person, then the time spent making this document is time well spent.

Enjoy everyone, and I look forward to seeing the document evolve.

This is the command I run to get the PDF to look the way it does with `pandoc`:

~~~~~~~~~~
    pandoc -s -S -o Homebrew\ for\ OS\ X.pdf Homebrew\ for\ OS\ X.md
~~~~~~~~~~

The main thing to note is that there is not --toc input flag because I hand that myself in the markdown document so that the title page can have a pagebreak before the table of contents gets entered in. Nitpicky, I know, but it works and make it look the way I intended so that's how I'm leaving it. :)

Shameless Self Promotion
=====================

Initial document, v1.0, written by Matthew Ibarra
https://github.com/pengii23
