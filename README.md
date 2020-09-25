# Buchvorlage

# Vivliostyle 2.1.1

Webbuch: https://akademie-oeffentliches-gesundheitswesen.github.io/Buchvorlage/vivliostyle/#src=../webbuch/&bookMode=true&

From here: https://akademie-oeffentliches-gesundheitswesen.github.io/Buchvorlage/vivliostyle/

add unzipped EPUB by pasting in ../webbuch/

Note: /vivliostyle and /webbuch are on the same directory level

# Running Jekyll locally

Follow the instructions here https://docs.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll

If Gemfile already present on top level of repository then just serve with

> bundle exec jekyll serve --incremental

Gemfile will have this contents

source 'https://rubygems.org'
gem 'github-pages', group: :jekyll_plugins

Site will be on http://127.0.0.1:4000/

On windows add: gem 'wdm'

# Markdown

## Images

Use:

{% include image.html url="65b1a628-3996-4bd2-8933-b3c50774f530.png" description="Tabelle 1: KJGD relevante Regelungen in den GDGs der Länder" %}

Add images for Jekyll to: /images
