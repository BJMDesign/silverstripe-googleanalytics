# Google Analytics Module #

## Maintainer Contact ##
Luke Hudson (nickname: silverluke)
<luke (at) silverstripe (dot) com>

## Requirements ##
This module requires SilverStripe 2.4

## Documentation ##
http://doc.silverstripe.com/doku.php?id=modules:newsletter

## Installation Instructions ##
1. Copy the 'googleAnalytics' folder to the base of your silverstripe installation.
2. Navigate to /db/build to create the table for this module (eg. http://mysite/db/build)
	
## Usage ##

### Analytics ###

In the main CMS interface, an 'Analytics' report has been added to the 'Site
Reports' feature (under the site tree)

This report provides access to Google Analytics from within silverstripe (via
the 'View Google Analytics' item).  It also allows you to add the Google
Analytics tracking "urchin" to your site without modifying your site template.
To use this feature, copy the snippit of code provided in the google analytics
interface, and paste in the the box provided by the 'Setup Analytics' item.
Visitors to your site will now be tracked by Analtics.

### Index Status ###

A new piece of data has been added to every page in your silverstripe
installation.  In the main CMS, there is now an 'Index' tab under the 'Reports'
tab.  This provides a view of which search engines have indexed each page on
your site, and if the latest version of your pages has been indexed by search
engines.

