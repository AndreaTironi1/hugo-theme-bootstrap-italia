# Bootstrap Italia - Hugo Theme

Disclaimer: hugely WIP (but we are working on it ASAP)

## Install

Follow these steps to have a working Hugo site

* Create a new Hugo site with

  `hugo new site site_name`
* Add the content of this repo within

  `site_name/themes/hugo-theme-bootstrap-italia`
  `rename site_name/themes/hugo-theme-bootstrap-italia-master site_name/themes/hugo-theme-bootstrap-italia'
  or
  `cd site_name`
  `git init`
  `git submodule add https://github.com/francescozaia/hugo-theme-bootstrap-italia themes/hugo-theme-bootstrap-italia`
  
* Add this line to your `site_name/config.toml` file:

  `theme = "hugo-theme-bootstrap-italia"`
  
* Edit your website `site_name/config.toml` to override rules defined in `site_name/themes/hugo-theme-bootstrap-italia/config.toml`.

* Test your website with `hugo server --bind=ip -p=port -D`. 
 
Note: in order to add content to the _main_ part of the website, you can just create a `site_name/content/_index.md` with some Markdown in it.
