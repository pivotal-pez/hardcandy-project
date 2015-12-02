# PEZ Hardcandy

## Goals
### Primary
  - Dispense hardware through PEZ similar to how Heritage orgs are dispensed

### Secondary
  - Determine how much refactoring of existing Innkeeper (metal dispensing service) is appropriate

## Anti-Goals
  - List the anti-goals, the don'ts, the things that shouldn't happen

## Proposed MVP's
### Hard Candy MVP-1: Vend Single Host Lab

Command line utility to perform the following epics:

  - Vend me metal
  - Show me my metal
  - Return my metal

__Note:__ Initially call Innkeeper (metal provisioning service) with it's current
interface. Then refactor and add a REST API around Innkeeper.

### Hard Candy MVP-#: Basic HaaS Management
  - Check showback billback (consumptions stats by cost center)
  - Show me metal availability
  - Define inventory
  - Manage inventory
  - Check consumed resources
  - Expand my metal
  - Extend lease custom
  - Expire notify metal

### Hard Candy MVP-#: Vend Multi-Host Lab

## Risks & Issues
### Near Term

### Long Term

## Iteration Cadence
  - One week iterations
  - Demo, retrospective and planning on Tuesday afternoons at the old PEZ time

## Decisions
  - Okay to use a command line interface initially
  - Leverage existing Innkeeper functionality as much as possible to create and end-to-end system. Then determine what is needed to refactor Innkeeper code and consolidate PEZ and Innkeeper projects
  - Consider adding functionality to PEZ Portal to create a rudimentry HaaS dispensing UI
  - After adding single host lab, revisit priorities and consider implementing, `Vend Multi-Host Lab` MVP before the `Basic HaaS Management` MVP

## Personnas
  - Metal User - User who wants some metal
  - PEZ  - The Pivotal elastic zone system
  - Innkeeper - The hardware provisioning system
  - Management User - Management user who is concerned about usage, cost, etc.


## Retrospective
### Worked Well
  - Topic/title  
  __(benefit)__ why this is a good practice

### Needs Improvement
  - Topic/title  
  __(scenario)__ describe the observed situation  
  __(improve)__ describe some ideas to improve it

## Questions/Follow Ups
  - Open items that need follow up
