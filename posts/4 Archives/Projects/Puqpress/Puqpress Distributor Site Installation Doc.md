---
date: 2022-08-07
company: Puqpress
summary: "Installig Wordpress Distributor Site"
publish: false
tags: wordpress
---

# Puqpress Distributor Site Installation Doc

## Help on installation

Please call TJ or email Niels ([niels@primordial.nl](https://mailto:niels@primordial.nl)).

Niels knows about you installing the site and expects questions.

Please add TJ to the CC.

## Files
[http://projects.primordial.nl/puq.zip](http://projects.primordial.nl/puq.zip)
[http://projects.primordial.nl/puq.sql.zip](http://projects.primordial.nl/puq.sql.zip)

## Login
User: baristatech
Pass: uv4TKKVrRdL#UK)ihMQKLvIS


Todo’s - necessary for PUQPress dealer site
1.  **hosting setup**
Mysql database
Php 5.6 + (preferred higher version 7.4)

2. Google tagmanager / analytics setup + e-commerce
3. Setup Google map keys in store locator

/wp-admin/edit.php?post_type=wpsl_stores&page=wpsl_settings

Browser key and server key
[https://console.cloud.google.com/google/maps-apis/overview](https://console.cloud.google.com/google/maps-apis/overview)

4. setup email addresses in contact forms.

1.  contact form is connected to find a dealer.. that we don’t use.. (yet)

Please don’t touch)
5. Add recaptcha key if needed
5. Connect mailchimp. (Newsletter)

Setup a mail chimp account connect anohter mail chimp widget

Use mailchinmp key, and select list
[http://projects.primordial.nl/puq/wp-admin/options-general.php?page=another-mailchimp-widget](http://projects.primordial.nl/puq/wp-admin/options-general.php?page=another-mailchimp-widget)

6. Connect mail chimp to WooCommerce)
Connect to WooCommerce for collecting data of consumers and being able to mail them with deals, follow ups etc..
7. Setup payment methods WooCommerce
8. check policy’s etc..