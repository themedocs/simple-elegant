---
title: "Site Style & Typography"
description: "Simple & Elegant gives you full control over your site’s look from the Customizer."
---

Simple & Elegant gives you full control over your site’s look from the Customizer.

- **Theme styling** includes the accent color, text color, background and more.
- **Typography** includes setting up your body font, heading font and their sizes.

With Simple & Elegant, you can use a Google font, a Typekit font, any third-party font service, or your own uploaded font.

### 1. Google Font

Using a Google font is straightforward — just pick one under **Customizer > Typography**.

### 2. Typekit Font

To set up a Typekit (or other third-party) font, you’ll need two things: the **font name** and the **font script**. The code provided by Typekit looks something like this:

```
<script src="//use.typekit.net/xxxxxxx.js"></script>
<script>try{Typekit.load();}catch(e){}</script>
```

Copy and paste that code into **Typography > Head Code**. After that, specify the font name in the **Custom Font Name** option below the Google Font selection.

### 3. Self-hosted font (a font you upload)

Upload your font to your server (you may need to use FTP rather than the WordPress uploader, as some systems don’t allow uploading fonts via WordPress). You’ll then have a URL like `http://yourdomain.com/FONT-NAME.ttf`.

Enter your `FONT-NAME` in the **Custom Font Name** field, then go to **Customizer > Typography > Head Code** and add this code:

```
<style type="text/css">
@font-face {
  font-family: FONT-NAME;
  src: url(http://yourdomain.com/FONT-NAME.ttf);
}
</style>
```
