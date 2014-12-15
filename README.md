# emacs-sos

StackOverflow Search (SOS) mode for Emacs.

## Usage

Invoked with the `sos` command

    M-x sos

Enter your query and search results are displayed with their excerpts in an org-mode buffer:

    M-x sos RET why is emacs so awesome? RET

In the search results buffer, if you have a question at point, you can use `sos-answer` to retrieve all answers for that question. *You can also press "A" on the question to run `sos-answer`*.

    M-X sos-answer

## How Does It Look

![emacs sos search results screenshot](https://github.com/omouse/emacs-sos/raw/master/emacs-sos-screenshot.png)

## Copyright and License

Licensed under the GNU GPL v3, see [LICENSE](./LICENSE) for full text of license.

Copyright (C) 2014-2015 Rudolf Olah <omouse@gmail.com>
