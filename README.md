pick
========

A medium inspired Jekyll blog theme. I made few changes to the Jekyll theme [Mediator](https://github.com/dirkfabisch/mediator) witch itself is inspired from the Ghost theme [Readium 2.0](http://www.svenread.com/readium-ghost-theme/).
See it live here : [http://pick.jclagache.me](http://pick.jclagache.me)

Features
-------
* Fully Responsive layout
* Use header images in articles, if you want to (add tag "image" and url to the image in the front matter section of a post)
* Minimal design
* Featured article support
* FontAwesome implemented for easy use of icons fonts
* Free & Open Source Font usage

Getting Started
---
- [Fork this repository](https://github.com/jclagache/pick)
- Clone it: `git clone https://github.com/YOUR-USER/pick`
- Install the [GitHub Pages gem](https://github.com/github/pages-gem) (includes Jekyll): `bundle install`
- Run the jekyll server: `jekyll serve`

You should have a server up and running locally at <http://localhost:4000>.

Configuration
-----

The main settings happen in side of the _config.yml file:

### Site

Main settings for the site 

* **title**: name of your site
* **description**: description of your site
* **logo**: small logo for the site
* **cover**: bottom post page background image

* **name**: name site owner
* **email**: mail address of the site owner
* **author**: author name
* **author_image**: small image of author (300x * 300px)

* **baseurl**: the subpath of your site, e.g. /blog/
* **url**: the base hostname & protocol for your site

 
### Social 

The template allows to add all major social plattforms to your site.
Fill the the form for each plattform. If you leave the share_* entries empty, the sharing buttons below a post are not shown.  

* **icon**:	name of social plattform (must match a name of [font-awsome](http://fortawesome.github.io/Font-Awesome/) icon set )
* **url**:	url of your account
* **desc**: slogan of the plattform
* **share_url**: share url
* **share_title**: first part of url for the title
* **share_link**: second part of the share url for the link to the post

The Liquid template engine will magical combine the different parts to a share url. 

```
http://twitter.com/share?text=post_title&amp;url=post_url
````

See [_config.yml](https://github.com/jclagache/pick/blob/master/_config.yml) for more examples. 

Licensing
---------

[MIT](https://github.com/jclagache/pick/blob/master/LICENCE) with no added caveats, so feel free to use this on your site without linking back to me or using a disclaimer or anything silly like that.

Contact
-------
[@jclagache](https://twitter.com/jclagache)

