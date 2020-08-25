
## Saturn-V TIP Proposal

### Name
* `Saturn-V`
* Repo Name: `saturn-v-tip`

This is the first TIP proposal under the TSWG and it represents the next evolutionary step towards the *moon shot* known as decentralized identity. Acknowledging the [recently successful NASA/Space-X mission](https://www.cnet.com/news/spacex-splashdown-replay-see-nasa-astronauts-safely-return-to-earth-from-iss/) that has revitalized attention to space exploration, history reveals that our early success in space was significantly aided by the **Saturn V** multi-stage rocket platform. The *Saturn V* three-stage rocket served as a *Heavy Lift Vehicle* for space exploration. It was the most powerful rocket that had ever flown successfully. The  *Saturn V* was used in the Apollo program in the 1960s and 1970s. It also was used to launch the Skylab space station.  Containing three (3) powerful fuel-stages, this massive rocket was used to propel man to the moon. Since we are in the early stages of the technology adoption lifecycle for decentralized identity and we seek a technical recipe to bootstrap an interoperable digital trust marketplace. Analogous to the first three layers of the ToIP Stack, this initial TIP represents an exemplar of a technical collaboration to help propel decentralized identity into mainstream adoption. In fact the *Saturn V* project required that three separate companies, each responsible for a separate fuel-stage, collaborated to integrate their fuel-engines into [a single interoperable rocket platform](https://www.space.com/18422-apollo-saturn-v-moon-rocket-nasa-infographic.html) that would propel Appolo and Skylab missions. Today, we seek to integrate technology for three ToIP Layers to achieve a common goal -- help propel the adoption of digital credentials.

### Purpose
Today, the decentralized identity community continues the *moon shot* started by the *Sovrin Foundation* towards self-sovereign identity. This proposal is unique as it represents a vertical interoperable stack that is already familiar to most industry participants. This proposal is effectively receiving the baton that began with the Sovrin Network and will focus on evolving that effort into a network of networks model.  

### Convener(s)

* Stephen Curran (*nominated*)
* Richard Esplin (*nominated*)
* Dan Gisolfi

### Stakeholders
The following vendors are [activity working on interoperability](https://docs.google.com/presentation/d/1WkqSpFERc8now-f-Pz7PsRg9NMywSiZb92rTqJx5y00/edit#slide=id.g8d58b271ca_2_17) in support of this TIP:

* esatus
* Evernym
* IBM
* Main-Incubator (R&D Unit of Commerzbank Group)
* Telus/ATB-Financial
* Trinsic

### Key Motivators
<font color='cyan'>List the reasons that triggered the proposal.</font>

1. We need to describe an example TIP that is of interest to many in the ToIP Foundation.
2. As portions of the Sovrin Community, focused on governance and standardization, transitions under the broader umbrella of the ToIP Foundation, we need a description of the architecture in which the community desires to embrace.   
3. We need a methodology that will allow alternative TIPs to be compared to the one most familiar with many in the ToIP Foundation.
4. We need a forum for the
[Indy Interop-athon](https://wiki.hyperledger.org/pages/viewpage.action?pageId=36734079) events that are focused on making the network of networks concepts reality of public identity utilities based on Hyperledger Indy.
5. We need to separate the layers and taking the Sovrin Governance Framework, which is a blend of a 4-Layer framework, and examining the technical underpinnings required allows the ToIP TWG to flesh out the details that are needed for separation.

### Core Principles
The stakeholders believe that the proposed technical stack is purpose built to provide the foundational infrastructure necessary to support various implementations of the stack, particularly those that support personal digital identity as identified by Christopher Allen [~~10 Core Principles~~](https://docs.google.com/document/d/1WqUOqdTBc3JACIlRviJoWJRcJHTNTNzk9_As9v-jwrY/edit#heading=h.ws45zwyr4hfb) [10 Core Principles](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html). These same principles guided the initial efforts behind the Sovrin Governance Framework, created by by the [Sovrin Foundation](http://sovrin.org). As the decentralized identity community evolves into a network of networks model, these principles will help shape the applicability of solutions.

This TIP is aimed to provide both personal (people) and non-personal (organizations and things) digital identity. As such the following Core Principles are intended to support the 

# Driving Forces

While the Saturn V TIP is aimed at Layers 1, 2, and 3 of the ToIP Stack, there are various drivers that have been considered. Each of these is aimed at a human-centric view of digital identity so the technical stack provided by this TIP must support these. 

Kim Cameron's 7 Laws of Identity
![7 laws by ...](https://www.identityblog.com/wp-content/images/2009/06/7_Laws_of_Identity.jpg)

Sovrin 12 Core Principles:

1. Self-Sovereignty
2. Guardianship
3. Openness & Interoperability
4. Accountability
5. Sustainability
6. Transparency
7. Collective Best Interest
8. Decentralization by Design
9. Inclusive by Design
10. Privacy by Design
11. Security by Design
12. Data Protection by Design and Default

The following are Christopher Allen's SSI principles
[source](http://www.lifewithalacrity.com/2016/04/the-path-to-self-soverereign-identity.html)


| Principle | Description |
| --- | --- |
| Existence | Users must have an independent existence. |
| Control | Users must control their identities. |
| Access | Users must have access to their own data. |
| Transparency | Systems and algorithms must be transparent. |
| Persistence | Identities must be long-lived. |
| Portability | Information and services about identity must be transportable. |
| Interoperability | Identities should be as widely usable as possible. |
| Consent | Users must agree to the use of their identity. |
| Minimization | Disclosure of claims must be minimized. |
| Protection | The rights of users must be protected. |

### Technical Stack Proposal
<font color='cyan'>Identify the technologies associated with each layer of the ToIP Stack that will help to define this TIP.</font>

| ToIP Technical Stack Layer | TIP Technology |
| --- | --- |
| Three | Hyperledger Aries |
| Two | Hyperledger Aries |
| One | Hyperledger Indy |

### Use cases to be validated
In addition to the common business patterns associated with decentralized identity, namely `password-less auth` and `digital onboarding`, this TIP proposal will [build on existing proof-points](https://sovrin.org/category/use-cases/) to establish a generalized list of uses-cases that will help to demonstrate cross-industry adoption.
