# Things you should know about theme updating

**1. It Is Always Recommended To Backup Your Current Setup**&#x20;

* We recommend you have a current backup of your site. Simply go to **Tools > Export** and export your backup.
* You also can use Free[ UpdraftPlus plugin](https://wordpress.org/plugins/updraftplus/) to backup  your site easily&#x20;

**2. Do Not Keep Older Copies of The Theme In WP Theme Folder**&#x20;

You should completely remove all previous theme folders before adding the new updated theme folder. Don't just rename the theme folder. If you rename your theme folder when you update, then the path will be no longer valid. Because WordPress stores menus and widget settings and some other settings by folder path, you will need to rename your theme folder back to what it was before, then your settings, menus, widgets will be restored. So the total renaming process has no meaning.

**3. Reset Browser Cache, Server Cache, and Plugin Cache**

* It is always recommended to reset your browser, plugin, and server cache when you update. Visual issues may happen and more often than not, it's caused by caches, and they need to be emptied. Each browser allows you to remove cookies, history, and other data. If your theme or Insight Core version is not updated after uploading the new files, it is due to a server-side caching system.&#x20;
* Some hosting providers have server-side cache systems installed to optimize the speed of content delivery, please clear any server-side cache or ask your host to do it. This is also true for Google Pagespeed setups or Cloudflare setups.

**4. Update Child Theme**&#x20;

If you have copied template files from parent theme to child theme, please make sure to revert to parent theme first to confirm if the issue exists there too. If it doesn’t, please update the templates copied to the child theme with the parent theme.

**5. Required & Recommended Plugins Must Be Updated**&#x20;

When you update the theme, you will see a notification message in your admin telling you the required and recommended plugins need to be updated. Follow the onscreen prompts to install the plugin updates.&#x20;

We have listed some required plugins and they have to be installed and activated for theme features to work. Make sure you are always using the most recent version of these plugins. You will be prompted to install it upon installing or updating your theme.&#x20;

If you dismiss the prompt or do not see it, then you can go to **Plugins** > **Installed Plugins** > Update Available (if any) and update the plugins there.
