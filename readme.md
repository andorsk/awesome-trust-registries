# awesome-trust-registries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of trust registry systems and adjacent technology.

Disclaimer: Not all protocols and models are interoperable. 

## Protocols

- [DNSsec](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) : A suite of extension specifications by the Internet Engineering Task Force (IETF) for securing data exchanged in the Domain Name System (DNS) in Internet Protocol (IP) networks. Used sometimes for extending to Trust Registries.
- [Extensible Provisioning Protocol](https://icannwiki.org/Extensible_Provisioning_Protocol) : an XML based protocol used by the Internet industry, particularly the registrars and registries in managing domain names.
- [Open ID Federation \(OIDF\)](https://openid.net/specs/openid-federation-1_0.html) : A specification that describes how two Entities that would like to interact can establish trust between them by means of a trusted third party called a Trust Anchor.
- [Trust Registry Query Protocol v2](https://github.com/trustoverip/tswg-trust-registry-protocol) : API based protocol that asks: `Does Entity X have Authorization Y, in the context of Ecosystem Governance Framework Z?`
- [WHOIS](https://www.rfc-editor.org/rfc/rfc3912) :  WHOIS is a TCP-based transaction-oriented query/response protocol that is widely used to provide information services to Internet users.
- [Registry Lock](https://en.wikipedia.org/wiki/Registrar-Lock) : Status code set by registrar intended to combats domain hijacking.
- [RDAP](https://www.icann.org/rdap) : IETF based protocol that enables users to access current registration data and was created as an eventual replacement for the WHOIS protocol.
- [NANDA Registry](https://github.com/aidecentralized/nandapapers/blob/main/v0.3%20Beyond%20DNS%20-%20Unlocking%20the%20%20Internet%20of%20AI%20Agents%20via%20the%20NANDA%20Quilt%20of%20Registries%20and%20Verified%20AgentFacts.pdf) : Proposes a federated security architecture that combines NANDA’s minimal registry with the Agent Name Service (ANS) for dual-trust anchoring. This 
- [RPKI](https://en.wikipedia.org/wiki/Resource_Public_Key_Infrastructure) : proves the association between specific IP address blocks or ASNs and the holders of those Internet number resources. 
- [SAML](https://docs.oasis-open.org/security/saml/Post2.0/sstc-saml-tech-overview-2.0.html) : An Identity Provider (IdP) can issue SAML Assertions about users, including metadata, which can be used to communicate affiliations.

## Models

- [Credential Trust Establishment](https://identity.foundation/credential-trust-establishment/): A document model that describes whether a user should trust the issuer of this credential?. 
- [EBSI Trust Chains](https://hub.ebsi.eu/get-started/design/trust-chain) : An interaction model which defines three roles: Root Trusted Accreditation Organisation (Root TAO), Trusted Accreditation Organisation(s) (TAOs), and Trusted Issuer(s) (TIs).
- [x509 Certs](https://en.wikipedia.org/wiki/X.509): A standard defining the format of public key certificates used as a basis for HTTPS and TLS. 
- [W3C Verified Issuer / Verifier Verifier List Data Model](https://w3c-ccg.github.io/verifiable-issuers-verifiers/) : This work focuses on how a party or its agent can decide whether or not to engage with a counterparty in a transaction.
- [IEEE Std 1484.2-2024 LER Ecosystem Standard](https://sagroups.ieee.org/1484-2/) : "ecosystem-scale issuing, holding, and presenting verifiable credentials for education, skills-based hiring, and career advancement"
- [ISO mDL ISO/IEC 18013](https://www.iso.org/standard/69084.html) : The VICAL (Verified Issuer Certificate Authority List) is a list of trusted mobile drivers license issuers.

## Providers

- [AI Agent Store](https://aiagentstore.ai/reg) : AI Agent Registry
- [EU Trust Lists](https://eidas.ec.europa.eu/efda/tl-browser/#/screen/home) : The Member States of the European Union and European Economic Area publish trusted lists of qualified trust service providers in accordance with the eIDAS Regulation.
- [CIRA](https://dtlab-labcn.org/en/trust-registry-canadian-internet-registry-authority-cira/): Canadian Internet Registration Authority
- [cheqd](https://docs.cheqd.io/product/studio/trust-registries) : Leverages the EBSI Trust Chain Model over DID Linked Resources.
- [Microsoft Entra Agent ID](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/announcing-microsoft-entra-agent-id-secure-and-manage-your-ai-agents/3827392) : SaaS delivered enterprise grade directory for agents.
- [Northern Block](https://northernblock.io/tag/trust-registry/) : Higher assurance trust registry leveraging DNSSec.
- [Sphereon's OpenID Federation Server](https://hub.docker.com/r/sphereon/openid-federation-server/) : Docker container serving REST APIs for publishing OpenID Federation entity statements
- [Sphereon's OpenID Federation Admin Server](https://hub.docker.com/r/sphereon/openid-federation-admin-server/) : Docker container serving REST APIs for managing OpenID Federation entity statements
- [Trinsic](https://docs.trinsic.id/reference/services/trust-registry-service/) : Trust Registry API using Trust Over IP's Trust Registry Protocol v1 spec.
- [TRAIN](https://train.trust-scheme.de/info/) : The approach allows for the flexible definition, consideration and publication of trust lists as well as the verification of trust framework compliance (e.g., eIDAS including LoAs or other trust framework/schemes that can also be application/industry-specific) with different Levels of Assurance (LoA), using DNS(SEC) as a root trust anchor. 
- [Who.is](https://www.whois.com/whois/whois.net) : A Whois domain lookup allows you to trace the ownership and tenure of a domain name.
- [Yoti](https://www.yoti.com/) : SSI Network

### MCP Registries

- [Cursor MCP Registry](cursor.directory/mcp) : Integrated with the Cursor IDE, offering MCP server browsing within the development environment.
- [Official Registry](https://github.com/modelcontextprotocol/registry) : Maintained by the MCP project itself, this registry offers a centralized, community-driven repository of MCP server implementations, complete with metadata and RESTful API
- [Mastra](https://mastra.ai/mcp-registry-registry) : A meta‑registry listing other existing MCP registries—essentially a registry of registries 
- [MCP.so](mcp.so): A large community directory featuring over 3,000 MCP servers with quality filtering
- [PulseMCP](pulsemcp.com) : Tracks MCP servers and checks compatibility with clients—every server is manually approved 
- [Smithery AI](https://smithery.ai/) : A curated registry providing easy installation via CLI/Smithery API 

## SDKs 

- [Veramo SDK for cheqd](https://github.com/cheqd/did-provider-cheqd) : NPM package to enable developers to interact with the cheqd ledger using Veramo SDK, a modular and pluggable client app SDK for decentralised identity and SSI applications.
- [Dock SDK](https://docs.dock.io/open-source-community/blockchain-sdk/trust-registry/sdk) : Blockchain based trust registry.
- [Ory Hydra](https://www.ory.sh/docs/hydra/sdk/overview) : The Ory Hydra SDK allows for integration with a self-hosted Ory Hydra OAuth2 Server.
- [Sphereon](https://github.com/Sphereon-Opensource/OpenID-Federation) : OpenID Federation Monorepo
- [Trinsic SDK](https://github.com/trinsic-id/sdk) : Trust Registry v1 API SDK
- [TBD SSI Service](https://github.com/TBD54566975/ssi-service) : A golang service that allows you to build Trust Registries. 
- [Sunbird RC Cord](https://github.com/Sunbird-RC/sunbird-rc-core) : Sunbird RC is an open-source software framework for rapidly building electronic registries, enable atestation capabilities, and build verifiable credentialling with minimal effort.
- [XFSC Toolbox](https://www.gxfs.eu/set-of-services/) : German government sponsored project of open source-based software components were developed for the creation of federated digital ecosystems

## APIs

- [cheqd Studio](https://docs.cheqd.io/product/getting-started/studio) : API product for interacting with the cheqd network, including creating Trust Registries using the EBSI Trust Chain model.
- [Sphereon](https://app.swaggerhub.com/apis/SphereonInt/OpenIDFederationAPI/) : OpenID Federation API

## Ecosystems 

- [Estonian Internet Foundation](https://www.internet.ee/) : Estonia's trust infrastructure.
- [Trinsic Identity Acceptance Network](https://docs.trinsic.id/learn/concepts/ecosystems/) : SSI Ecosystem for Acceptance
- [Velocity](https://www.velocitynetwork.foundation/) : Velocity Network Foundation® is a non-profit membership organization, hosting the leading workforce-tech and ed-tech vendors and solution providers, on a mission to build the next-gen data utility layer underlying the global labor market
- [GAN Foundation](https://gan.foundation/) : The Global Acceptance Network (GAN) Organization is a neutral, nonprofit entity dedicated to establishing a public utility for digital trust. Just as the Internet’s Domain Name System required global, multi-stakeholder governance through ICANN, the GAN Organization serves as the governing body for this new layer of digital trust infrastructure.
- [GAIN/Global Assured Identity Network](https://openid.net/cg/gain-poc/) : " a user-centric and high-trust identity paradigm: the Global Assured Identity Network (GAIN). Instead of logging in directly, an EndUser asks a trusted and regulated provider (e.g., their bank, telecommunications provider, or another regulated entity) to verify that they are the person and/or have the credentials that they claim" [[source](https://gainforum.org/GAINWhitePaper.pdf)]
- [Gaia-X Ecosystems](https://gaia-x.eu/community/ecosystems/) : Integrated organizational data integration platform which leverages [GAIA-X Trust Framework](https://docs.gaia-x.eu/policy-rules-committee/trust-framework/22.10/). Non-profit
- [Privado](https://marketplace.privado.id/ecosystem) : Privacy focused ecosystem that lets you launch your own credentials with ZKP, on-chain verification, SSI, and Transitive trust. 

## Workshops

- [Registration Operations Workshop (ROW)](https://regiops.net/registration-operations-workshop-row) : Informal industry conference that offers a platform for discussing the technical intricacies of registration operations within the domain name system.
## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first. We thank anyone that decides to contribute to this repository and encourage contributions.

<a href="https://github.com/andorsk/awesome-tr/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=andorsk/awesome-tr" />
</a>
