---
title: "Translate Theme"
description: "Simple & Elegant includes a simple-elegant.pot file in /wp-content/themes/simple-elegant/languages/. Open it with translation software such as Poedit, transl..."
---

Simple & Elegant includes a `simple-elegant.pot` file in `/wp-content/themes/simple-elegant/languages/`. Open it with translation software such as [Poedit](https://poedit.net/), translate the strings you need, and save the `.po` and `.mo` files with the appropriate names. For example, to translate into German, save your files as `de_DE.po` and `de_DE.mo`. See [Installing WordPress in Your Language](https://wordpress.org/documentation/article/installing-wordpress-in-your-language/) for more about file naming.

Then open `wp-config.php` in your WordPress root folder, find the line defining the language and set it to the language you want.

### Example: translating into French

**Step 1:** Open `wp-config.php` in your WordPress root folder. You’ll need an FTP client or a file manager to do this.

**Step 2:** Set your site language to French. On modern WordPress, you can simply choose the language under **Settings > General > Site Language**. (On older versions, edit the `WPLANG` definition in `wp-config.php`, e.g. `define('WPLANG', 'fr_FR');` — for German it would be `define('WPLANG', 'de_DE');`.)

**Step 3:** In your theme, copy `simple-elegant.pot` to `fr_FR.po`.

**Step 4:** Open `fr_FR.po` with Poedit, translate the strings, and save the files as `fr_FR.po` and `fr_FR.mo` in the same `simple-elegant/languages` folder.
