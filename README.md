# Authorize.Net Webhooks API Examples

This repository contains a postman collection which allows you to easily configure and manage Authorize.Net Webhooks.

##Usage

Simply download (or edit/copy) the webhooks.postman_collection.json file.
Import into Postman

##Authentication
To test with your own Authorize.Net sandbox account simply replace the Authorization header with your Authorize.Net API_LOGIN_ID and TRANSACTION_KEY.  Remember to add a colon and base64 encode.

##Examples

* Get Event Types - Lists the current set of events your account can enroll a webhook on.
* Create a Webhook - Enroll a http endpoint to receive a webhook for the specified event(s)
* Get a Webhook - Surely this ones obvious :-)
* Update a Webhook - Modify the endpoint, status, etc
* Get Notifications - Get a list of all the notifications that have been sent to your webhooks along with status info about the response.
* Get Notifications (by date range) - As above with filtering criteria
* Delete a web hook - remove a webhook.
