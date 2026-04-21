The ZTCPP(Zero Trust Control and Policy Protocol) Working Group will define interoperable protocols and frameworks that support:
- Authenticated-before-connect access to protected resources
- Dynamic trust and context signaling - [Shruti] - we typically do not use trust where zero trust is concerned. We use assure or confidence levels
- Zero Trust control-plane communication
- Application of Zero Trust principles within network infrastructure

## Scope of Work:
The WG will produce specifications and guidance for Zero Trust protocol interoperability,
including authenticated-before-connect mechanisms, in-network policy enforcement considerations and control-plane requirements. 
The WG will reuse existing IETF protocols where possible and define new mechanisms only when gaps are identified.
[Shruti] - I am not sure we have a zero trust protocol. Just suggesting - probably it may be helpful to define the zero trust principles for which interopreability is to be developed.

## Out of Scope:
- Redefinition of Zero Trust principles or architectures
- Vendor-specific or proprietary mechanisms
- Endpoint security technologies unrelated to protocol interoperability

## Deliverables:
- Zero Trust Problem Statements and Gap Analysis(Informational)
- Network-infrastructure aligned Zero Trust considerations (Informational/BCP) - [Shruti] - you may also want to consider application alignment as well. for example any compromise at a supply chain level (ex. NPM) or at CI/CD pipeline or a SQL injection would result in compromises... perhaps we should look at these aspects as well 
- Zero Trust protocol interoperability framework (Informational)
- Authenticated-before-connect mechanisms (Standards Track)
- Control-plane protocol requirements (Informational)

## Milestones:
- Adopt Problem Statements and Gap Analysis/Network-infrastructure aligned Zero Trust considerations drafts.(6 months)
- Adopt framework and requirements drafts(12 months)
- Adopt authenticated-before-connect draft(18 months)
- Publish above WG documents as RFCs(24 months)
- Publish deployment and interoperability guidance(24 months)
- Re-Charter or Close the WG

## Coordination:
The WG will coordinate with SAAG, ACE, RATS, OAuth, and other relevant WGs.
