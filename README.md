# Evaluating the portal network as a data availability layer

## What is it?

I will research the viability of using the portal network for data availability (DA).

To be more specific, I will investigate the feasibility of using the portal network to serve and permanently store EIP-4844 blobs.

## What Problem(s) are Being Solved?

The specific research questions, suggested by Danny Ryan, are:

- Given DA requirements is Portal fit for the task?
- Given DA requirements can Portal be adapted for the task?
- Are there components of Portal that are valuable to help solve DA requirements (e.g. neighborhood gossip)?

A secondary question I'll be looking into is:

- Can the portal network be used to permanently store blobs (even after they are deleted from L1)?

## Why is it Important?

- Data availability and retrieval layers will become more and more important as Ethereum progresses through the rollup-centric roadmap and moves data away from the main chain.
- Researching more efficient and decentralized ways to implement a DA layer is vital for the health of the ecosystem.
- This research could provide the ecosystem with a lightweight, highly decentralized solution for accessing blob data, potentially even after the blobs are deleted from the main chain. 
- This project would push forward the Portal Network's capabilities in delivering diverse kinds of data, opening up new use cases for it.

## How Does This Project Differ from Similar Ones?

Currently, the most important proposed solutions for DA are:

- **Data Availability Sampling (DAS)**: Where each network node downloads a small, redundant, and randomly selected subset of the total data.
- **Data Availability Committees (DACs)**: Involve trusted parties that store or attest to data availability. 
- **L1 temporary storage**: The solution proposed in EIP-4844. where all nodes in the network store blobs of data for a certain amount of time.

Getting the Portal Network to participate as a DA layer, would bring the following benefits:

- **Data retrieval.** The whole data would be stored in the portal network, not just samples of it like in DAS.
- **Fully decentralized storage.** No need for trusted parties as in DACs.
- **Permanent storage.** Portal could store blobs permanently, and keep serving its data after they are deleted from L1.

## Proposed Tasks and Roadmap

### Month 1
- **Main Objectives:**
  - Gain a comprehensive understanding of the DA requirements.
- **Tasks:**
  - Analyze the specifications surrounding EIP-4844, and other relevant DA EIPs.
  - Write explanatory notes and articles on these specifications.
  - Synthesize findings into a comprehensive article, defining the requirements the Portal network must meet.
- **Deliverables:**
  - An article explicitly defining the DA requirements for the Portal network.
  - A series of articles explaining the specifications of various DA EIPs.
  - Weekly updates.

### Month 2
- **Main Objectives:**
  - Develop an in-depth understanding of the state-of-the-art in DA layers.
- **Tasks:**
  - Research existing solutions proposed as DA layers.
  - Conduct a comparative analysis of these solutions.
- **Deliverables:**
  - An article detailing current DA layer solutions, comparing their differences, strengths, and weaknesses.
  - Weekly updates.

### Months 3 and 4
- **Main Objectives:**
  - Assess the Portal network’s viability for the DA requirements.
  - Compare the Portal network with other DA layer solutions.
- **Tasks:**
  - Deep dive into the Portal network specifications and the Trin client.
  - Identify components of the Portal network that could align with DA requirements.
  - Perform a comparative analysis of the portal network against other DA solutions.
- **Deliverables:**
  - A detailed article addressing the initial research questions.
  - A comparative analysis report of the Portal network against other DA solutions.
  - Weekly updates.

