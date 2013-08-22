bootstrap-flat
==============

A simple flat theme for Twitter Bootstrap 3. To see Bootstrap flat in action, check out the [documentation](http://scottdorman.github.io/bootstrap-flat).

****

While Bootstrap 3 does away with the skeumorphic design characteristics of earlier versions, making it mostly a flat design, it doesn't completely embrace the "modern" design elements (inspired by Microsoft's Modern Design Language of Windows Phone and Windows 8) and still includes soft, rounded edges on many of the UI elements.

There are several other "flat" or "modern" skins for Bootstrap but they are completely custom Bootstrap implementations and in most cases include their own, modified, version of bootstrap.css. This makes it difficult to upgrade to newer versions of Bootstrap as it's dependent on those skins being updated as well.

This project aims to change that and is built using Bootstrap's recommended method of providing "light" customizations. In other words, there have been absolutely no functional changes to Bootstrap but only surface layer visual changes. There are no custom colors, custom controls, or custom JavaScript files to include.

To simply achieve the standard Bootstrap 3 look with a completely flat user interface (no rounded edges), you need to include the bootstrap-flat.css file after you include the Bootstrap source.

If you want some additional custom styles, include the bootstrap-theme.css after you include the Bootstrap source. Right now (more to come), this only adds a custom themed button style .btn-striped that will apply the Bootstrap button color (from .btn-danger, .btn.warning, etc.) and turn it into a left-vertical stripe.
