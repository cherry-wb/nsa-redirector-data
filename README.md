# nsa-redirector-data
Port scan data on NSA redirector nodes revealed by the Shadow Broker
Port Scans taken 2016-10-31 through 2016-11-02

#data overview
So the new data dumps from the Shadow Broker includes both IPs and hostnames. Some of the hostname's are no longer resolving. Therefore, I have broken up my scanning efforts into two groups
* IPs - scans of the IP addresses as they were in the dumps
* domains - scans of the IP addresses to which to the hostname's currently point

#file details

* alive-domain-ips
  * list of the ip addresses that currently resolve from the domain names in the data dump and are alive
* alive-ips
  * list of the ip address in the data dump that are alive
* final_host
  * list of hostnames extracted from data dump
* final_ips
  * list of IPs extracted from data dump
* ping-scan-results-domains
  * ping scan results from the domains group
* ping-scan-results-ips
  * ping scan results from the IPs group
* port-scan-results-domains
  * port scan results from the domains group
* port-scan-results-ips
  * port scan results from the IPs group
* service-scan-results-domains
  * port scan results from the domains group
* service-scan-results-ips
  * port scan results from the IPs group
