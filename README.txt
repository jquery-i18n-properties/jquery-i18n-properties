
History
-------

This project was originally created by Nuno Miguel Correia Serra Fernandes
and published on Google Code.  In 2014 it has been migrated to Github
and the official repository is now

  https://github.com/jquery-i18n-properties/jquery-i18n-properties

It has been used in various projects including the WebRTC phone
JSCommunicator (at http://jscommunicator.org) - see the demo there to
see jquery-i18n-properties in action.

Building a minified JavaScript file
-----------------------------------

1. Install the closure compiler tool:

   # apt-get update && apt-get install closure-compiler

2. Run it:

   closure-compiler --js jquery.i18n.properties.js \
                    --js_output_file jquery.i18n.properties.min.js


