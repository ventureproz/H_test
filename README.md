# Venture Proz New Release

[![Build Status][ventureproz-image]][ventureproz-url] [![dependency status][dep-image]][dep-url]

This repository contains the Homestead Release of the [ventureproz.com](https://ventureproz.com/) website.


![Screenshot]("Screenshot")

## Prerequisite
* node
* npm

## Installation
Make sure you have node.js and npm installed.

Clone the repository and install the dependencies

```bash
git clone https://github.com/ventureproz
cd ventureproz-com
npm install
npm install -g grunt-cli
```

## Build static resources

```bash
grunt
```

## Run

```bash
npm start
```

see the interface at http://localhost:3000

## Publish latest master to GitHub Pages

```
git checkout gh-pages
git merge master
grunt build
git commit -am "Updated build"
git push origin gh-pages
```


