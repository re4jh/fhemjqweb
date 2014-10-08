fhemjqweb
=========

FHEMJQWEB is FHEMWEB with jQuery and a bunch of modern web techniques.

1. To get a running extra www2 you should copy an original www to www2 and replace those files, you find in the repository.
2. Copy 99_FHEMJQWEB.pm to your FHEM Folder (default is /opt/fhem/FHEM)
3. Don't forget to define your FHEMJQWEB
```
define jqFrontend FHEMJQWEB <portnumber> global
```
4. Currently i work and develop with the following attributes
```
attr jqFrontend HTTPS 1
attr jqFrontend alias Web Access Desktop
attr jqFrontend basicAuth <base64_of_my_username_password_combination>
attr jqFrontend stylesheetPrefix dark
```
5. FHEMJQWEB is derived from FHEMWEB, so read its <a href="http://fhem.de/commandref.html#FHEMWEB" target="_blank">commandref</a>!


