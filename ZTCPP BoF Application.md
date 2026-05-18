# Name: Zero Trust Control and Policy Protocols (ZTCPP)
## Description 
Existing Zero Trust architectures define policy and access control models, but do not fully standardize interoperable, cryptographically sound mechanisms for enforcing authorization prior to connection establishment while minimizing exposure of protected resources. Current secure connectivity approaches often require coordination across infrastructure components (e.g., routing, NAT, firewalls), governance processes, and distributed enforcement systems. This operational complexity arises in part from the absence of interoperable mechanisms to express identity- and service-based policy intent and bind that intent directly to communication sessions, resulting in inconsistent enforcement and reduced agility across deployments.<br>

This gap becomes increasingly important in environments where automated discovery and exploitation techniques (including those driven by AI) rapidly target exposed network infrastructure. Interoperable policy distribution alone is not sufficient; consistent Zero Trust outcomes require that policy intent be enforced with fidelity at runtime, including service-level least-privilege semantics.<br>

ZTCPP will focus on the following interoperable framework and protocols that support: <br>
- Authenticated-before-connect access to protected resources <br>
- Dynamic assurance (confidence levels) and context signaling <br>
- Zero Trust control-plane communication and policy lifecycle management <br>
- Mechanisms to bind policy decisions to concrete sessions, flows, or channels with verifiable enforcement outcomes <br>

The work assumes both human and non-human identities (e.g., users, workloads, services, devices, and agents) and aims to interoperate with existing identity systems so that the resulting mechanisms can be applied consistently across heterogeneous environments and deployment models.<br>

## Required Details
- Status: "WG forming"
- Responsible AD: Deb Cooley, Christopher Inacio 
- BOF proponents: Aijun Wang <wangaj3@chinatelecom.cn>, Philip Griffiths <philipleonardgriffiths@gmail.com>,Benfeng Chen <benfeng@gmail.com>,Erik Johnson <ejohnson@cloudsecurityalliance.org>, Xuansi <six1@chinatelecom.cn> 
- Number of people expected to attend: 100
- Length of session (1 or usually 2 hours): 2 hours
- Conflicts (whole Areas and/or WGs)
   - Chair Conflicts: TBD
   - Technology Overlap: TBD
   - Key Participant Conflict: SEC AD

## Information for IAB/IESG
To allow evaluation of your proposal, please include the following items:

- Any protocols or practices that already exist in this space: <br>
  NIST SP 800-207 defines the Zero Trust Architecture and principles, but it does not define interoperable control and policy protocol semantics for how those principles are realized across heterogeneous implementations. Several implementations already exist, yet the industry still needs standardized specifications to avoid vendor lock-in and to ensure interoperable exposure control, policy distribution, and runtime enforcement across components from different vendors. <br>

- Which (if any) modifications to existing protocols or practices are required: TBD
   
- Which (if any) entirely new protocols or practices are required: <br>
   Interoperable control and policy protocols, including mechanisms for authenticated-before-connect access, policy lifecycle coordination across enforcement points, and binding policy intent to concrete sessions, flows, or channels with verifiable enforcement outcomes, as described by Zero Trust architectures such as NIST SP 800-207.

- Open source projects (if any) implementing this work: <br>
   OpenNHP: https://github.com/openNHP/opennhp/ (focus on authenticated-before-connect and resource hiding) <br>
   OpenZiti: https://github.com/openziti (identity-first connectivity fabric enabling authenticated-before-connect access, service-based policy, and end-to-end binding of identity and policy to application sessions across heterogeneous environments) <br>

These projects exercise different aspects of Zero Trust architecture and help illustrate interoperability gaps across exposure control, policy distribution, and runtime enforcement.
   

## Agenda
   - Use cases, scenarios and requirements(20 minutes)
     <ol type="1">
     <li> Zero trust standards in IETF: Use cases and problem statement (https://datatracker.ietf.org/doc/draft-liu-ztcpp-zt-problem-statement/) </li>  
     <li> Consideration of Applying Zero Trust Philosophy in Network Infrastructure (https://datatracker.ietf.org/doc/html/draft-li-ztcpp-network-infra-consideration) </li> <br>
     </ol>

   - Protocol Gap Analysis for Zero Trust Control and Policy Interoperability(20 minutes)
     <ol type="1">
     Draft: TBD <br>
     </ol>

   - A Framework for Zero Trust Control and Policy Interoperability (15 minutes)
     <ol type="1">
     Draft: TBD <br>
     Purpose: Describe how interoperable mechanisms can address authenticated-before-connect access, policy lifecycle coordination, and binding policy intent to concrete sessions and flows with verifiable enforcement outcomes.
     </ol>
      
   - Discussion of candidate protocol approaches and implementation models (15 min)
     <ol type="1">
     Example drafts / open source projects may be referenced here as illustrations, not as the assumed solution direction
     </ol>
      
   - ZTCPP Charter (20 minutes)
     <ol type="1">
     ZTCPP Charter https://github.com/ietf-ztcpp/Charter/blob/main/Charter.md <br>
     </ol>
      
   - Open Discussion(30 minutes)


## Links to the mailing list, draft charter if any (for WG-forming BoF), relevant Internet-Drafts, etc.
   - Mailing List: ztcpp@ietf.org (subscribe the list at: https://mailman3.ietf.org/mailman3/lists/ztcpp.ietf.org/
   - Draft charter:  https://github.com/ietf-ztcpp/Charter/blob/main/Charter.md

   - Relevant Internet-Drafts:
      - Use Cases:
        <ol type="1">
        <li> Zero trust standards in IETF: Use cases and problem statement (https://datatracker.ietf.org/doc/draft-liu-ztcpp-zt-problem-statement/) </li>  
        <li> Consideration of Applying Zero Trust Philosophy in Network Infrastructure (https://datatracker.ietf.org/doc/html/draft-li-ztcpp-network-infra-consideration) </li> <br>
        </ol>
       
      - Candidate approaches
        <ol type="1">
        <li> Protocol Gap Analysis for Zero Trust Control and Policy Interoperability(Draft: TBD)</li>
        <li> A Framework for Zero Trust Control and Policy Interoperability (Draft: TBD) </li>
        <li> Network-Infrastructure Hiding Protocol(https://datatracker.ietf.org/doc/draft-opennhp-ztcpp-nhp/)</li> 
        
        </ol>
