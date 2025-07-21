# dropshipping_dns_blocklist

List of drop shipping shops operating in Switzerland. May be used as DNS blocklist.

This list is compiled and provided on best effort/best knowledge. False positives may occur. Use at your own risk. No warranty. 

False positives can be reported using issues or be removed by a related pull request. Please report/remove only one URL per issue or pull request. Please add a short comment why an URL is considered to bo be a dropshipping shop. For transparancy reasons please add a related statement if you are the operator or holder of the related shop or domain. Please check the related guideline. 

Adding a new dropshipping shop can be requested either using an issue or as a pull request. Please add only one URL per issue or pull request. Please add a short comment why an URL should be considered a dropshipping shop.Please check the related guide.

The core of the blocklist is based on the open source contribution of Stiftung für Konsumentenschutz Schweiz. 


--

How to use the list as DNS blocklist in unbound dns/opnsense?
- Go to blocklists
- Select "advanced mode"
- In the field "URLs of Blocklists" add https://raw.githubusercontent.com/AnAnalogGuy/dropshipping_dns_blocklist/refs/heads/main/dropshipping_dns_blocklist_ch
- Press the "Save button". The blocklists will be downloaded and applied.
- In the logfiles you should see the list has been downloaded and a little less than 300 entries have been added to the blacklist
- Open a browser tab and add one of the URLs to check if your DNS server does resolve it. If you end with a "not found" error, the blocklist has worked as intended.
