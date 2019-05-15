[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](http://www.repostatus.org/badges/latest/active.svg)](http://www.repostatus.org/#active)
[![Build Status](https://travis-ci.org/coderbot92/frontend-boilerplate.svg?branch=master)](https://travis-ci.org/coderbot92/frontend-boilerplate)
[![Repo Type: Boilerplate](https://img.shields.io/badge/repo%20type-boilerplate-yellowgreen.svg)](#boilerplate-for-frontend-development)
[![HitCount](http://hits.dwyl.io/coderbot92/frontend-boilerplate.svg)](http://hits.dwyl.io/coderbot92/frontend-boilerplate)
[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)
[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/coderbot92/frontend-boilerplate/blob/master/LICENCE)

# Boilerplate for Frontend Development

This is the repo containing boilerplate folder settings and configuration files for frontend development.

It contains the source code of a blog project as an example.

Terminal settings such as .bash_profile, .gitconfig and associated files are also present to setup a productive development environment. 

## Table of Contents

* [Instructions](#instructions)
* [Code Editor Consistency](#code-editor-consistency)
* [MacOS Apps](#macos-apps)
* [Terminal Settings](#terminal-settings)

## Instructions

* Clone the project
* Open the project folder in VS Code

## Git Configurations
* The git configurations are present in the file .gitconfig in the repo root
* Change the configurations according to your needs
* After cloning repo the following command must be run to incorporate these configs locally:
```bash
$ git config --local include.path ../.gitconfig
```
* To verify and see the git configurations for current repository:
```bash
$ git config --list
```
* To see the list of remotes and see the details of a particular remote e.g. to see which branches are tracked:
```bash
$ git remote -v
$ git remote show origin
```

## Code Editor Consistency

- [EditorConfig](http://editorconfig.org/) is used for managing consistent editor configurations across different editors that can be used in project.

## MacOS Apps
- [Alfred](https://www.alfredapp.com/)
- [Dash](https://kapeli.com/dash)
- [AppCleaner](https://freemacsoft.net/appcleaner/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [PyCharm IDE](https://www.jetbrains.com/pycharm/)
- [Anaconda](https://www.anaconda.com/)
- [GitHub Desktop](https://desktop.github.com/)
- [Dropbox](https://www.dropbox.com/downloading)
- [Chrome](https://www.google.com/chrome/)
- [VLC Player](https://www.videolan.org/vlc/download-macosx.html)

## Terminal Settings

- Install [homebrew](https://brew.sh/) which is a simple package manager for macOS just like [apt](https://en.wikipedia.org/wiki/APT_(Debian)) in Ubuntu (Linux)

- Use [bash](https://www.gnu.org/software/bash/) shell for command processing because it is widely supported

- Install [terminal-snazzy](https://github.com/sindresorhus/terminal-snazzy) theme for better looking terminal

- Copy and paste all the files (which include .bash_profile and .gitconfig) in the terminal folder to your home directory

- Install [tldr](https://github.com/tldr-pages/tldr) for simple man pages with examples

## Setting up Project

```bash
# to install all dependencies of package.json (linters etc.)
$ npm install

# to install any new npm package and add to dependencies in package.json
$ npm install <package-name> --save

# to see installed npm packages in node_modules folder
$ npm list --depth=0

# to see if any npm package has newer version
$ npm outdated

# to update all packages to latest
$ npm update
```

## Style Guide

[Udacity Frontend Style Guide](https://udacity.github.io/frontend-nanodegree-styleguide/index.html)

| Construct                  | Naming Rule        |
|:--------------------------:|:------------------:|
| function name              | lowerCamelCase     |
| variables, function params | lowerCamelCase     |
| class data member          | lowerCamelCase     |
|                            |                    |
| class name (and file name) | UpperCamelCase     |
| enum name                  | UpperCamelCase     |
|                            |                    |
| constants                  | UPPER_SNAKE_CASE   |
| enum variables             | UPPER_SNAKE_CASE   |
|                            |                    |
| all html (tags, attributes, attributes values) | lowercase |
| html tags class and id names                   | lowercase-with-dashes |
| css rules                                      | lowercase |

## Git Commit Style

**feat**: a new feature <br/>
**fix**: a bug fix <br/>
**docs**: changes to documentation <br/>
**style**: formatting, style corrections, no code change <br/>
**refactor**: refactoring production code <br/>
**test**: adding tests, refactoring test; no production code change <br/>
**chore**: updating build tasks, no production code change <br/>

