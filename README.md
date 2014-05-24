# Marked 2 App Puppet Module for Boxen

**[Marked](http://marked2app.com/)** is a previewer for Markdown files. Use it with your favorite text editor and it updates every time you save. With robust features for previewing, reviewing and exporting beautiful documents, you can work in plain text while reveling in rich formatting.


[![Build Status](https://travis-ci.org/boxen/puppet-marked2.svg?branch=master)](https://travis-ci.org/boxen/puppet-marked2)

## Usage

```puppet
include marked2
```

## Required Puppet Modules

* `boxen`

## Development

Set `GITHUB_API_TOKEN` in your shell with a [Github oAuth Token](https://help.github.com/articles/creating-an-oauth-token-for-command-line-use) to raise your API rate limit. You can get some work done without it, but you're less likely to encounter errors like `Unable to find module 'boxen/puppet-boxen' on https://github.com`.

Then write some code. Run `script/cibuild` to test it. Check the `script`
directory for other useful tools.
