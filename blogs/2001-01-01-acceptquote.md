---
title: "AcceptQuote"
url: "//developers.whmcs.com/api-reference/acceptquote/"
date: "2001-01-01"
feed_url: "https://developers.whmcs.com/api-reference/index.xml"
---
Accepts a quote Request Parameters Parameter Type Description Required action string “AcceptQuote” Required quoteid int The quote id to be accepted and converted to an invoice Required Response Parameters Parameter Type Description result string The result of the operation: success or error invoiceid int The newly created invoice id Example Request (CURL) $ch = curl_init(); curl_setopt($ch, CURLOPT_URL, 'https://www.example.com/includes/api.php'); curl_setopt($ch, CURLOPT_POST, 1); curl_setopt($ch, CURLOPT_POSTFIELDS, http_build_query( array( 'action' => 'AcceptQuote', // See https://developer
