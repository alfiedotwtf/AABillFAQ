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

# Disclaimer

**This is some legal information about the AA Act, and should be read as such. It
is not intended to be legal advice. If you need advice about your particular
situation, you should contact a lawyer. If you need a referral for a lawyer,
you are welcome to get in touch. Of course, given that this is relatively new
law, the information we have about it may change over time as it starts being
used. We welcome feedback to that end. This was drafted by Lizzie O'Shea, with
assistance from Patrick Fair.**

# Answered Questions

*There has been confusion around who can recieve a warrant, TAN, TAR, and TCN.
Some people are saying that only telco providers in the traditional sense
receive these and then get staff and contractors to execute them, while others
say that anyone can be approached directly who have knowledge of a system or
the capability to access and modify a system, regardless of their current
status: i.e local or remote, citizen or foreigner, employee or contractor or
former employee or ever hobbyist.*

*Who can be approached with a warrant, TAN, TAR, and TCN to execute it?*

Let's start with TAR/TAN/TCN (for ease of reference, let's call all of these
Sch 1 notices – while noting that a TAR is actually a voluntary request). A Sch
1 notice can be given to a "designated communications provider." This is a
defined term at s 317C and is very broad. For example, it includes a person who
"provides an electronic service that has one or more end-users in Australia."
Section 317D(2) specifically includes a website in the definition of
"electronic service." The former-Law Enforcement and Cyber Security Minister
Angus Taylor's office
[confirmed](https://www.afr.com/news/cyber-security-laws-to-cover-all-businesses-angus-taylor-confirms-20180815-h13zdo)
to the Australian Financial Review that the laws would apply to "any entity
operating a website."

The definition of designated communications provider refers to "persons" which
can be individual people or legal persons (a legal person is a entity capable
of being sued, like a company).

For practical reasons, if an individual worker was be given a Sch 1 notice, it
is highly likely they will need to tell other people in their company about
them in order to execute the notice. Under s 317ZB, for example, the designated
communications provider is only required to comply with the Sch 1 notice to the
extent that the carrier or provider is capable of doing so. So it is
technically possible that an individual employee could be given a Sch 1 notice,
but it is also unlikely for practical reasons that they would be somehow
required to carry out the requirements without their employer knowing, for
example. The agency would be better off just giving the notice to the company
itself.  Section 317ZF(3)(a) may also offer protection of an individual in
these circumstances. It states that an employee of a designated communications
provider may disclose information about Sch 1 notices "in connection with the
administration or execution of this Part." There is a little ambiguity about
who this applies to in the drafting, but its plain meaning looks like it would
offer protection to an employee disclosing this information to others for
carrying out the Sch 1 notice.

As to whether someone from the list (local or remote employee, citizen or
foreigner, employee or contractor or former employee or even hobbyist) could be
given a Sch 1 notice, the answer is yes. The person is only required to comply
to the extent they are capable of doing so, but there is no restriction on
where the person is located, or whether the person is a current or a former
employee (though the language is unclear on this point).

However, it should be noted that the relevant agency will probably have a hard
time getting a company based entirely outside of the country to comply with any
Sch 1 notice. While such a notice could seemingly be served, there remains
practical obstacles to enforcing it in circumstances where the company has no
assets or employees in the jurisdiction (provided the company is not prepared
to comply of its own accord). The point here is practical more than legal - the
power still exists.  For this reason, any company with employees or an office
located in Australia can be given a Sch 1 notice, and they face serious risks
if they do not comply, including significant fines.

The AA Bill also contained some new provisions relating to warrants. This
included the insertion of a new section into the Surveillance Devices Act, s
64A which requires that a person with knowledge of a computer or a computer
system to assist a law enforcement officer to access information. This can be
anyone. It should be noted that this new provision is subject to the secrecy
provisions in s 45 of that act. Those secrecy provisions have a long list of
exceptions, they are mostly particular and narrow.

It is very important to have clear idea of what is being required and under
what power.

---

*Can these warrants and notices force you to build or modify software that
circumvents a product's security, your company's security, or even somebody
else's security (not the target), so that they can use it as a stepping
stone to get into the target's computer.*

*E.g. their target buys your microphone, which needs a Windows driver to run.
Can you be forced to modify your Windows driver and push a targetted update
that will then allow spying or even remote access to their computer)*

