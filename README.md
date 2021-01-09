# Awesome Silverstripe CMS [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<!--lint ignore double-link-->
[<img src="images/logo-silverstripe-cms.png" align="right" width="200">](https://www.silverstripe.org/)

> Useful resources for Silverstripe Framework and CMS
<!--lint ignore double-link-->
[Silverstripe CMS](https://www.silverstripe.org) is an open source PHP framework for building web applications. It is a rapid development MVC framework that serves as a classic fully fledged CMS or as a headless CMS, which can be queried either via GraphQL or a custom API.
Following the "Active Record" design pattern, you can easily extend the built-in functionality with a project specific data model.

[Contributions welcome](CONTRIBUTING.md), please send a pull request or open an issue to start a discussion.

Outdated items can be found in the [archive](ARCHIVE.md).

## Contents
<!-- PLEASE USE `doctoc --maxlevel 3 README.md` TO KEEP THE TOC TO AN APPROPRIATE SIZE -->
<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [Resources](#resources)
  - [Official Websites](#official-websites)
  - [Documentation & Tutorials](#documentation--tutorials)
  - [Blogs](#blogs)
  - [Video Channels](#video-channels)
  - [Community](#community)
  - [Conferences & Meetups](#conferences--meetups)
- [Very Useful Modules](#very-useful-modules)
  - [Module Listings](#module-listings)
  - [General Modules](#general-modules)
  - [I18N (Internationalisation)](#i18n-internationalisation)
  - [Site Search](#site-search)
  - [Development Helpers](#development-helpers)
  - [Fancy Form Fields](#fancy-form-fields)
- [Tools](#tools)
  - [Management](#management)
  - [IDE Plugins](#ide-plugins)
  - [Virtualisation](#virtualisation)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Resources
### Official Websites
<!--lint ignore double-link-->
- [www.silverstripe.org](https://www.silverstripe.org) - Framework and CMS.
- [www.silverstripe.com](https://www.silverstripe.com) - Silverstripe Ltd., the company behind the CMS.

### Documentation & Tutorials
- [API Docs](http://api.silverstripe.org/) - Autogenerated API documentation.
- [Technical Documentation](http://doc.silverstripe.org/framework/en/) - For developers. Explains all core concepts.
- [Using the CMS](http://userhelp.silverstripe.org/) - Documentation for end users how to use the core features.
- [Silverstripe Lessons](https://www.silverstripe.org/learn/lessons/) - Learn how to build a Silverstripe site step by step with a real-world project.
- [Font reference](https://silverstripe-fonts.dorset-digital.net/) - Built in icon font for backend usage.
- [TinyMCE Configuration Examples For SS3](https://github.com/jonom/silverstripe-tinytidy) - Configuration examples for the HTMLEditorField.


### Blogs
- [Official Silverstripe Blog](https://www.silverstripe.org/blog/) - News around Silverstripe CMS.
- [SilverStrip.es](http://www.silverstrip.es) - Useful findings of Silverstripe developers.

### Video Channels
- [Official StripeCon YouTube Channel](https://www.youtube.com/channel/UC38vU3H_UrdGFnc3vTJiORA) - Talks of various StripeCon conferences.
- [Official Silverstripe Vimeo Channel](https://vimeo.com/silverstripe) - Various videos from meetups and conferences.

### Community
- [Stack Overflow](https://stackoverflow.com/questions/tagged/silverstripe) - Silverstripe related questions on Stack Overflow.
- [Silverstripe User Slack](https://silverstripe-users.slack.com/) - Community slack channel for instant help or hanging around with other developers.
  - [Invitation to Silverstripe User Slack](https://www.silverstripe.org/community/slack-signup)
- [Forum](https://forum.silverstripe.org/) - Official forum for asking questions or discussing.

### Conferences & Meetups
- [European Silverstripe Conference](https://www.stripecon.eu) - Every year in another country.
- [Meetups](https://www.meetup.com/topics/silverstripe/all/) - A list of Silverstripe related Meetups.

## Very Useful Modules
### Module Listings
- [SS Addons: Themes and Modules](https://addons.silverstripe.org) - The official module registry.
- [SSMods: Detailed Module Search](http://ssmods.com) - Alternative module search.
- [Most Used Modules](https://addons.silverstripe.org/add-ons?sort=relative) - Shows which modules are downloaded most.
- [Silverstripe Recipes on Packagist](https://packagist.org/packages/silverstripe/recipe-plugin/dependents) - Preconfigured sets of modules for different kind of projects.

### General Modules
- [Multiuser editing alert](https://github.com/silverstripe/silverstripe-multiuser-editing-alert) -  Alerts users in the Silverstripe CMS when multiple people are editing the same page.

### I18N (Internationalisation)
- [Fluent](https://github.com/tractorcow-farm/silverstripe-fluent) - Multi-language translate module for Silverstripe, without having to manage separate site trees.
- [Autotranslate](https://github.com/bratiask/silverstripe-autotranslate) -  Creates automatic translations of fields using Google Translate API.

### Site Search 
- [Silverstripe Searchable](https://github.com/i-lateral/silverstripe-searchable) - Adds more complex site searching using the Silverstripe ORM. With dedicated templates for search results across multiple search objects.
- [Searchable DataObjects](https://github.com/g4b0/silverstripe-searchable-dataobjects) - Fast and simple MySQL based search. Useful for single language sites.
- [Fulltext Search](https://github.com/silverstripe/silverstripe-fulltextsearch) - Full fledged search interface for Solr4.
- [Fulltext Search Local Solr](https://addons.silverstripe.org/add-ons/silverstripe/fulltextsearch-localsolr) - Easy to install Solr4 instance for local development.
- [Solr search](https://github.com/firesphere/silverstripe-solr-search) - Interface for Solr search, supporting up to the latest Solr version. With submodules for e.g. transitioning from the "Fulltext Search" module, as well as subsite, fluent and others.

### Development Helpers
- [Debugbar](https://github.com/lekoala/silverstripe-debugbar/) -  Shows debugging statistics in your browser.
- [IdeAnnotator](https://github.com/silverleague/silverstripe-ideannotator) -  Auto-generates class annotations on dev/build.
- [Populate](https://github.com/dnadesign/silverstripe-populate) -  Populate your database through YAML files.
- [Mock DataObjects](https://github.com/unclecheese/silverstripe-mock-dataobjects) -  Allows DataObjects to self-populate intelligently with fake data.
- [Version Truncator](https://github.com/axllent/silverstripe-version-truncator) - Automatically delete old SiteTree page versions.
- [UserSwitcher](https://github.com/sheadawson/silverstripe-userswitcher) - Adds a small form both in the frontend and backend to quickly login as any user.
- [Masquerade](https://github.com/dhensby/silverstripe-masquerade) -  Allows an Administrator to "login" as another "Member". This can be useful for debugging and remote support.

### Fancy Form Fields
- [Markdown Field](https://github.com/Silverstripers/markdownfield) -  Can replace your HTMLEditorFields (using TinyMCE) so you can utilise Markdown syntax.
- [Code Editor Field](https://github.com/nathancox/silverstripe-codeeditorfield) -  Gives you a syntax-highlighted text area field - great for CMS-based YAML or HTML.

## Tools
### Management
- [SSPak](https://github.com/silverstripe/sspak) - Tool for managing bundles of db/assets from Silverstripe environments.
- [SSPy](https://github.com/Firesphere/silverstripe-sspy) - Python version of SSPak, that can handle assets more than 2GB.

### IDE Plugins
- [VSCode Silverstripe](https://marketplace.visualstudio.com/items?itemName=adrian.silverstripe) - Syntax highlighting for Silverstripe template files in VSCode.
- [Jetbrains / PHPStorm Silverstripe Template Language Support](https://plugins.jetbrains.com/plugin/7201-silverstripe-template-language-support) - Syntax highlighting for Silverstripe template files.
- [PHPStorm / Webstorm Live Templates](https://github.com/northcreation-agency/silverstripe-php-web-storm-live-templates) - Shortcuts for adding various Silverstripe specific code snippets.

### Virtualisation
#### Vagrant
There is no official box like Laravel has its homestead box. However, there are a few good boxes out there for Vagrant you could use:
- [Twisted Bytes](https://www.twistedbytes.nl/en/blog/php-vagrant-box/) - Useful vagrant box with multiple PHP versions, MariaDB or PostgreSQL, mail catcher and much more.
- [Twisted Bytes Box Templates](https://derkbox.com) - Useful templates for different development scenarios using the Twisted Bytes vagrant box.
- [Laravel Homestead](https://github.com/laravel/homestead) - Prepackaged box for local development.
- [Scotchbox](https://box.scotch.io) - Popular LAMP/LEMP stack for local development.
- [Zauberfisch Vagrant Boxes](https://github.com/Zauberfisch/vagrant-boxes) -  Preconfigured Vagrant boxes for SS3 and SS4.

#### Docker

- [brettt89/silverstripe-web](https://hub.docker.com/r/brettt89/silverstripe-web) -  Apache + PHP Docker image with pre-installed PHP modules for SilverStripe support.
- [brettt89/sspak](https://hub.docker.com/r/brettt89/sspak) -  SSPak Docker image.
- [brettt89/silverstripe-solr-cwp](https://hub.docker.com/r/brettt89/silverstripe-solr-cwp) -  CWP Solr Docker image.
