---
title: "AddCancelRequest"
url: "//developers.whmcs.com/api-reference/addcancelrequest/"
date: "2001-01-01"
feed_url: "https://developers.whmcs.com/api-reference/index.xml"
---
Adds a Cancellation Request Request Parameters Parameter Type Description Required action string “AddCancelRequest” Required serviceid int The Service ID to cancel Required type string The type of cancellation. ‘Immediate’ or ‘End of Billing Period’ Optional reason string The customer reason for cancellation Optional Response Parameters Parameter Type Description result string The result of the operation: success or error serviceid int The id of the service the request was for userid int The id of the user the service belongs to Example Request (CURL) $ch = curl_init(); curl_setopt($ch, CURLOP
