***THIS DOCUMENT IS FOR DEMONSTRATION PURPOSES ONLY AND SHOULD NOT BE USED AS LEGAL OR FINANCIAL ADVICE***

# Corporate Governance for Primal ETH, Inc.

> Ether [...] is one of the lower principles of what we call primordial substance, one of the dreams of old, and which has now become again the dream of modern science.

> --H.P. Blavatsky, *The Secret Doctrine* 1888

This document proposes a corporate governance structure for Primal ETH, a Delaware company.  As Primal ETH seeks to brand itself as an Ethereum-specific fundraising portal, an overall goal for this corporate structure is to use Ethereum-based applications wherever practicable.  This document is split up into the following three sections: (1) Stock; (2) Board of Directors; and (3) Shareholders Voting.  Each of these sections will give a brief overview of a proposal, followed by the relevant law governing each proposal, then followed by a more detailed explaination of the proposal.

## Stock

### Overview

The stock is a restricted class with voting rights.  It will be held in a smart contract and paired with ETH so that it is dynamically priced similar to Uniswap exchanges, with the smart contract being the sole liquidity provider.  In order to receive the stock, purchasers must obtain a verification token, which can be obtained through another smart contract that acts as a faucet.  The purchaser must give us his/her name and mailing address in exchange for the verification token so that ownership may be reflected on our corporate ledger, as is required by Del. law.

### Relevant Law

