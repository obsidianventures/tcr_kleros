# Roadmap: Token Curated Registries for Kleros + MakerDAO
The purpose of this repository is to create a framework for token curated registries ("TCRs") on Kleros for real-world assets. The immediate goal will be to architect the TCRs for the Trust and Tinlake models, starting with Tinlake first. It has more traction and history than the Trust legal model. These models are the legal frameworks being used by companies that are listing real-world assets for collateral on MakerDAO. 

The TCR will rely on guidelines, procedures and jurors in the Kleros ecosystem. The TCR will operate using a dispute procedure for a specific kind of court in Kleros that we will now name as the "Asset Listing Court". The purpose of the securities court will be to:

1. Assess the quality of real-world tokens and assets
2. Arbitrate cross-border securities disputes for tokens on the blockchain
3. Provide a rating for the compliance of each asset in the form of a coloured badge (more below)

This project will roll out in three phases for the next 24 to 36 months:

1. Phase 1: Pilot the first two lists with the General Court for Real-World Asset token models on Kleros
2. Phase 2: Create new court for Asset Listing and Claims
3. Phase 3: Scale a Kleros Asset Court with real-time compliance data. 

The document in this roadmap summarizes the criterion and listing requirements for Phase 1 and 2. I recommend creating a court while we list the first TCRs. Phase 3 is to be determine and a much more ambitious project. A lot of the learnings from Phases 1 and 2 will guide 3, including the materials in this document.

The goal of this project is for Kleros to provide the world's real-time compliance infrastructure for on-chain securities, NFTs and real-world assets. Applications in DeFI, CeFI, central governments, Binance, Coinbase, exchanges and other protocols will be able to leverage Kleros' open source framework to rate, list and arbitration claims for on-chain assets.

Before getting into it, here are some logistics that I recommend for putting together the resources & team necessary to pull this off. After all, Kleros is a start-up with a community and limited resources. 

# Execution strategy: Kleros' resources & logistics

My first recommendation is to hire an internal team over time focused on real-world assets in the Kleros community. This project will take time and will scale. For now, you'll only need one person dedicated as a project manager for the next 6 to 12 months. The project manager would need to work with Sébastien, Jimmy and Federico to publish the TCR and educate the MakerDAO and Kleros community about it. You'll need one advisor supporting on the project. 

By next year as it grows you'll need a team of 3 to 5 people, with the last 4 to 5 people supporting other platforms to list models, tokens as well as a member of the team to manage the new Real World Asset Court. By 2023 this could grow to a team of 5 to 10 people who are overseeing the performance of the Real-World Assets court on Kleros and creating partnerships with arbitral courts around the world. 

Over time, those courts will need to accept Kleros decisions. I've drafted the roadmap and content below using research and review from the Kigali, American, Hong Kong, Singapore, London, Caribbean, Bahamas, and other arbitral acts, rules and procedures from around the world. 

# Phase 1: Pilot two RWA curated lists with the General Court

The content below is part of a primary document for listing a curated list for real world assets on Kleros' registry. The General Court can review using 2 to 4 jurors who can challenge or approve the list when it is being curated.

### What are these lists for?

This section summarizes the materials necessary to list to the Kleros TCR registry with a list for "Real-World Assets". This list will be used to rate compliance for real-world asset token models being used to list multiple assets as MakerDAO collateral through the Real-World Asset core unit led by Sébastien. 

### What is it solving for?

Right now, it's solving for a blocker in the MakerDAO collateral onboarding process. The collateral onboarding process for listing real-world assets on MakerDAO is not going through a strong enough legal diligence. The party responsible for the onboarding process is the Real World Assets Core Unit. Their focus is on assessing the potential financial risks to the DAI peg when a real-world asset is listed as collateral. The team is not best placed to assess the legal structure & compliance of those assets, but they have to look at it anyway because there is no party or core unit dedicated to assessing the legal risk of real-world assets.

This could affect the DAI peg, because:

1. The Core Unit spends time assessing legal risk for both the assets and the token models for listing real-world assets
2. The Core Unit is spending less time focusing on the financial risks for those assets to the DAI peg
3. More & more assets are being listed with new and different models

