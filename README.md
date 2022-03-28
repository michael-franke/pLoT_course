# The probabilistic Language of Thought: A course

Materials for a course on the (probabilistic) Language of Thought, covering the topic from a theoretical and practical point of view.

This repo contains a jupyter-book. There are two intended uses:
1. Look at it as a book. Available at [this page](https://thelogicalgrammar.github.io/pLoT_course).
1. Use the chapter notebooks in jupyter colab. Each notebook installs the required packages (i.e. Piantadosi's LOTlib3). The chapters (notebooks) can be imported directly from the repo (use link: https://github.com/thelogicalgrammar/pLoT_course) into colab.

> **_TECHNICAL NOTE:_**  Suppose you wanted to host your own version of the book that you edit. Then, you need to:
> 1. Fork the repository and clone it locally.
> 1. Make the changes you want to the files.
> 1. cd from root to `book`.
> 1. Build the book with jupyter-book. This updates the book in `_build'.
> 1. Commit and push into your fork. Note that at this point you still have not hosted/changed the book's website.
> 1. Update the ghp-import branch (which hosts the actual book) with `ghp-import -n -p -f _build/html`.
> 1. After a few minutes, you should be able to see your version of the book!