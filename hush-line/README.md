# **🤫 Hush Line Project Info**

## Info

Hush Line is a free and open-source, self-hosted anonymous tip line that makes it easy for organizations or individuals to install and use. It's intended for journalists and newsrooms to offer a public tip line; by educators and school administrators to provide students with a safe way to report potentially sensitive information, or employers, Board rooms, and C-suites for anonymous employee reporting. 

Other tools in this space are SecureDrop and GlobalLeaks, two robust, widely adopted whistleblowing platforms whose installation process can be prohibitive without an admin to do it for you. Some systems even require special infrastructure to operate, and for a good reason, when you allow people to send you files anonymously, you'll receive both malicious and dirty data. Both require significant time and money to manage. 

It's not much easier for the person sending a message, either. They must create accounts, download new software, and manage PGP keys. It requires a significant commitment to share some information—another prohibitively tricky requirement.

Even tools like Signal or Protonmail require the end-user to reveal information about themselves, or find disposable phone numbers and email addresses, a tricky hurdle for the non-technical user. 

In contrast, Hush Line is a text-only, one-way messenger that acts as the first handshake of a relationship where two parties want to exchange information. It's a low-risk method of offering a safe channel for someone to reach you without requiring them to reveal anything about themselves, create an account, manage PGP keys, or acquire a burner phone, email address, or phone number. 

The tool deploys to either an onion-only instance or Tor + public web. It's a web and email server and a Python app that encrypts a message with your public PGP key once a message gets submitted, then saves it, and finally emails the encrypted message to you. Your data never gets saved in an unencrypted state. And since all messages are sent to your email, you never have to log in to the device.

We configure Nginx with hardened security headers so no external and potentially nefarious resources can load, automatically set up renewing Let's Encrypt HTTPS certificates so your data is always transmitted safely, privacy-preserving logging which scrubs IP addresses before saving to server logs, and enable automatic updates by default so you never miss a critical security patch.

You only need a public PGP key on a keyserver and an SMTP-compatible email address. We ask for your key this way because uploading it includes verifying your email address, helping us know you are whom you say.

Built with popular and ubiquitous hardware and software in mind, it works seamlessly on Raspberry Pi and Debian-based operating systems. You can even add an e-paper display to make your Hush Line address easy to discover.

We want to offer a solution to those who want to help that have reportable or actionable information but don't want to face retaliation or get involved. Over 60% of people have witnessed or experienced workplace harassment or discrimination [1]. Only 15% of those people ever make a formal written complaint [1]. That's a big oversight for employers, which could become a significant liability left unattended. And the reason people don't report? They're afraid of retaliation. 

How much better, safer, and more informed could our schools, workplaces, and society be with a safe way to share information that places the privacy of their communities first?

1. https://hbr.org/2020/10/do-your-employees-feel-safe-reporting-abuse-and-discrimination