To reduce these risks, the Core Unit relies on using a white label platform to list real-world assets for real-estate NFTs built on Centrifuge, with a white label version of the Securitize security token protocol and using the Tinlake Blockchain Protocol. The Centrifuge Platform provides a legal token and structure to list real-world assets. So, the Core Unit relied on this platform to launch other RWA assets and eventually it became a standard for other RWA listing companies to use.

The result is that 18 of the 26 real world collateral assets being listed on MakerDAO use a token model. These models are referred to as Centrifuge and Trust. They are both built on Delaware law and have limitations. For example, Centrifugre recently halted the listing service for RWA on its platform. Nearly half of the RWA on MakerDAO use Centrifuge. This kind of delay and disruption due to a centralized platform and token model like Centrifuge delays the listing & trading of RWA. That means the collateral and DAI peg could be affected if this is happening at scale.

The TCRs provide a decentralized and flexible method for verifying and rating the compliance for RWA for on-chain platforms like MakerDAO. A properly structured list on Kleros can be used as part of the MakerDAO collateral onboarding process. That means that the Core Unit at MakerDAO can rely on the list to rate legal token models for both Tinlake, Centrifuge and others in the future. The TCR will also provide a framework to scale new models outside of the Delaware jurisdiction.

### How will this list for curating legal models work on Kleros?

The TCR list will enable users to submit models for listing real-world assets on MakerDAO.  These models are legal structures created by MakerDAO community members. The structures are based in Delaware and there are two of them that are being used to list multiple assets. At our last count, 26 real-world assets are listing on MakerDAO. Over 12 of them use the Tinlake model, and 5 of them use the Trust Model. 

The first purpose of this list is to rate compliance for real-world assets listed on-chain. The link to the TCR can be shared in the MakerDAO collateral onboarding proposal and process for the community. The workflow for the TCRs would be included as part of the existing MakerDAO collateral onboarding process. The purpose of this is to provide for a part of the MakerDAO process for onboarding collateral where tokens **must** first be approved by the Kleros protocol with sufficient quality before being listed in MakerDAO. 

We have enough resources to list the Centrifuge ("**Tinlake**") and Trust ("**Trust**") models. They are structured in more detail and throughout this repository at @Models. Both of these token models use Delaware-based corporate structures to create tokens using subscription agreements and listing agreements.  The purpose & criterion for the court will evolve over time to accept both **token models and real world assets**. For now, we're focused on the models because the immediate and focused need is to solve the over-centralization of legal models for RWA on MakerDAO and the risks this could present to the DAI peg. 

Token models are general frameworks for onboarding collateral assets onto blockchains in the jurisdiction of Delaware. In the future, these frameworks will continue to scale and grow as the market for real world assets on the blockchain continue to grow. The TCRs will provide a filter mechanism to decide on the quality of those token models.

## What listing criteria will we need?

The list is the starting point to create a court over time (more below). To do that the listing criteria were built with this goal in mind. These criteria will be what we can use to create a new court in Phase 2: The Kleros Real-World Asset Court.

Each TCR listed on Kleros will need to require the following data, components and information:

1. **Jurisdiction** - the jurisdiction through which the legal model applies and can be used. For example, for Centrifuge this will be Delaware Law. The format can be a country drop-down, be sure to separate Delaware and the United States of America. 
2. **Creator** - Each of the models being created now are new legal frameworks for tokens and are being created by individuals, law firms and companies. Understanding and speaking with the people behind these models is useful because it provides assurance based on their background and experience in this space.  The format can be an entry field for text.
3. **Proof** - this would provide proof on if the asset has been used before in real-world assets or listings on-chain. This format for entry can be a field for text.
4. **Evidence** - these can be provided in a Google Drive, Dropbox or IPFS link. Ideally, IPFS. This format for entry can be a field for text or URLs. 
   1. **Diagram** - A visual flow of how each legal model works. This makes it a lot easier to follow and most of these models will come with in.
   2. **Contracts** - these are contracts and documents that architect what the token model looks like and is made up of. For example, each token model will be a list of certain sets of documents/samples that would be provided as part of the framework. 
   3. **URL Listing** - a link to the place where the model is being used, written about or tested.
   4. **Compliance** - Each TCR will provide a framework for how it will meet certain compliance measures, especially those related to data protection, KYC and AML while on the blockchain.

