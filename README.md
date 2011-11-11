# Load Any Version of jQuery on Your Webpage

The two script tags in `snippet.htm` replace the typical jQuery include
tag, like `<script src="//ajax.googleapis.com/ajax/libs/jquery/1.7.0/jquery.min.js"></script>`.

Replace the version number in the googleapis.com path to the
default/main version you want to use on your webpage. Also, be sure to
change the local path in the second script tag to a local copy of
jQuery.

As-is, jQuery will be included on your page just like normal. However,
if you pass `?jqversion=` and a version tag, you can load any version,
even betas and release-candidates, in your page and help the
jQuery project test these versions before final release.

For example, `http://yoursite.com/?jqversion=1.7.1rc1` will load
`1.7.1rc1` from the jQuery CDN.

Demo: http://jsbin.com/exipas/2/
