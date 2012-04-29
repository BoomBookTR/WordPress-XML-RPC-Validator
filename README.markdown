# WordPress XML-RPC validator #

WordPress plugin that checks the validity of the XML-RPC Endpoint of WordPress sites.

## Details ##

This plugin does the following:

- Download the document at the URL specified on the web form
- Find-download-parse the RSD Document
- Test the XML-RPC endpoint calling system.listMethods
- Verify that all methods are all available
- Start a real call using dummy credentials and verify that the XML-RPC service is active
- Steps Two
- Get the user blogs
- Start few xmlrpc calls on each blog and analyses the response (it checks for invalid characters for example)

## External libs ##

This plugin uses the following libs:

- https://github.com/daniloercoli/php-mobile-useragent