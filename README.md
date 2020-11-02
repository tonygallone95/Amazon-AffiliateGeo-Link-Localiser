# Amazon-AffiliateGeo-Link-Localiser
A simple but effective link localizer for Amazon Affiliates.

Overview: This Link Localiser has been built to automatically redirect users to the correct Amazon locale, for example; If you're linking directly to a product on Amazon.co.uk, a user from America will also land on Amazon UK and most likely not make a purchase due to overseas shipping. 

This link localiser takes an individual ASIN for each amazon locale you wish to monetize in addition to individual tracking IDs:
https://yourwebsite.com/LinkLocaliser.html?UK_ASIN=B005IBKI1W&US_ASIN=B005IBKI1W&CA_ASIN=B005IBKICCUK&CA_TAG=CATAGTEST&TAG=RYCR_UK&US_TAG=RYCR_US  (This example is for the US and UK - all locales are supported)

Once a user clicks the link, javascript on the LinkLocaliser.html page gets their country code and builds a corresponding Amazon link. For example:
If a US user clicks the link, the following URL will be built: Amazon.com/gp/product/B005IBKI1W?tag=RYCR_US
If a UK user clicks the link, the following URL will be built: Amazon.co.uk/gp/product/B005IBKI1W?tag=RYCR_UK
If a CA user clicks the link, the following URL will be built: Amazon.ca/gp/product/B005IBKICCUK?tag=CATAGTEST

Once the correct Amazon link has been built, an automatic redirect takes place.

All of this happens in 0.05 seconds

Usage:   

  1) Host the LinkLocaliser.html file on your domain
  2) https://yourwebsite.com/LinkLocaliser.html?UK_ASIN=B005IBKI1W&US_ASIN=B005IBKI1W&UK_TAG=RYCR_UK&US_TAG=RYCR_US

  1) Host the javascript file (LinkLocaliser.html) on your website.
  2) Ensure the 3rd party API service is still up and running by visiting https://get.geojs.io/v1/ip/geo.js, look for your country_code in the returned JSON
  3) Build a URL with the number of ASINs and TAGs you want to use.
  4) Download a VPN to test each location works before deploying any links.
  5) Deploy your links and enjoy the extra sales

Future features:
