# How to get Instagram Access Token

Starting from **March 2020**, Facebook requires users to create a Facebook app with Instagram Basic Display API to get a long-live Instagram Access Token. Follow our instructions on this section to get your own Instagram Access Token and paste it back on the **Appearance -> Theme Options -> Additional Code -> Instagram Token**

**You will need:**

* A Facebook account.
* An Instagram account with media.

### **Step 1: Create a new App**

\
Go to [developers.facebook.com](https://developers.facebook.com/), click **My Apps**, and create a new app.

![](../.gitbook/assets/ig-1.png)

![](../.gitbook/assets/ig-step2.png)

![](../.gitbook/assets/ig-step3.png)

![](../.gitbook/assets/ig-step4.png)

Once you have created the app and are in the App Dashboard, navigate to **Settings** > **Basic**, scroll the bottom of the page, and click **Add Platform**.

![](../.gitbook/assets/Screenshot\_58.png)

Choose **Website**, add your website’s URL, and save your changes.

![](../.gitbook/assets/Screenshot\_55.png)

![](../.gitbook/assets/Screenshot\_511.png)

### **Step 2: Configure Instagram Basic Display**

Click **Products**, locate the **Instagram Basic Display** product, and click **Set Up** to add it to your app.

![](../.gitbook/assets/ig-step5.png)

Click **Basic Display**, scroll to the bottom of the page, then click **Create New App**.

![](../.gitbook/assets/ig-step6.png)

In the form that appears, complete each section using the guidelines below.\
_**Display Name**_\
Enter the name of the Facebook app you just created.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-42-21.png)

_**Valid OAuth Redirect URIs**_

Enter your website’s URL.

For example: [https://la-studioweb.com/](https://la-studioweb.com/)

After you enter a URL, save your changes and check the URL again; Instagram may have appended a trailing forward slash depending on your URL structure.

_**Deauthorize Callback URL**_

Enter your website’s URL again.

_**Data Deletion Request Callback URL**_

Enter your website’s URL once again.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-44-29.png)

_**App Review**_

Skip this section for now since you will not be switching the app to **Live Mode** during the tutorial.

Save your changes before heading to the next step.

### **Step 3: Add an Instagram Test User**

Navigate to **Roles** > **Roles** and scroll down to the Instagram Testers section. Click **Add Instagram Testers** and enter your Instagram account’s username and send the invitation.

![](../.gitbook/assets/ig-step7.png)

![](../.gitbook/assets/Screenshot\_59.png)

Open a new web browser and go to [www.instagram.com](https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.instagram.com%2F\&h=AT3IpFSLdh5MMecvubFoSiffDnOhipinduFlVQEukLk8fH553\_YldBY9hlCWjLXyqVPYOBc6r4J7QjpF-q9Ys1RUW64vHJQlFdq8WjVDluEBjJf-rh-qsD1QNxXUiZuthm82NTKAIZjyCFL24-lQHw) and sign in to your Instagram account that you just invited. Navigate to **(Profile Icon)** > Click on the **cogwheel icon next to “Edit Profile” button** > **Apps and Websites** > **Tester Invites** and accept the invitation.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-48-01.png)

![](../.gitbook/assets/Screenshot-at-Jul-02-10-49-01.png)

Your Instagram account is now eligible to be accessed by your Facebook app while it is in **Development Mode**.

### **Step 4: Generate Access Token for Test User**

Navigate to **App Dashboard** > **Products** > **Instagram** > **Basic Display** page and scroll down to **User Token Generator** section. Click on “**Generate Token**” button.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-50-33.png)

Log in with your Instagram account. Allow the app to access your Instagram account data.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-51-23.png)

![](../.gitbook/assets/Screenshot-at-Jul-02-10-51-59.png)

Click on “I understand” checkbox then copy your Instagram Access Token.

![](../.gitbook/assets/Screenshot-at-Jul-02-10-52-35.png)

Paste your Instagram Access Token on **Theme Options -> Integrations -> Instagram Token**

![](<../.gitbook/assets/Screenshot at Aug 10 17-22-59.png>)

{% hint style="info" %}
**Note:** Long-lived tokens are valid for 60 days and our app will refresh your token automatically before they expiring. You will not have to manually regenerate your access token.
{% endhint %}