|  |  |  |
| --- | --- | --- |
| **Name:** Hush Line | **Websites:**<br>[https://hushline.app](https://hushline.app/)<br>[https://try.hushline.app](https://try.hushline.app/) | **Created By:** [Science & Design](https://scidsg.org/) |
| **Software type:** Open Source | **Year started:** 2023 | **Contributor Locations:** US, EU, APAC |
| **License:** Public Domain | **Team Size:** 3 | **Contributor Type:** Volunteer |
| **Git Repository:** [Link](https://github.com/scidsg/hush-line) | **Donations:** [Link](https://opencollective.com/scidsg/contribute/hush-line-support-55786) | **Research:** [Link](https://cryptpad.fr/form/#/2/form/view/aznAzzpG6Fh3K1Dq0JjslCK-NmSugmfLTP7ej+SqRl0/) |
| **Social Content:** [Link](https://docs.google.com/spreadsheets/d/1XVRLtIabsoK6syTikEU6pNrpv9PYCSV4Pta9WRl15CM/edit#gid=0) | **Design:** [Link](https://www.figma.com/file/f2KCnJCooSQa3C3vy051Bc/Hush-Line---Collaborate?node-id=1%3A238&t=q78TDDi48CPY3xjN-1) | **Design Content:** [Link](https://docs.google.com/spreadsheets/d/1SLfWoYwQQDNbczTBgUR6ewWDzlay5ql-RFJnslrJHKI/edit) |

## Users

- Journalists and newsrooms can use Hush Line to give the public a safe way to leave a confidential tip.
- Employers and board rooms can use Hush Line to build trust by allowing colleagues to leave suggestions or report concerns anonymously.
- Educators and school staff can use Hush Line to host a safe way for students to share information with someone they trust.

## Use Cases

- As a journalist, I need to provide sources with a trustworthy way to send information, so they have confidence that the methods will protect their privacy.
- As an educator, I need to provide students with a safe way to share information with school staff they trust, so critical information can be received while protecting the student's identity.
- As an employee that has witnessed workplace abuse, I need a secure and private way to share information with company executives, so that my identity is kept secret to avoid provoking a hostile retaliatory response.
- As a student, I want a way to report sensitive information without sharing who I am, so I can help to make change without impacting my educational experience.
- As a business leader, I want to make my team feel like they can share sensitive information without risking their career, so I can build trust in the team with which I work.
- As a source, I need a way to access someone's Hush Line, even if the Tor Network and the original URL are blocked in my country, so I can share information even in the most oppressive environments.

## Locations

- Global
- Areas where censorship is prevalent, including Iran, China, Russia, and Belarus

## **Problems we're solving**

Individuals need safe ways to communicate confidential information without fear of being compromised. Whether the sender or receiver, security, privacy, and usability are critical in establishing trust when handling confidential information.

Journalists and newsrooms depend on confidential communications. Geneva Overholder, a contributor to the New York Times, says, "to journalism, sources are the lifeblood of newsgathering."[1] Whistleblowers risk their personal and professional reputations to expose wrongdoing, and the risks they face include imprisonment and exile. Even the families of journalists and whistleblowers have faced harassment or even detainment. [2] With such stakes, sources need confidence that they won't be burned.

In schools, students have entirely different expectations of trust and safety. A 16-year study of one school showed that when they implemented measures in the name of security, including metal detectors, gates, and removing decorative elements from campus, the feeling of safety went down. Peer violence increased, calls to the police quadrupled, and teachers grew increasingly concerned. [3]

Trust matters a lot in the workplace - in a Harvard Business Review study, individuals at high-trust companies report "74% less stress, 106% more energy at work, 50% higher productivity, 13% fewer sick days, 76% more engagement, 29% more satisfaction with their lives, 40% less burnout." [4] And research from MIT shows that "trusting employees are 260% more motivated to work, have 41% lower rates of absenteeism, and are 50% less likely to look for another job." And did you know that a quarter of employees do not trust their employers? [5]

Tools exist to facilitate trust - SecureDrop, GlobalLeaks, OnionShare. SecureDrop, for example, is actively used by organizations including The New York Times, Pro Publica, Financial Times, and many others.[6] It allows organizations to receive files from anonymous sources and is built for high-threat models. Hush Line approaches the problem differently: simplifying the feature set so that using the service helps protect both the organization and the user. Instead of accepting files requiring air-gapped computers and advanced knowledge, Hush Line is a message-only service. It focuses on building trust first by serving as the initial handshake between the two parties. The user does not have to create an account, generate keys (or even know what PGP is), or download new software.

The app installs with a simple wizard configuring Nginx, Tor, automatically renewing Let's Encrypt certificates, automatic updates,, and email notifications.With functionality built to satisfy high-thread model scenarios, Hush Line's experience is made to be a tool anyone can get running in minutes..

1. [https://www.nytimes.com/2004/02/06/opinion/the-journalist-and-the-whistle-blower.html](https://www.nytimes.com/2004/02/06/opinion/the-journalist-and-the-whistle-blower.html)

2. [https://www.theguardian.com/world/2013/aug/18/glenn-greenwald-guardian-partner-detained-heathrow](https://www.theguardian.com/world/2013/aug/18/glenn-greenwald-guardian-partner-detained-heathrow)

3. [https://theconversation.com/culture-of-trust-is-key-for-school-safety-92731](https://theconversation.com/culture-of-trust-is-key-for-school-safety-92731)

4. [https://hbr.org/2017/01/the-neuroscience-of-trust](https://hbr.org/2017/01/the-neuroscience-of-trust)

5. [https://sloanreview.mit.edu/article/how-to-build-a-high-trust-workplace/](https://sloanreview.mit.edu/article/how-to-build-a-high-trust-workplace/)

6. [https://securedrop.org/directory/](https://securedrop.org/directory/)

## Grant History

| **Organization** | **Support Type** | **Vendor** | **Services** | **Status** | **Dates** |
| --- | --- | --- | --- | --- | --- |
| StartSmall, LLC | Financial | Project-Specific | 
| OTF | Services | Red Team Lab | Security Audit | ✅ Awarded | July 2023 |
| OTF | Services | A11y Lab | Accessibility Audit | ✅ Awarded | July 2023 |
