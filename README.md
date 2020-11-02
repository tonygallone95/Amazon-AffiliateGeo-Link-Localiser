# Amazon-AffiliateGeo-Link-Localiser
A simple but effective link localizer for Amazon Affiliates.

Overview: This Link Localiser has been built to automatically redirect users to the correct Amazon locale, for example; If you're linking directly to a product on Amazon.co.uk, a user from Canada will also land on Amazon UK and most likely not make a purchase due to overseas shipping. 

This link localiser takes an individual ASIN for each amazon locale you wish to monetize in addition to individual tracking IDs: 
https://yourwebsite.com/LinkLocaliser.html?UK_ASIN=''&US_ASIN=''&UK_TAG=RYCR_UK&US_TAG=RYCR_US

The end result is a URL that looks like this: (This example is for the US and UK - all locales are supported)
https://yourwebsite.com/LinkLocaliser.html?UK_ASIN=B005IBKI1W&US_ASIN=B005IBKI1W&UK_TAG=RYCR_UK&US_TAG=RYCR_US


Usage:   

  1) 
  2) https://yourwebsite.com/LinkLocaliser.html?UK_ASIN=B005IBKI1W&US_ASIN=B005IBKI1W&UK_TAG=RYCR_UK&US_TAG=RYCR_US

  1) Host the javascript file (LinkLocaliser.html) on your website.
  2) Ensure the 3rd party API service is still up and running by visiting https://get.geojs.io/v1/ip/geo.js, look for your country_code in the returned JSON
  3) 

Future features:
