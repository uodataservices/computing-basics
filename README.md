# Computing Fundamentals

If nobody has told you, it's not obvious that the tab key autocompletes on the
command line... or even how to get there.

Most people's experience of computing today is through user interfaces that —
for convenience — conceal a lot of the underlying tech. It's possible to be
using sophisticated apps on tablets today without ever interacting with a file
system.

So this is a collection of "superbasics" for students to discover some of the
the really low-level things nobody told them about.

* learn shortcuts!
* use tab completion!
* never put spaces in your filenames!

:-)

And yes, before we forked this repository at least one of us on a Mac bounced on the left-arrow key
because we didn't know about the Alt-click position-on-command-line trick in
Terminal ;-)

## About

Many students come to college with little or no experience using their computers on a system level. That's OK: you didn't need to. Until now.

Specifically, search-based computer interfaces mean that some students leave every file and executable in their downloads folder. And using browser-based learning means some others have learned to program entirely on the web. It's worked so far, but there comes a time when students need to understand more, whether to more easily upload homework to Canvas, or to load data for analysis into an R or Python program.

This site is a copy of the [CompSci Superbasics site](https://github.com/davewhiteland/compsci-superbasics) adapted to the needs of University of Oregon students and faculty by UO Libraries.

## Jekyll

> See DEVELOPMENT.md if you're going to be doing any work — there's a gotcha
> on the way the topics and pages are ordered.

The site uses Jekyll's containers to manage a collection of topic-pages that
are previous-next linked together.

See `_config.yml`'s `collections` — if you add a new page, add it to the
`order` in there: the navigation links are constructed from those.

Add new topics to the `topics` collection.

The CSS was originally based on the
[block-log theme](https://jekyllthemes.io/theme/block-log)
by [Anandu B Ajith](https://github.com/anandubajith)
and the responsive hamburger is implemented using the
label-of-hidden-checkbox CSS-only trick inspired by
[Code Boxx'a css-ham-menu](https://code-boxx.com/). 

