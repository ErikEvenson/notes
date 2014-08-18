# Personal technology stack

Versions are the currently used versions.

## Development stack

### Primary development stack

These are fundamental development tools that I pay the most attention to.  Installation means are typical.

- [Amazon Simple Storage Service (Amazon S3)](http://aws.amazon.com/s3/) - "Amazon S3 is storage for the Internet."
	- Online service.
- [backbone](http://backbonejs.org/) 1.1.2 - "Backbone.js gives structure to web applications by providing models with key-value binding and custom events, collections with a rich API of enumerable functions, views with declarative event handling, and connects it all to your existing API over a RESTful JSON interface."
	- Bower-installed.
- [bootstrap](http://getbootstrap.com/) 3.1.1 - "Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web."
	- Bower-installed.
	- Version 3.2.0 is available.
	- Some of 3E Enterprise's legacy code uses version 2.x.
- [bower]() 1.3.8 -
- [Coffeescript](https://www.npmjs.org/package/coffee-script) 1.7.1 - "A little language that compiles into JavaScript."
	- npm-installed.
- [git](http://git-scm.com/) 2.1.0 - "Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency." 
	- Installed via homebrew or apt-get depending on platform.
- [heroku toolbelt](https://toolbelt.heroku.com/) 3.8.2 (NOT PINNED) - packages up git, foreman, and the heroku command line interface.
	- Manually installed.
- [javascript](http://en.wikipedia.org/wiki/Javascript)
- [jquery](http://jquery.com/) 1.10.2 - "jQuery is a fast, small, and feature-rich JavaScript library."
	- Bower-installed.
	- Version 1.11.1 and 2.1.1 are available.
- [marionette](http://marionettejs.com/) 1.7.4 - "Backbone.Marionette is a composite application library for Backbone.js that aims to simplify the construction of large scale JavaScript applications."
	- bower-installed.
- [node](http://nodejs.org/) 0.10.28 - Node.js is a platform built on Chrome's JavaScript runtime for easily building fast, scalable network applications.  Note that npm comes with node now.
	- Manually installed.
- [OS X]()
- [PostgreSQL](http://www.postgresql.org/) 9.3.3 - Database.
	- Manually installed.
- [python](http://packages.ubuntu.com/precise-updates/python) 2.7.3-0ubuntu2.2 - interactive high-level object-oriented language (default version).  This version is used as the base python for the development environment.
	- apt-get and manually-install.
- [python](https://www.python.org/) 2.7.3/2.7.8 - interactive high-level object-oriented language.  Version 2.7.3 is typically used in development VMs based on Ubuntu 12.04.  Version 2.7.8 is the version typically used as a runtime.
	- Manually installed.
- [underscore](http://underscorejs.org/) 1.6.0 - "Underscore is a JavaScript library that provides a whole mess of useful functional programming helpers without extending any built-in objects."
	- bower-installed.
- [ubuntu](http://www.ubuntu.com/) 14.04 as desktop and 12.04 as virtual machine.
	- bower-installed.
- [vagrant]()
- [yoeman]()
	- npm-installed.

### Secondary development stack

Frequently used secondary tools.

- [backbone.paginator](https://github.com/backbone-paginator/backbone.paginator) 2.0.2 - "A pageable, drop-in replacement for Backbone.Collection called Backbone.PageableCollection."
	- bower-installed.
- [backbone.picky](https://github.com/derickbailey/backbone.picky) 0.2.0 - "Selectable entities as mixins for Backbone.Model and Backbone.Collection!"
	- bower-installed.
- [bison](http://packages.ubuntu.com/precise/bison) 1:2.5.dfsg-2.1 - YACC-compatible parser generator
	- apt-get-installed.
- [bootstrap3-datetimepicker](http://eonasdan.github.io/bootstrap-datetimepicker/) 3.0.0 - "Date/time picker widget for Twitter Bootstrap v3."
	- bower-installed.
- [build-essential](http://packages.ubuntu.com/precise-updates/build-essential) 11.5ubuntu2.1 - Informational list of build-essential packages.
	- apt-get-installed.
- [curl](http://packages.ubuntu.com/precise/curl) 7.22.0-3ubuntu4.8 - Get a file from an HTTP, HTTPS or FTP server.
	- apt-get-installed.
- [flex](http://packages.ubuntu.com/precise/flex) 2.5.35-10ubuntu3 - A fast lexical analyzer generator.
	- apt-get-installed.
- [ghostscript](http://packages.ubuntu.com/precise-updates/ghostscript) 9.05~dfsg-0ubuntu4.2 - an interpreter for the PostScript language and for PDF.  There may be a version pre-installed on heroku that is shadowing this version.
	- apt-get-installed.
- [json2](https://github.com/douglascrockford/JSON-js) * - "JSON is a light-weight, language independent, data interchange format."
	- bower-installed.
- [libbz2-dev](http://packages.ubuntu.com/precise/libbz2-dev) 1.0.6-1 - high-quality block-sorting file compressor library - development.
	- apt-get-installed.
- [libjpeg-dev](http://packages.ubuntu.com/precise/libjpeg-dev) 8c-2ubuntu7 - Independent JPEG Group's JPEG runtime library.
	- apt-get-installed.
- [libmemcached-dev](http://packages.ubuntu.com/precise/libmemcached-dev) 0.44-1.1build1 - Development files for libmemcached.
	- apt-get-installed.
- [libncurses5-dev](http://packages.ubuntu.com/precise/libncurses5-dev) 5.9-4 - developer's libraries for ncurses.
	- apt-get-installed.
- [memcached](http://packages.ubuntu.com/precise-updates/memcached) 1.4.13-0ubuntu2.1 - A high-performance memory object caching system.
	- apt-get-installed.
- [mercurial](http://packages.ubuntu.com/precise/mercurial) 2.0.2-1ubuntu1 - easy-to-use, scalable distributed version control system.
	- apt-get-installed.
- [python-dev](http://packages.ubuntu.com/precise-updates/python-dev) 2.7.3-0ubuntu2.2 - header files and a static library for Python (default).
- [python-pip](http://packages.ubuntu.com/precise/python-pip) 1.0-1build1 - alternative Python package installer
	- apt-get-installed.
- [python-setuptools](http://packages.ubuntu.com/precise/python-setuptools) 0.6.24-1ubuntu1 - Python Distutils Enhancements (setuptools compatibility).
	- apt-get-installed.
- [python-software-properties](http://packages.ubuntu.com/precise/python-software-properties) 0.82.7.7 - Manage the repositories that you install software from.  This software provides an abstraction of the used apt repositories.  It allows you to easily manage your distribution and independent software vendor software sources.
	- apt-get-installed.
- [redis-server](http://packages.ubuntu.com/precise/redis-server) 2:2.2.12-1build1 - Persistent key-value database with network interface.
	- apt-get-installed.
- [SASS](https://rubygems.org/gems/sass) 3.3.8 - CSS extension language.
	- gem-installed.
- [tesseract](http://packages.ubuntu.com/precise/tesseract-ocr) 3.02.01-2 - OCR engine.
	- apt-get-installed.
- [Vagrant](https://github.com/caskroom/homebrew-cask/blob/master/Casks/vagrant.rb) 1.6.3 [Change log](https://github.com/mitchellh/vagrant/blob/master/CHANGELOG.md) - used to manage development environment configuration.
	- homebrew-cask-installed.
- [VirtualBox](https://github.com/caskroom/homebrew-cask/blob/master/Casks/virtualbox.rb) 4.3.12 [Changelog](https://www.virtualbox.org/wiki/Changelog) 4.3.12-93733 - used to host development environment.
	- homebrew-cask-installed.

### TO BE ADDED

"backbone.syphon": "0.4.1",
"backgrid": "0.3.5",
"backgrid-select-all": "0.3.5",
"backgrid-paginator": "1730e0231c51d4606945a3d3492213ec37b9dcdc",
"backgrid-filter": "0.3.5",
"spin.js": "2.0.1",
"backgrid-moment-cell": "0.3.5",
"highcharts-release": "4.0.1",
"numeral": "1.5.3",
"moment": "2.5.1",

- [bower](https://www.npmjs.org/package/bower) 1.3.5 - front end package management.
- [coffeegulp](https://www.npmjs.org/package/coffeegulp) 0.0.4 - A tiny wrapper around Gulp to run your gulpfile.coffee.
- [Coffeescript](https://www.npmjs.org/package/coffee-script) 1.7.1 - a little language that compiles into JavaScript.
- [npm]() 1.4.14 -
- [npm-check-updates](https://www.npmjs.org/package/npm-check-updates) 1.2.0 - Find newer versions of dependencies than what your package.json allows.
- [require.js](https://www.npmjs.org/package/requirejs) 2.1.14 - JavaScript file and module loader.
- [yuglify](https://www.npmjs.org/package/yuglify) 0.1.4 - cli wrapper for uglify and cssmin used by YUI.


- [gulp](http://gulpjs.com/) 3.8.0 - The streaming build system.
  [gulp-coffeelint]() 0.3.3 -
  [gulp-shell]() 0.2.5 -


- [mercurial](https://pypi.python.org/pypi/Mercurial) 3.0.1 - Fast, easy to use, distributed revision control tool for software developers.

- [virtualenv](https://pypi.python.org/pypi/virtualenv/1.11.6) 1.11.6 - A tool to create isolated Python environments.
- [virtualenvwrapper](https://pypi.python.org/pypi/virtualenvwrapper) 4.3 - a set of extensions to Ian Bicking’s virtualenv tool.

Installed during testing:

- [coverage]
- [pylint]
- [nose-progressive](https://pypi.python.org/pypi/nose-progressive) 1.5.1
- [django-debug-toolbar]
- [django-snippetscream]

## vagrant-installed

Installed during provisioning:

- [pip](https://pip.pypa.io/en/latest/index.html) 1.5.6 - The PyPA recommended tool for installing and managing Python packages.

## vagrant-installed

- [hashicorp/precise64](https://vagrantcloud.com/hashicorp/precise64) 1.1.0 - A standard Ubuntu 12.04 LTS 64-bit box.
- [vagrant-vbguest](https://github.com/dotless-de/vagrant-vbguest) 0.10.0 - automatically keeps VirtualBox Guest Additions up to date.

  Derived:
- [Ubuntu 12.04 LTS (Precise Pangolin)](http://releases.ubuntu.com/12.04/) 12.04

## Services

- [Amazon Simple Storage Service (Amazon S3)](http://aws.amazon.com/s3/) - used for storing static content.  Part of Amazon Web Services.

=== OLD ===

## Back end

- [amqp](https://pypi.python.org/pypi/amqp) 1.4.5 - A Celery dependency
- [anyjson](https://pypi.python.org/pypi/anyjson) 0.3.3 - A Celery dependency.  JSON implementation library.
- [billiard](https://pypi.python.org/pypi/billiard) 3.3.0.17 - A Celery dependency.  Python multiprocessing fork with improvements and bugfixes.
- [boto](http://docs.pythonboto.org/en/latest/) 2.29.1 [Changelog](http://docs.pythonboto.org/en/latest/#release-notes) - A Python interface to Amazon Web Services.
- [botocore](https://github.com/boto/botocore) 0.46.0 - The low-level, core functionality of boto 3.
- [celery](http://www.celeryproject.org/) 3.1.11 - An asynchronous task queue/job queue based on distributed message passing.
- [coverage.py](http://nedbatchelder.com/code/coverage/) 3.7.1 - A tool for measuring code coverage of Python programs.
- [Django](https://www.djangoproject.com/) 1.6.5 - A web framework.
- [django-admin-bootstrapped](https://github.com/riccardo-forina/django-admin-bootstrapped) 1.6.4 - A Django admin theme using Twitter Bootstrap.
- [django-async-messages](https://github.com/codeinthehole/django-async-messages) 0.3 - Send asynchronous messages to users
- [django-braces](https://github.com/brack3t/django-braces) 1.4.0 - Reusable, generic mixins for Django.
- [django-countries](https://pypi.python.org/pypi/django-countries) 1.5 - Provides a country field for Django models.
- [django-crispy-forms](http://django-crispy-forms.readthedocs.org/en/latest/) 1.4.0 - a Django application that lets you easily build, customize and reuse forms using your favorite CSS framework, without writing template code and without having to take care of annoying details.
- [django-datatable-view](https://github.com/pivotal-energy-solutions/django-datatable-view) 0.5 3 - Yet another datatables implementation for Django.
- [django-dirtyfields](https://pypi.python.org/pypi/django-dirtyfields) 0.3 - Tracking dirty fields on a Django model instance.
- [django-heroku-memcacheify](https://github.com/rdegges/django-heroku-memcacheify) 0.5 - Automatic Django memcached configuration on Heroku.
- [django-localflavor](https://github.com/django/django-localflavor) 1.0 - Country-specific Django helpers, formerly of contrib fame (work in progress).
- [django-mailbox](https://readthedocs.org/projects/django-mailbox/) 3.0.3 - Import mail from POP3, IMAP, local mailboxes or directly from Postfix or Exim4 into your Django application automatically.
- [django-mathfilters](https://github.com/dbrgn/django-mathfilters) 0.1.3 - django-mathfilters provides a set of simple math filters for Django.
- [django-nose](https://github.com/jbalogh/django-nose) 1.2 - Django test runner using nose.
- [django-pipeline](https://github.com/cyberdelia/django-pipeline) 1.3.23 - Pipeline is an asset packaging library for Django.
- [django-profiles](https://bitbucket.org/ubernostrum/django-profiles) 0.2 - This is a fairly simple user-profile management application for Django, designed to make the management of site-specific user profiles as painless as possible.
- [django-pylibmc-sasl](https://pypi.python.org/pypi/django-pylibmc-sasl) 0.2.4- This package provides a memcached cache backend for Django using pylibmc.
- [django-registration-username-addition (forked)](https://bitbucket.org/eevenson/django-registration) - used to handle user registration.  This is a fork of [django-registration](https://bitbucket.org/ubernostrum/django-registration).  The fork adds the username to template contexts.  This is a fairly simple user-registration application for Django, designed to make allowing user signups as painless as possible.
- [django-smtp-ssl](https://github.com/bancek/django-smtp-ssl) 1.0 - SMTP SSL email backend for Django.
- [django-storages](http://django-storages.readthedocs.org/en/latest/) 1.1.8 (reviewed)- a collection of custom storage backends for Django.
- [django-tastypie](http://django-tastypie.readthedocs.org/en/latest/) 0.11.1 - Provides RESTful API services.
- [django-taggit](https://github.com/alex/django-taggit) 11.2 - Simple tagging for django.
- [django-widget-tweaks](https://pypi.python.org/pypi/django-widget-tweaks) 1.3 - Tweak the form field rendering in templates, not in python-level form definitions.
- [dj-database-url](https://github.com/kennethreitz/dj-database-url) 0.3.0 - Use Database URLs in your Django Application.
- [foreman](https://github.com/ddollar/foreman) 0.63.0 - Manage Procfile-based applications.
- [futures](https://pypi.python.org/pypi/futures) 2.1.6 - Backport of the concurrent.futures package from Python 3.2.
- [gunicorn](http://gunicorn.org/) 18.0 - a Python WSGI HTTP Server for UNIX.
- [Heroku](https://www.heroku.com/) - Cloud computing designed and built for developers.  API defined here: https://devcenter.heroku.com/articles/platform-api-reference.
- [heroku-buildpack-libraries](https://github.com/EATechnologies/heroku-buildpack-libraries) - a generic buildpack for compile and deploy libraries on heruku.
- [heroku-buildpack-multi](https://github.com/ddollar/heroku-buildpack-multi.git) - multibuildpack
- [heroku-buildpack-python](https://github.com/heroku/heroku-buildpack-python) - Python buildpack
- [heroku postgres](https://www.heroku.com/postgres)
- [heroku scheduler](https://addons.heroku.com/scheduler)
- [kombu](https://pypi.python.org/pypi/kombu) 3.0.16 - Messaging library for Python.  Stay away from versions prior to 3.0.16.
- [Logentries](https://logentries.com/) - Log management and analytics.
- [MemCachier](https://www.memcachier.com/) - Memcache.
- [memcached](http://memcached.org/) 1.4.13 - Distributed memory object caching system.
- [Nose](https://nose.readthedocs.org/en/latest/) 1.3.3 - Nicer testing for python.
- [PG Backups](https://addons.heroku.com/pgbackups)
- [pip](http://www.pip-installer.org/en/latest/) 1.5.6 - The PyPA recommended tool for installing and managing Python packages.
- [Pillow](http://python-pillow.github.io/) 2.4.0 [Changelog](https://github.com/python-pillow/Pillow/blob/master/CHANGES.rst) - The 'friendly' PIL fork.  Used in optical character recognition of documents.
- [psycopg2](https://pypi.python.org/pypi/psycopg2) 2.5.2 - Python-PostgreSQL Database Adapter.
- [PyExecJS](https://pypi.python.org/pypi/PyExecJS) 1.0.4 - Run JavaScript code from Python.
- [pylibmc](http://sendapatch.se/projects/pylibmc/) 1.3.0 [Changelog](https://github.com/lericson/pylibmc/blob/master/docs/changelog.rst) - Quick and small memcached client for Python.
- [Pylint](http://www.logilab.org/project/pylint) 1.2.1 - Linting for python code.
- [Python](http://www.python.org/) 2.7.4
- [python-dateutil](http://labix.org/python-dateutil) 2.2 - The dateutil module provides powerful extensions to the standard datetime module, available in Python 2.3+.
- [python-eco](https://github.com/ikeikeikeike/python-eco) 1.1.0rc3.1 - Python Eco is a bridge to the Eco (CoffeeScript Template) Compiler.
- [python-mimeparse](https://pypi.python.org/pypi/python-mimeparse) 0.1.4 - A module provides basic functions for parsing mime-type names and matching them against a list of media-ranges.
- [pytz](http://pythonhosted.org//pytz/) 2014.4 - World timezone definitions, modern and historical.
- [ReadBot](https://github.com/mwmeyer/readbot) 1.0 - used in optical character recognition of documents.
- [Redis](http://redis.io/) 2.2.12 - used as a message broker for celery.
- [Redis To Go](https://devcenter.heroku.com/articles/redistogo) - A key-value store similar to memcached, but non-volatile; it supports lists, hashes, sets, and ordered sets.
- [Respond](https://github.com/scottjehl/Respond) 1.1.0 - A fast & lightweight polyfill for min/max-width CSS3 Media Queries (for IE 6-8, and more)
- ruby 1.9.3p0
- [schema](https://github.com/halst/schema) 0.2.0 - A library for validating Python data structures, such as those obtained from config-files, forms, external services or command-line parsing, converted from JSON/YAML (or something else) to Python data-types.
- [setuptools](https://pypi.python.org/pypi/setuptools) 3.6 - Easily download, build, install, upgrade, and uninstall Python packages.
- [six](https://pypi.python.org/pypi/six) 1.6.1 - Python 2 and 3 compatibility utilities
- [South](http://south.aeracode.org/) 0.8.4 - Scema and data migrations.
- [SSL](https://addons.heroku.com/SSL) - Heroku addon for SSL encryption for https:// urls.
- [Unipath](https://github.com/mikeorr/Unipath) 1.0 - An object-oriented approach to Python file/directory operations.
- [xlwt](https://pypi.python.org/pypi/xlwt) 0.7.5 - Library to create spreadsheet files compatible with MS Excel 97/2000/XP/2003 XLS files, on any platform, with Python 2.3 to 2.7.

## Front end

### New front end

- [backbone](http://backbonejs.org/) 1.1.2 (reviewed) - Front end application foundation.
- [backbone.syphon](https://github.com/derickbailey/backbone.syphon/) 0.4.1 - serialize a Backbone.View into a JavaScript object.
- backbone.paginator 2.0.0
- [backbone.picky](https://github.com/derickbailey/backbone.picky) 0.2.0 - selectable entities as mixins for Backbone.Model and Backbone.Collection.
- [Backgrid.js](http://backgridjs.com/) 0.3.5 - front end grid management.
- [backgrid-filter](https://github.com/wyuenho/backgrid-filter) 0.3.5 - Server-side, client-side and full-text searching widgets for Backgrid.js
- [backgrid-moment-cell](https://github.com/wyuenho/backgrid-moment-cell) 0.3.5 - Backgrid.js datetime cell type using moment.js.
- [backgrid-paginator](https://github.com/wyuenho/backgrid-paginator) 1730e0231c51d4606945a3d3492213ec37b9dcdc - Paginator for Backgrid.js.  Commit used to force use of backbone.paginator.
- [backgrid-select-all](https://github.com/wyuenho/backgrid-select-all) 0.3.5 - Select-all extension for Backgrid.js
- [Bootstrap](http://getbootstrap.com/) 3.1.1 - front end framework
- fine-uploader
- [Highcharts](http://www.highcharts.com/) 4.0.1 - a charting library.
- [json2](https://github.com/douglascrockford/JSON-js) 3d7767b6b1 - JSON in JavaScript.  This library doesn't seem to be versioned.
- lunr
- [Marionette](http://marionettejs.com/) 1.8.2 - front end application infrastructure.
- [moment](http://momentjs.com/) 2.5.1 - A javascript date library for parsing, validating, manipulating, and formatting dates.  Moment is also used by backgrid-moment-cell and can retard new versions.
- [numeral](http://numeraljs.com/) 1.5.3 - A javascript library for formatting and manipulating numbers.

- [spin.js]() 2.0.1 - A spinning activity indicator.
- [underscore](http://underscorejs.org/) 1.5.2 - Javasript utilities.

### Old front end

The old front end loads these via base.html and will be retired.  Some duplicates may exist with the new front end with different versions.  These are mainly javascript and HTML libraries that are stored in version control under `vbenergyzone/static/js/vender` and should be considered frozen until the old front end is retired.  In some cases versions are hard to determine.

- [backbone](http://backbonejs.org/) 1.0.0 - Front end application foundation.  May have been install purely as a study.
- [Bootbox](http://bootboxjs.com/) 3.3.0 - create programmatic dialog boxes
- [Bootstrap](http://twitter.github.com/bootstrap/) 2.3.2 - front end framework
- [DataTables](http://www.datatables.net/index) 1.9.4 - a plug-in for the jQuery Javascript library. It is a highly flexible tool, based upon the foundations of progressive enhancement, which will add advanced interaction controls to any HTML table.
- datetimepicker
- [Highcharts](http://www.highcharts.com/) 3.0.2 - a charting library.
- [Jeditable](http://www.appelsiini.net/projects/jeditable) version?
- [jquery](http://jquery.com/) 1.10.2
- [jquery-cookie](https://github.com/carhartl/jquery-cookie) 1.3.1 - A simple, lightweight jQuery plugin for reading, writing and deleting cookies.
- [json2](https://github.com/douglascrockford/JSON-js) version? - JSON in JavaScript.
- [modernizr](http://modernizr.com/) 2.6.2
- [underscore](http://underscorejs.org/) 1.5.1 - Javasript utilities.

### General
- [Universal Command Line Interface for Amazon Web Services (aws-cli)](https://github.com/aws/aws-cli) 1.3.16 [Changelog](https://github.com/aws/aws-cli/blob/develop/CHANGELOG.rst)
- [bash](http://www.gnu.org/software/bash/manual/bashref.html) 4.2.24 - shell.
- [fine-uploader](http://fineuploader.com/) 4.4.0 - Used to directly upload documents to S3.  Requires building and tweaking.  Specifically, comments in built javascript seem to screw up asset pipeline.
- gulp-coffeelint
- [CSS](http://www.w3.org/Style/CSS/) - a simple mechanism for adding style (e.g., fonts, colors, spacing) to Web documents.
- [git](http://git-scm.com/) 1.7.9.5 - Distributed version control system.  This is the version that is installed in the virtual environment.

- [heroku CLI](https://devcenter.heroku.com/categories/command-line) 3.7.3
- [Homebrew](http://mxcl.github.io/homebrew/) - http://brew.sh/
- [homebrew-cask](https://github.com/phinze/homebrew-cask) - a friendly homebrew-style CLI workflow for the administration of Mac applications distributed as binaries.
- [HTML5](http://www.w3.org/html/wg/) - content markup.
- [Javascript](http://en.wikipedia.org/wiki/JavaScript) - front end language.
- [jquery](http://jquery.com/)
- [jquery-cookie](https://github.com/carhartl/jquery-cookie)
- [modernizr](http://modernizr.com/)
- [New Relic for Python](https://docs.newrelic.com/docs/python/new-relic-for-python) 2.20.0.17 [Changelog](https://docs.newrelic.com/docs/releases/python) - Python agent for New Relic
- [nfsd](http://docs.vagrantup.com/v2/synced-folders/nfs.html) -- used for syncing folders between host and guest machine in vagrant development environment.

