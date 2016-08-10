# Bible for Desktop
[![Build Status](https://travis-ci.org/jiahaog/nativefier.svg?branch=development)](https://travis-ci.org/jiahaog/nativefier)
[![Code Climate](https://codeclimate.com/github/jiahaog/nativefier/badges/gpa.svg)](https://codeclimate.com/github/jiahaog/nativefier)
[![npm version](https://badge.fury.io/js/nativefier.svg)](https://www.npmjs.com/package/nativefier)
[![Dependency Status](https://david-dm.org/jiahaog/nativefier.svg)](https://david-dm.org/jiahaog/nativefier)

Electron based app for reading the Bible.com website

# About
I wanted a way to read the Bible from Bible.com without always going to the browser. I really like the site that Bible.com has and all the features and tools they provide to their users. 

My goal is to help bring this to the desktop for more people to use. 

# Where to go from here? 
The creation of the apps is Based off [Jia Hao](https://github.com/jiahaog)'s project [Nativefier](https://github.com/jiahaog/nativefier). 

## So how do I build the app...
```bash
$ nativefier google.com
```

## Installation

With [Node.js](https://nodejs.org/) `>=4` installed,

```bash
# for use from the command line
$ npm install nativefier -g
```

## For this app
## Installation

With [Node.js](https://nodejs.org/) `>=4` installed,

```bash
# for use from the command line
$ npm install nativefier -g
$ nativefier -n "Bible.com for Desktop" -p win32 -a ia32 "https://www.bible.com/bible/59/gen.1"
$ nativefier -n "Bible.com for Desktop" -p win32 -a x64 "https://www.bible.com/bible/59/gen.1"
$ nativefier -n "Bible.com for Desktop" -p osx "https://www.bible.com/bible/59/gen.1"
$ nativefier -n "Bible.com for Desktop" -p linux "https://www.bible.com/bible/59/gen.1"
```

After this is will create a folder for the app and you are good to go. 

# Releases
If you do not want to go through this if it seems like a lot of work, I have updated the [releases](#) area for you. 
- [Windows 32 bit](#)
- [Windows 64-bit](#)
- [Linux](#)
- [macOS](#)
