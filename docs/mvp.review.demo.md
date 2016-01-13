# Review/Demo Vend ms1.small MVP

## PEZ Haas MVP 1 Capability Summary
Self-service (no human intervention from PEZ team required) to vend enough hardware to
spin up vSphere or PCF.

## Goal Review
### Done
  - (done) a starting point for all things pez
  - (done) automated provisioning of servers, storage, etc
  - (done) provision from bare metal
  - (done) easily supported provisioning
    - self service provisioning of metal
  - (done) self service (no human interaction)
  - (done) cli/non-gui method of interacting with pez
  - (done) easy point and click UX
  - (done) Multi-DC support at inventory level
    - available through the implementation of service broker
  - (done) Dog Food
    - Only Innkeeper is outside of Cloud Foundry
  - (done) Vend PXI booted servers

### Partial
  - (partial) network config automation
    - can assign a preconfigured network dynamically
  - (partial) leasing or calendaring (inventory management)
    - can create and destroy manually, no lease mechanism based on time
  - (partial) ability to yield back resources on schedule or on-demand
    - can yield back resources on-demand, no on schedule capability
  - (partial) deliver by EOY 2015
    - Need firewall port opened

### ToDo
  - archive leased compute
  - exec dash (w/ utilization mapped to cost center)
  - showback / billback
  - Inventory Availability View (who has what? what can i grab?)
  - quotas for users
  - status health page (working or not? custom messaging to users)
  - easy on boarding of compute resources into HaaS Pool
  - Vend VShpere
  - Vend PCF
  - lessen AWS spend
    - not live yet, once we turn it on this will be realized
  - (what does this mean?) heterogenous infrastructure
  - garbage collection / tenant management

## Open Issues Keeping from being at the fingertips of every Pivot
 - Open firewall rules to allow Heritage to connect to Core

## Demo
  - Show vending hardware from service broker
  - Return the hardware

## Release/Transition Activities
  - Everything already deployed to production
  - Open firewall
  - Decide who it's activated for (only activated to PEZ organization)
  - Open to other orgs as determined  
  - PEZ handoff on garbage collection procedure (Josh)  
  - General knowledge xfer on how to activate and de-activate for an Organization (pez dev)
