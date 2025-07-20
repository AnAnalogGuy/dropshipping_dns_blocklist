# dropshipping_dns_blocklist

List of drop shipping shops operating in Switzerland. May be used as DNS blocklist.

This list is compiled and provided of a best effort/best knowledge basis. False positives may occur. Use at your own risk. No warranty. 

False positives can be reported using "Issues" or be removed by pull request. Please only one URL per issue and pull request. Please a a short comment why an URL is considered being a dropshipping shop. Please check the related guide. 

Adding a new dropshipping shop can be requested either as a pull request. Please only one URL per issue and pull request. Please add a short comment why an URL should be removed/is considered being a false positive. Please add a related statement if you are the operator or holder of the related shop or domain. Please check the related guide.

The core of the blocklist is based on the open source contribution from Konsumentenschutz Schweiz. 


--

How to use with unbound dns/opnsense?
- Go to blocklists
- Select "advanced mode"
- In the field "URLs of Blocklists" add https://raw.githubusercontent.com/AnAnalogGuy/dropshipping_dns_blocklist/refs/heads/main/dropshipping_dns_blocklist_ch
- press "Tab" key and the "Save button"
- In the logfiles you should see the list has been downloaded and a little less than 300 entries have been added to the blacklist
- open a browser tab and add one of the URLs to check if your DNS server does resolve it. If you end with a "not found" error, the blocklist has worked as intended.
