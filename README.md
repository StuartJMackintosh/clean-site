
# Theme manual

> ALPHA incomplete


## Origin

Amalgamation of [https://github.com/BesrourMS/clean-blog](clean-blog) and default Pico theme

requires no plugins, no 3rd party assets


## Behavour



## Variables

The theme reads various variables which are either system, site or page

### System variables

See std pico docs

### Page variables  (page yaml)

Title: Test site
Description: System thinking and design for a better digital world
Img: /assets-6433359e750f3/images/head.jpeg
hidden: true
template: post / contact / bio / team

### Site variables (_meta.md)

Name
: Logo

Example
: Logo: %assets_url%/images/logo.png

Use
: Showing the masthead. If not specified, a default is provided

Tagline: Developing purpose, strategy and business
Social:
    - title: Visit us on GitHub
      url: https://github.com/StuartJMackintosh
      icon: github
    - title: Linkedin
      url: https://www.linkedin.com/in/stuartjmackintosh/
      icon: linkedin

if ypu want a favicon, set this in _meta.md. If unset, no favicon will be served.
favicon: %assets_url%/images/favicon.ico

blogdir: blog #if subfolder exists with this name, showlist of articles, newest first
showing title, desc, author, date

## Templates

In addition to the default 'index' template, there are some other qiick templates that render content and provide automated pages.

These are:

### contact

### team


### bio


### post





