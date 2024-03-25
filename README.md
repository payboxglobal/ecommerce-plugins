## Wordpress Widget
A simple plugin based on woocommerce for Wordpress integrators, this plugin works provided you are using woocommerce for your store.

## Requirements
- PHP 7.0 or later (tested up to 8.1.6)
- WordPress 6.0.7
- WooCommerce 7.7.0

## Install Wordpress
- Unzip wordpress-6.0.7.zip. Within it is a single folder `wordpress/`.
- Copy all the contents within `wordpress/` to the desired location on your web server.
    - If you want to integrate WordPress into the root of your domain (e.g. https://example.com/), move or upload all contents of the unzipped WordPress directory (excluding the WordPress directory itself) into the root directory of your web server.
    - If you want to have your WordPress installation in its own subdirectory on your website (e.g. https://example.com/blog/), create the blog directory on your server and upload the contents of the unzipped WordPress package to the directory via FTP.
    - Note: If your FTP client has an option to convert file names to lower case, make sure it’s disabled.
- Run the WordPress installation script by accessing the URL in a web browser. This should be the URL where you uploaded the WordPress files.
    - If you installed WordPress in the root directory, you should visit: https://example.com/
    - If you installed WordPress in its own subdirectory called blog, for example, you should visit: https://example.com/blog/
That’s it! WordPress should now be installed.

## Install the WooCommerce in WordPress
- Unzip the `woocommerce.7.7.0.zip` file locally so that you have the `woocommerce/` folder on your hard drive.
- Transfer the extracted folder to the `wp-content/plugins` directory of your WordPress site via SFTP or remote file manager.
From the Plugins menu in the Administration Screen, click Activate for the transferred plugin.

## Setup for use
- On the WooCommerce PayBox Gateway setup page, go through and fill out your merchant details and make amends where you see fit.
- After the above is complete, head to the General tab on the same page.
- Scroll to the Currency options section and set Ghana Cedi (GHS) as your main currency.
- Now visit your site, add some items to your cart and checkout using PayBox
- All done!