### Here's the Tinlake model

The first two draft models will be the "TInlake" and "Trust" model, both of have already been largely vetted and approved by the MakerDAO Real World Assets Coure Units. Here's the listing criteria for the Tinlake model. The trust model is still in development and can be added later.

[models/Listing Criteria - Tinlake.md](models/Listing Criteria - Tinlake.md)





## What's the workflow to pull this off in the MakerDAO collateral onboarding process?

Here's the newer workflow for the MakerDAO collateral onboarding process. The TCR lists for existing TCRs we're creating above for Tinlake and Trust will be used as part of the process at the very beginning of the process at **"Stage 1: Greenlight"**. A community member listing and asset on MakerDAO would need to include a link to the relevant TCR on Kleros.

The ideal court for this workflow on Kleros would be a court dedicated to Real-World Assets being listed. There is no such court at the moment on Kleros, we would need to create a new one. For now, and for speed of experimentation, this TCR can be used with the General Court, with a new set of listing criteria that will be used as part of the workflow. For the first TCR and General Court, we would need 3 to 5 jurors to look over each model.

Each juror would provide the following return / decision in a document. These requirements can be listed in the listing criteria for the TCR and used by the General Court as part of its decision making process for any disputes or issues that comes its way when it is curating the list. 

1. **Score** - each token model will be provided with a "Score". The Score will be denominated by colors and will determine the status of the models as they are being arbitrated.
   1. Green: the token model has been approved by Kleros jurors;
   2. Red: the token model has been challenged and does not pass the quality test of Kleros jurors;
   3. Yellow: the token model is currently being arbitrated;
   4. Orange: the token model has been provisionally approved pending certain changes to the templates, structures or other documents provided in the decision by Kleros jurors;
2. **Requirement** - each token model and TCR will come with a set of requirements that summarize how the token model meets legal criteria to be listed as a token. The requirements serve as a summary of the token model and its primary characteristics.

The TCR list for curating real world assets starts off focused on legal models for tokens. Over time, another list will soon emerge to add assets / tokens directly on the Kleros protocol to have them listed. This will kick-start the process for a need to arbitrate claims for those tokens since they will have a native listing on the Kleros protocol through the TCR product. Over time that will pressure the need for a new court to be created that will be focused entirely on listing, claims and appeals for on-chain real-world assets. None of the existing courts on Kleros have the specific criteria to list and arbitrate disputes for real-world assets.

This new court process can be initiated now in the Kleros community, but will be part of a longer phase in the Kleros community. The court would be the bridge between the real-world and on-chain assets' compliance. This will be the start to decentralized commercial arbitration.

# Phase 2: Create a new court on Kleros for listing, claims & appeals for on-chain real-world assets

## Introduction to the Kleros Asset Court

The Kleros Asset Court is the real-time compliance infrastructure for on-chain securities, NFTs and protocol tokens. The Asset Court uses TCRs and arbitral decisions for a real time list of the assets which are level to list in every country & jurisdiction. The Asset Court will leverage on existing commercial arbitration & dispute rules and procedures to build a more decentralized process to arbitrate disputes and reward claims through appeals.

Asset listing, arbitration and disputes will all come onto the blockchain over the next few years. New use cases will arrive and the kind of court that will be necessary to process 1,000s of disputes a second on chain will need to be built to be flexible and in phases. These assets will exist across all borders, and the need for commercial arbitration will accelerate quickly, since commercial arbitration is part of the dispute mechanisms to resolve securities disputes across borders. But, the current commercial arbitration process is slow, paper-based and highly centralized in the hands of a few jurors around the world. 

As a result, current methods of commercial arbitration will not be able to scale and accomodate resolving disputes real-world assets on-chain. And, even if they did - those arbitral courts would be too slow to resolve disputes and would not reflect the cultural and legal diversity of the wallet & addresses around the world that will be interacting with real-world assets on-chain. 

