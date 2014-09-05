## Development stack

### Primary development stack

These are fundamental development tools that I pay the most attention to.

- [Amazon Simple Storage Service (Amazon S3)](http://aws.amazon.com/s3/) - "Amazon S3 is storage for the Internet."
- [Apache]()
- [assemble](http://assemble.io/)
- [backbone](http://backbonejs.org/) 1.1.2 - "Backbone.js gives structure to web applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing API over a RESTful JSON interface."
- [bash](http://www.gnu.org/software/bash/manual/bashref.html) 4.2.24 - shell.
- [bootstrap](http://getbootstrap.com/) 3.1.1 - "Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web."
	- Version 3.2.0 is available.
	- Some of 3E Enterprise's legacy code uses version 2.x.
- [bower]() 1.3.8 -
- [celery]()
- [CentOS](http://www.centos.org/) 5.9 - 
- [Coffeescript](https://www.npmjs.org/package/coffee-script) 1.7.1 - "A little language that compiles into JavaScript."
- [cPanel/WHM](http://cpanel.net/) [Changelog](https://documentation.cpanel.net/display/ALD/Change+Logs) 11.44.1b17 - 
- [git](http://git-scm.com/) 2.1.0 - "Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency." 
- [heroku toolbelt](https://toolbelt.heroku.com/) 3.8.2 (NOT PINNED) - packages up git, foreman, and the heroku command line interface.
- [homebrew](http://brew.sh/) 0.9.5 - "The missing package manager for OS X."
- [homebrew-cask](http://caskroom.io/) 0.39.3 - "Homebrew Cask extends Homebrew and brings its elegance, simplicity, and speed to OS X applications and large binaries alike."
- [javascript](http://en.wikipedia.org/wiki/Javascript)
- [jquery](http://jquery.com/) 1.10.2 - "jQuery is a fast, small, and feature-rich JavaScript library."
	- Version 1.11.1 and 2.1.1 are available.
- [marionette](http://marionettejs.com/) 1.7.4 - "Backbone.Marionette is a composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications."
- [node](http://nodejs.org/) 0.10.28 - Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications.  Note that npm comes with node now.
- [OS X]()
- [PostgreSQL](http://www.postgresql.org/) 9.3.3 - Database.
- [puppet](http://puppetlabs.com/) - "Open source Puppet is a flexible, customizable framework available under the Apache 2.0 license designed to help system administrators automate the many repetitive tasks they regularly perform."
- [python](http://packages.ubuntu.com/precise-updates/python) 2.7.3-0ubuntu2.2 - interactive high-level object-oriented language (default version).  This version is used as the base python for the development environment.
- [python](https://www.python.org/) 2.7.3/2.7.8 - interactive high-level object-oriented language.  Version 2.7.3 is typically used in development VMs based on Ubuntu 12.04.  Version 2.7.8 is the version typically used as a runtime.
- [underscore](http://underscorejs.org/) 1.6.0 - "Underscore is a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects."
- [ubuntu](http://www.ubuntu.com/) 14.04 as desktop and 12.04 as virtual machine.
- [vagrant](https://github.com/caskroom/homebrew-cask/blob/master/Casks/vagrant.rb) 1.6.3 [Change log](https://github.com/mitchellh/vagrant/blob/master/CHANGELOG.md) - used to manage development environment configuration.
- [vagrant-librarian-puppet](https://github.com/mhahn/vagrant-librarian-puppet) 0.7.1 - A Vagrant plugin to install Puppet modules using Librarian-Puppet.
- [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) 0.10.0 - automatically keeps VirtualBox Guest Additions up to date.
- [VirtualBox](https://github.com/caskroom/homebrew-cask/blob/master/Casks/virtualbox.rb) 4.3.12 [Changelog](https://www.virtualbox.org/wiki/Changelog) 4.3.12-93733 - used to host development environment.
- [yoeman](http://yeoman.io/) 1.2.1 - Use development tools at [webcore](https://github.com/ErikEvenson/webcore).

### Secondary development stack

Frequently used secondary tools.

- [augeas](http://augeas.net/) 1.1.0 - "Augeas is a configuration editing tool."
- [backbone.paginator](https://github.com/backbone-paginator/backbone.paginator) 2.0.2 - "A pageable, drop-in replacement for Backbone.Collection called Backbone.PageableCollection."
- [backbone.picky](https://github.com/derickbailey/backbone.picky) 0.2.0 - "Selectable entities as mixins for Backbone.Model and Backbone.Collection!"
- [bison](http://packages.ubuntu.com/precise/bison) 1:2.5.dfsg-2.1 - YACC-compatible parser generator
- [bootstrap3-datetimepicker](http://eonasdan.github.io/bootstrap-datetimepicker/) 3.0.0 - "Date/time picker widget for Twitter Bootstrap v3."
- [build-essential](http://packages.ubuntu.com/precise-updates/build-essential) 11.5ubuntu2.1 - Informational list of build-essential packages.
- [curl](http://packages.ubuntu.com/precise/curl) 7.22.0-3ubuntu4.8 - Get a file from an HTTP, HTTPS or FTP server.
- [flex](http://packages.ubuntu.com/precise/flex) 2.5.35-10ubuntu3 - A fast lexical analyzer generator.
- [ghostscript](http://packages.ubuntu.com/precise-updates/ghostscript) 9.05~dfsg-0ubuntu4.2 - an interpreter for the PostScript language and for PDF.  There may be a version pre-installed on heroku that is shadowing this version.
- [json2](https://github.com/douglascrockford/JSON-js) * - "JSON is a light-weight, language independent, data interchange format."
- [libbz2-dev](http://packages.ubuntu.com/precise/libbz2-dev) 1.0.6-1 - high-quality block-sorting file compressor library - development.
- [libjpeg-dev](http://packages.ubuntu.com/precise/libjpeg-dev) 8c-2ubuntu7 - Independent JPEG Group's JPEG runtime library.
- [libmemcached-dev](http://packages.ubuntu.com/precise/libmemcached-dev) 0.44-1.1build1 - Development files for libmemcached.
- [libncurses5-dev](http://packages.ubuntu.com/precise/libncurses5-dev) 5.9-4 - developer's libraries for ncurses.
- [memcached](http://packages.ubuntu.com/precise-updates/memcached) 1.4.13-0ubuntu2.1 - A high-performance memory object caching system.
- [mercurial](http://packages.ubuntu.com/precise/mercurial) 2.0.2-1ubuntu1 - easy-to-use, scalable distributed version control system.
- [python-dev](http://packages.ubuntu.com/precise-updates/python-dev) 2.7.3-0ubuntu2.2 - header files and a static library for Python (default).
- [python-pip](http://packages.ubuntu.com/precise/python-pip) 1.0-1build1 - alternative Python package installer
- [python-setuptools](http://packages.ubuntu.com/precise/python-setuptools) 0.6.24-1ubuntu1 - Python Distutils Enhancements (setuptools compatibility).
- [python-software-properties](http://packages.ubuntu.com/precise/python-software-properties) 0.82.7.7 - Manage the repositories that you install software from.  This software provides an abstraction of the used apt repositories.  It allows you to easily manage your distribution and independent software vendor software sources.
- [redis-server](http://packages.ubuntu.com/precise/redis-server) 2:2.2.12-1build1 - Persistent key-value database with network interface.
- [SASS](https://rubygems.org/gems/sass) 3.3.8 - CSS extension language.
- [tesseract](http://packages.ubuntu.com/precise/tesseract-ocr) 3.02.01-2 - OCR engine.
