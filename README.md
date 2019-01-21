# [WordPress](https://wordpress.org/) on [Heroku](http://heroku.com)

Project Information:

[![Build Status](https://travis-ci.org/everesthack/everesthack.svg?branch=develop)](https://travis-ci.org/everesthack/everesthack)

[![Join the chat at https://gitter.im/wordpress-heroku/Lobby](https://badges.gitter.im/wordpress-heroku/Lobby.svg)](https://gitter.im/wordpress-heroku/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

--------

## About:
This project is a template for installing and running [WordPress](http://wordpress.org/) on [Heroku](http://www.heroku.com/).

It is based on [Bedrock](https://roots.io/bedrock/), a modern WordPress stack that helps you to get started with the best development tools and a modern project structure.

All resources used in this project are free-of-charge. You can upgrade them post-deployment.

## Table of Contents
- [Getting Started](#gettingstarted)
- [Features](#features)
- [WIKI](https://github.com/PhilippHeuer/wordpress-heroku/wiki)
- [Changelog](./CHANGELOG.md)

## Getting Started
#### Deploy using Heroku CLI (suggested for customization)
Plase check out the [deployment page](https://github.com/everesthack/everesthack/Deployment) in the wiki for a step-by-step guide.

## Features
 - [x] Better folder structure
 - [x] Dependency management with [Composer](http://getcomposer.org)
 - [x] Easy WordPress configuration with environment variables from Heroku
 - [x] Autoloader for mu-plugins (use regular plugins as mu-plugins)
 - [x] Enhanced security (separated web root and secure passwords with [wp-password-bcrypt](https://github.com/roots/wp-password-bcrypt))

## Problems?

If you have problems using your instance of WordPress, you should check the [official documentation](https://codex.wordpress.org/).
If you discover an issue with the deployment process provided by *this repository*, then [open an issue here](https://github.com/everesthack/evresthack/issues/new).

## License

Released under the [MIT license](./LICENSE).
