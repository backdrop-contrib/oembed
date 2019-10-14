oEmbed
======

oEmbed is a CKEditor plugin that allows you to insert embedded content (such as
photos, video, audio, etc.) via an external URL. For example, you can embed a
YouTube video into your content simply by pasting in the URL to the video. The
same goes for Flickr photos, Soundcloud audio, and much more!

This module provides a very simple integration between CKEditor's '[Media
(oEmbed) Plugin](https://ckeditor.com/addon/oembed)' and Backdrop.

NOTE: This module will automatically add `<iframe>` and `<div>` tags to the list
of 'Allowed HTML Tags' for any text format it's enabled on.

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page of a text format under Administration >
  Configuration > Content authoring > Text editors and formats > [FORMAT]
  (admin/config/content/formats/[FORMAT]).

- Enable the CKEditor text editor (if not already).

- Add (by dragging to the Active Toolbar) the 'oEmbed' button.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/oembed/issues.

Current Maintainers
-------------------

- Peter Anderson (https://github.com/BWPanda).

Credits
-------

- Written for Backdrop by Peter Anderson (https://github.com/BWPanda).
- Integrates CKEditor's 'Media (oEmbed) Plugin'
  (https://ckeditor.com/addon/oembed).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

