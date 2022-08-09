# Theme requirements

To use ZUMMA, you must be running **WordPress 5.0 or higher, PHP 5.6 or higher, and MySQL 5 or higher**. We have tested it with Mac, Windows, and Linux. Below is a list of items you should ensure your host can comply with.

* Check to ensure that your web host has the minimum requirements to run WordPress.
* Always make sure they are running the latest version of WordPress.
* You can download the latest release of WordPress from the official [WordPress](https://wordpress.org) website.
* Always create secure passwords for FTP and Database.

{% hint style="info" %}
**Hosting is more secure** when PHP applications, like WordPress, are running using your account’s username instead of the server’s default shared username (www or www-data). The most common way for hosting companies to do this is using PHP. Just ask your potential host if they run PHP or something similar.
{% endhint %}

## Recommended PHP Configuration Limits <a href="#recommended-php-configuration-limits" id="recommended-php-configuration-limits"></a>

Many issues that you may run into such as white screen, demo content fails when importing, empty page content, and other similar issues are all related to low PHP configuration limits. The solution is to increase the PHP limits. You can do this on your own, or contact your web host and ask them to increase those limits to a minimum as follows:

* `max_execution_time 180`
* `memory_limit 256M`
* `post_max_size 32M`
* `upload_max_filesize 32M`

You can verify your PHP configuration limits in the System tab in the Elementor. Take a look in the left sidebar for **WP Dashboard** > **Elementor** > **System info**.

![](<../.gitbook/assets/Screenshot at Aug 10 05-41-28.png>)

Your mission is to make those 4 sections turn from yellow to green.



### **Tips For This Part** :thumbsup:****

* **WP Memory Limit**: find the file wp-config.php. Add the line&#x20;

```
define(‘WP_MEMORY_LIMIT', '256M' )
```

above the line **/That's all, stop editing! Happy blogging./**

![](https://3490417153-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FCGEvkIGZQql1dvbXwu25%2Fuploads%2FRY3Qng0qawYZifoUqT7O%2Ftheme%20requirements%202%20WP-Memory-Limit.png?alt=media\&token=a1eadca2-9725-4db5-bb66-005e544323c9)

* **WP Debug Mode**: It is not important to set WP Debug Mode then do not worry about it.
* **PHP Time limit**: find the file wp-config.php. Add the line **“set\_time\_limit(600);”** above the line **/That's all, stop editing! Happy blogging./**

![](https://3490417153-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FCGEvkIGZQql1dvbXwu25%2Fuploads%2FGxZRvSKWIdGavkPfsArB%2Ftheme%20requirements%203%20PGP-Time-limit.png?alt=media\&token=7c4fed5f-f86b-4694-8ac5-e21b32673ab4)

* **PHP Max Input Vars**: Find .htaccess in folder Root of website. Add the line **“php\_value max\_input\_vars 5000”**

## How to choose PHP version and enable PHP extension <a href="#how-to-choose-php-version-and-enabale-php-extension" id="how-to-choose-php-version-and-enabale-php-extension"></a>



**Step 1**: Go to cPanel find **Select PHP version**

![](https://3490417153-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FCGEvkIGZQql1dvbXwu25%2Fuploads%2Fuza0mFtjxRdJ177RuR52%2F2.1%20select-php-version.png?alt=media\&token=71bac955-11d7-4301-9282-a1722d5c796b)

**Step 2**: Choose version 5.6 and enable XML reader extension

**Step 3**: Save the file

![](https://3490417153-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FCGEvkIGZQql1dvbXwu25%2Fuploads%2FDgp10nUTVp7rA4FtzrzB%2F2.2%20image.png?alt=media\&token=53a881fb-1970-4243-b84a-a7c93e5e4040)

{% embed url="https://www.youtube.com/watch?ab_channel=RINMusic&v=Kv2Ok5b0e14" %}
