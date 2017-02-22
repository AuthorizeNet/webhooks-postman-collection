# Authorize.Net Webhooks API Examples

This repository contains a Postman collection which allows you to easily test the configuration and management of                        Authorize.Net Webhooks. Full Webhooks documentation is available at http://developer.authorize.net/api/reference/features/webhooks.html.

##Usage

Simply download (or edit/copy) the webhooks.postman_collection.json file.
Import into Postman

##Authentication
To test with your own Authorize.Net sandbox account simply replace the Authorization header with your Authorize.Net API_LOGIN_ID and TRANSACTION_KEY.  Remember to add a colon and base64 encode as specified in the Webhooks documentation. Or, enter your API_LOGIN_ID and TRANSACTION_KEY into the "Username" and "Password" fields in the Postman "Authorize" tab to create the Authorization header.

##Examples

* Get Event Types - Lists the current set of events your account can enroll a Webhook on.
* Create a Webhook - Enroll a http endpoint to receive a Webhook for the specified event(s).
* Get a Webhook - Surely this one's obvious. :-)
* Update a Webhook - Modify the endpoint, status, etc..
* Get Notifications - Get a list of all the notifications that have been sent to your Webhooks endpoints along with status info about the response.
* Get Notifications (by date range) - As above with filtering criteria.
* Delete a Webhook - remove a Webhook.
* Send a Test Notification. - send a test notification to the specified Webhook.
