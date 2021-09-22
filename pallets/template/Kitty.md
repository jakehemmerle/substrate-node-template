# Kitty Pallet

Requirements:

- Kitty must have a 128 bit DNA, which is randomly generated
- Kitty must have one owner
- A user can have zero or more kitties

Pallet Design should have those sections:

- Types
- Config
- Storages
- Calls
- Events
- Implementations
- Additional comments or pseudo code

## Pallet

- Types
  - Kitty
    - dna: [u8; 32]
- Config
  - Randomness?
  - Event Interface?
- Storages
  - Kitty: KittyId => Kitty
  - KittyByOwner: address => KittyId
- Calls
  - fn create()
  - fn transfer(KittyId, newOwner)
- Events
  - KittyCreated
  - KittyTransfered
- Implementations
- Additional comments or pseudo code
