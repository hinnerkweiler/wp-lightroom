Lightroom to Wordpress Publish Service
--------------------------------------

This plugin lets you post to wordpress directly from lightroom. It creates a new post when you add a photo to the collection with meta data from the image. Caption and Title need to be specified. It'll then retrieve any comments, and it'll try to link lightroom categories to wordpress equivalents (they need to already exist in wordpress). Then it will upload the image to the media library and set it as the featured image for the new post. Ideal for single post photoblog.


It consists of a wordpress plugin and a lightroom plugin.

Lightroom
---------
* In Lightroom goto File > Plugin Manager
* Click add, browse to the directory where Wordpress.lrdevplugin is, hit add
* Goto you library, scroll to the bottom left where publish services are and right click edit, wordpress should be listed
* You need to enter your username, password, and url to the blog, setup what size you'd like your images to be and compression settings

Wordpress
---------
* Upload wp-lightroom to wp-content/plugins/
* Goto Plugins in the admin dashboard, activate the wp-lightroom plugin
* No configuration needed
