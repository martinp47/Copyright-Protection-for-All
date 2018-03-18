# Copyright Protection for All
```
Resolving Disputes in the Fair Trade Music Model
```

   * [2 Minute Video](#2-minute-video)
   * [Code](#code)
   * [Introduction](#introduction)
   * [Background](#background)
   * [RelateID](#relateid)
   * [The Dispute Resolution Challenge](#the-dispute-resolution-challenge)
   * [The Smart Contract – License Assigned](#the-smart-contract--license-assigned)
   * [The Dispute](#the-dispute)
   * [The Dispute Resolution Process](#the-dispute-resolution-process)
   * [Resolution](#resolution)
   * [Smart Contract Overview](#smart-contract-overview)

# Who We Are
* [PeaceTones](https://peacetones.org)
* [RelateID](https://relateid.com)
* [eJust Systems](https://www.ejustsystems.com/)

# 2 Minute Video
[Copyright Protection for All video](http://www.youtube.com/watch?v=IBMa7vf2e7c&t=35s)
[Copyright Protection for All final video](https://www.youtube.com/watch?v=WrCXUJBOx1g&feature=youtu.be)

# Code
For this hackathon, the team is using the [Hyperledger](https://www.hyperledger.org/) project. You can find the code for this project in the following repositories:
* [Smart Contracts](https://github.com/relateid/cl-and-b-ny-2018)
* [Model](https://github.com/relateid/cl-and-b-ny-2018-model)

# Introduction
Music CAN change the world! PeaceTones&reg; enables musicians to develop and disseminate their art by brining crucial legal, technology, and business skills to historically unheard musicians. This empowers them as leaders and shapers of positive social change.

eJust and RelateID have joined forces with PeaceTones&reg; to address the question, “who owns created music?”. Join us as we combine eJust’s highly efficient dispute resolution framework and RelateID’s innovative identity verification, asset association, and storage protocols to address this crucial question.

We NEED your help – and so do people like Emmanuel, the Liberian refugee at the heart of the dispute we will resolve.

Music CAN change the world – and YOU can help. Join us Saturday at the [2018 Computational Law and Blockchain Festival](https://legalhackers.org/clbfest2018/). Follow the links below to find out more.

We look forward to working with you!

# Background
PeaceTones&reg; enables musicians to develop and disseminate their art by brining crucial legal, technology, and business skills to historically unheard musicians. Traditionally, in a developing country, refugee camp, or anywhere in the world (really), to initiate the music creation process, a producer relies on intermediaries for introductions and connections to identify musicians and verify the identity of the artists and the originality of their work. The secure, scalable trust-based RelateID blockchain simplifies and digitally enhances this process.

# RelateID
RelateID is a secure, scalable trust-based personal data blockchain for the world. It returns power over identity and the assets associated with that identity to the individual and gives him/her control over who accesses what private information, and for how long. The RelateID Identity Verification process (as it pertains to this case) is outlined in the attached Flow Diagram.

In addition to individual identities, complex immutable non-fungible transferable assets can be created, shared, and transferred on the RelateID network. This includes many forms of digital intellectual property, such as musical releases, art, technical papers, or literature, which can be created and managed by individuals or entities. Files can be stored on the distributed global file system known as the Inter Planetary File System (IPFS), and a unique asset can be created to track purchase and ownership of every copy of that asset (who has purchased what song and for how long, for example). The location of the asset in the IPFS can be encrypted into the asset token and transferred to anyone on the network. The location can only be acquired by the owner of the token, and each time the token is transferred, the location of the file on the IPFS – known as the hash of the file – can be changed, and the old hash removed to ensure that no one is able to access the files without permission. Any copies will be revealed as copies and not the original, based on the original time and date of creation of the original file.

With the RelateID identity and asset verification processes, the PeaceTones&reg; artist is securely, legally, and immutably linked to his or her music.

# The Dispute Resolution Challenge
PeaceTones&reg; is a trusted organization on the RelateID network. It has identified Emmanuel, a Liberian refugee, as a talented musician, and Kelsey, a trusted PeaceTones&reg; representative, has validated him on the RelateID network. Emmanuel creates a song and – with guidance from PeaceTones&reg; – uploads the song to the RelateID network. A hashing algorithm automatically creates cryptographic evidence on the IPFS that the song belongs exclusively to Emmanuel, and he may assign rights to it as he pleases.

# The Smart Contract – License Assigned
Emmanuel’s song is “discovered” by an Agent, who would like to use it in an advertisement. Emmanuel enters into a smart contract, licensing the song to the Agent for the exclusive purpose of using it for a set period in that single advertisement. The Smart Contract is executed, and the agreed $250 is automatically transferred from the Agent to Emmanuel.

# The Dispute
Unbeknownst to Emmanuel, the Agent authorizes use of the song in three additional advertisements and reaps the equivalent of $750 in rewards. Emmanuel discovers that his song has been used in multiple advertisements, and approaches the Agent, who dismisses him. He initiates a dispute pointing to the Smart Contract as evidence that the Agent licensed the song for the sole purpose if using it in a single advertisement.

Working with PeaceTones, Emmanuel is directed to eJust, a trusted organization on the RelateID network, to register and resolve the dispute.

# The Dispute Resolution Process
Following the eJust framework, dispute resolution proceedings are divided in four phases:

**1. Request for Arbitration (RfA):**
  * Working with PeaceTones®, Emmanuel, the Claimant, electronically provides contact information for both parties, himself and the Agent, and references the Smart Contract as evidence of the facts, legal arguments, and claims
  * The identity of both parties and the subject matter is verified on the RelateID network

**2. Response:**
  * The Administrator notifies the Respondent (the Agent) that an RfA has been filed by Emmanuel
  * The Agent reviews the RfA and drafts a response, providing his own facts, legal arguments, and claims
  * The response is submitted on electronically via the RelateID platform

**3. Investigation:**
  * An unbiased, third-party Arbitrator is appointed to the case
  * The Arbitrator reviews the elements submitted by the parties, Emmanuel and the Agent
  * The Arbitrator may ask for additional information, evidence, and/or arguments
  * The parties may also further discuss certain elements

*Final Offer Before Award (FOBA): By offering the possibility of settlement to both parties, the arbitrator’s goal is to maintain a business relationship, while acknowledging the existence of a dispute. Communication is key, as is the opportunity for the parties to make offers, in particular a final offer before award, and ultimately reach an agreement. The benefit of reaching such an agreement during arbitration proceedings is the fact it is recorded in the form of an award.*

**4. Award:**
  * Arbitrator drafts the award
  * Both parties are notified of the award is notified to the parties
  * Optional: If a party does not execute the award; the award can be enforced
# Resolution
The Arbitrator concluded that the terms of the Smart Contract are clear and should be enforced. The Agent is ordered to compensate Emmanuel the full amount he has received from the advertiser for the additional ads incorporating the song. Emmanuel is paid $750 -- $250 per additional ad.

# Smart Contract Overview
The smart contracts and all the code is available on the attibuted github repositories listed above. In short, two smart contracts exist with their associated unit tests.

## Validation of Person
The first smart contracts ensures that people added to the network meet the requirements to ensure trustability. The process is as follows.

An organization assigns someone, within said organization, to validate people and add them to the network. The smart contract will ensure that the assigned person (to add people to the network) is considered 'real' by the network. Additionally, the contract will ensure that the organization, the person is assigned to, is a 'trusted' organization. In the event that the person adding someone to the network is not considered 'real' or the organization is not 'trusted' then the transaction fails and the new person is not added to the network.

## Selling A Song On The Network
Organizations may sell songs on behalf of an artist. Artists may also sell a song themselves. The smart contract ensures that all the criteria for a sale is met as well as ensuring payment.

For example, PeaceTones&reg; is able to sell Emmanuels song. In so doing, both parties agree that PeaceTones&reg; will recieve 10% for each sale. The smart contract, in this situation, will pay Emmanuel 90% and PeaceTones&reg; 10%.

No sale is made in the event that the buyer does not have sufficent funds availble.

Once the song is sold, a record is created on the block chain called LicensedSong. This object will have all the information required to ensure protection for the consumer, PeaceTones&reg; and, most importantly, Emmanuel.

Note that at the time off sale, a license is applied to the sale. The current implementation supports a license type of 'COMMERCIAL_USE' and one for 'PERSONAL_USE'. The details of these licenses are not flushed out in the POC, however, they highlight the systems capabilities when it comes to dispute resolution. For example, should someone buy a song for 'PERSONAL_USE' but Emmanuel finds out it is being used commercially he would be able to file a dispute and all the facts would be easily retrieval on the blockchain.

In summary, this smart contract showcases the use cases to ensure fair payment as well as protecting the artist through the application of 'cementing' licensing agreements directly on the blockchain to ensure protection for Emmanuel.
