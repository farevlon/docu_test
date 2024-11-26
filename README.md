# Using MkDocs for HWS4.0 Documentation


## 1- Installation and Information

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

### Installation

* `pip install mkdocs` - Install mkdocs. 
* `pip install mkdocs-material` - Install mkdocs-material for the template fonts. 


### Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

### Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.

### Hosting the site

To host the site there are different alternatives:

* Public Repo: 
    * GitHub Pages (free)  
* Private: 
    * Another hosting provider (e.g., Netifly, AWS) (cost)
    * GitHub Enterprise (cost)

## Alternatives

* Public: 
    * Readthedocs (free)
    


## 2- Example for a documentation site

### Creating a project 

(Having the Repo initialized/cloned)
Using the terminal create a new documentation project:

`mkdocs new test_docu`



Mkdocs will create: 

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.

Add the folders and md files, so the new folder structure is:

    mkdocs.yml    # The configuration file.
    docs/
        measurement/
            measurement.md
        ui/
            ui.md
        index.md  # The documentation homepage.

### Testing the site locally 

Use the command:
`mkdocs serve`

The site will be displayed as localhost: http://127.0.0.1:8000/

### Deploy and hosting the site into GitHub Pages with a public Repository
Deploy the site in GitHub Pages using the following command in the terminal:
`mkdocs gh-deploy`

https://farevlon.github.io/docu_test/


