# Pica
Pica is a front end asset library developed by the TKML studio. Built off of
ThoughtBot's bourbon, neat, and bitters for a base.

## Project Dependencies

Recommend running [ThoughtBot Laptop Script](http://github.com/thoughtbot/laptop) for environment set up

* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Foreman gem for serving Rails apps locally
* Heroku Config plugin for local ENV variables
* Heroku Toolbelt for interacting with the Heroku API
* Hub gem for interacting with the GitHub API
* Homebrew for managing operating system libraries (OS X only)
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Rbenv for managing versions of the Ruby programming language
* Redis for storing key-value data
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output


[NVM](https://github.com/creationix/nvm) for node package managment (Similar to RVM)

## Project Setup
This project utilizes Playbook, reference Playbook's [setup guide](https://github.com/centresource/generator-playbook#get-started).

1. Clone this repository
2. Install ruby if RVM says it is missing `rvm install ruby-2.1.0`
3. Set nvm package `nvm use v0.10.25` at time of writing this.
4. Run `npm install -g yo`
5. `npm install`
6. `bower install`
7. `bundle install`

### Grunt Tasks
- Check, test & build for production: `grunt`
- Serve the site locally: `grunt serve`
- Deploy to production: `grunt deploy`
- Check source: `grunt check`
- Run tests: `grunt test`
- Build for production: `grunt build`

