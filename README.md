Zermelo App - Open Source Edition
=================================

The Zermelo App allows students, teachers and parents to view schedules and announcements from their Zermelo Portal. Feel free to
fork this app and modify it any way you like. Please note that Zermelo and the Zermelo logo are trademarks of Zermelo Software B.V.
You are not allowed to claim that your version of the app is in any way the official one. Note that this does not constitute an extra
license term for the MIT license below, it's just a part of trademark law.

Improvements to the Open Source Edition of the Zermelo app will be merged into the official Zermelo app and be published to the appstores.
The Zermelo App has about 100.000 installs right now. If you want to share your improvements with all these people please submit a pull request.
If you find bugs, feel free to add them on Github.

For documentation on how to use the Zermelo API please take a look at http://developers.zermelo.nl

Building
========

PhoneGap
--------

The easiest way to build the app both for Android and iOS is using [PhoneGap Build](https://build.phonegap.com). You should create an account
and add signing keys for the platforms you are interested in. Then you can ZIP the contents of the "www" directory (without actually having
"www" as a subdirectory). You can then upload this ZIP file to PhoneGap build to build the app.

Building using Apache Cordova
-----------------------------

You can also use Apache Cordova to build the app:

````bash
zermelo-app$ cordova platform add android

zermelo-app$ cordova build
````

License - App
=============

The code for the app is available under the MIT license. By contributing patches, or submitting pull requests you agree
to license your contributions under the MIT license. You retain all copyright on your contributions. Note that due to the components used,
the app as it is distributed here falls under the GPLv3 license.

Copyright (c) Zermelo Software B.V. and contributors

Permission is hereby granted, free of charge, to any person
obtaining a copy of this software and associated documentation
files (the "Software"), to deal in the Software without
restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES
OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT
HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

License - Components
====================

The app uses various (open source) libraries. The main one is Sencha Touch. Sencha Touch is included in this repository under the GPLv3
license. Note that the Apple and Microsoft app stores do not allow the GPLv3. A solution for this is to use the commercial license for
Sencha Touch. Sencha Touch is available under the commercial license for free from the Sencha Touch website.

Licenses for other components can be found in the respective directories and files.
