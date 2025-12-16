# capacoa-artsdata-usermeta

This is a Wordpress plugin that adds additional fields to [CAPACOA's WP REST User API](https://www.capacoa.ca/wp-json/wp/v2/users) so CAPACOA member organizations can be uploaded to Artsdata.

This plugin is for CAPACOA only.

Here is an example call to get a list of 50 users:

`GET /wp-json/wp/v2/users?per_page=50`

# Pipeline to Artsdata

The data made available from this Wordpress plugin is used by the data pipeline in the artsdata-planet-capacoa repository.
https://github.com/culturecreates/artsdata-planet-capacoa


# CAPACOA member directory webpage

The CAPACOA member directory displays data from Artsdata using the following Wordpress short-code plugin
https://github.com/culturecreates/artsdata-shortcode