Yes. A Sch1 notice can be given to any company (or person) in the supply chain
and other companies in the supply chain will have no way of knowing whether the
product has been compromised or tampered with under this Act. This is one of
the controversial provisions in the Act, because a user cannot tell if software
or hardware installed in a system can be trusted.

This question also raises an interesting point about the object of the Sch 1
notice. There is a general limit on Sch 1 notices, in that they have no effect
to the extent (if any) to which such a notice would require a designated
communications provider to do an act or thing for which the agency would be
required to have or obtain a warrant or authorisation under certain acts (see s
317ZH). It’s slightly clunky drafting, but in general terms, the point of this
provision is to make sure the agency gets a warrant when it wants the
designated communications provider to disclose information.

The agency might issue the Sch 1 notice to ensure it gets the "access and
assistance" to enable the information described in the warrant to be delivered.
What happens if the Sch 1 notice tells you to install software or equipment
that gives the agency direct access to the information they want without asking
the designated communications provider? It may be debatable but it looks like
the agency won't need a warrant or authorization if they can get access the
data without asking the designated communications provider.

That’s fine for warrants, but authorisations are a little more tricky. For
example, the metadata retention regime authorises certain agencies to request
metadata without a warrant but require the agency (without going to a judicial
officer) to get the metadata if they issue an authorisation. There is an
interesting (and alarming) example here that might illustrate the point.

It is easy to imagine that an agency might want the metadata of a leaker of
sensitive government information, if they suspect the leaking breaks the law.
The agency would be authorised to obtain the metadata of the leaker without a
warrant.  This means the agency could issue a Sch 1 notice that is directed
towards finding out the identity of the leaker, including against people that
the leaker might be in contact with (ie people other than the target). This Sch
1 notice could include things like installing malware on the phone of a
journalist who might be publishing the leaks. In this example, the Sch 1 notice
is being used to undermine a person’s security who is not the target, pursuant
to an authorisation.

---

*If approached directly with a warrant or notice, are you allowed to tell
anyone? e.g colleagues in order to assist in executing them, bosses to let them
know they are compromising the safety of their systems and their own work
schedule will be affected, and legal team to check validity of request*

If you are given a Sch 1 notice, you are allowed to tell certain people. In
general, the regime permits a person given a Sch 1 notice to share information
about that notice for the purposes of executing it. That includes people within
the agency who gave you the Sch 1 notice. It also includes people within your
company, both above you and below you in reporting terms, as well as
contractors.

It is important to think about what is reasonable in the context, and how a
court might interpret this at a later time. One way to protect yourself is to
ask for a list of people in writing to whom you can make disclosures from the
agency that has given you the Sch 1 notice.

For the purposes of being a bit more specific, the relevant section is s 317ZE.
It’s lengthy and it is a bit technical, but here are a couple of provisions
that are probably most likely to be relevant. You are able to disclose
information about a Sch 1 notice:

* in accordance with any requirement imposed by a law of the Commonwealth, a
State or a Territory;

* for the purpose of obtaining legal advice in relation to the provisions
around unauthorized disclosures.

This means if you are unsure, you should seek legal advice, which you are
permitted to do under the Act.

---

*What happens if there is a bug in your execution of the warrant or notice,
which leads to unauthorised disclosure?*

Section 371ZJ cover this kind of situation. It sets out that a designated
communications provider is not subject to any civil liability for an act or
thing done in compliance with (or in good faith in purported compliance with) a
technical assistance notice or a technical capability notice. (Note that
technical assistance requests are excluded from this. Note also that they are
voluntary).

If there is a bug in the execution of the warrant, provided it is done in good
faith, the person who writes it will not be held liable for unauthorized
disclosures that might come about as a result.

---

*When approached with a warrant or notice, how does one verify the authenticity
of the people serving them, and the legality of the request?*

The recipient of a Sch 1 notice should never accept anything they are told over
the telephone by email or in person. They should contact the agency directly
using an independently obtained number or contact details in order to obtain
independent verification of the identity of the issuing party.

