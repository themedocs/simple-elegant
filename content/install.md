---
title: "Install Theme"
description: "Before installing the Simple & Elegant theme, you have to install WordPress. To install WordPress, please check this page: How to install WordPress."
---

Before installing the Simple & Elegant theme, you have to install WordPress. To install WordPress, please check this page: [How to install WordPress](https://wordpress.org/documentation/article/how-to-install-wordpress/).

There are two ways to install Simple & Elegant. If you get a “stylesheet missing” issue during installation, please see the [Common installing issues](#common-issues) section below.

### Method 1: Install from the WordPress backend

We assume you have already logged into your WordPress backend.

**Step 1:** Go to **Dashboard > Appearance > Themes**.

**Step 2:** Click **Add New**, then click **Upload Theme**.

![Appearance > Themes screen with the Upload Theme button highlighted](/simple-elegant/assets/se-install-upload-theme.png)

**Step 3:** Upload the `simple-elegant.zip` file then click **Activate**. Note that if your downloaded package was `Simple - Elegant v2.1.zip`, you need to unzip that package first to get the `simple-elegant.zip` file — that is the actual theme file.

**Step 4:** Go to **Appearance > Install Plugins** to install the necessary plugins. **Visual Composer** and **(Simple & Elegant) Addons** are mandatory.

- Install **(Simple & Elegant) Portfolio** if you want a portfolio on your site.
- Install the **WooCommerce** plugin if you wish to set up a shop.

### Method 2: Install via FTP

We assume you have knowledge of FTP. FileZilla is a free FTP client — you can [learn more about it here](https://filezilla-project.org/).

**Step 1:** Unzip your download package from ThemeForest. If you don’t see a folder named `simple-elegant`, continue to unzip `simple-elegant.zip` — you’ll get a folder named `simple-elegant`.

**Step 2:** Upload the `simple-elegant` folder to `ROOT_FOLDER/wp-content/themes/` on your server and wait for the upload to complete.

**Step 3:** Go to **Dashboard > Appearance > Themes**. You’ll see Simple & Elegant there — click to activate the theme.

**Step 4:** Go to **Appearance > Install Plugins** to install the necessary plugins. **Visual Composer** and **(Simple & Elegant) Addons** are mandatory. Install **(Simple & Elegant) Portfolio** for a portfolio, and **WooCommerce** for a shop.

### Common installing issues

**Theme is missing the style.css stylesheet.** This usually means you uploaded the wrong zip. Make sure you upload `simple-elegant.zip` (the actual theme file), not the full ThemeForest download package.

**Cannot upload…** If you install via Method 1 (uploading from the backend), you may hit this because of your server’s upload limit. Check your limit at **Dashboard > Media > Add New** — you’ll see “Maximum upload file size: xx MB” at the bottom. The `simple-elegant.zip` file is **16 MB**, so if your server’s upload limit is smaller (the default is 8 MB on most hosts), ask your hosting provider to increase it to at least **32 MB**, or use Method 2 (FTP) instead.
