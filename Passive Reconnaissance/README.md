# What is Passive Reconnaissance?
Passive Reconnaissance is the process of gathering information without interacting directly with the target system, using only publicly accessible data sources.
# What is Data Collected ?
1. email addresses, phone numbers, IP addresses, domain names, suppliers, deployed technologies, geographic locations and social networking accounts. Cybercriminals can find most of this data by using search engines such as Google via Google Dorking.
2. what type of computers are being used, what operating systems are running, which software has been installed, an application's programming language and similar details.
3. physical searches to get at sensitive information. This might include digging through trash or looking for data stored on discarded computers.

# Tools
- [Google Dorking](https://github.com/chr3st5an/Google-Dorking): Google dorking is a passive attack or hacking method involving the use of a custom query.
- [Censys](https://search.censys.io/): Censys helps organizations, individuals, and researchers find and monitor every server on the Internet to reduce exposure and improve security.
- [Shodan.io](https://www.shodan.io/): Shodan is a search engine that lets users search for various types of servers connected to the internet using various filters.
- Social engineering on Social Networking Sites: Various types of information like contact info, date of birth, location, friends list, interest, etc. help in profiling the target, luring the target via fake profile.
- Email Headers: Gives info about senders IP address, mail server etc.
- [Cookie Editor extensions](#what-you-can-learn-with-cookie-editors) on browsers (just view) 
- [Whois](https://labex.io/tutorials/linux-linux-whois-command-with-practical-examples-423010): A Whois domain lookup allows you to trace the ownership and tenure of a domain name. You can obtain the name and server link information with Whois, the domain registrant's email and phone number, important dates related to the domain, and much more.
- [Wappalyzer](https://www.wappalyzer.com/): Wappalyzer APIs provide instant access to website technology stacks, company and contact details, social media profiles, email verification and more.
- [Immuni Web security test](https://www.linkedin.com/pulse/day-88-immuniweb-community-edition-comprehensive-free-soumya-swarup-sa4jc/) : ImmuniWeb Community Edition is a collection of free tools to ensure security, privacy, and compliance of web and mobile applications, APIs, and more. It's offered as part of ImmuniWeb's effort to raise security awareness and make the web safer.
- DNS lookup tools like [nslookup](https://cheat.sh/nslookuphttps://cheat.sh/nslookup), [dig](https://cheat.sh/dig), [DNSDumpster](https://dnsdumpster.com/)
- [theHarvester](https://www.cheat-sheets.org/project/tldr/command/theharvester/): theHarvester is a reconnaissance tool that allows hackers to gather information about email accounts, subdomains, and hostnames.
- [Maltego](https://medium.com/@whart842/maltego-reference-guide-584bed1384a8): Maltego is an open-source intelligence (OSINT) and link analysis tool used for gathering and connecting data from various online sources.
- [Recon-ng](https://hackertarget.com/recon-ng-tutorial/): Recon-ng is a full-featured reconnaissance framework designed with the goal of providing a powerful environment to conduct open-source web-based reconnaissance quickly and thoroughly.
- [OSINT Framework](https://osintframework.com/)
- [Wayback Machine](https://web.archive.org/) : Wayback Machine, a digital archive created by the Internet Archive, allows users to view past versions of websites. It acts as a "time machine" for the internet, enabling users to access websites that may no longer be available or to see how websites have changed over time.
- [Netcraft](https://searchdns.netcraft.com/) web application to find the company’s restricted domain
- [Wireshark](https://hackertarget.com/wireshark-tutorial-and-cheat-sheet/): If an attacker can gain access to an organization’s Wi-Fi network or otherwise eavesdrop on the network traffic of an employee (e.g., by eavesdropping on traffic in a coffee shop), analyzing it in Wireshark can provide a great deal of useful intelligence about the target network.

# What You Can Learn with Cookie Editors

Using browser extensions like EditThisCookie, Cookie-Editor, or Storage Inspector, you can:

- View Session or Tracking Cookies

    Learn technologies used (e.g., session IDs, JWTs, Cloudflare, Google Analytics).

- Discover Authentication Mechanisms

    Tokens, flags like HttpOnly, Secure, SameSite.

- Fingerprint Server-Side Behavior

    Are cookies regenerated? Persistent? Encrypted?

- Tamper Cookies (Active)

    See how servers respond to forged roles (admin=true, user_id=1).