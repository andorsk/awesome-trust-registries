# awesome-trust-registries [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of trust registry systems

## Protocols

- [Trust Registry Protocol v2](https://github.com/trustoverip/tswg-trust-registry-protocol) : API based protocol that asks: `Does Entity X have Authorization Y, in the context of Ecosystem Governance Framework Z?`
- [DNSsec](https://en.wikipedia.org/wiki/Domain_Name_System_Security_Extensions) : A suite of extension specifications by the Internet Engineering Task Force (IETF) for securing data exchanged in the Domain Name System (DNS) in Internet Protocol (IP) networks. Used sometimes for extending to Trust Registries.
- [OIDF](https://openid.net/specs/openid-federation-1_0.html) : A specification that describes how two Entities that would like to interact can establish trust between them by means of a trusted third party called a Trust Anchor.

## Models

- [x509 Certs](https://en.wikipedia.org/wiki/X.509): A standard defining the format of public key certificates used as a basis for HTTPS and TLS. 
- [Credential Trust Establishment](https://identity.foundation/credential-trust-establishment/): A document model that describes whether a user should trust the issuer of this credential?. 
- [EBSI Trust Chains](https://hub.ebsi.eu/get-started/design/trust-chain) : An interaction model which defines three roles: Root Trusted Accreditation Organisation (Root TAO), Trusted Accreditation Organisation(s) (TAOs), and Trusted Issuer(s) (TIs).
- [W3C Verified Issuer / Verifier Verifier List Data Model](https://w3c-ccg.github.io/verifiable-issuers-verifiers/) : This work focuses on how a party or its agent can decide whether or not to engage with a counterparty in a transaction. 

## Providers

- [EU Trust Lists](https://eidas.ec.europa.eu/efda/tl-browser/#/screen/home) : The Member States of the European Union and European Economic Area publish trusted lists of qualified trust service providers in accordance with the eIDAS Regulation.
- [Cheqd](https://docs.cheqd.io/identity/advanced/trust-infrastructure) : Leverages the EBSI Trust Chain Model over DID Linked Resources. 
- [TRAIN](https://train.trust-scheme.de/info/) : The approach allows for the flexible definition, consideration and publication of trust lists as well as the verification of trust framework compliance (e.g., eIDAS including LoAs or other trust framework/schemes that can also be application/industry-specific) with different Levels of Assurance (LoA), using DNS(SEC) as a root trust anchor. 
- [Northern Block](https://northernblock.io/tag/trust-registry/) : Higher assurance trust registry leveraging DNSSec.
- [Trinsic](https://docs.trinsic.id/reference/services/trust-registry-service/) : Trust Registry API using Trust Over IP's Trust Registry Protocol v1 spec. 
- [CIRA](https://dtlab-labcn.org/en/trust-registry-canadian-internet-registry-authority-cira/): Canadian Internet Registration Authority
- [Who.is[https://www.whois.com/whois/whois.net) : A Whois domain lookup allows you to trace the ownership and tenure of a domain name. 

## SDK's 

- [Dock SDK](https://docs.dock.io/open-source-community/blockchain-sdk/trust-registry/sdk)
- [Trinsic SDK](https://github.com/trinsic-id/sdk)
- [TBD SSI Service](https://github.com/TBD54566975/ssi-service)

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
