## Overview ##

The goal of this project is to provide a thin layer around the Eloqua SOAP messaging that consumes the standard Eloqua WSDL and implements the Eloqua API 1.2 spec.  The Eloqua PHP SDK supports all methods enumerated in the Eloqua WSDL, including the those which are currently undocumented.

Included in the tarball is [EXAMPLES](http://code.google.com/p/eloqua-php-sdk/source/browse/trunk/EXAMPLES), which includes a code example for every Eloqua API method call.

If the SDK appears to be slow, you likely have WSDL caching disabled.  It can be enabled either by the following entry in php.ini:

`soap.wsdl_cache_enabled=1`

or by the following function call:

`ini_set('soap.wsdl_cache_enabled', 1);`

## Dependencies ##

The SDK requires the native PHP SOAP client, standard in PHP 5.0.1+.

## Source ##

The source is currently available via anonymous SVN and as a tarball.  Release snapshots can be found in tags/.<br />

## Feedback ##

Please feel free to drop me a line at dlanstein gmail if you have any feedback, it would certainly be appreciated.

## Acknowledgements ##

I would like to thank my employer, [Splunk, Inc.](http://www.splunk.com), for donating time to this and many other open-source projects (like <a href='http://code.google.com/p/salesforce-python-toolkit/'>this one</a>).