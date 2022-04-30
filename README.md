## Step 1: Add New Directus Site

On a new server in your [cleavr.io account](https://cleavr.io), add a new site and select **Directus** as the app type.

Expand **Advanced Options** and enable the option to **Setup Database**. Select MySQL for your database server type. 

![Add database](https://docs.cleavr.io/images/directus/database.png)


## Step 2: Connect code repository

In the web app section, select **Complete Setup** for the web app that was created for the site.

On the **Code Repository** tab, enter the following:

**Version Control Provider**: GitHub

**Repository**: `cleavr/directus-example`

**Branch**: `master`

Click **Update**.


## Step 3: Deploy!

Once you have everything configured, deploy! 🚀

After deployment, check the `Build Assets` logs. You will get the initial email and password to login to your Directus app.

![Initial Directus Admin Details](https://docs.cleavr.io/images/directus/initial-directus-admin.png)

Use the email and password to login to your Directus App. You can change the credentials later.

![Directus Admin Login](https://docs.cleavr.io/images/directus/directus-admin-login.png)

![Directus Collections](https://docs.cleavr.io/images/directus/directus-collections.png)
