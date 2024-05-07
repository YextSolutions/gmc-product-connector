# gmc-product-connector

# Product Description

Our Google Merchant Center Product Connector imports all of your products from Google Merchant Center into the Knowledge Graph. The app uses OAuth2 to get access to your GMC account. The app automatically pulls in the following fields:

- Additional Size Type
- Ads Redirect URL
- Canonical Link
- Display Ads
- Energy Efficiency Class
- Excluded Destinations
- Google Product Category
- Identifier Exists
- Included Destinations 
- Item Group ID
- Maximum Energy Efficiency Class
- Minimum Energy Efficiency Class
- Pickup Method
- Promotion IDs
- Sale Info
- Sales Channel
- Shipping Info
- Shipping Label
- Shopping Ads Excluded Countries
- Shopping Ads Labels
- Sizes
- Target Country
- Tax Category Label
- Tax Info
- Transit Time Label


# Requirements

In order for this connector to run, you must have already linked your Google account with Yext with the correct scope. You must also have your Merchant ID associated with your Google Merchant Center account.


### To install the GMC Product Connector:


1. If you’ve already linked your Google account with Yext (and have its ID readily available), skip to Step 5. Otherwise, head to Knowledge Graph (in the navigation bar) > Configuration > Linked Accounts. In the Google provider row, click Add a Linked Account.
2. Select the following scope: https://www.googleapis.com/auth/content and click Link.
3. In the popup modal, select the Google account associated with your Business Profile. 
4. Click Continue and then provide a name for your Linked Account. Copy the ID, and click Save.
5. Head to the Google Google Merchant Center Product Connector app listing and click Install. 
6. On the following screen, click Next. Then enter your Linked Account ID followed by Merchant ID for the Google Merchant Center account from which you would like to pull products. Click Authorize.
7. You will be redirected to the connector page where you can click Edit Configuration to see the data that will be pulled in. Or, you can click Run Connector to automatically import the data.