If there is some uncertainty about this, you should speak to a lawyer, which
the Act permits you to do. The lawyer should also be able to give you advice
about whether the Sch 1 notice is lawful.

We note the following about who is authorised to give what:

* Technical assistance notices must be given the Director-General of Security or
  the chief officer of an interception agency. If the technical assistance
  notice is given by the chief officer of an interception agency, it must be
  approved by the Australian Federal Police Commissioner.

* Technical capability notices may only be given by the Attorney General, in
  accordance with a request made by the Director-General of Security or the
  chief officer of an interception agency. The Communications Minister must
  also approve the technical capability notice.

* The Attorney General can probably delegate this authority, but there should
  be some indication that this has happened in the notice itself.

* Prior to giving the technical capability notice, the Attorney General is
  required to consult the designated communications provider.  The provider may
  request that assessors be appointed to determine whether the notice should be
  given.

In general, Sch 1 notices must be in writing, except in certain circumstances,
such as an imminent risk of serious harm or substantial damage to property, or
it is not practical to do so. But the relevant person is generally required to
make a written record of the decision within 48 hours.

---

*Are warrant canary's legal or even possible to disclose warrants or notices?*

Under s 317ZF, a person must not disclose information about a Sch 1 notice.
This includes "technical assistance notice information," "technical capability
notice information," and "technical assistance request information." All these
terms are defined, and they all include "the existence or nonexistence" of the
relevant notice or request.

For example, imagine that a company posted information online such as: "it has
been six months since we haven't received a technical assistance notice" and
then this information is taken down or adjusted when these facts changed.  This
would be information about the existence or nonexistence of a technical
assistance notice and would be in breach of s 317ZF.

There is clearly something of a logical loop here, in that it is somewhat
tricky to clearly define what might be a disclosure about the non-existence of
the notice or request. But the point of the provision appears to be to prevent
the use of warrant canaries, and a court is therefore likely to interpret it in
that way.

For completeness, we also note that there are relevant provisions at s 317ZA
and 317ZB which requires a person to comply with a requirement under a
technical assistance notice or a technical capability notice. A requirement
here will most likely include the prohibition on disclosing information about
that notice. That is, disclosing information about the notice will be a
contravention.

Notably, a person must not be complicit in the contravention of s 317ZA. That
is, you cannot:

* aid, abet, counsel or procure a contravention
* induce, whether by threats or promises or otherwise, a contravention
* be in any way, directly or indirectly, knowingly concerned in, or party to, a
  contravention
* conspire with others to effect a contravention.

# Unsorted and Unanswered Questions

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

* How may an individual seek legal advice wrt the receipt of a TAN/TAR/TCN
  without risking noncompliance or violating nondisclosure?

* Is it legal to implement international code review practices that would
  render a stealth implementation of a TAN/TAR/TCN impossible?

* What if executing a TCN is actually impossible

* What if executing a warrant or Notice, you need the help of others

* In an outsourced environment (e.g managed service provider) if you go against
  your contractural agreement to excersise a warrant or Notice on computer
  systems you have access to but do not own, are you criminally liable

* Can contractors (working via an agency and not employed by the company) be
  subject to warrants or Notices directly or even via their agencies, or the
  company they are working with

  * What are the legal ramifications if you quit when asked to exercise a
    warrant or Notice

* Under the Criminal Code, it is a criminal offence to interfere with
  communication facilities. If carring out a warrant or Notice requires you to
  interfere with communication facilities, are you liable for criminal charges

  * Does that mean the people involved who created the warrant or Notice
    conspired to commit a crime

  * Does this mean any evidence during the illegal act is not admisible in
    court

  * Does this mean legal proceeding could make public a warrant or Notice

* 317ZB "... makes an exception for contravention of foreign laws in a foreign country"
  * If a provider needs legal advice about a foriegn law, are you allowed to
    disclose a warrant or Notice to a foriegn lawyer

* Does any provision cover asking your employer for leave or other similar
  administrative arrangements

* Because of 317E, does this mean Open Source software is exempt the AABill
