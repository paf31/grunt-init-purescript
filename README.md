# Warning

This repository is outdated and no longer supported. For getting started with new PureScript projects, try the [`pulp`](https://github.com/bodil/pulp) tool instead.

# grunt-init-purescript

A `grunt-init` template for creating new PureScript projects.

## Usage

Clone this repo into `~/.grunt-init/purescript/`, then run with `grunt-init purescript`.

Install Grunt, `grunt-init`, `grunt-cli`, and Bower if you haven't already:

    npm install -g grunt grunt-init grunt-cli bower
 
Install the PureScript project template for use with `grunt-init`:

    mkdir ~/.grunt-init
    git clone https://github.com/purescript-contrib/grunt-init-purescript.git \
        ~/.grunt-init/purescript
 
Create a PureScript project from the template and fetch its dependencies:

    mkdir /path/to/your_ps_project
    cd /path/to/your_ps_project
    grunt-init purescript
 
Install your project's dependencies:

    npm install
    bower update
 
Build your project and hack away:

    grunt
