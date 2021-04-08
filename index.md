---
layout: default
title: Home
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# Focus on writing good documentation
{: .fs-9 }

Just the Docs gives your documentation a jumpstart with a responsive Jekyll theme that is easily customizable and hosted on GitHub Pages.
{: .fs-6 .fw-300 }

[Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 } [View it on GitHub](https://github.com/pmarsceill/just-the-docs){: .btn .fs-5 .mb-4 .mb-md-0 }

---

## Getting started

### Dependencies

Just the Docs is built for [Jekyll](https://jekyllrb.com), a static site generator. View the [quick start guide](https://jekyllrb.com/docs/) for more information. Just the Docs requires no special plugins and can run on GitHub Pages' standard Jekyll compiler. The [Jekyll SEO Tag plugin](https://github.com/jekyll/jekyll-seo-tag) is included by default (no need to run any special installation) to inject SEO and open graph metadata on docs pages. For information on how to configure SEO and open graph metadata visit the [Jekyll SEO Tag usage guide](https://jekyll.github.io/jekyll-seo-tag/usage/).

### Quick start: Use as a GitHub Pages remote theme

1. Add Just the Docs to your Jekyll site's `_config.yml` as a [remote theme](https://blog.github.com/2017-11-29-use-any-theme-with-github-pages/)
```yaml
remote_theme: pmarsceill/just-the-docs
```
<small>You must have GitHub Pages enabled on your repo, one or more Markdown files, and a `_config.yml` file. [See an example repository](https://github.com/pmarsceill/jtd-remote)</small>

### Local installation: Use the gem-based theme

1. Install the Ruby Gem
```bash
$ gem install just-the-docs
```
```yaml
# .. or add it to your your Jekyll site’s Gemfile
gem "just-the-docs"
```
2. Add Just the Docs to your Jekyll site’s `_config.yml`
```yaml
theme: "just-the-docs"
```
3. _Optional:_ Initialize search data (creates `search-data.json`)
```bash
$ bundle exec just-the-docs rake search:init
```
3. Run you local Jekyll server
```bash
$ jekyll serve
```
```bash
# .. or if you're using a Gemfile (bundler)
$ bundle exec jekyll serve
```
4. Point your web browser to [http://localhost:4000](http://localhost:4000)

If you're hosting your site on GitHub Pages, [set up GitHub Pages and Jekyll locally](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll) so that you can more easily work in your development environment.

### Configure Just the Docs

- [See configuration options]({{ site.baseurl }}{% link docs/configuration.md %})

---

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](http://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/pmarsceill/just-the-docs/tree/master/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/pmarsceill/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contribut---
layout: default
title: Introduction 
nav_order: 1
permalink: /
---

# Introduction
This documentation serves as a guide to using Greenshot’s core features. Greenshot is a screenshot suite that allows users to have control over screen capture, editing, and uploading. 

## Software Requirements
Windows / MacOS Operating System
GreenShot Application

<span style="background-color:#F7D12E;color:black;">_note:_ Currently, This user guide only provides instructions for the Windows version of GreenShot. The Mac version of Greenshot may not follow some instructions outlined in this user guide.</span> 


Greenshot is available free for Windows users and available on MacOS from the app store. The Greenshot application is available for download at https://getgreenshot.org/downloads/
 
## Intended Use
Greenshot is a desktop capturing application that allows users to have enhanced control over the process of taking screenshots.Greenshot has all the functionalities of the default Windows/MacOS screenshot tool along with many additional features like the obfuscation tool or instant uploads to imgur. Greenshot offers users full control in their capturing, editing, saving and uploading screenshots.

## Procedures Included
In this guide we will be covering the five features that will set you on your way to becoming a Greenshot power user:
- Capturing a screen region
- Capturing a window
- Capturing an entire screen
- Obfuscating sensitive information with the editor
- Exporting your screenshots to different file types
- Uploading to imgur/imgur integration

## Typographical Conventions
This user guide uses the typological conventions listed in the table below.

| Convention | Typeface | Examples |
|---|---|---|
| Key Terms and Emphasis | _Italics_  | _Capture_, _History_           |
| Keystrokes and Clicks  | **[Bold]** | **[PrtSc]**, **[Right-Click]** |

<span style="background-color:#F7D12E;color:black;">_note:_ Notes give additional information about a step. Notes will be preceded with the word “_note_:” encased in a yellow box.</span>
