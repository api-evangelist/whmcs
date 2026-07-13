---
title: "AddBannedIp"
url: "//developers.whmcs.com/api-reference/addbannedip/"
date: "2001-01-01"
feed_url: "https://developers.whmcs.com/api-reference/index.xml"
---
Adds an IP to the ban list. Request Parameters Parameter Type Description Required action string “AddBannedIp” Required ip string Required reason string Admin only reason Required days int If passed, expires date is auto calculated Required expires \datetime YYYY-MM-DD HH:MM:SS Optional Response Parameters Parameter Type Description result string The result of the operation: success or error banid int The id of the new ban entry Example Request (CURL) $ch = curl_init(); curl_setopt($ch, CURLOPT_URL, 'https://www.example.com/includes/api.php'); curl_setopt($ch, CURLOPT_POST, 1); curl_setopt($ch
