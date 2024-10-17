# what-is-DNS-server

### DNS (Domain Name System) is a system that converts human-friendly website names (like [www.example.com](http://www.example.com/)) into the numeric IP addresses computers use to locate and communicate with each other on the internet.


DNS animated Explained in depth :- 

[How DNS Works In Six Steps - Verisign](https://www.verisign.com/en_US/website-presence/online/how-dns-works/index.xhtml?loc=en_US)

### DNS records are specific entries in the Domain Name System that provide various types of information about a domain or host. Here are some of the most common types of DNS records:
DNS (Domain Name System) records are entries in the DNS database that provide information about a domain. Here are some of the most common types:

1. **A Record**: Maps a domain name to an IPv4 address. For example, `example.com` to `192.0.2.1`.

2. **AAAA Record**: Maps a domain name to an IPv6 address. For example, `example.com` to `2001:0db8:85a3:0000:0000:8a2e:0370:7334`.

3. **CNAME Record**: Canonical Name record that maps an alias name to the true (canonical) domain name. For example, `www.example.com` can point to `example.com`.

4. **MX Record**: Mail Exchange record that specifies mail servers responsible for receiving email on behalf of a domain. It includes priority levels.

5. **TXT Record**: Text record that can hold arbitrary text, often used for verification (like SPF records for email validation).

6. **NS Record**: Name Server record that specifies the authoritative name servers for a domain.

7. **SRV Record**: Service record used to define the location of specific services, like VoIP or messaging services.

8. **PTR Record**: Pointer record used for reverse DNS lookups, mapping an IP address to a domain name.
