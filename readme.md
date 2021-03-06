<p align="center">
<img src="https://camo.githubusercontent.com/ebf016c308b7472411bd951e5ee3c418a44c0755/68747470733a2f2f73332e616d617a6f6e6177732e636f6d2f662e636c2e6c792f6974656d732f33513238333030343348315931633146314b32442f64697265637475732d6c6f676f2d737461636b65642e706e67" alt="Directus Logo"/>
</p>

<p align="center">Open-Source Headless CMS & API</p>
<p>&nbsp;</p>

[![Join the chat at https://slack.getdirectus.com](https://img.shields.io/badge/chat-on%20slack-C7205A.svg)](https://slack.getdirectus.com)
![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=<badge_key>)
[![GitHub issues](https://img.shields.io/github/issues/directus/directus.svg)](https://github.com/directus/directus/issues)
[![GitHub license](https://img.shields.io/badge/license-GPL-blue.svg)](https://raw.githubusercontent.com/directus/directus/master/license.md)
[![StackShare](http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/ranger/directus)

_Checkout our [live demo](https://preview.getdirectus.com)!_

## Description
Directus is a free and open-source database API and 'headless' CMS. Unlike traditional CMS that encompass your entire project codebase, the decoupled approach of Directus offers an API and SDKs to connect your content to: websites, native apps, kiosks, IoT devices, or any other data-driven projects.

Directus makes no assumptions about how you should architect your database – giving you complete freedom to optimize structure and performance for projects of any size or complexity. Built on top of the API is our feature-rich admin webapp (CMS) which dynamically maps to your database's schema, instantly providing your users/clients with an intuitive interface for managing content.

Learn more at [getdirectus.com](https://getdirectus.com) and follow us on Twitter: [@directus](https://twitter.com/directus)

Please consider supporting us on [Patreon](https://www.patreon.com/directus)!

## Installation
Download the latest pre-built version from [our releases page](https://github.com/directus/directus/releases) or clone this repo and install the composer dependencies by running `composer install` from the root folder.

### Requirements:
NGINX or Apache Server, MySQL 5.2+, PHP 5.5+ (curl, gd, finfo, pdo_mysql)

### Database types
While Directus has been abstracted to allow for different database adapters in the future, currently only MySQL is supported. PostgreSQL, SQLite, and MongoDB support is under development – and we hope to expand support for additional database types as we gain contributors.

## Documentation

### Directus ADMIN
The full documentation about using the admin Directus can be found over at [docs.getdirectus.com](https://docs.getdirectus.com).

You can find the source of this documentation in [our docs repo](https://github.com/directus/docs).

### Directus API & SDKs
Our full API reference can be found over at [api.getdirectus.com](https://api.getdirectus.com). Together with the endpoints and supported params, you can also find code examples for our supported SDKs.

You can find the source of this documentation in [our API docs repo](https://github.com/directus/api-docs).

## Contributing to Directus
First of all, thank you for taking the time to work on Directus!

The following is a set of guidelines for contributing to Directus and its components. These are just guidelines, not strict rules. Feel free to propose changes to this and other documents in a pull request.

### How Can I Contribute?

#### Financial Support
[<img src="https://user-images.githubusercontent.com/522079/33287837-0218cbfc-d388-11e7-9fbe-36ff3261b61a.png" alt="Patreon" />](https://www.patreon.com/directus)

#### Reporting Bugs
Think you've discovered a bug? First, read through our [docs](https://docs.getdirectus.com) to be sure – then submit a ticket to our [GitHub Issues](https://github.com/directus/directus/issues/new). And if you already know a good solution, we love [Pull Requests](https://github.com/directus/directus/pulls)! **For all security related issues, please chat with us directly through [getdirectus.com](https://getdirectus.com/).**

#### Translations
Directus has multilingual support – and we're looking for anyone interested in helping translate our [English default language file](https://github.com/directus/directus/blob/master/api/locales/en.json) into other languages. It's as easy as copying that `en.json` file and changing the values!

PR any translations into [this Directory](https://github.com/directus/directus/tree/master/api/locales).

Huge thanks to the following contributors!

- 🇺🇸  [@benhaynes](https://github.com/benhaynes)
- 🇫🇷  [@EmilienCo](https://github.com/EmilienCo) & [@JackNUMBER](https://github.com/JackNUMBER)
- 🇪🇸  [@WellingGuzman](https://github.com/WellingGuzman)
- 🇩🇪  [@katywings](https://github.com/katywings) & [@ymilhahn](https://github.com/ymilhahn)
- 🇨🇳  [@TigerHix](https://github.com/TigerHix) & [@Gfast2](https://github.com/Gfast2)
- 🇧🇷  [@michaelnagy](https://github.com/michaelnagy)
- 🇮🇹  [@AeonZh](https://github.com/AeonZh)
- 🇳🇱  [@RijkvanZanten](https://github.com/RijkvanZanten)
- 🇯🇵  [@hokkaidobeard](https://github.com/hokkaidobeard)
- 🇳🇴  [@franctic-aerobic](https://github.com/franctic-aerobic)


#### Suggesting Enhancements
When you are creating an enhancement suggestion, please include as many details as possible. Fill out the required template; including the steps that you imagine you would take if the feature you're requesting existed.

#### Requesting Features
Use our [Feature Request Tool](https://request.getdirectus.com/) to request new features or vote on existing commmunity suggestions.

#### Your First Code Contribution
Unsure where to begin contributing to Directus? You can start by looking through the [`Beginner`](https://github.com/directus/directus/issues?q=is%3Aopen+is%3Aissue+label%3ABeginner), [`good first issue`](https://github.com/directus/directus/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) and [`Help Wanted`](https://github.com/directus/directus/issues?q=is%3Aopen+is%3Aissue+label%3A%22Help+Wanted%22) issues. `Beginner` and `good first issue` issues are issues that often only require a few lines of code. `Help wanted` issues are a bit more involved than beginner issues.

Want to help but have some trouble understanding the issue, ask us and we will help you to get you started.
#### Pull Requests
Pull requests are always welcome for every part of Directus. Please make sure to adhere to our [`.editorconfig`](http://editorconfig.org) rules and to lint your code with [XO](https://github.com/sindresorhus/xo).

## Public Roadmap
_This is what we want to get done next:_

### Q4 2017
- CMS App Decoupled from API
- API 2.0 - Speed improvements, better relational filtering / querying and increased i18n support

### Q1 2018
- [Support Node.JS as backend platform](https://request.getdirectus.com/r/3)
- [Support for multiple database (multitenant)](https://request.getdirectus.com/r/1)
- [Digital Asset Management improvements](https://request.getdirectus.com/r/2)
- [Web Hooks](https://request.getdirectus.com/r/9)

- [GraphQL endpoint](https://request.getdirectus.com/r/11)
- [Support for PostgreSQL DBs](https://request.getdirectus.com/r/14)
- Marketplace for easier distribution of interfaces / extensions


## Team
- Project Lead: [Ben Haynes](https://github.com/benhaynes)
- Development Lead: [Welling Guzmán](https://github.com/wellingguzman)
- Interface Lead: [Rijk van Zanten](https://github.com/rijkvanzanten)

Key developers: [coolov](https://github.com/coolov), [freen](https://github.com/freen), [jel-massih](https://github.com/jel-massih), [Lasha](https://github.com/Lasha)

Sponsors: Bas Jansen

## Copyright, License, and Trademarks
* Directus Core codebase released under the [GPLv3](http://www.gnu.org/copyleft/gpl.html) license.
* Example Code, Design Previews, Demonstration Apps, Custom Extensions, Custom interfaces, and Documentation copyright 2017 [RANGER Studio LLC](http://rngr.org/).
* RANGER Studio owns all Directus trademarks, service marks, and graphic logos on behalf of our project's community. The names of all Directus projects are trademarks of [RANGER Studio LLC](http://rngr.org/).
