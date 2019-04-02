---
layout: page
permalink: /submissions/
title: Submission Guidelines
show_meta: false
published: true
description: "Submissions"
comments: false
mathjax: false
gistembed: true
noindex: false
sitemap:
    priority: 0.5
    changefreq: 'monthly'
    lastmod: 2016-02-13
tags:
---

So you want to contribute?  Awesome!

Each file lives in it's own sub-directory in the catalog directory and should have at least the following:

- A FreeCAD project file (fcstd).

    This is necessary so the file can be revised and maintained over time.
    The document should have at least one top-level document object.
    The top-level object should have its label set to match the file name (eg Drilling_1)
    The file should be saved with a thumbnail included (Preferences/Document 'Save thumbnail into project when saving document')
    Change the FreeCAD project information and mark the file license as Creative Commons.

- A STEP file.  This allows the shapes to be used by other CAD/CAM applications. From FreeCAD, Select the top level object and export as a step with colors (eg Drilling1.stp)

- Create a page in the _pages directory explaining the purpose of the file, key features, and any other notes. It's worth copying one of the other examples as a starting point.  They contain some additional boilerplate to help with navigation on the site.

- Screenshot image
   Create a screenshot image of the part to be used on the website.  The image should be 320x320 with transparent background.  The macro below can be useful.


<code data-gist-id="30216c6b6b47103c96159be64461425b" data-gist-file="screenshot.FCMacro" data-gist-line="1-18"></code>

