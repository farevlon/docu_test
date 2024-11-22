# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Installation

* `pip install mkdocs` - Install mkdocs. 
* `pip install mkdocs-material` - Install mkdocs-material for the fonts. 


## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

## Hosting the site

To host the site there are different alternatives:

* Public Repo: 
    * GitHub Pages (free)  
* Private: 
    * Another hosting provider (e.g., Netifly)
    * GitHub Enterprise 
    
## Hosting the site with GitHub Pages

(Having the Repo initialized/cloned)
Using the terminal create a new documentation project:
`mkdocs new test_docu`

Mkdocs will create: 

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.


Deploy the site in GitHub Pages using the following command in the terminal:
`mkdocs gh-deploy`


## Alternatives

* Public: 
    * Readthedocs (free)

