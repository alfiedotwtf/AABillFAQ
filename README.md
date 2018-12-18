# Assistance and Access Bill 2018 FAQ for Australian IT workers

This repo will try and collate questions and answers on the new Assistance and
Access Bill 2018 for anyone working in the IT industry within Australia.

See this tweet for more info:

* [https://twitter.com/Lizzie_OShea/status/1071222470378541056](https://twitter.com/Lizzie_OShea/status/1071222470378541056)

Here is the link for the bill, as passed by both Houses:

* [https://www.legislation.gov.au/Details/C2018A00148](https://www.legislation.gov.au/Details/C2018A00148)

## Asking Questions

Let me emphasise that there are no stupid questions, just stupid policy.

Feel free to ask questions by pull request, or create an issue here:

* [https://github.com/alfiedotwtf/AABillFAQ/issues/new](https://github.com/alfiedotwtf/AABillFAQ/issues/new)

And if you are uncomfortable asking a question publicly, feel free to email me
at ([alfie@alfie.wtf](mailto:alfie@alfie.wtf)), Signal (+61 400 777 227), or Twitter DM ([alfiedotwtf](https://twitter.com/alfiedotwtf/)).

My PGP key is included in this repo.

*NOTE* This is taking a while, so please stay tuned...

# Process

* Dump below all the questions from the last few of days from various sources

* Group them into categories

* Then merge/sort/filter

* Send them to lawyers

* Tidy up document and find a place to host it

# Top 5 Questions

1. There has been confusion around who can recieve a warrant, TAN, TAR, and
	 TCN. Some people are saying that only telco providers in the traditional
	 sense receive these and then get staff and contractors to execute them,
	 while others say that anyone can be approached directly who have knowledge
	 of a system or the capability to access and modify a system, regardless of
	 their current status: i.e local or remote, citizen or foreigner, employee or
   contractor or former employee or ever hobbyist.

   Who can be approached with a warrent, TAN, TAR, and TCN to execute it?

2. Can these warrants and notices force you to build or modify software that
	 circumvents a product's security, your company's security, or even somebody
	 else's security (not the target), so that they can use it as a stepping
   stone to get into the target's computer.

	 E.g. their target buys your microphone, which needs a Windows driver to run.
	 Can you be forced to modify your Windows driver and push a targetted update
   that will then allow spying or even remote access to their computer)

3. If approached directly with a warrant or notice, are you allowed to tell
	 anyone? e.g colleagues in order to assist in executing them, bosses to let
	 them know they are compromising the safety of their systems and their own
	 work schedule will be affected, and legal team to check validity of request

4. What happens if there is a bug in your execution of the warrant or notice,
   which leads to unauthorised disclosure?

5. When approached with a warrant or notice, how does one verify the
   authenticity of the people serving them, and the legality of the request?

6. Are warrant canary's legal or even possible to disclose warrants or notices?

# Questions

* Is a 'warrant canary' considered "technical assistance notice information"
  under s. 317B?

* Is leaving a warrant canary up after a TCN is issued a "making a false or
  misleading statement" or "engaging in dishonest conduct." under paragraph 2
  of s. 317E? Does this mean a designated communications provider cannot be
  ordered to take down or leave up a warrant canary as per s. 317C? If so, how
  does this not contradict s. 317ZF?

* Are any of the following "carriage service provider"s under the
  Telecommunications Act 1997? (This has ramifications under s. 317C)
  * Tor node operators
  * Operators of servers used for online communication (e.g.: IRC, SIP, Jabber,
    Tox etc)

* Is software considered a "...part of the infrastructure of a
  telecommunications network" as per "facility" in the Telecommunications Act
  1997 s. 7? (This has ramifications under s. 317C)

* What is the definition of "arranges for the supply" as per item 2 of s. 317C?
  * Would a transaction processing entity (e.g.: PayPal, fiat cryptocurrency
    exchange) involved in the payment for listed carriage service be considered
    "arranging for the supply"?
  * Digital Distribution Platforms (e.g.: Steam, Google, CleverBridge)

* Are any the following considered a designated communications provider as per
  item 3 of s. 317C?
  * Vendor or consultant to the carriage service provider (subject to a TCN)
  * Service provider hosting a code repository (that is subject to TCN)
  * Catering service provider for a designated communication provider.

* Are any the following considered a designated communications provider as per
  item 4 of s. 317C?
  * Person running a server instance used to facilitate communication (e.g.: IRC
    server, Tor node, Tox node, SIP server)
  * Website owner or Administrator (e.g.: Alfie John of alfie.wtf)
  * Cryptocurrency 'miner' participating on an online blockchain or another
    similar networked ledger technology.
  * An electronic service provider that has intentionally geo-blocked
    Australian users.
  * BitTorrent 'Leacher' or 'Seeder'

* Are any the following considered a designated communications provider as per
  item 6 of s. 317C?
  * Unincorporated uncontracted volunteer open source developer (or anyone with
    commit privileges to a repo)
  * Unincorporated uncontracted volunteer who personally mirrors software
    available for download.
  * Unincorporated uncontracted volunteer who manages an open source project.

* Are any building maintenance personnel (e.g.: HVAC, cleaning crew) of a
  facility considered a designated communications provider as per item 7 of s.
  317C?

* Are any the following considered a designated communications provider as per
  item 8 of s. 317C?
  * SoC (system-on-a-chip) manufacturers (e.g.: Qualcomm)
  * SIM/smartcard manufacturers (e.g.: Gemalto)
  * IC and microcontroller manufacturers (e.g.: Texas Instruments,
    STMicroelectronics, Intel, fabs)
  * Distributors (e.g.: RS Components)
  * PCB manufacturers.

* Would the person 'setting up' an internet connection for a domestic premises
  (facility?) be considered a designated communications provider as per item 9
  of s. 317C?

* Are any the following considered a designated communications provider as per
  item 10 of s. 317C?
  * OEMs (e.g.: Dell)
  * Retailers (e.g.: JB Hi-Fi)
  * Equipment Installers (e.g.: support consultant, on-site technician)

* Are any the following considered a designated communications provider as per
  item 11 of s. 317C?
  * SoC (system-on-a-chip) manufacturers (e.g.: Qualcomm)
  * SIM/smartcard manufacturers (e.g.: Gemalto)
  * IC and microcontroller manufacturers (e.g.: Texas Instruments,
    STMicroelectronics, Intel, fabs)
  * PCB manufacturers.
  * Distributors (e.g.: RS Components)

* Are any the following considered a designated communications provider as per
  item 12 of s. 317C?
  *  Systems Administrators
  *  Network Administrators
  *  Certificate Authority/HSM Administrators or anyone else 'installing' a HSM
     (Hardware Security Module)
    * DNSSEC Administrators?
  *  Individual person of OEM that is ultimately provisioning company image
     onto OEM system (e.g.: Dell technician preinstalling a company image before
     shipping to said company)

* Are any the following considered a designated communications provider as per
  item 13 of s. 317C?
  * An end-user, or person assisting end-user, powering on a mobile phone
    device (This would have major ramifications)

* Are any the following considered a designated communications provider as per
  item 14 of s. 317C?
  * Hard disk manufacturers (e.g.: Seagate, WD)
  * Flash memory manufacturers (e.g.: SanDisk)
  * SIM/smart card manufacturers (e.g.: Gemalto)
  * Optical media manufacturers (e.g.: Verbatim)
  * Tape media manufacturers (e.g.: Sony, Fujifilm)

* Are any the following considered a designated communications provider as per
  item 15 of s. 317C?
  * Canonical (Producer of Ubuntu operating system fork)
  * RedHat (Sponsor of the Fedora Project, Producer of RedHat)
  * General Dynamics C4 Systems (seL4 microkernel project)
  * Linux package repository mirror provider (e.g.: Debian apt repos, AARNet,
    Digital Pacific)

* Who determines if a "carrier or provider is capable" as per paragraph 1 of s.
  317ZA?

* Is organising any opposition (protest, sit-in, boycott, promoting
  alternatives etc.) to this law, after the Bill has been assented, considered
  a contravention of paragraph 1 of s. 317ZA as per paragraph 2 of the same
  section?

* Assuming a piece of software is already highly decentralised and anonymised
  so that particular persons cannot be identified, if a developer designs their
  software distribution system to ensure they have no control over the channels
  particular persons can update their software (e.g.: BitTorrent, mirrors, or other
  broadcast-like technology unlike Google and their Play Store and Apple and
  their Appstore), would that be sufficient enough to ensure the software update
  process is no longer be utilised as an attack-vector against a particular
  person as ordered by a TCN?

* Can employees or contractors be targeted directly to make changes or access
  systems without going through the company or organisation they work for?

* If an employee or contractor is directly approach to make changes or access
  systems, are they allowed to tell their supervisors and any assisting staff
  in order to proceed
  * If not, what happens if they get caught
  * If not, how do they notify other staff to not remove the capability
  * What happens to the people who find changes or unapproved access

* if an individual is directly approached to make changes or access systems of
  previous employers, what happens if they get caught

* Does the forcing of individuals to modify code or access system go against
  the Constitution (e.g on just terms)

* Does the bill apply to Australians based overseas

* Do these notices and warrants apply to foreign visitors while travelling
  to Australia for vacation

* Is it possible that a Notice can be supplied to Certificate Authorities to
  forged TLS certificates

* Can Notices be issued to source code hosting companies such as BitBucket to
  serve modified code to targets

* How does this work with companies that are SOX and SOC 2 compliant

* What happens if the Notice or warrant is issued to a company who wants to
  comply but the employees refuse

* Can individuals tell anyone like an employer, colleagues, lawyers if they
  have been issued a warrant or Notice

* what is the definition of "systemic weakness"

* "A person covered in paragraph (1)(b) may disclose... for the purpose of
  obtaining legal" how widely can you ask for advice

* What happens when a company cannot comply to a warrant or a Notice because of
  technical design (i.e do not hold any keys or data)

* Can the government walk up to me, demand I create a backdoor in my work
  software or access work databases, and I can not tell my employer or client

* What happens if someone finds a vulnerability
	* and fixes it
	* and notifies others

* Are warrant and Notice canaries legal

* What are the implications for Open Source software in Australia

* Are we able to handle any European data in Australia as it could be a
  potential violation of GPDR

* When a weakness is discovered, what happens when it is fixed by someone not
  under a Notice

* What happens when to target a user, we would have to decrypt for all users

* What happens if we do client-side encryption - do we have to modify the
  decryption to target an individual?
	* What are the ramifications if we are caught if we can not target the payload
	  to the individual and so have to serve it to everyone (think CDN)?

* Can you be fired for complying with a warrant or Notice because you
  undermined your employer's security

* Can you be fired or be under penalty for complying with a warrant or Notice
	but it caused a security breach, GDPR breach, or accidentally disclosed the
	actions of the warrant or Notice

* Can warrants and Notices go directly to staff or contractors rather than
  management/owners
	* Are direct approaches allowed to let employers, colleagues know
	* What if they need help from others to get execute the warrant or Notice

* What are the penalties for refusing a warrant, TAR, TAN, or TCN
	* What if you can not genuinely comply because of external constraints or the
	  risk of disclosure

* If we are served with a TCN, TAR, or TAN, is it legal to engage a lawyer, or
  does the non-disclosure provisions include attorney-client privilege?

* If I am served a TCN, but the execution of it would breach GDPR or HIPPA,
  what do I do?

* If my employment is terminated because I am executing a TCN, do I have legal
  recourse against the Commonwealth?

* If I am overseas and get served with a TCN, which would break local laws if
  executed, what do I do?

* What is the definition of "whole class of technology" and "target
  technology"?

* If served with a TCN, TAR or TAN, how long do we have do comply?

* Does the execution of a TCN count as forced labour/slavery?

* who can be targeted to implement a TCN? And individual? A company? Both? Can
  an employee be targeted without their employer being told?

* what secrecy/non disclosure provisions are provided for in a TCN? What are
  the consequences of breaking same?

* what mechanisms exist for disputing a TCN, both when it is declared and in
  the event that the judge/expert opinion is wrong?

* is there a fixed period after which TCN changes can be rolled back? Or must
  they be permanent or exist until specifically revoked

* what happens when a TCN change is inadvertently altered or has a bug
  introduced or introduces a bug? Who pays any business costs due to the bug?

* Are there punishments here?

* must a TCN be specific in its target(s)? It seems vastly different asking for
  a generic all user change vs something that would target one individual

* will historical TCNs be disclosed? Post-facto review is standard in the
  industry, especially when things are not 100% successful.

* Are Australians overseas subject to these notices?

* Would a warrant canary be a viable way of alerting employers/anyone that you
  have been compelled to "assist" or is this useless due to a law passed in
	2015?  
  * See https://www.schneier.com/blog/archives/2015/03/australia_outla.html
	* How can the aggregate disclosure statistics be given (can we provide
	  overlapping 6-month windows, or do they have to be disjointed?).

* Who can issue warrants and Notices

* A technical person reviewing code/config/state finds software/configuration
  that they believe may be the result of a TCN, or may be a malicious backdoor.
	If they communicate information about what they have found to another person,
  can they be in violation of the rules of a TCN they are unaware of?
	* (Context for question: concern around chilling effects the law may have on
	  reporting/discussing non-AAbill backdoor

* How will this interact with the consumer law?
	* If we sell a product labelled as secure and we are forced to add a flaw into
		that security does the customer have a right to refund under the consumer
    law as unfit for purpose?
	* Could we then have cause for the government to cover any financial losses
	  related to this as the customers issue comes from the governments order?

* In a case where an employee complies with a technical capability notice (TCN),
  backdoors their company's software, and is subsequently dismissed by the
	employer for undermining said software. What options does the employee have
  with regards to unfair dismissal or any form of compensation for loss of
  income?

* Can Article 12 or any other UDHR and/or other foreign or domestic legislation
	relating to privacy protection be used as a legal basis for not complying
  with a TCN?

* I would like to know how this bill will impact the use of open source
  software when stable and reliable software have licenses which provide no
  enterprise support and no obligation to change for its users.

* What are the obligations of open source maintainers for software directed to
  break down security?

* If there is no maintainer (passed away etc), will it be mandated to fork a
  repository to take on additional responsibility and capability just to
  introduce security flaws? How will this work, its resources and the
  sustainability of said problems be funded - even in the event no funding or
  liquidation is occurring.

* Upstream changes required to meet a Capability Notice for code maintained
	outside of Australia. What will happen to projects which have multiple
	parties across the world including if only one Australian citizen is
  maintaining?

* Are maintainers expected to introduce security flaws to comply with a Notice
  and not consult other maintainers, stakeholders or the community - even when
  tight approval processes are already in place to prevent the scenario being
  imposed?

* what, if any, legislation allows for intelligence agencies to insert covert
  assets into organisations

* What we need to do to repeal this law? Is it even possible?

* how does this law affect working visa holders/permanent residents?

* If forced to build backdoors, what happens with open source software?
	* Under most open source software licenses, wouldn't open source software
	  vendors be required to inform users that some of the code is going to be
    closed source?

* Is it possible that the Government could avoid the restriction of creating
  systemic weakness, by forcing tech companies to serve malicious updates to
  specific targets.

* what would happen if a TCN required us to violate a copyright license? (For
  instance, we are forced to add a backdoor to a GPLv3+ work and then ship it
  to a user -- legally we have to give them the source code but this would
  disclose the backdoor.)

* Is refusing to simply give up a password enough to be penalised under the
  bill

* What happens to the person who got issued the warrant or notice if during
	executing the order it was accidently disclosed to the target or other people

* Can plausible deniability protect you against accidental disclosure

* What, if any, avenues exist at the state level either through legislation or
  the judicial system to protect/offer legal recourse for developers served
  with a notice?

* How can I confirm a request is real

* Even though you're covered for civil, what about foreign law GDPR/SOX/SOC2

* What is the meaning behind the clause "pre-condition"

* What are the legal implications of quiting if your company is served a
  warrant or notice

* how do you document/prove that a TAR that was given orally
	* e.g. if you don't comply, what is to say you actually received it

* Could a technician fixing your phone or computer be forced to install spyware

* If I get served with one of these requests, what do I do? In particular, how,
  where and when do I find a lawyer to help me?

* If there is a legal way to make a canary, how should one go about it

* what kind of language should we seek to have added to contracts to allow us
  to legally sign those contracts while allowing for the possibility we may
  need to deliver malware to our clients

* for software distributed to general consumers, what kind of changes to the
  software license / terms of service should we include to advise them that we
  may at any time without notice include malware in the software

* What format will a request for assistance take? Is it a letter, an email or a
  tap on the shoulder by an intelligence/police officer

* If an employer is served a warrant or notice, can you quit without being
  legally liable

* If a vulnerability is discovered, how do you determine if it was an accident
  and fix it, or a something done under a notice

* Who is liable for loss or harm due to a changed from a notice

* what are the implications if you have a startup or small business, or work
  for yourself, and your business is closing (either in the case where you had
	decided to close it in response to a notice, or the case where you received a
  notice when plans to wind down where already in progress
