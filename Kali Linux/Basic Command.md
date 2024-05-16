- **Command: `ping #ip_address`**
  - Description: Sends ICMP echo requests to the specified IP address to test connectivity.
  - Shows: Round-trip time, packet loss.
  - Note: ICMP packets can be blocked by firewalls or routers, leading to false negatives.

- **Command: `ping #website_address`**
  - Description: Sends ICMP echo requests to the specified website to test connectivity.
  - Shows: Round-trip time, packet loss.
  - Note: ICMP packets can be blocked by firewalls or routers, leading to false negatives.

- **Command: `host #website_address`**
  - Description: Performs DNS lookup to retrieve the IP address associated with the website.
  - Shows: IP address of the website.
  - Note: DNS records can be cached or manipulated, leading to incorrect results.

- **Command: `nslookup #website_address`**
  - Description: Queries DNS servers to retrieve information about a domain.
  - Shows: IP address, DNS record details.
  - Note: DNS records can be cached or manipulated, leading to incorrect results.

- **Command: `whois #website_address`**
  - Description: Retrieves domain registration information from WHOIS database.
  - Shows: Registrant details, registration date, expiry date, etc.
  - Note: WHOIS data can be outdated or privacy-protected, leading to incomplete information.

- **OR, Use website:**
  - Link: [Find IP Address of Website](https://www.site24x7.com/tools/find-ip-address-of-web-site.html)
  - Description: This website allows you to find the IP address associated with a website by simply entering its URL.
  - Note: The accuracy of the result depends on the DNS resolution of the website.
