Singularity login page
======================

Source of the Singularity's login panel splash page.
It adds the ability to notify users about availability of new release.
Otherwise it loads normal grid login page.

In order to change the version update notifications to the users
change line

    var current_version = "1.8.0 (4114)";

to whichever is thelatest version is available on the main site
<http://www.singularityviewer.org/>