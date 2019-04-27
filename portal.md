# ETHEREUM-BASED REGULATION CROWDFUNDING PORTAL DEMONSTRATION

## Plain English Overiew

We're building an SEC-compliant funding portal that needs to verify that an individual investor actually exists as a legal person, and that that invidual isn't spending more than $2,200 per year on this kind of fundraising (called "Regulation Fundraising).  The goal is to make this portal as automated as possible using uPort, Chainlink, and OpenLaw.

## Legalalise Overview

The objective of this project is to present the Securities and Exchange Commission with a working model for a fundraising portal that's compliant with SEC Rules concerning Regulation Fundraising.  (https://www.sec.gov/rules/final/2015/33-9974.pdf).  This working model is intended to streamline SEC compliant fundraising using the [OpenLaw](OpenLaw.io) platform and Ethereum token sales.

Issuers using Regulation Crowdfunding are can raise up to $1.07 million within a 12-month period from the general public, including non-accredited investors.  However, these individual investors are restricted by the amount they are allowed to invest.  The SEC provided a chart showing the different limits investors are able to make depending on their annual income or net worth.  In order to ensure investors aren't exeeding their limit, the SEC has put into place, what they call, "funding portals," private businesses acting as brokers or intermediaries for the issuers and investors.  Specifically, the SEC defines funding portals as

>any [broker] acting as an intermediary in a transaction involving the offer or sale of securities for the account of others, solely pursuant to Securities Act Section 4(a)(6), that does not: (1) offer investment advice or recommendations; (2) solicit purchases, sales or offers to buy the securities offered or displayed on its website or portal; (3) compensate employees, agents or other persons for such solicitation or based on the sale of securities displayed or referenced on its website or portal; (4) hold, manage, possess or otherwise handle investor funds or securities; or (5) engage in such other activities as the Commission, by rule, determines appropriate. [Source](https://www.sec.gov/rules/final/2015/33-9974.pdf). [Note that rule 300(c)(2) modified Exchange Act Section 3(a)(80) by changing "person" to "broker."]

In addition, these funding portals must register with the SEC as a broker under Exchange Act Section 15(b), or as a funding portal pursuant to Section 4A(a)(1) and proposed Rule 400 of Regulation Crowdfunding.  Rule 300(a).  [SEC Guidelines on Registering Portals](https://www.sec.gov/divisions/marketreg/tmcompliance/fpregistrationguide.htm)  The funding portals also must register with any applicable self-regulatory organization, as defined in Exchange Act Section 3(a)(26).  Exchange Act Section 3(h)(1)(B) separately requires, as a condition of the exemption from broker registration, that a funding portal be a member of a national securities association that is registered with the Commission under Exchange Act Section 15A. Id.  In other words, the portal has to also register with FINRA.  [Note: FINRA has simplistic workshop video for funding portals on their [website](http://www.finra.org/industry/funding-portals).]

The funding portal's directors, officers, and/or partners are prohibited from owning or receiving any benefit from issuers using their platform. Rule 300(b).  However, the portal *as an entity* may receive compensation from issuers provided that (1) the intermediary receives the financial interest from the issuer as compensation for the services provided to, or for the benefit of, the issuer in connection with the offer or sale of such securities being offered or sold in reliance of Regulation Crowdfunding through the intermediary's platform; and (2) the financial interest consists of securities of the same class and having the same terms, conditions, and rights as the securities being offered or sold in reliance of RC through the intermediary's platform.  Id.

In other words, the issuer can compensate the portal for services provided in the form of money or common stock (same securities offered on the portal to the general public).

**Measures to reduce the risk of fraud**.  Securities Act Section 4A(a)(5) requires an intermediary to "take such measures to reduce the risk of fraud."  This "requires that an intermediary have a ***reasonable basis*** for believing that an issuer seeking to offer and sell securities" through the intermediary's platform complies with the related requirements in Regulation Crowdfunding [emphasis added] Rule 301(a).  

In addition, Rule 301(b) "requires an intermediary to have a ***reasonable basis for believing that an issuer has established means to keep accurate records*** of the holders of the securities it would offer and sell through the intermediary's platform, and provides that in satisfying this requirement, an intermediary may rely on the representations of the issuer concerning its means of recordkeeping unless the intermediary has reason to question the reliability of those representations."

Rule 301(c)(1) requires an intermediary to deny access to its platform if the intermediary has a ***reasonable basis*** for believing that an issuer is subject to a disqualification under Rule 503 of Regulation Crowfunding.  The rule also requires, as per Section 4A(a)(5), that an intermediary conduct a background and securities enforcement regulatory history check on each issuer whose securities are to be offered by the intermediary, as well as on each of its officers, directors, and 20% owners.

Rule 301(c)(2) requires denial of access to its platform when the intermediary has a reasonable basis for believing that the issuer or offering presents the potential for fraud or otherwise raises concerns about investor protection.  It also requires (i) an intermediary deny access to an issuer if it reasonably believes that it is unable to adequately or effectively assess the risk of fraud of the issuer or its potential offering, and (ii) if the intermeidary becomes aware of information after it has granted the issuer access to its platform that causes it to reasonably believe that the issuer or the offering presents the potential for fraud or otherwise raises concerns regarding investor protection, the intermediary must promptly remove the offering from its platform, cancel the offering and return to investors any funds they may have committed.

Rule 302(a)(2) prohibits a portal from accepting an investor that has not "opened an account" with the portal, and the portal obtained the investor's consent to electronic delivery of materials.  The portal is further required to provide all information required by Subpart C of Regulation Crowdfunding through electronic means.  This information must be provided through an electronic message that either contains the information, includes a specific link to the information as posted on the intermediary's platform, or provides notice of what the information is and that it is located on the intermediary's platform or the issuer's website.  Email is explicityly ***allowed***.

The comments to rule 302(a)(2) state that "opening an account" is required so that the portal can collect identifying information that could help prevent duplicative or fraudulent accounts.  In regards to duplicative or fraudulent accounts, ***uPort*** has the potential to solve this issue entirely by veryifying the indentity of individual investors.

Rules 302(b)(1)(i)-(viii) require portals to deliver, at account opening, educational materials that are in plain language and otherwise designed to communicate effectively and accurately the following:

• the process for the offer, purchase and issuance of securities through the intermediary;
• the risks associated with investing in securities offered and sold in reliance on Section
4(a)(6);
• the types of securities that may be offered on the intermediary’s platform and the risks
associated with each type of security, including the risk of having limited voting power
as a result of dilution;
• the restrictions on the resale of securities offered and sold in reliance on
Section 4(a)(6);
• the types of information that an issuer is required to provide in annual reports, the
frequency of the delivery of that information, and the possibility that the issuer’s
obligation to file annual reports may terminate in the future;
• the limits on the amounts investors may invest, as set forth in Section 4(a)(6)(B);
• the circumstances in which the issuer may cancel an investment commitment;
• the limitations on an investor’s right to cancel an investment commitment;
• the need for the investor to consider whether investing in a security offered and sold in
reliance on Section 4(a)(6) is appropriate for him or her; and
• that following completion of an offering, there may or may not be any ongoing
relationship between the issuer and intermediary.
• risks reasonably tailored to a portal's offerings and investors.

(Rule 302(c) requirement)

• the portal must inform investors, at the account opening stage, that any person who promotes an issuer's offering for compensation, whether past or prospective, or who is a founder or an employee of an issuer that engages in promotional activities on behalf of the issuer on the intermediary's platform, must clearly disclose in all communications on the platform the receipt of the compensation and the fact that he or she is engaging in promotional activities on behalf of the issuer.

(Rule 302(d) requirement)

• provide information to investors about the manner in which the portal will be compensated by the issuers.

The comments state that we are not prohibited from providing additional material.

Rule 303(a) requires disclosure of information required under Rules 201 and 203(a) not later than 21 days prior to the first day on which securities are sold to any investor:

(1) be publicly available on the intermediary’s platform, in a manner that reasonably permits a person accessing the platform to save, download or otherwise store the information; 

(2) be made publicly available on the intermediary’s platform for a minimum of 21 days before any securities are sold in the offering, during which time the intermediary may accept investment commitments; and 

(3) remain publicly available on the intermediary’s platform until the offer and sale of securities is completed or cancelled (including any additional information provided by the issuer).

Rule 303(a)(4) expressly ***forbids*** a portal to require an account to access that information.

**Compliance with Investment Limits**

Rule 303(b)(1) requires that a portal must have a ***reasonable basis*** for believing that the investor satisfies the investment limits established by Section 4(a)(6)(B).  The rule further allows an intermediary to rely on an investor's representations concerning annual income, networth, and the amount of the investor's other investments in securities sold in reliance of Section 4(a)(6) through other intermediaries unless the intermediary has a reasonable basis to question the reliability of the representation.

Rule 302(b)(2) requires that, each time before accepting an investment committment, to obtain from the investor a representation that the investor has reviewed the portal's educational materials, understands that the entire amount of his/her investment may be lost and is in a finacial condition to bear the loss of the investment.  Furthermore, the rule requires that a portal obtain from the investor answers to questions demonstrating the investor's understanding that there are restrictions on the investor's ability to cancel an investment commitment and obtain a return of his/her investment, that it may be difficult for the investors to resell the secruties, and that the investor should not invest any funds in a crowdfunding offering unless he/she can afford to lose the entire amount of his/her investment.

Rule 303(c) requires a portal to provide, on its platform, channels through which investors can communicate with one another and with representatives of the issuer about offerings made available on the intermediary's platform.  Portals are expressly ***prohibited*** from participating in communications in these channels.  The portal is also required to (2) make the communications channels publicly available; (2) permit only those persons who have opened accounts to post comments; and (3) require any person posting a comment in the communication channels to disclose whether he or she is a founder or an employee of an issuer engaging in promotional activities on behalf of the issuer, or is otherwise compensated, whether in the past or prospectively, to promote the issuer's offering.

Rule 303(d) requires the portal to promptly send to the investor a notification upon receipt of an investment commitment.  The notification must disclose: (1) the dollar amount of the investment commitment [note: we might have to use a ChainLink oracle as an automated way to show the dollar amount, at the time of commitment, in ETH]; (2) the price of the securities, if known; (3) the name of the issuer; and (4) the date and time by which the investor may cancel the investment commitment.  This notitification must be provided by email or other electronic media, and would be documented in accordance with applicable recordkeeping rules.

Rule 303(e)(1) requires the portal to ensure that all offering proceeds are only provided to the issuer when the aggregate capital raised from all investors is equal to or greater than a target offering amount.  Rule 303(e)(2) requires that a portal, because it can't receive funds, directs the investors to transmit money directly to a qualified third party that has agreed in writing to hold the funds for the benefit of the investors and the issuer and to promptly transmit or return the funds to the person entitled to such funds.  The rule defines "qualified third party" to mean a registered broker or dealer that carries customer or broker or dealer accounts and holds funds or securities for those persons, a bank, or a credit union insured by the National Credit Union Administration. that has agreed in writing to either: (i) hold the funds in escrow for the persons who have the beneficial interests in the funds and to transmit or return the funds directly to the persons entitled to them when the appropriate event has occurred; or (ii) establish a bank account for the exclusive benefit of investors and the issuer.

[note: since the trusted third party could be a bank account, perhaps it could also be a smart contract to act as an escrow.  However, this wouldn't satisfy the requirement of needing a bank to agree to this in writing.

Rule 303(e)(3) requires a portal to promptly direct transmission of funds from the qualified third party to the issuer when the aggregate amount of investment commitments from all investors is equal to or greater than the target amount of the offering and the cancellation period for each investor has expired, provided that in no event may the funding portal direct this transmission of funds earlier than 21 days after the date on which the portal makes publicly available on its platform the information required to be provided by the issuer under Rules 201 and 203(a).

Rule 303(f)(1) requires that a portal, at or before the completion of a transaction, give or send to each investor a notification disclosing: (1) the date of the transaction; (2) the type of security that the investor is purchasing; (3) the identity, price and number of securities purchased by the investor, as well as the number of securities sold by the issuer in the transaction and the price(s) at which the securities were sold; (4) certain specified terms of the security, if it is a debt or callable security; and (5) the source, form, and amount of any remuneration received or to be received by the intermediary in connection with the transaction, whether from the issuer or from other persons.  This notification would be required to be provided by email or other electronic media, and to be documented in accordance with applicable recordkeeping rules.

Rule 303(f)(2) requires the portal that gives or sends to each investor the notification would be exempt from the requirements of Exchange Act Rule 10b-10 for the subject transaction.

Rule 304(a) gives investors an unconditional right to cancel an investment commitment for any reason until 48 hours prior to the deadline identified in the issuer's offering materials.

Rule 304(b)provides that if an issuer reached the target offering amount prior to the deadline identified in its offering materials, it could close the offering once the target offering amount was reached, provided that: (1) the offering had been open for a minimum of 21 days; (2) the intermediary provided notice about the new offering deadline at least five business days prior to the new offering deadline; (3) investors would be given the opportunity to reconsider their investment decision and to cancel their investment commitment until 48 hours prior to the new offering deadline; and (4) at the time of the new offering deadline, the issuer continued to meet or exceed the target offering amount.

Rule 304(c) provides that if there was a material change to the terms of an offering or to the information provided by the issuer about the offering, the intermediary would be required to give or send to any investors who have made investment commitments notice of the material change, stating that the investor’s investment commitment will be cancelled unless the investor reconfirms his or her commitment within five business days of receipt of the notice.  if the investor failed to reconfirm his or her investment within those five business days, the intermediary would be required, within five business days thereafter, to: (1) provide or send the investor a notification disclosing that the investment commitment was cancelled, the reason for the cancellation and the refund amount that the investor should expect to receive; and (2) direct the refund of investor funds.

Rule 305(a) prohibits an intermediary from compensating any person for providing it with the “personally identifiable information” of any investor.  The definion of personally identifiable information is in Rule 305(b).

Rule 400 establishes a streamlined registration process for a funding portal to register with the SEC.

The project is divided into the following four parts: (0) Preliminary Matters; (1) Issuer Streamlining; (2) Purchaser Portal; and (3) Identity Solutions.  Each of these parts are described below.

## Part 0: Preliminary Matters

0. Creating a working demonstration of the portal.
1. Creating a subsidiary owned in whole or part by Open, ESQ LLC.
2. Registering subsidiary as a fundraising portal with the SEC.
3. Registering subsidiary as a fundraising portal with FINRA.

## Part 1: Issuer Streamlining

### Proposal A

#### Assumptions

0. The portal must ensure that no officers, directors, the like, and/or partners are receiving direct benefit from the issuers.
1. As per Rule 301(c)(1) & (2), the Portal is responsible for performing due dilligence on the issuer, its officers directors, and >20% owners.
2. Using that due dilligence, the portal needs the ability to deny access to issuer for which the portal has a reasonable basis that fraud is or was being committed.
3. Only skilled attorneys are capable of understanding the application of specific facts to legal starndars.

#### Conclusion

Decisions on whether specific issuers use the platform can't be made in a decentralized way.  Instead, they must ultimately be made by attorneys.

#### Proposal

Design the portal so that attorneys can have a period of time to do due dilligence on the issuer, and give the attorneys the power to deny the issuer ***at anytime*** they believe there is a reasonable basis for violations.

### Proposal B

#### Assumptions

0. Regulation crowdfunding allows portals, ***as business entities***, to accept payment for services provided to issuers in the form of money or the same common equity being offered through the portal to the general public.
1. The SEC considers cryptocurrency, including ETH, to be money.
2. The market this portal is targeting is comprised only of U.S.-based companies that want to fundraise using token sales.
3. Developers of this demonstrations wish to use the efficiency of what's been called "smart legal contracts" being developed on OpenLaw.
4. The expertise of the participants in this demonstration is generally with Ethereum-based smart contracts.

#### Conclusion

The portal will provide streamlining to U.S.-based companies wishing to launch their token sales on Ethereum.  This will include providing online forms using OpenLaw whenever appropriate.  The portal will change issuers for these services, in either money or common stock, along with the cost of due dilligence described in Proposal A.

## Part 2: Investor Streamlining

#### Assumptions

0. The portal is required to ensure that an investor doesn't go over his/her investment limit.
1. The portal is allowed to rely on representations from the investor, unless the portal has reason to question the reliability of those representations.
3. In order to prevent duplicative and fraudulent accounts, the portal must ensure that a portal account is linked to an actual person with a real identity.
4. The portal must send certain educational material and disclosures to an investor electronically (email) upon account creation.
5. When an investor is fully compliant with these requirements, a ChainLink oracle can autonomously call a function on Issuer's token sale, whitelisting the investor's address.

## Part 3: Identity Solutions
