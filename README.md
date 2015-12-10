#The Ckeditor-dropoff Plugin

This pluggin is a easy and lasy way to disable navigator drop on Ckeditor.

Why disable it? Some times you don't want the an user can drop an image into ckeditor for example.

Did you try do config.removePlugins = 'dragdrop,basket'; but it doesn't work at all?

Then it's what you need!

# Installation

1. Download it
2. Move ./dist/dropoff to ckditorfolder/plugins
3. Locate ckeditor "config.js"
4. Put "dropoff" on config.extraPlugins, like this config.extraPlugins = 'mypreviousplugin,dropoff'
5. Be Happy!
