This repository contains the [markdown code](https://guides.github.com/features/mastering-markdown/) of the EpiTools wiki website.

To generate the website we use the [MkDocs](https://www.mkdocs.org) site generator, please [install](https://www.mkdocs.org/#installation) this first if you wish to edit the website content.

To make a simple change to the website:

1. modify the desired markdown files in the `source` directory using the Github edit functionality
2. clone the repository `$ git clone https://github.com/epitools/wiki.git` or update `$ git pull` on your machine
3. (optional) preview changes with `$ mkdocs serve`
4. upload updated website with `$ mkdocs gh-deploy`

For more complex changes, we recommend editing and committing the files on your machine (i.e. also step 1).
