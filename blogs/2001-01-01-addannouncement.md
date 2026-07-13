---
title: "AddAnnouncement"
url: "//developers.whmcs.com/api-reference/addannouncement/"
date: "2001-01-01"
feed_url: "https://developers.whmcs.com/api-reference/index.xml"
---
Adds an announcement. Request Parameters Parameter Type Description Required action string “AddAnnouncement” Required date \datetime Date in the format YYYY-MM-DD HH:MM:SS Required title string Required announcement string Announcement text Required published bool Pass as true to publish Optional Response Parameters Parameter Type Description result string The result of the operation: success or error announcementid int The id of the new announcement Example Request (CURL) $ch = curl_init(); curl_setopt($ch, CURLOPT_URL, 'https://www.example.com/includes/api.php'); curl_setopt($ch, CURLOPT_POS
