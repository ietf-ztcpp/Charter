The ZTCPP (Zero Trust Control and Policy Protocol) Working Group will define interoperable protocols and frameworks that support:
- Authenticated-before-connect access to protected resources
- Dynamic assurance (confidence levels) and context signaling
- Zero Trust control-plane communication and policy lifecycle management
- Mechanisms to bind policy decisions to concrete sessions, flows, or channels with verifiable enforcement outcomes  
- Application of Zero Trust principles within network infrastructure
- Adaptation to 5G/6G operator network scenarios and AI/agent-based communication systems
  
## Problem Statement:
Existing Zero Trust architectures define policy and access control models, but do not fully standardize interoperable, cryptographically sound mechanisms for enforcing authorization prior to connection establishment while minimizing exposure of protected resources. Current secure connectivity approaches often require coordination across infrastructure components (e.g., routing, NAT, firewalls), governance processes, and distributed enforcement systems. This operational complexity arises in part from the absence of interoperable mechanisms to express identity- and service-based policy intent and bind that intent directly to communication sessions, resulting in inconsistent enforcement and reduced agility across deployments.

This gap becomes increasingly important in environments where automated discovery and exploitation techniques (including those driven by AI) rapidly target exposed network infrastructure. Interoperable policy distribution alone is not sufficient; consistent Zero Trust outcomes require that policy intent be enforced with fidelity at runtime, including service-level least-privilege semantics.

## Scope of Work:
The WG will produce specifications and guidance for Zero Trust protocol interoperability,
including authenticated-before-connect mechanisms, in-network policy enforcement considerations and control-plane requirements. 
The WG will identify the Zero Trust principles for which interoperability is to be developed and define new mechanisms only when gaps are identified.
- For authenticated-before-connect: Specify protocol mechanisms that combine cryptographic authentication and pre-connection authorization; convey authorization decisions prior to connection establishment; minimize pre-authentication exposure of service identifiers, network endpoints, and related metadata. This includes consideration of how these mechanisms interact with broader Zero Trust control requirements, including:
  – exposure to protected resources is controlled prior to authorization,
  – policy decisions are distributed and updated across enforcement points, and
  – policy intent is bound to runtime sessions and flows with verifiable enforcement outcomes.
- The work assumes identity as a foundational concept, including both human and non-human identities (e.g., workloads, services, devices, and agents), and aims to interoperate with existing identity systems (e.g., OIDC, PKI, and workload identity) rather than define new identity mechanisms.
- For 5G/6G network scenarios: Adapt to typical scenarios; develop interoperability specifications for protocol based on Zero Trust principles in operator networks; and address trust verification and policy scheduling issues brought by multi-domain security requirements in operator networks.
- For AI agent scenarios: Based on Zero Trust principles, research security requirements for AI agents scenarios.

These concerns—controlling exposure, distributing policy, and binding policy intent to runtime sessions and flows—are distinct but interdependent and collectively required to achieve consistent Zero Trust outcomes across implementations.

## Out of Scope:
- Redefinition of Zero Trust principles or architectures
- Vendor-specific or proprietary mechanisms
- Endpoint security technologies themselves are out of scope; however, posture, attestation, and context signals and their protocol interactions (e.g., signaling, freshness, and enforcement consequences) are considered in scope for interoperability.
- 5G/6G network architecture design, Algorithm model design, training, and optimization of AI agents

## Deliverables:
- Zero Trust Problem Statements and Gap Analysis (Informational)
- Network-infrastructure aligned Zero Trust considerations, including 5G/6G network (Informational/BCP)
- Application aligned Zero Trust considerations (Informational/BCP)
- Zero Trust protocol interoperability framework (Informational)
- Authenticated-before-connect mechanisms (Standards Track)
- Control and policy plane protocol (Standards Track)

## Milestones:
- Adopt Problem Statements and Gap Analysis/Network-infrastructure aligned Zero Trust considerations drafts (6 months)
- Adopt framework and requirements drafts (12 months)
- Adopt authenticated-before-connect protocol draft (18 months)
- Adopt control and policy plane protocol draft (18 months)
- Publish above WG documents as RFCs (24 months)
- Publish deployment and interoperability guidance (24 months)
- Re-Charter or Close the WG

## Coordination:
The WG will coordinate with SAAG, ACE, RATS, OAuth, and other relevant WGs.
