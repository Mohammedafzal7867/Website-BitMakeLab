# Bitmake documentation website

Contains all the latest Bitmake resources.

Site is build using Material for MkDocs.  This allows the content to be written in markdown, from which MkDocs will build HTML.


Material for MkDocs can be found here: https://squidfunk.github.io/mkdocs-material/

To install it you need Python and then run  :

    pip install mkdocs-material

It also uses the Macros plugin: https://mkdocs-macros-plugin.readthedocs.io

To install it:

    pip install mkdocs-macros-plugin

# Test, debug
You can test and debug the site:

    mkdocs serve --livereload

# Build

When ready, build the site:

    mkdocs build

To clear out all files before building use:

    mkdocs build --clean
    
This creates the site subdirectory, which can be deployed to the server.
