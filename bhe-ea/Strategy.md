# Strategy

## Role of Strategy

"Layers of Change"

Things we pay for / directions the larger organization is going toward:

  * Consumption based accountablity
  * Lowest total cost of ownership
  * Outsource tedious work
  * Multi-cloud - Oracle + Azure
  * Container based platform
  * Web browser as user interface
  * Consolidate customer identity to a single outsourced provider (Azure B2C)
  * Consolidate user identity to a single outsourced provider (Azure)
  * Use rewrites as opportunities to update skills within teams
  * Have a strategy for developing talent within the group
  * API Driven design
  * Self-service as done


1. All teams will henceforth expose their data and functionality through service interfaces.
2. Teams must communicate with each other through these interfaces.
3. There will be no other form of interprocess communication allowed: no direct linking, no direct reads of another team’s data store, no shared-memory model, no back-doors whatsoever. The only communication allowed is via service interface calls over the network.
4. It doesn’t matter what technology they use. HTTP, Corba, Pubsub, custom protocols — doesn’t matter.
5. All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.
6. Anyone who doesn’t do this will be fired.
7. Thank you; have a nice day!