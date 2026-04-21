The ZTCPP(Zero Trust Control and Policy Protocol) Working Group will define interoperable protocols and frameworks that support:
- Authenticated-before-connect access to protected resources
- Dynamic trust and context signaling - [Shruti] - we typically do not use trust where zero trust is concerned. We use assure or confidence levels
- Zero Trust control-plane communication
- Application of Zero Trust principles within network infrastructure
- Adaptation of 5G/6G operator network and AI agents conmmunicaiton scenarios

## Scope of Work:
The WG will produce specifications and guidance for Zero Trust protocol interoperability,
including authenticated-before-connect mechanisms, in-network policy enforcement considerations and control-plane requirements. 
The WG will reuse existing IETF protocols where possible and define new mechanisms only when gaps are identified.
- For 5G/6G network scenarios: Adapt to typical scenarios; develop interoperability specifications for Zero Trust protocols in operator networks; and address trust verification and policy scheduling issues brought by multi-domain security requrments in operator networks.
- For AI agent scenarios: Focused on AI agent communication security, defining authentication, authorization, and identity assurance mechanisms for AI agent-to-agent, AI agent-to-network, and AI agent-to-service communication. It will map security gaps in AI agent communication flows and develop Trust-based protocol interfaces and interaction rules to protect confidentiality, integrity, and auditability of AI agent communication.

[Shruti] - I am not sure we have a zero trust protocol. Just suggesting - probably it may be helpful to define the zero trust principles for which interopreability is to be developed.

## Out of Scope:
- Redefinition of Zero Trust principles or architectures
- Vendor-specific or proprietary mechanisms
- Endpoint security technologies unrelated to protocol interoperability
- 5G/6G network architecture design, Algorithm model design, training, and optimization of AI agents

## Deliverables:
- Zero Trust Problem Statements and Gap Analysis(Informational)
- Network-infrastructure aligned Zero Trust considerations, inculding 5G/6G network(Informational/BCP)
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
