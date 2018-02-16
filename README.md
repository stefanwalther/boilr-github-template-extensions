# boilr-github-template-extensions

> Boilr templates for creating GithHub templates for Qlik Sense visualization extensions.

---

## Purpose
Boilr templates for creating GithHub templates for Qlik Sense visualization extensions.

The following files are generated:

```
.
└── .github
    ├── ISSUE_TEMPLATE.md
    └── PULL_REQUEST_TEMPLATE.md

1 directory, 2 files

```

## Installation
Install [boilr](https://github.com/tmrts/boilr) first. 

Then use 

```
$ boilr download stefanwalther/boilr-github-template-extensions <template-tag>
```

e.g.
```
$ boilr download stefanwalther/boilr-github-template-extensions boilr-github-template-extensions
```

## Usage
### Download the template

```
$ boilr template download stefanwalther/boilr-github-template-extensions <template-tag>
```

### Fork, modify locally and save it

```
$ git clone stefanwalther/boilr-github-template-extensions
```

cd into it, then

```
$ boilr template save $(PWD) <template-tag>

# e.g. 
$ boilr template save $(PWD) boilr-github-template-extensions
```

if you have for force the local updates, use

```
$ boilr template save $(PWD) <template-tag> -f
```

### Use it

```
$ boilr template use boilr-github-template-extensions .
```

### Get all templates

Get a list of all - locally installed - templates:

```
$ boilr template list
```

## About

### Related projects
Some related projects:

 

### Author
**Stefan Walther**

* [twitter](http://twitter.com/waltherstefan)  
* [github.com/stefanwalther](http://github.com/stefanwalther) 
* [LinkedIn](https://www.linkedin.com/in/stefanwalther/) 
* [qliksite.io](http://qliksite.io)

### License
MIT

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.6.0, on February 16, 2018._

