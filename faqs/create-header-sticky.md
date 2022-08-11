# Create Header Sticky

### How to Create a Shrinking Header With Elementor

\
Once you have your regular header ready to go, this section will cover how to make it shrink.

To create this effect, you’ll rely heavily on some custom CSS. However, we’ll give you the exact code that you need and walk you through customizing it to match your site.

#### 1. Edit Your Header Template in Elementor

To get started, use Elementor Theme Builder to edit the template for your header.

In your WordPress dashboard, go to **Templates → Theme Builder** and click **Edit With Elementor** for your header template.

#### 2. Perform Some Basic CSS Housekeeping

To make sure your header works with the CSS code that you’ll use in the next sections, you’ll want to perform a little housekeeping.

First, open the settings for the section that contains your header.

In the **Layout** tab, set the **HTML Tag** drop-down equal to **header**:

![](https://elementor.com/cdn-cgi/image/f=auto,w=610/marketing/wp-content/uploads/sites/9/2020/08/header-html-tag.png)

Also in the **Layout** tab, make sure there’s no **** Minimum Height set, set the **Vertical Align** to **Middle**, and then set **Columns Gap** to **No Gap** to avoid unnecessary padding. **Tip**: Avoid using top/bottom padding under Advanced.

![](https://elementor.com/cdn-cgi/image/f=auto,w=597,h=1129/marketing/wp-content/uploads/sites/9/2020/08/header-vertical-align-middle.jpg)

Then, go to the **Advanced** tab and Set Up Motion Effects to Make Your Header Stick



To make sure your header sticks to the top as users start scrolling, you can use Elementor’s **Motion Effects** feature.

Open the settings for the section that contains your header. Then, go to the **Advanced** tab and open the **Motion Effects** settings:

* Set the **Sticky** drop-down equal to **Top**.
* Make sure that the **Sticky On** box only includes **Desktop** – you’ll need to delete the other devices.
* Set the **Effects Offset** equal to **90** (to your header’s height).

![
](https://elementor.com/cdn-cgi/image/f=auto,w=617/marketing/wp-content/uploads/sites/9/2020/08/shrinking-header-motion-effects.png)

{% hint style="info" %}
**Note:** To disable the header sticky, you should change the value of **Sticky** to **None**
{% endhint %}
