# Changelog

Please report any bugs and feature requests via our
[GitHub Issue Tracker](https://github.com/McPringle/apus/issues).
For questions and support requests, please use
[GitHub Discussions](https://github.com/McPringle/apus/discussions).

---

## Version 2

**Release date: work in progress 🚧**

### Features

* Add support for event agenda hosted on Sessionize.com (BaselOne, Java Forum Nord, etc.)
* Add support for Java Forum Stuttgart
* New demo event plugin to show fake data for demos and testing
* The update frequency of the event agenda is now configurable
* Add support for session tracks with default icons and custom SVG images
* Theming: all colors are now configurable
* Create hashed passwords for admin access on the command line
* New config option to show/hide event room legend

### Bugfixes

* Fixed possible XSS attack with modified Mastodon posts

### Maintenance

* All icons are now system independent
* Sessions without a language will not display a language flag
* Better use of available space for social media posts

## Version 1

**Release date: 2024-04-10**

### Features

* Display agenda of DOAG events (JavaLand, CyberLand, CloudLand, etc.)
* Display posts of Mastodon containing a configurable hashtag
* Display images from Mastodon posts (configurable)
* Filter sensitive Mastodon posts
* Filter Mastodon replies
* Filter Mastodon posts by words
* Hide single Mastodon posts
* Block Mastodon profiles
* English and German translation
* Dynamic updates of Agenda and Mastodon posts