Even with these limitations, the real-world assets brought on chain are ultimately governed by real-world contracts, trade laws and biltateral investment treaties that provide final arbitral courts with the final approval on disputes and claims for cross-border securities and assets. Many of those courts and treaties are modelled on frameworks that are open source and available. That means that the new court on Kleros will need to interface with the rules and procedures built by these courts and arbitral tribunals - **because decisions / appeals made on Kleros' Asset Court will need to provide grounds of evidence in the procedures of arbitral courts around the world**. For example:

1. MakerDAO lists real-world asset from a Delaware based company
2. An NFT for that real-world asset is created on a legal model approved by the Kleros TCR
3. NFT is traded on platforms around the world using a series of addresses
4. NFT is sold on Platform B which took in KYC for that address being registered in Delaware. The same NFT is then sold on Platform A which took in KYC for the buying address being registered in Australi. The same NFT is then sold on Platform D which did not collect the correct KYC information but found the address' ISP to be in Madagascar.
5. The Delaware company files for bankruptcy but cannot claim the NFT from Platform D
6. Company provides for a claim to receive the NFT from Platform D as damanges on Kleros
7. Kleros jurors accept decision in appeal in favor of the Company using Delaware law
8. The address holder in Madagascar files to overturn the Kleros appeal in the court of Madagascar, who then sends it for dispute resolution under the rules of the London Court of International Tribunal
9. The London Court finds in favor of address holder in Madagascar under English law. The court does not use the Kleros decision as evidence because the Kleros rules and procedures are not in line with the latest versions of the London arbitral rules.

This is an example of the level of complexity that will exist between Kleros' Asset Court and real-world arbitral courts for the dispute resolution over assets and relating claims. That just means that the Kleros Asset Court infrastructure will need to be built to accomodate for this.

## What will the Kleros Asset Court look like?

Kleros's Asset Court will be a scalable, diverse and on-chain native court to resolve disputes. It will have the legal grounding to be accepted as evidence real-world arbitral and tribunal courts if someone decides to appeal a case beyond just the Kleros' protocol. 

This is a new court and needs to be created. The first use cases will be real-world asset compliance for assets listed on MakerDAO. That means that it can leverage the primary documents and criterion for the TCR list for real-world assets as part of the requirements for creating the court. This will also include any decisions and materials produced by the General Court during the pilot. 



The structure of the Kleros Courts to dispute Asset Claims will grow, and for now we're focused on building the first implementation of it using token-curated models for MakerDAO. The first iteration of this court will be called the "Asset Listing" court, and will be a court whose purpose is to oversee the quality of the compliance for assets/corporate structures being listed on the blockchain. Over time, the court will grow to add on an Asset Claims Court, Asset Arbitration Court, and will be structured according to different regions. The decisions of these courts will need to comply over time with the general rules for International Arbitration centers and growing trade agreements around the world. 

Here's a diagram of what the court could look like over time:

DIAGRAM

## Creating the first court: "Asset Listing"

These will roll out in phases, with our focus today on Asset Listing Court as the first court to be created. Here are some of the initial court parameters for the Asset Listing Court. The Asset Listing Court will specifically focus on curating the TCR list as well as reviewing the listing of assets onto platforms around the world that are security tokens, NFTs or protocol tokens to rate their compliance. The Asset Listing Court is the natural extension from the pilot of TCRs using the General Court for the Tinlake and Trust models. 

 

## "Asset Listing Court": Juror Qualification & Number of Jurors

This court will require a sizaeble number of jurors and therefore may start off as one of the more expensive courts. That's because it will need more jurors to agree to decisions at the initial decisions to reduce friction in appeals, and increase the diligence in the initial decision. To do this, we would need to create a court with certain parameters. Some of those parameters and considerations are below. First, we have to admit that securities arbitration is a very specific and intense field of knowledge. The first step would be to identify the **ideal** kind of juror:

1. Background and knowledge in securities and corporate law;
2. At least 3 to 5 years of corporate and securities experience in the jurisdiction of the TCR (the TCRs will start off as jurisdiction specific);
3. Experience launching tokens or a background in building token economics for tokenized platforms;
4. Active investing portfolio using any kind of digital or real world asset;
5. Has securities experience across multiple jurisdiction.

