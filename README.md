# siteBlockList
Websites to block

This repository contains a file with domains and IPv4 addresses that needs to be blocked.
Firewall downloads this file, resolves domain names and re-builds the block filter.

Do not use RegEx, like *.whatsapp.com. You can simply add whatsapp.com which will block all subdomains (i.g. api.whatsapp.com).