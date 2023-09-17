# **Pi Relay Project Info**

## Links

- [Roadmap](https://github.com/orgs/scidsg/projects/14/views/1)
- [App Repository](https://github.com/scidsg/pi-relay)
- [Website Repository](https://github.com/scidsg/pirelay.computer)
- Design Files
   - [Website](https://www.figma.com/file/sMVeaFDpJEIQOTHr2SRBWt/Pi-Relay-Website?type=design&node-id=1%3A808&mode=design&t=yLPXXIYhk9r1vDno-1)
   - [Splash Screen](https://www.figma.com/file/y9VccPNrUM7jDmy9P0N2Jn/Pi-Relay-Splash-Screen?type=design&node-id=1%3A808&mode=design&t=61aAFJivnOs9XHOA-1)
   - [Devices](https://www.figma.com/file/YHzSBo6okChGcnvN8Q01Ne/Pi-Relay-Devices?type=design&node-id=1%3A808&mode=design&t=K8xkIyICjWvV31bf-1)
   - [Marketing](https://www.figma.com/file/Y8BdOLeo2PZdFESD3Qzhl2/Pi-Relay-Marketing?type=design&node-id=5%3A474&mode=design&t=hh0CFTGoVwdXOjRr-1)  

## Info

Pi Relay is an easy way to turn a Raspberry Pi into a Tor middle relay, making it a fun, easy, and accessible way to strengthen the Tor Network and grow the anonymity set from home. The installation is fully guided, automating the process of safely deploying a Relay without installing packages, manually editing a torrc file, or navigating the terminal. While it's not *that* hard to do, it's *very* easy to mess up, and we want to avoid accidentally running an exit relay from home or forgetting to add bandwidth limits. We only ask a few things during setup, including how much data you'd like to share that month and your bandwidth caps.

The goal is to enable the home user to easily and safely contribute back to the Tor network using popular and ubiquitous hardware. Optionally add an e-paper display to visualize information about your Relay, including basic metadata and a live updating graph of the total bandwidth you've shared that accounting period. 

Our first version of the tool focuses on people at home - from the premise that lots of people have extra hardware and want to help, but there's a technical barrier because once you ask someone to read documentation, open the terminal, and manually edit or craft a file, you'll lose most of your audience.

We want people all over the world to be able to participate in making the internet safer by streamlining the process of adding trustworthy, properly configured, automatically updating Tor relays.

Soon we want to expand to address institutional users, partnering with public libraries, universities, and businesses to run high-speed exit and bridge relays.

|  |  |  |
| --- | --- | --- |
| **Name:** Pi Relay | **Website:**<br>[https://pirelay.computer](https://pirelay.computer/) | **Created By:** [Science & Design](https://scidsg.org/) |
| **Software type:** Open Source | **Year started:** 2023 | **Contributor Locations:** US, EU, APAC |
| **License:** Public Domain | **Team Size:** 3 | **Contributor Type:** Volunteer |
| **Donations:** [Link](https://opencollective.com/scidsg/contribute/pi-relay-supporter-61700) | 

## Users

- Civil Society Professioanls can use Pi Relay to help grow the size of the Tor Network.
- Newsrooms can run a Bridge to offer their journalists direct and reliable access to the Tor Network.
- Librarians can run a network of Pi Relay devices to use public instistutions for the digital advancement of free knowledge.
- Businesses can run Pi Relay to donate larger amounts of bandwidth to speeding up the Tor Network.

## Use Cases

- Civil Society Professionals: As a human rights advocate in a region with internet censorship, I need to set up a Pi Relay, so that I can contribute to expanding the Tor Network and facilitate more secure and uncensored internet access for myself and others in my community.
- Journalists and Newsrooms: As a journalist reporting on sensitive issues, I need to have a reliable and secure way to access and share information, so by using Pi Relay, I can consistently connect to the Tor Network and protect my sources and myself from surveillance.
- Librarians: As a librarian at a public library, I need to promote free access to knowledge. By establishing a network of Pi Relay devices, I can contribute to digital literacy and free information access, helping patrons circumvent censorship and access global resources.
- Businesses: As a business that values digital privacy and freedom of information, I need to contribute to the Tor Network. By running Pi Relay, I can donate bandwidth, thus enhancing the network's speed, availability, and overall performance.

## Locations

- Global
- Areas where censorship is prevalent, including Iran, China, Russia, and Belarus

## **Problems we're solving**

Over the past decade, internet freedom has been in consecutive decline, according to Freedom House's 2020 Freedom on the Net report, which assesses internet freedom in 65 countries, accounting for 87% of the world's internet users [1]. Countries like China, Myanmar, India, Iran, Russia, and Belarus employ aggressive surveillance and control measures, including arrests of journalists, use of spyware, IP blocking, and DNS tampering [2]. These practices suppress free speech, limit access to information, and drive pervasive surveillance.

As a countermeasure to online censorship and surveillance, the Tor network offers users an anonymous connection to the internet, making your physical location and online activity difficult to track and control. However, the efficacy of the Tor network depends heavily on the number and distribution of its volunteer-operated servers or relays.

With around 7,000 active relays as of July 2023, the Tor network faces significant challenges in consistently providing secure, fast, and reliable connections worldwide, particularly in high censorship areas [3]. Dingledine, Mathewson, and Syverson (2004) highlighted the direct relation between the Tor network's performance and its number of relays [4]. Similarly, a 2016 study by Greschbach et al. found improved Tor connections' speed and performance with increased relay density in a geographic area [5]. This underscores the importance of expanding the Tor relay network, a goal made easier by tools like Pi Relay.

Pi Relay empowers anyone with a Raspberry Pi, an affordable mini-computer, to set up a Tor relay effortlessly. This democratizes the relay setup process, thereby improving the Tor network's growth, resilience, and efficiency. Each addition of a Pi Relay to the system pushes forward the global fight against internet censorship, enhancing privacy, security, and freedom in digital communication.

1. Freedom House. (2020). Freedom on the Net 2020: The Pandemic’s Digital Shadow. https://freedomhouse.org/report/freedom-net/2020/pandemics-digital-shadow

2. King, G., Pan, J., & Roberts, M. E. (2013). How Censorship in China Allows Government Criticism but Silences Collective Expression. https://gking.harvard.edu/publications/how-Censorship-China-Allows-Government-Criticism-Silences-Collective-Expression

3. Tor Project. (2023). Tor Metrics - Relay Counts and Bandwidth Stats. https://metrics.torproject.org/

4. Dingledine, R., Mathewson, N., & Syverson, P. (2004). Tor: The Second-Generation Onion Router. Naval Research Lab Washington DC. https://svn-archive.torproject.org/svn/projects/design-paper/tor-design.pdf

5. Greschbach, B., Pulls, T., Roberts, L. G., Winter, P., & Murdoch, S. J. (2016, October). The Effect of DNS on Tor's Anonymity. In NDSS. https://arxiv.org/abs/1609.08187

## Grant History

| **Organization** | **Support Type** | **Vendor** | **Services** | **Status** | **Dates** |
| --- | --- | --- | --- | --- | --- |

