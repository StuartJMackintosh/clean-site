
# Theme manual

> ALPHA incomplete

This theme is specifically built for pico_cms on Nextcloud, to deliver a straight forward elegant boostratp 5 site.


## Origin

Amalgamation of [https://github.com/BesrourMS/clean-blog](clean-blog) and default Pico theme

requires no plugins, no 3rd party / CDN assets


## Behavour



## Variables

The theme reads various variables which are either system, site or page

### System variables

See standard pico docs

### Page variables  

In the yaml block at the top of each page

Title: Test site
Description: System thinking and design for a better digital world
Img: /assets-6433359e750f3/images/head.jpeg
hidden: true
template: post / contact / bio / team

### Site variables 

In the file _meta.md

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

To provide a 48x48 favicon, set the path and name in _meta.md. If unset, a default favicon will be served.
favicon: %assets_url%/images/favicon.ico

TODO: blogdir: blog #if subfolder exists with this name, showlist of articles, newest first
showing title, desc, author, date



## Pages

Simply add pages to the folder and the title will appear in the menu, unless property ```hidden: true``` is set

## Templates

In addition to the default 'index' template, there are some other qiick templates that render content and provide automated pages.

These are:

### contact

### team


### bio


### post


## Debugging

The debug page parameter includes a template to show current variables.

just add debug: true to the meta on the page


## Author

I am not a developer!






