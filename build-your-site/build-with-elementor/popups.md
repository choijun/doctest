# Popups

Popups are call to action modal windows that popup and overlay the page at a specified moment or under specific triggers and conditions. Popups are designed to focus a user’s attention once they have taken an action.

{% embed url="https://youtu.be/2lPoObvlB8I" %}

To begin, go to _Templates > Popups_. Control the layout, conditions, rules and styles of the popup, and then design the popup content.

{% hint style="info" %}
**Note**: Click the Popup Settings gear icon in the panel’s bottom toolbar to edit the popup settings. ![](https://elementor.com/help/wp-content/uploads/sites/14/2019/07/cog.png)
{% endhint %}

![](https://elementor.com/cdn-cgi/image/f=auto,w=1024,h=1024/marketing/wp-content/uploads/sites/14/2022/02/image-9-1024x474.png)

### Design Popup

#### Settings

**Layout**

1. **Width**: Set the exact width of the popup, using either px or vh
2. **Height**: Set the exact height of the popup, using either px or vh. Use 100vh for both width and height to create full-screen popups
3. **Horizontal**: Choose the horizontal position of the popup, from Left, Center or Right
4. **Vertical**: Choose the vertical position of the popup, from Top, Center, or Bottom
5. **Overlay**: Show or Hide the background overlay
6. **Close Button**: Choose to Show or Hide the Close button
7. **Show Button After x seconds** (if Show Close Button was chosen): Select the number of seconds to wait before showing the close button
8. **Entrance Animation**: Choose the popup’s entrance animation such as fade and zoom from the dropdown selections. Choose any animation effect to preview the effect.
9. **Exit Animation**: Choose the popup’s exit animation such as fade and zoom from the dropdown selections. Choose any animation effect to preview the effect.
10. **Animation Duration**: Set the length of time for animation, in milliseconds

**General Settings**

1. **Title**: Enter the title of popup. This title will only show on the backend, not to the user.
2. **Status**: Draft, Pending Review, Private, or Published

**Preview Settings**

1. **Preview Dynamic Content as**: Choose from any Archives, Pages, Posts, Media, or 404 pages.

Note: To see the content you’ve chosen, you must reload the page after selecting the dynamic content.

#### Style

![](https://elementor.com/marketing/wp-content/uploads/sites/14/2022/02/image-10.png)

**Popup**

1. **Background Type**: Choose a background color, image, or gradient
2. **Border Type**: Select the type of border, choosing from none, solid, double, dotted, dashed, or grooved
3. **Border Radius**: Set the border radius to control corner roundness for each side of the popup
4. **Box Shadow**: Adjust box shadow options

**Overlay**

1. **Background Type**: Choose a background color, image, or gradient

**Close Button**

1. **Position**: Choose to display the Close button on the Inside or the Outside of the popup
2. **Vertical Position**: Use the slider to select the vertical position of the Close button
3. **Horizontal Position**: Use the slider to select the horizontal position of the Close button

**Normal | Hover**

1. **Color**: Select the color of the Close button for both the Normal and Hover states
2. **Background Color**:  Choose the background color of the Close button for both the Normal and Hover states
3. **Size**: Set the size of the close button

***

#### Advanced

![](https://elementor.com/marketing/wp-content/uploads/sites/14/2022/02/image-11.png)

**Advanced**

1. **Show Close Button After (sec)**: Enter a number of seconds. The close button will only appear after that time has passed.
2. **Automatically Close After (ms)**: Enter the number of ms to wait before automatically closing the popup. Leave blank to disable automatic close.
3. **Prevent Closing on Overlay**: Select Yes to prevent users from being able to close the popup by clicking on the overlay.
4. **Prevent Closing on ESC Key**: Select Yes to prevent users from being able to close the popup by pressing the ESC key.
5. **Disable Page Scrolling**: Select Yes to prevent users from scrolling the page shown behind the popup
6. **Avoid Multiple Popups**: If the user has seen another popup on the page he visits, hide this popup by selecting Yes
7. **Open By Selector**: Enter a list of selectors that will manually trigger the popup (CSS IDs, classes or data-elements). [See instructions](https://elementor.com/help/popups/#customselector)
8. **Margin**: Adjust the margins
9. **Padding**: Adjust the padding around the popup
10. **CSS Classes**: Add your custom class without the dot (e.g. my-class)

**Custom CSS**

**Custom CSS**: Enter your own CSS

***

### Control Popup via Publish Settings

#### Set Conditions

_Conditions_ allow you to set on which pages of your website the popup will appear.

![](https://elementor.com/cdn-cgi/image/f=auto,w=1024,h=1024/help/wp-content/uploads/sites/14/2020/04/Control-Popup-via-Publish-Settings--1024x615.jpg)

Set the conditions that determine where your popup is used (excluding manual triggering). For example, add an Include condition and choose _Singular > Front Page_ to only show the popup on the site’s home page. [Learn more about Conditions.](https://elementor.com/help/conditions/)

#### Set Triggers

_Triggers_ are the user actions that cause your campaign to popup. Select Yes or No for each option that will cause the popup to occur.

![](https://elementor.com/cdn-cgi/image/f=auto,w=1024,h=1024/help/wp-content/uploads/sites/14/2020/04/triggers-1024x612.jpg)

1. **On Page Load**: If set to Yes, set the number of seconds to wait, upon page load, before popup is triggered.
2. **On Scroll**: If set to Yes, select direction (Up or Down) and the amount to scroll before popup is triggered. Down scroll is based on the _percentage_ of the page scrolled down; Up scroll is based on the _number of pixels_ scrolled up.
3. **On Scroll To Element**: If set to Yes, enter the Selector name (CSS ID) that will trigger the popup when user scrolls to it. You must add the CSS ID to the Advanced tab of the element as well.
4. **On Click**: If set to Yes, enter the number of clicks that will trigger the popup
5. **After Inactivity**: If set to Yes, enter the number of seconds of user inactivity that will trigger the popup.
6. **On Page Exit Intent**: Set to Yes to trigger the popup when user’s mouse activity indicates intent to exit the page

#### Advanced Rules

_Advanced Rules_ specify other requirements that must be met to generate a popup.

![](https://elementor.com/cdn-cgi/image/f=auto,w=1024,h=1024/help/wp-content/uploads/sites/14/2020/04/Advanced-Rules--1024x668.jpg)

1. **Show after X page views**: If set to Yes, set the number of page views before popup is triggered.
2. **Show after X sessions**: If set to Yes, set the number of user sessions before popup is triggered (a session starts when the user visits the website and ends when the user closes the browser).
3. **Show up to X times**: Max times the popup will be displayed. If Count is set to On Open, this will only allow the popup to open as many times as the number set. If Count is set to On Close, the popup will only open until the user has closed it for the Xth time, after which it will not open again. This setting is set in the Local Storage and will remain there until deleted.
4. **When arriving from specific URL**: If set to Yes, Show or Hide the popup if a user arrives from a specific URL (enter the specific URL). Regex is an option for advanced users to set advanced rules for matching URL patterns.
5. **Show when arriving from**: If set to Yes, show if user arrives from search engines, an external link (enter URL of specific link) and/or an internal link (enter URL of specific link).
6. **Hide for logged in users**: Set to Yes to hide popup for all logged-in users or from select custom roles. For websites with cache, this feature might not work properly
7. **Show on devices**: Set to Yes to choose to show on Desktop, Tablet, and/or Mobile devices

{% hint style="info" %}
Note: Popups cannot be displayed more than once if the page is not reloaded or re-entered.
{% endhint %}

#### Control Popup Via Manual Triggering

Popups can be triggered manually. Dynamic links can use the Popup Action to open or close a Popup. Form can use the Actions After Submit option to open or close a Popup. Any element can use a unique selector (class, ID or data-element) to manually trigger a popup when that element is clicked.

* From any link element, choose _Dynamic > Actions > Popup_. Click **Popup** to select either _Open Popup_ or _Close Popup_. If Close Popup is chosen, the option, “_Don’t Show Again_” will become an available option.
* From an Elementor form, choose _Actions After Submit > Add Action > Open Popup or Close Popup_
* From a Custom Selector: Any element can have a selector set which can be used as a manual popup trigger. Edit the element and go to _Advanced > CSS Classes_ (or _CSS ID_) and give the element a class name (without the preceding dot) or ID name (without the preceding #). In the popup’s _Conditions_, choose the page that includes the element with the unique selector (e.g. _Conditions > Include > Singular > Pages > Your Page Title_). When a users visits that page, and clicks on the element, the popup will trigger. This is useful for opening a popup from a theme’s navigation menu item, content within a Text Editor widget, from a non-Elementor element or script, etc

{% hint style="info" %}
When triggering a popup from a custom selector, please note that the element doesn’t have to be a “link”. A normally non-clickable element, such as plain text, can be clicked to generate the popup as well. Also note that the _Triggers_ and _Advanced Rules_ will be **disregarded** while using this option.
{% endhint %}
