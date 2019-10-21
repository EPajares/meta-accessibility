## Adding a tool
Create a new post in `_tools` folder with the following front matter options:

```yaml
---
title: GOAT
image: goat.png
contact:
    name: 
    address: 
    email: 
    url: 
# Tool type tags
mode: [walking, cycling]
scale: [street,neighborhood]
terms: open
type: web
target: public
---
```

Image: Enter a full URL to an external image (including the `http` part) or upload the image to `uploads` folder and specify only image file name e.g. `image: goat.png`.

Tool type tags: for reference of all available tags see `_data/navigation_tools.yml` file. Enter multiple tags as `mode: [walking, cycling]`.

## Installation

Install the dependencies with [Bundler](http://bundler.io/):

```bash
bundle install
```

Run the following to generate your site:
```bash
bundle exec jekyll serve
```

You can find more on [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

## Development

Install [UIkit](https://getuikit.com/) font end framework dependency via Npm:
```bash
npm install
```
Enable live browser reload with the following:
```bash
bundle exec jekyll s --livereload
```