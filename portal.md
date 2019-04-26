# DECENTRALIZED REGULATION FUNDRAISING PORTAL DEMONSTRATION

## Plain English Overiew

We're building an SEC-compliant funding portal that needs to verify that an individual investor actually exists as a legal person, and that that invidual isn't spending more than $2,200 per year on this kind of fundraising (called "Regulation Fundraising).  The goal is to make this portal as automated as possible using uPort, Chainlink, and OpenLaw.

## Legalalise Overview

The objective of this project is to present the Securities and Exchange Commission with a working model for a decentralized fundraising portal that's compliant with [17 CFR §§ 200, 227, 232, 239, 240, 249, 269, & 274 (2016)](https://www.sec.gov/rules/final/2015/33-9974.pdf).  This working model is intended to streamline SEC compliant fundraising using the [OpenLaw](OpenLaw.io) platform and Ethereum token sales.

Issuers using Regulation Crowdfunding are can raise up to $1.07 million within a 12-month period from the general public, including non-accredited investors.  However, these individual investors are restricted by the amount they are allowed to invest.  The SEC provided a chart showing the different limits investors are able to make depending on their annual income or net worth.  In order to ensure investors aren't exeeding their limit, the SEC has put into place, what they call, "funding portals," private businesses acting as brokers or intermediaries for the issuers and investors.  Specifically, the SEC defines funding portals as

>any [broker] acting as an intermediary in a transaction involving the offer or sale of securities for the account of others, solely pursuant to Securities Act Section 4(a)(6), that does not: (1) offer investment advice or recommendations; (2) solicit purchases, sales or offers to buy the securities offered or displayed on its website or portal; (3) compensate employees, agents or other persons for such solicitation or based on the sale of securities displayed or referenced on its website or portal; (4) hold, manage, possess or otherwise handle investor funds or securities; or (5) engage in such other activities as the Commission, by rule, determines appropriate. [Source:](https://www.sec.gov/rules/final/2015/33-9974.pdf). [Note that rule 300(c)(2) modified Exchange Act Section 3(a)(80) by changing "person" to "broker."]

In addition, these funding portals must register with the SEC as a broker under Exchange Act Section 15(b), or as a funding portal pursuant to Section 4A(a)(1) and proposed Rule 400 of Regulation Crowdfunding.  Rule 300(a).  [SEC Guidelines on Registering Portals](https://www.sec.gov/divisions/marketreg/tmcompliance/fpregistrationguide.htm)  The funding portals also must register with any applicable self-regulatory organization, as defined in Exchange Act Section 3(a)(26).  Exchange Act Section 3(h)(1)(B) separately requires, as a condition of the exemption from broker registration, that a funding portal be a member of a national securities association that is registered with the Commission under Exchange Act Section 15A. Id.  In other words, the portal has to also register with FINRA.  [Note: FINRA has simplistic workshop video for funding portals on their [website](http://www.finra.org/industry/funding-portals).]

The funding portal's directors, officers, and/or partners are prohibited from owning or receiving any benefit from issuers using their platform. Rule 300(b).  However, the portal *as an entity* may receive compensation from issuers provided that (1) the intermediary receives the financial interest from the issuer as compensation for the services provided to, or for the benefit of, the issuer in connection with the offer or sale of such securities being offered or sold in reliance of Regulation Crowdfunding through the intermediary's platform; and (2) the financial interest consists of securities of the same class and having the same terms, conditions, and rights as the securities being offered or sold in reliance of RC through the intermediary's platform.  Id.

In other words, the issuer can compensate the portal for services provided in the form of money or common stock (same securities offered on the portal to the general public).

The project is divided into the following three parts: (1) Issuer Streamlining; (2) Purchaser Portal; and (3) Identity Solutions.  Each of these parts are described below.

**Measures to reduce the risk of fraud**.  Securities Act Section 4A(a)(5) requires an intermediary to "take such measures to reduce the risk of fraud."  This "requires that an intermediary have a ***reasonable basis*** for believing that an issuer seeking to offer and sell securities" through the intermediary's platform complies with the related requirements in Regulation Crowdfunding [emphasis added] Rule 301(a).  

In addition, Rule 301(b) "requires an intermediary to have a ***reasonable basis for believing that an issuer has established means to keep accurate records*** of the holders of the securities it would offer and sell through the intermediary's platform, and provides that in satisfying this requirement, an intermediary may rely on the representations of the issuer concerning its means of recordkeeping unless the intermediary has reason to question the reliability of those representations."

Rule 301(c)(1) requires an intermediary to deny access to its platform if the intermediary has a ***reasonable basis*** for believing that an issuer is subject to a disqualification under Rule 503 of Regulation Crowfunding.  The rule also requires, as per Section 4A(a)(5), that an intermediary conduct a background and securities enforcement regulatory history check on each issuer whose securities are to be offered by the intermediary, as well as on each of its officers, directors, and 20% owners.

Rule 301(c)(2) requires denial of access to its platform when the intermediary has a reasonable basis for believing that the issuer or offering presents the potential for fraud or otherwise raises concerns about investor protection.  It also requires (i) an intermediary deny access to an issuer if it reasonably believes that it is unable to adequately or effectively assess the risk of fraud of the issuer or its potential offering, and (ii) if the intermeidary becomes aware of information after it has granted the issuer access to its platform that causes it to reasonably believe that the issuer or the offering presents the potential for fraud or otherwise raises concerns regarding investor protection, the intermediary must promptly remove the offering from its platform, cancel the offering and return to investors any funds they may have committed.




## Part 1: Issuer Streamlining

### Proposal A

#### Assumptions

^As per Rule 301(c)(1) & (2), the Portal is responsible for performing due dilligence on the issuer, its officers directors, and >20% owners.
^Using that due dilligence, the portal needs the ability to deny access to issuer for which the portal has a reasonable basis that fraud is or was being committed.
^Only skilled attorneys are capable of understanding the application of specific facts to legal starndars.

#### Conclusion

Decisions on whether specific issuers use the platform can't be made in a decentralized way.  Instead, they must ultimately be made by attorneys.

#### Proposal

Design the portal so that attorneys can have a period of time to do due dilligence on the issuer, and give the attorneys the power to deny the issuer ***at anytime*** they believe there is a reasonable basis for violations.

### Proposal B

#### Assumptions

^The expertise of the participants in this demonstration is generally with Ethereum-based smart contracts.
^The market this portal is targeting is specifically U.S.-based companies that want to fundraise using token sales.
^Developers of this demonstrations wish to use the efficiency of what's been called "smart legal contracts" being developed on OpenLaw.
^Regulation crowdfunding allows portals, ***as business entities***, to accept payment for services provided to issuers in the form of money or the same common equity being offered through the portal to the general public.

#### Conclusion

The portal will provide streamlining to U.S.-based companies wishing to launch their token sales on Ethereum.  This will include providing online forms using OpenLaw whenever appropriate.  The portal will change issuers for these services, in either money or common stock, along with the cost of due dilligence described in Proposal A.


## Part 2: Purchaser Portal

## Part 3: Identity Solutions
