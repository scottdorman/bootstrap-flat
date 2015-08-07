# Bootstrap Flat [![GitHub license](https://img.shields.io/github/license/scottdorman/bootstrap-flat.svg)](https://github.com/scottdorman/bootstrap-flat/blob/master/LICENSE)

| | |
|-------|------|
|bootstrap-flat|[![NuGet downloads](https://img.shields.io/nuget/dt/bootstrap.flat.svg)](http://www.nuget.org/packages/bootstrap.flat) [![NuGet version](https://img.shields.io/nuget/v/bootstrap.flat.svg)](http://www.nuget.org/packages/bootstrap.flat)  [![Bower version](https://img.shields.io/bower/v/bootstrap-flat.svg)](http://www.nuget.org/packages/bootstrap-flat)|
|bootstrap-flat-less|[![NuGet downloads](https://img.shields.io/nuget/dt/bootstrap.flat.less.svg)](http://www.nuget.org/packages/bootstrap.flat.less) [![NuGet version](https://img.shields.io/nuget/v/bootstrap.flat.less.svg)](http://www.nuget.org/packages/bootstrap.flat.less)|
|bootstrap-flat-sass|[![NuGet downloads](https://img.shields.io/nuget/dt/bootstrap.flat.sass.svg)](http://www.nuget.org/packages/bootstrap.flat.sass) [![NuGet version](https://img.shields.io/nuget/v/bootstrap.flat.sass.svg)](http://www.nuget.org/packages/bootstrap.flat.sass)|

A simple flat theme for [Twitter Bootstrap](http://getbootstrap.com) 3. To see Bootstrap flat in action, check out the [documentation](http://scottdorman.github.io/bootstrap-flat).

****

While Bootstrap 3 does away with the glossy and gradient characteristics of earlier versions, making it mostly a flat design, it doesn't completely embrace the "modern" design elements (inspired by Microsoft's Modern Design Language of Windows Phone and Windows 8) and still includes soft, rounded edges on many of the UI elements.

There are several other "flat" or "modern" skins for Bootstrap but they are completely custom Bootstrap implementations and in most cases include their own, modified, version of bootstrap.css. This makes it difficult to upgrade to newer versions of Bootstrap as it's dependent on those skins being updated as well.

This project aims to change that and is built using Bootstrap's recommended method of providing "light" customizations. In other words, there have been absolutely no functional changes to Bootstrap but only surface layer visual changes. There are no custom colors, custom controls, or custom JavaScript files to include.

To simply achieve the standard Bootstrap 3 look with a completely flat user interface, you need to include the bootstrap-flat.css file after you include the Bootstrap source. If you want some additional custom styles, include the bootstrap-flat-extras.css stylesheet after you include the Bootstrap and Bootstrap Flat stylesheets.

## Bugs and feature requests

Have a bug or a feature request? [Please open a new issue](https://github.com/scottdorman/bootstrap-flat/issues). Before opening any issue, please search for existing issues and read the [Issue Guidelines](https://github.com/necolas/issue-guidelines), written by [Nicolas Gallagher](https://github.com/necolas/).



## Versioning

For transparency and insight into our release cycle, and for striving to maintain backward compatibility, Bootstrap will be maintained under the Semantic Versioning guidelines as much as possible.

Releases will be numbered with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes and misc changes bumps the patch

For more information on SemVer, please visit [http://semver.org/](http://semver.org/).



## Authors

**Scott Dorman**

+ [http://twitter.com/sdorman](http://twitter.com/sdorman)
+ [http://github.com/scottdorman](http://github.com/scottdorman)


## Copyright and license

Copyright 2013 Scott Dorman under [the Apache 2.0 license](LICENSE).

