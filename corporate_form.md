# Corporate Governance for Primal ETH, Inc.

This document proposes a corporate governance structure for Primal ETH, a Delaware company.  As Primal ETH seeks to brand itself as an Ethereum-specific fundraising portal, an overall goal for this corporate structure is to use Ethereum-based applications wherever practicable.  This document is split up into the following three sections: (1) Stock; (2) Board of Directors; and (3) Shareholders Voting.  Each of these sections will give a brief overview of a proposal, followed by the relevant law governing each proposal, then followed by a more detailed explaination of the proposal.

## Stock

### Overview

### Relevant Law

[8 Del 224](https://delcode.delaware.gov/title8/c001/sc07/index.shtml)

Summary: Corporate records can be stored using distributed networks, as long as the corporate ledger can be used to prepare a list of stockholders.

Any records administered by or on behalf of the corporation in the regular course of its business, including its stock ledger, books of account, and minute books, may be kept on, or by means of, or be in the form of, any information storage device, method, or 1 or more electronic networks or databases (including 1 or more distributed electronic networks or databases), provided that the records so kept can be converted into clearly legible paper form within a reasonable time, and, with respect to the stock ledger, that the records so kept (i) can be used to prepare the list of stockholders specified in §§ 219 and 220 of this title, (ii) record the information specified in §§ 156, 159, 217(a) and 218 of this title, and (iii) record transfers of stock as governed by Article 8 of subtitle I of Title 6. Any corporation shall convert any records so kept into clearly legible paper form upon the request of any person entitled to inspect such records pursuant to any provision of this chapter. When records are kept in such manner, a clearly legible paper form prepared from or by means of the information storage device, method, or 1 or more electronic networks or databases (including 1 or more distributed electronic networks or databases) shall be valid and admissible in evidence, and accepted for all other purposes, to the same extent as an original paper record of the same information would have been, provided the paper form accurately portrays the record.

[8 Del 202](https://delcode.delaware.gov/title8/c001/sc06/index.shtml):

Summary: Restrictions on stock transfers are allowed as long as the restriction is "noted conspicuously" on certificated stocks, or contained in notices for un-certificated stocks.  The restrictions are binding on successors.  These restrictions are presumed reasonable if done for the company to keep or hold a regulatory advantage.  In our case, the advantage is preventing the stocks from being listed on an exchange, or otherwise publicly transferable, so as to avoid SEC penalties.

(a) A written restriction or restrictions on the transfer or registration of transfer of a security of a corporation, or on the amount of the corporation's securities that may be owned by any person or group of persons, if permitted by this section and noted conspicuously on the certificate or certificates representing the security or securities so restricted or, in the case of uncertificated shares, contained in the notice or notices given pursuant to § 151(f) of this title, may be enforced against the holder of the restricted security or securities or any successor or transferee of the holder including an executor, administrator, trustee, guardian or other fiduciary entrusted with like responsibility for the person or estate of the holder. Unless noted conspicuously on the certificate or certificates representing the security or securities so restricted or, in the case of uncertificated shares, contained in the notice or notices given pursuant to § 151(f) of this title, a restriction, even though permitted by this section, is ineffective except against a person with actual knowledge of the restriction.

(b) A restriction on the transfer or registration of transfer of securities of a corporation, or on the amount of a corporation's securities that may be owned by any person or group of persons, may be imposed by the certificate of incorporation or by the bylaws or by an agreement among any number of security holders or among such holders and the corporation. No restrictions so imposed shall be binding with respect to securities issued prior to the adoption of the restriction unless the holders of the securities are parties to an agreement or voted in favor of the restriction.

(c) A restriction on the transfer or registration of transfer of securities of a corporation or on the amount of such securities that may be owned by any person or group of persons is permitted by this section if it:

(1) Obligates the holder of the restricted securities to offer to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing, a prior opportunity, to be exercised within a reasonable time, to acquire the restricted securities; or

(2) Obligates the corporation or any holder of securities of the corporation or any other person or any combination of the foregoing, to purchase the securities which are the subject of an agreement respecting the purchase and sale of the restricted securities; or

(3) Requires the corporation or the holders of any class or series of securities of the corporation to consent to any proposed transfer of the restricted securities or to approve the proposed transferee of the restricted securities, or to approve the amount of securities of the corporation that may be owned by any person or group of persons; or

(4) *Obligates the holder of the restricted securities to sell or transfer an amount of restricted securities to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing, or causes or results in the automatic sale or transfer of an amount of restricted securities to the corporation or to any other holders of securities of the corporation or to any other person or to any combination of the foregoing*; or

(5) Prohibits or restricts the transfer of the restricted securities to, or the ownership of restricted securities by, designated persons or classes of persons or groups of persons, and such designation is not manifestly unreasonable.

(d) Any restriction on the transfer or the registration of transfer of the securities of a corporation, or on the amount of securities of a corporation that may be owned by a person or group of persons, *for any of the following purposes shall be conclusively presumed to be for a reasonable purpose*:

(1) Maintaining any local, state, federal or foreign tax advantage to the corporation or its stockholders, including without limitation:

a. Maintaining the corporation's status as an electing small business corporation under subchapter S of the United States Internal Revenue Code [26 U.S.C. § 1371 et seq.], or

b. Maintaining or preserving any tax attribute (including without limitation net operating losses), or

c. Qualifying or maintaining the qualification of the corporation as a real estate investment trust pursuant to the United States Internal Revenue Code or regulations adopted pursuant to the United States Internal Revenue Code, or

(2) *Maintaining any statutory or regulatory advantage or complying with any statutory or regulatory requirements under applicable local, state, federal or foreign law.*

(e) Any other lawful restriction on transfer or registration of transfer of securities, or on the amount of securities that may be owned by any person or group of persons, is permitted by this section.

(Italics added)

### Purchase

The stock is a restricted class, meaning it can only be transferred back to the corporation.  In order for someone to purchase Primal ETH stock, they must have an Ethereum account with one of our Validation Tokens.

#### Validation Token

In order to accept an incoming transfer of Primal Token, an Ethereum address must have a Validation Token.  The Validation Token must verify that the owner of the Ethereum address has submitted his/her name and physical address so that it can be recorded onto Primal ETH's corporate ledger.  The Token must also be non-transferable so that another unregistered address cannot use it to purchase our stock.

Ideally, the corporate ledger would be updated automatically.  Here is an example of what our ledger should reflect:

Eth Address | Name | Address | Shares
------------ | ------------- | ------------- | -------------
0x9d6d492bD500DA5B33cf95A5d610a73360FcaAa0 | John Smith | 555 Aether Drive, New York, NY | 100
0x9d6d492bD500DA5B33cf95A5d610a73360FcaAa0 | Jane Roe | 444 Satoshi Wei, Denver, CO | 250

Information regarding the stockholder's name and address should not be made public, or stored on the blockchain.

There is the question of what happens if someone gives our ledger a fake name and address.  Purchasers should be warned beforehand, and even perhaps be forced to agree to a click-wrapped agreement, that if they give false information, their stock could be dissolved.  If we suspect fraud, we could verify the account by sending a letter to the address provided.  If we receive a return-to-sender, we could freeze the account until or unless the person listed in the ledger can verify his/her information.

Once an Ethereum address has a Validation Token, and we have a name and physical address associated with that account, the purchaser can purchase stock from our smart contract.

#### Smart Contract

A purchaser will initiate the exchange of ETH for stock by sending an amount of ETH to the smart contract.  The smart contract will check to make sure msg.sender's balance of validation tokens is >= 1, then send stock to the purchaser's address (or else return error).  The stock should be dynamically priced similar to Vitalik Buterin's blog post that was the impetus for Uniswap, with the smart contract getting the sole benefit of increased fees.

### Sell

The purchaser can *only* sell the stock back to the corporation.

## Board of Directors Voting

### Overview

### Relevant Law

## Shareholders Voting

### Overview

### Relevant Law
