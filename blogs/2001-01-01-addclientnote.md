---
title: "AddClientNote"
url: "//developers.whmcs.com/api-reference/addclientnote/"
date: "2001-01-01"
feed_url: "https://developers.whmcs.com/api-reference/index.xml"
---
Adds a Client Note Request Parameters Parameter Type Description Required action string “AddClientNote” Required userid int The Client ID to apply the note to Required notes string The note to add Required sticky bool Should the note be made sticky. Makes the note ‘sticky’ and displays the note throughout the client’s account and on any tickets they submit in the admin area Optional Response Parameters Parameter Type Description result string The result of the operation: success or error noteid int The id of the newly created note Example Request (CURL) $ch = curl_init(); curl_setopt($ch, CURL
