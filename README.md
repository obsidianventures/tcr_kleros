# Token Curated Registries for Kleros + MakerDAO
The purpose of this repository is to create a framework for token curated registries ("TCRs") on Kleros for real-world assets. The immediate goal will be to architect the TCRs for the Trust and Centrifuge Model. These are existing models that have been used on MakerDAO to produce collateralized instances for users to mint DAI.

The TCR will rely on guidelines, procedures and jurors in the Kleros ecosystem. The TCR will operate using a dispute procedure for a specific kind of court in Kleros that we will now name as the "Securities Court". The purpose of the securities court will be to:

1. Assess the quality of real-world tokens and assets
2. Arbitrate cross-border securities disputes for tokens on the blockchain

The structure and parameters of the court will be determined using the framework for the different models, and the MakerDAO TCRs. Below, we go into more detail on what the TCRs can look like. Subsequently, into more of what the criteria for the courts could look like.

## TCRs and their workflow

The initial TCRs (let's call it "Phase 1") will focus on creating a list of token **models**. Phase 2 will focus on real world asset tokens. The purpose of this repository is on Phase 1, but is being built to be extendable for Phase 2.

The workflow for the TCRs would be included as part of the existing MakerDAO collateral onboarding process. The purpose of this is to provide for a part of the MakerDAO process for onboarding collateral where tokens **must** first be approved by the Kleros protocol with sufficient quality before being listed in MakerDAO. The problem here is that some tokens may take a while to approve, given that they are going through a commercial arbitration process on Kleros to assess their quality. The way we will avoid these long waiting times is by:

1. (Phase 1) Focusing on TCRs for token models first to create a general framework for real world asset collateral;
2. (Phase 2) Creating TCRs for tokens that will refer back to approved models. 

Therefore, to be approved, a TCR for a real world asset on either MakerDAO or Phase 2 of the TCRs on Kleros, would only need to prove that they're classified under an existing and approved TCR model on Kleros for real world assets.

Token models are general frameworks for onboarding collateral assets onto blockchains in the jurisdiction of Delaware. In the future, these frameworks will continue to scale and grow as the market for real world assets on the blockchain continue to grow. The TCRs will provide a filter mechanism to decide on the quality of those token models.

The TCRs will be made up of the following components:

1. **Evidence** - these are contracts and documents that architect what the token model looks like and is made up of. For example, each token model will be a list of certain sets of documents/samples that would be provided as part of the framework. The evidence in this case wil almost always be templates of the documents that are being used to create the digital versions of the tokens for the end-user of the real world assets. In this case, the end users are MakerDAO vault owners;
2. **Badge** - each token model will be provided with a "Badge". The Badge will be denominated by colors and will determine the status of the models as they are being arbitrated.
   1. Green: the token model has been approved by Kleros jurors;
   2. Red: the token model has been challenged and does not pass the quality test of Kleros jurors;
   3. Yellow: the token model is currently being arbitrated;
   4. Orange: the token model has been provisionally approved pending certain changes to the templates, structures or other documents provided in the decision by Kleros jurors;
3. **Requirement** - each token model and TCR will come with a set of requirements that summarize how the token model meets legal criteria to be listed as a token. The requirements serve as a summary of the token model and its primary characteristics.
4. **Workflow** token models for real world asset securiites can be confusing. Each TCR for a token model will provide a workflow that summarizes step-by-step how the process of operating the model works.
5. **Compliance** - Each TCR will provide a framework for how it will meet certain compliance measures, especially those related to data protection, KYC and AML while on the blockchain.

Here's what the architecture of the MakerDAO collateral onboarding process would look like:

# Structure of the Kleros Courts

Kleros would need a form of a court to assess the quality of the token models for real world assets in the TCRs. To do this, we would need to create a court with certain parameters. Some of those parameters and considerations are below. First, we have to admit that securities arbitration is a very specific and intense field of knowledge. The first step would be to identify the **ideal** kind of juror:

1. Background and knowledge in securities and corporate law;
2. At least 3 to 5 years of corporate and securities experience in the jurisdiction of the TCR (the TCRs will start off as jurisdiction specific);
3. Experience launching tokens or a background in building token economics for tokenized platforms;
4. Active investing portfolio using any kind of digital or real world asset;
5. Has securities experience across multiple jurisdiction.

At the very least, jurors will have to prove a level of legal knowledge or experience in the jurisdiction of the TCR. 

The ideal kind of juror will be really hard to find. That's because this new court would effectively replicate commercial arbitration, which is a really specific field of knowledge. Here are some of the parameters the court would need:

1. **Arbitration Guidelines** - a set of guidelines used to arbitrate or review the quality of the TCR. These guidelines would need to be built using some of the procedural elements from populate arbitration courts around the world:
   1. Hong Kong International Arbitration Center
   2. International Commercial Arbitration Center
   3. American Arbitration Center
   4. Kigali International Financial Center
   5. Caribbean Court of Justice (Arbitral Arm)
2. **Time-Frame** - given the time-sensitive nature of listing tokens as collateral for real world assets, there would need to be a specific time frame through which the voting for the TCR would be open following its listing for approval;
3. **Token Distribution** - the token distribution model for this kind of court will likely result in higher payments of tokens back to jurors for deciding on cases given the specialty of the securities knowledge required. 

# Draft Models

The first two draft models will be the "Centrifuge" and "Trust" model, both of which will be vetted and approved by the MakerDAO real world assets group. Here is a draft template of the Centrifuge model:

 [centrifuge.md](models/centrifuge.md) 





