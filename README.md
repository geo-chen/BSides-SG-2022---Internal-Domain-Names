# BSides SG 2022 - Internal-Domain-Names

## Finding 1 - CVE-2024-57174: Alphion Routers
Reference: 
 - https://github.com/BSidesSG/2022
 - https://chenzw.medium.com/internal-domain-names-f1cd2886c654

Team mate: chenzw.medium.com

Product Link: http://alphion.com

Description: 

The default configuration of Alphion Subscriber End Equipment Model ASEE series optical network terminals defines a previously unregistered domain name as the DNS suffix, which allows attackers to sniff end-user network traffic by registering the domain name and pointing the domain's wildcard DNS entry to an attacker-controlled IP address.

