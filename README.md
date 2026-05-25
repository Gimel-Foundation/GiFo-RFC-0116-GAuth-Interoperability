# GiFo-RFC-0116 (version 2.2.1)

GAuth Interoperability

New Request for Comments of Gimel Foundation (GiFo RFC) - Establishung the GAuth Interoperability

Abstract of RFC: This specification defines the interoperability layer for the Gimel Authorization (GAuth)
protocol. It formalizes three components required for independent GAuth
implementations:

• Extended Token Format: A JWT-based credential carrying Power of Attorney
(PoA) attributes as defined in GiFo-RFC 0115, with a parallel W3C Verifiable
Credential representation for eIDAS 2.0 / EUDI wallet interoperability.

• PoA Credential Schema: A canonical JSON Schema for the three-layer
capability model (core verbs, permission-based capabilities, agent-based
capabilities), serving as the single source of truth for both JWT claims and W3C
VC credential subjects.

• OAuth Engine Integration: A standardized interface for integrating any OAuth 2.1
/ OIDC-compliant authorization server as the token issuance engine for GAuth.

This RFC is a Gimel Foundation contribution paper intended for open-source publication
under Apache License 2.0. It defines the protocol-level contracts that enable
independent implementations to interoperate.

Proprietary platform extensions, i.e. so-called Exclusions (as per Legal Terms of Gimel
Foundation) like AI-based governance, DNA-based identity and PQC associated, Web3
integration, are outside the scope of this specification and are not covered by the
Apache 2.0 license (see Section 2 of this Request of Comment)..

You are more than welcome to contribute !

Legal Provisions for users of this page

Please see the Legal Provisions under https://gimelfoundation.com

In particular the following terms apply:

GiFo RFC 0080 Legal Provisions for the Gimel Foundation

GiFo RFC 0090 Legal Provisions Related to Gimel Foundation Documents

GiFo RCC 0100 Rights Contributors Provide to the Gimel Foundation
