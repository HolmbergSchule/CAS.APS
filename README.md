## Adding a new project


* Go to this directory: https://github.com/HolmbergSchule/CAS.APS/tree/master/_posts
* Create a new file in that directory with naming `yyyy-mm-dd-title.md`

![](https://github.com/HolmbergSchule/CAS.APS/blob/master/assets/images/add-file.png)

* Use the following template:

```
---
layout: post
title:  "Page title"
author: sal
organization:
    name: "Holmberg Schule"
    logo:  "assets/images/logo-holmberg.png"
categories: [ Jekyll, tutorial, web development ]
image: "https://holmbergschule.edu.ar/v4/wp-content/uploads/2018/08/logo-holmberg.png"
mapping:
    latitude: 51.101
    longitude: 0.1
---

## Projectbeschrijving

Your text in markdown formatting

## Ervaringen

> Add a personal quote

Your text in markdown formatting

## Persartikelen

Your text in markdown formatting

```

**Explanation of the template**
* **Layout** - Always use `post` to have the standard project page layout
* **Title** - Your page title
* **Author** - Always reference a predefined author from `authors` in https://github.com/HolmbergSchule/CAS.APS/blob/master/_config.yml. You can add new authors there.
* **Organization** - The organization that organizes the project. The organization needs a `name` between quotes and a link to the `logo` which can be an external image or with a local url (`/assets/images/yourimage.png`)
* **Categories** - The categories of the project between square brackets `[]`, separated by commas
* **Mapping** - The location of the project on the map with `latitude` en `longitude` coordinates (can be found by clicking on a location on https://www.google.be/maps).

Below `---` you can enter the project text in markdown syntax (see https://www.markdownguide.org/basic-syntax/).


## About the project

Project using Jekyll and jekyll-mapping