[8 Del 224](https://delcode.delaware.gov/title8/c001/sc07/index.shtml)

Summary: Corporate records can be stored using distributed networks, as long as the corporate ledger can be used to prepare a list of stockholders.

> Any records administered by or on behalf of the corporation in the regular course of its business, including its stock ledger, books of account, and minute books, may be kept on, or by means of, or be in the form of, any information storage device, method, or 1 or more electronic networks or databases (including 1 or more distributed electronic networks or databases), provided that the records so kept can be converted into clearly legible paper form within a reasonable time, and, with respect to the stock ledger, that the records so kept (i) can be used to prepare the list of stockholders specified in §§ 219 and 220 of this title, (ii) record the information specified in §§ 156, 159, 217(a) and 218 of this title, and (iii) record transfers of stock as governed by Article 8 of subtitle I of Title 6. Any corporation shall convert any records so kept into clearly legible paper form upon the request of any person entitled to inspect such records pursuant to any provision of this chapter. When records are kept in such manner, a clearly legible paper form prepared from or by means of the information storage device, method, or 1 or more electronic networks or databases (including 1 or more distributed electronic networks or databases) shall be valid and admissible in evidence, and accepted for all other purposes, to the same extent as an original paper record of the same information would have been, provided the paper form accurately portrays the record.

[8 Del 202](https://delcode.delaware.gov/title8/c001/sc06/index.shtml):

Summary: Restrictions on stock transfers are allowed as long as the restriction is "noted conspicuously" on certificated stocks, or contained in notices for un-certificated stocks.  The restrictions are binding on successors.  These restrictions are presumed reasonable if done for the company to keep or hold a regulatory advantage.  In our case, the advantage is preventing the stocks from being listed on an exchange, or otherwise publicly transferable, so as to avoid SEC penalties.

> (a) A written restriction or restrictions on the transfer or registration of transfer of a security of a corporation, or on the amount of the corporation's securities that may be owned by any person or group of persons, if permitted by this section and noted conspicuously on the certificate or certificates representing the security or securities so restricted or, in the case of uncertificated shares, contained in the notice or notices given pursuant to § 151(f) of this title, may be enforced against the holder of the restricted security or securities or any successor or transferee of the holder including an executor, administrator, trustee, guardian or other fiduciary entrusted with like responsibility for the person or estate of the holder. Unless noted conspicuously on the certificate or certificates representing the security or securities so restricted or, in the case of uncertificated shares, contained in the notice or notices given pursuant to § 151(f) of this title, a restriction, even though permitted by this section, is ineffective except against a person with actual knowledge of the restriction.

> (b) A restriction on the transfer or registration of transfer of securities of a corporation, or on the amount of a corporation's securities that may be owned by any person or group of persons, may be imposed by the certificate of incorporation or by the bylaws or by an agreement among any number of security holders or among such holders and the corporation. No restrictions so imposed shall be binding with respect to securities issued prior to the adoption of the restriction unless the holders of the securities are parties to an agreement or voted in favor of the restriction.

> (c) A restriction on the transfer or registration of transfer of securities of a corporation or on the amount of such securities that may be owned by any person or group of persons is permitted by this section if it:

> (1) Obligates the holder of the restricted securities to offer to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing, a prior opportunity, to be exercised within a reasonable time, to acquire the restricted securities; or

> (2) Obligates the corporation or any holder of securities of the corporation or any other person or any combination of the foregoing, to purchase the securities which are the subject of an agreement respecting the purchase and sale of the restricted securities; or

> (3) Requires the corporation or the holders of any class or series of securities of the corporation to consent to any proposed transfer of the restricted securities or to approve the proposed transferee of the restricted securities, or to approve the amount of securities of the corporation that may be owned by any person or group of persons; or

> (4) *Obligates the holder of the restricted securities to sell or transfer an amount of restricted securities to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing, or causes or results in the automatic sale or transfer of an amount of restricted securities to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing*; or

> (5) Prohibits or restricts the transfer of the restricted securities to, or the ownership of restricted securities by, designated persons or classes of persons or groups of persons, and such designation is not manifestly unreasonable.

> (d) Any restriction on the transfer or the registration of transfer of the securities of a corporation, or on the amount of securities of a corporation that may be owned by a person or group of persons, *for any of the following purposes shall be conclusively presumed to be for a reasonable purpose*:

> (1) Maintaining any local, state, federal or foreign tax advantage to the corporation or its stockholders, including without limitation:

> a. Maintaining the corporation's status as an electing small business corporation under subchapter S of the United States Internal Revenue Code [26 U.S.C. § 1371 et seq.], or

> b. Maintaining or preserving any tax attribute (including without limitation net operating losses), or

> c. Qualifying or maintaining the qualification of the corporation as a real estate investment trust pursuant to the United States Internal Revenue Code or regulations adopted pursuant to the United States Internal Revenue Code, or

> (2) *Maintaining any statutory or regulatory advantage or complying with any statutory or regulatory requirements under applicable local, state, federal or foreign law.*

> (e) Any other lawful restriction on transfer or registration of transfer of securities, or on the amount of securities that may be owned by any person or group of persons, is permitted by this section.

(Italics added)

### Purchase

The stock is a restricted class, meaning in this case that the stockholder is only able to transfer the stock back to the Company's smart contract.  This restriction is in place so that the Company's corporate ledger reflects the ownership of the stock, as required by § 224, as well as to prevent the stock from being sold on a secondary market, thus triggering SEC regulation.  In order for someone to purchase Primal ETH stock, they must have an Ethereum account with one of our Validation Tokens.

#### Validation Token

In order to accept an incoming transfer of Primal Token, an Ethereum address must have a Validation Token.  The Validation Token must, at the very least, verify that the owner of the Ethereum address has submitted his/her name and mailing address so that it can be recorded onto Primal ETH's corporate ledger.  The Token must also be non-transferable so that another unregistered ETH address cannot use it to purchase our stock, and also so the token doesn't end up on a secondary market.

Ideally, the corporate ledger would be updated automatically.  Here is an example of what our ledger should reflect:

Eth Address | Name | Address | Shares
------------ | ------------- | ------------- | -------------
0x9d6d492bD500DA5B33cf95A5d610a73360FcaAa0 | John Smith | 555 Aether Drive, New York, NY | 100
0x9d6d492bD500DA5B33cf95A5d610a73360FcaAa0 | Jane Roe | 444 Satoshi Wei, Denver, CO | 250

Information regarding the stockholder's name and address should not be made public, or stored on the blockchain.

There is the question of what happens if someone gives our ledger a fake name and address.  Purchasers should be warned beforehand, and even perhaps be forced to agree to a click-wrapped agreement, that if they give false information, their stock could be dissolved.  If we suspect fraud, we could verify the account by sending a letter to the address provided.  If we receive a return-to-sender, we could freeze the account until or unless the person listed in the ledger can verify his/her information.

Another question is whether we should allow anyone with an Ethereum address to purchase Primal ETH stocks this way.  There are two options here: (i) permissionless stock sales; and (ii) permissioned stock sales.

With a permissionless stock sale mechanism, Validation Tokens would be given to anyone who submits their name and address.  This mechanism seems to fit in well with overarching ethos of the cryptocurrency space, that decentralized and permissionless are the only way forward.  However, SEC dicta seems to imply that selling to the general public will invite scrutiny, even absent explicit statutory violations.  In other words, if companies sell to the public, the SEC will find a reason to shut you down.  Take this passage from the DAO report for example:

> Anyone was eligible to purchase DAO Tokens (as long as they paid ETH).  There were no limitations placed on the number of DAO Tokens offered for sale, the number of purchasers of DAO Tokens, or the level of sophistication of such purchasers.

> DAO Token holders were not restricted from re-selling DAO Tokens acquired in the offering, and DAO Token holders could sell their DAO Tokens in a variety of ways in the secondary market and thereby monetize their investment..."

Later on in the report while applying the *Howey* Test, the SEC emphasized that "form should be disregarded for substance."  The underlying policy at play, which is also the very impetus for the creation of the SEC, is need to protect unsophisticated investors from losing their life savings.  In implementing this policy, the SEC would use whatever mechanisms are at its disposal.

In this vein, the SEC could argue that a permissionless sale of equities puts the unsophisticated public-at-large at risk, and therefore it should be shut down, even absent a clear statutory violation.

There's always the option of fighting enforcement actions in court, but the time and expense needed for such litigation would be high, and the risk and reward would be low.  Courts generally defer to agencies (see (Chevron v. Natural Resources Defense Council, Inc.)[https://www.law.cornell.edu/supremecourt/text/467/837]), which means we'd be fighting an uphill battle.  There's also the likelihood of our reputation being damaged by the mere accusation of wrongdoing, which will likely be dissiminated in the press and on social media.  As such, any reputation we might've eaned with the community for implementing permissionless trading of our stock could be offset.  

Which brings us to the permissioned option.  Delaware law allows directors *or* stockholders to decide the terms of restricted stock.  We could let either group vote on whether to issue a validation to a new investor after an opportunity to assess the investor's character and background.  With fewer, close investors, Primal ETH appears to have more of the *form* of traditional, private corporations.  And with the opportunity to assess the investor's character and background, we'd be in a better position to avoid any unsophisticated investors.

This, of course, only perpetuates the problem of income inequality by excluding average investors in favor for experienced ones.  Not only is this detrimental public policy, but it could also harm our reputation.  The problem is that the state has an interest in keeping its citizens solvent because impoverished citizens are more likely to use public resources like medicare, welfare, and subsidized housing.  If a publicly distributed asset bubble pops, the state would become overwhelmed with wards.  To prevent this, the state bars its average citizens from investing in certain speculative assets.  But this bar also acts as a gatekeeper, preventing average investors from purchasing high risk/high reward investments (unless the state is the beneficiary of the purchase as in the case of state lotteries).  These investments therefore are in the sole domain of elite investors, who're often times already wealthy.  Thus, as the old saying goes, the rich get richer and the poor get poorer.

This labyrinth of competing policies is something we should keep in mind in case we're able to find an equitable path forward.  But for now, we should use a permissioned system for distributing Validation Tokens.

Once an Ethereum address has a Validation Token, and we have a name and physical address associated with that account, the purchaser can purchase stock from our smart contract.

#### Smart Contract

A purchaser will initiate the exchange of ETH for stock by sending an amount of ETH to the smart contract.  The smart contract will check to make sure msg.sender's balance of validation tokens is >= 1, then send stock to the purchaser's address (or else return error).  The stock should be dynamically priced similar to Vitalik Buterin's blog post that was the impetus for Uniswap, with the smart contract getting the sole benefit of increased fees.

### Sell

The purchaser can *only* sell the stock back to the corporation.  The process for this would be that the stockholder would click on a "sell" option and be told the current dynamic price for the stock.  If the stockholder sends stock back to the smart contract, the corporate ledger would ideally automatically update, and the stockholder would get an amount of ETH (as determined by dynamic pricing) in return.

## Shareholders Voting

### Overview

Annual stockholders meetings would be conducted remotely on a company webpage.  Holders of Primal stock could nominate directors, and vote on directors in a DAO-like setting (Aragon?).  We would need to record the stockholders who are present for our corporate records.  The meeting would be conducted through a streaming service.  There is an Ethereum-based streaming service called [LivePeer](https://livepeer.org), which we should utilize if practicable (or something similar).

It's important that the shareholders are given full control over the election of directors, with sufficient abilities to organize and share information in order to excercise their power.  Otherwise, it could be argued that the stockholders were forced to rely on the "managerial efforts of others", as the SEC found in it DAO report.  As such, we should provide a live chat in order to let shareholders exchange information.

### Relevant Law

[SEC Release No. 81207 Report of Investigation](https://www.sec.gov/litigation/investreport/34-81207.pdf)

Summary: SEC report of investigation found that The DAO sold unregistered securities in the form of investment contracts.  In applying the Howey Test, the SEC report found that (a) an investment of money was made in the form of ETH; (b) an expectation of profit was reasonable due to advertising and promoting; and (c) the "managerial efforts of others" requirement was met because the token holders didn't have sufficient control over the (un-incorporated) company.

> The central issue is “whether the efforts made by those other than the investor are the undeniably significant ones, those essential managerial efforts which affect the failure or success of the enterprise.” SEC v. Glenn W. Turner Enters., Inc., 474 F.2d 476, 482 (9th Cir. 1973).

> The voting rights afforded DAO Token holders did not provide them with meaningful control over the enterprise, because (1) DAO Token holders’ ability to vote for contracts was a largely perfunctory one; and (2) DAO Token holders were widely dispersed and limited in their ability to communicate with one another.

> First, as discussed above, DAO Token holders could only vote on proposals that had been cleared by the Curators.38 And that clearance process did not include any mechanism to provide DAO Token holders with sufficient information to permit them to make informed voting decisions. Indeed, based on the particular facts concerning The DAO and the few draft proposals discussed in online forums, there are indications that contract proposals would not have necessarily provide enough information for investors to make an informed voting decision, affording them less meaningful control. For example, the sample contract proposal attached to the White Paper included little information concerning the terms of the contract. Also, the Slock.it co-founders put forth a draft of their own contract proposal and, in response to questions and requests to negotiate the terms of the proposal (posted to a DAO forum), a Slock.it founder explained that the proposal was intentionally vague and that it was, in essence, a take it or leave it proposition not subject to negotiation or feedback. See, e.g., SEC v. Shields, 744 F.3d 633, 643-45 (10th Cir. 2014) (in assessing whether agreements were investment contracts, court looked to whether “the investors actually had the type of control reserved under the agreements to obtain access to information necessary to protect, manage, and control their investments at the time they purchased their interests.”).

> Second, the pseudonymity and dispersion of the DAO Token holders made it difficult for them to join together to effect change or to exercise meaningful control. Investments in The DAO were made pseudonymously (such that the real-world identities of investors are not apparent), and there was great dispersion among those individuals and/or entities who were invested in The DAO and thousands of individuals and/or entities that traded DAO Tokens in the secondary market—an arrangement that bears little resemblance to that of a genuine general partnership.


## Board of Directors Voting

### Overview

Each director will receive his/her voting token from the stockholder meeting.  The voting token will allow the directors to vote for proposals in a specific DAO.  A simple majority of directors should suffice to carry a vote, with at least 2/3 present for a quorum.  Meetings can be carried out remotely in accordance with Delaware law.

### Relevant Law
