Singularity Pages
=================

Source of the Singularity's login panel and download widget pages.
It adds the ability to notify users about availability of new release.
Otherwise it loads normal grid login page.

In order to change the version update notifications to the users
change line

    var current_version = "1.8.0 (4114)";

to whichever is the latest version is available on the main site
<http://www.singularityviewer.org/>

All of the work is done on "gh-pages" branch so that the pages can be
served from Githb pages.

Login page: <http://singularity-viewer.github.io/pages/login/>

Downloads widget: <http://singularity-viewer.github.io/pages/downloads/>
