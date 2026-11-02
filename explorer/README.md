# BANDIT — Machine Explorer Branding

These files provide the branding data needed to enrich
BANDIT's existing Solana-native peaqOS machine listing.

## Operator
explorer/operator-profile.json

## Machine
explorer/machine-profile.json

## Artwork
assets/bandit-operator.png
assets/bandit-banner.png

## Integration notes

Machine Explorer currently uses static branding maps
keyed by operator address and machine DID.

The Explorer implementation may require copying these
values into its internal JavaScript/TypeScript registry
and hosting the artwork in its public assets directory.

These JSON files are a handoff specification, not a
directly executable Explorer plugin.

No new machine registration or on-chain write is required.
