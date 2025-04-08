# csx

Online book for the X Class

# Setup
Make sure you have **Python 3** and **Homebrew** installed. Run the following:

    brew install sphinx-doc

# Edit
Only edit the source folder! (If you edit the docs folder your changes will be overwritten next time you build.)

For example, to update the Riemann Sums page edit source/assignments/2-riemann/riemann.rst.

Use Sphinx's mark-up syntax. (Look it up or use the existing files as examples.)

Build using one of the methods below. Check locally that the site looks correct before you add/commit/push to git to make it go live.

# Build - Method 1
From the project directory, run

    sphinx-build source/ docs/

# Build - Method 2
Optionally, if you have make installed, run

    make html
