fhemjqweb
=========

FHEMJQWEB is FHEMWEB with jQuery and a bunch of modern web techniques.

<ol>
	<li>To get a running extra www2 you should copy an original www to www2 and replace those files, you find in the repository.</li>
	<li>Copy 99_FHEMJQWEB.pm to your FHEM Folder (default is /opt/fhem/FHEM)</li>
	<li>Don't forget to define your FHEMJQWEB
	<pre>define jqFrontend FHEMJQWEB <portnumber> global</pre></li>
	<li>Currently testing and developing goes with the following attributes:
	<pre>
attr jqFrontend HTTPS 1
attr jqFrontend alias Web Access Desktop
attr jqFrontend basicAuth <base64_of_my_username_password_combination>
attr jqFrontend stylesheetPrefix dark
</pre></li>
	<li>FHEMJQWEB is derived from FHEMWEB, so read its <a href="http://fhem.de/commandref.html#FHEMWEB" target="_blank">commandref</a>!</li>
</ol>