At the very least, jurors will have to prove a level of legal knowledge or experience in the jurisdiction of the TCR. 

## "Asset Listing Court": Listing policy for rules & procedures

The listing policy, rules and procedures for decision making will be emulated using existing rules and procedures in some of the world's best arbitral courts:

1. Hong Kong International Arbitration Center
2. International Commercial Arbitration Center
3. American Arbitration Center
4. Kigali International Financial Center
5. Caribbean Court of Justice (Arbitral Arm)

The rules and procedures that govern the Asset Listing court will be similar to those that govern the these rules and procedures in the above courts and will be a single document as part of the court 'Rules and Procedures'. Here's a snippet of what that will look like (pending a lot more legal research).

https://docs.google.com/document/d/1xHu5T1mvMxgZttrO0E7j_N_epPwf4ne3WnBZclhfx9o/edit



# Phase 3: Scaling a Kleros Asset Court

The last phase of this, and by far the most complicated - will be scaling a multi-jurisdictional Kleros court for claims, listing and arbitration of any disputes related to on-chain assets. The Kleros Court will need several divisions that cater for the multitude of regulations across the world dealing with assets, securities, NFTs and tokens. To do that, the TCRs for curating real-world assets legal models and tokens will serve as the main architecture through which the Kleros Court **maintains an open source framework for live real-world compliance**. The other parts of the court will use this open source framework as evidence to rely on and arbitrate disputes.

The architecture of the Kleros Asset Court over time will therefore be made up of two major sections:

1. Live real-world compliance and token curated lists
2. Decision-making and arbitral awards: a decentralized commercial arbitration court

The phases 1 and 2 built out the live real-world compliance models and assets to be sure that Kleros is providing an open framework to rate compliance for all on-chain real-world assets. Since that model is open source, the data on the latest compliance rules, decisions and cases for different assets should stay current and accurate within the Kleros lists for real-world assets.

With that data, the Kleros Asset Courts rules for deciding and arbitrating cases will use these lists as evidence. Even more, the court will need to be built to facilitate real-world enforcement of decisions made by the Kleros Asset Court (more on that above). In this way, the Kleros Asset Court and the future of Kleros for Real World Assets will act as a compliance infrastructure for on-chain commercial arbitration.

This means that each decision made by the Kleros Asset Court will likely correspond to the major trade laws, bilateral investment treaties and frameworks for cross-border commercial arbitration. That would mean that the Kleros Asset Court over time will both be divided by section and focus... but also by jurisdiction. Those jurisdictions will be under major groupings of governments, like the following trade agreements with investment dispute settlement laws:

1. AfCFTA: African Continental Free Trade Agreement
2. BRICS: Brazil, Russia, India, China, South Africa
3. ASEAN: Association of South East Asian Nations
4. CARICOM: Caribbean Community
5. OAS: Organization of American States
6. NAFTA: North American Free Trade Agreement
7. European Union

Kleros courts could be divided by the major groupings of these states to cater for decisions that can pass between these major jurisdictions. It will likely rely on the rules and guidelines of the world's major arbitral courts.

### Further research needed

Some of the major research needed to architect this court will be focused on a jurisdiction by jurisdiction level. Each legal model provided on the TCRs will provide the grounding and documents to standardize the templates to different jurisdictions. Those templates can be added as lists, and both the jurors and a Kleros internal team would be needed to maintain those templates, models, as well as to look out for new regulatory rulings in these jurisdictions to update the latest models.

# Conclusion

The goal of this project is for Kleros to provide the world's real-time compliance infrastructure for on-chain securities, NFTs and real-world assets. Applications in DeFI, CeFI, central governments, Binance, Coinbase, exchanges and other protocols will be able to leverage Kleros' open source framework to rate, list and arbitration claims for on-chain assets.

The architecture is split up to execute this roadmap in three phases:

1. Phase 1: Pilot the first two lists with the General Court for Real-World Asset token models on Kleros
2. Phase 2: Create new court for Asset Listing and Claims
3. Phase 3: Scale a Kleros Asset Court with real-time compliance data. 

The resources for Phase 1 and 2 are available above. The phase 3 is a longer term project. 



