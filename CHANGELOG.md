Changelog
=========

1.2.0
-----
-   Fixed issue when non-unicode data was passed in metadata
-   Filters are now applied for substring matches ("password" will now also
    match "confirm_password")
-   Ignore django.http.Http404 exceptions by default when using 
    django middleware

1.1.2
-----
-   Log trace when HTTP exception

1.1.1
------
-   Log the trace when theres an exception notifying