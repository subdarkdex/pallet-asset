# pallet-assets

This is a forked repo from paritytech/substrate - Rococo Branch. It is a temporary pallet to demostrate the usage of the `pallet-generic-token-dealer` as part of the Open Grant for Subdex. 

This is likely going to be make redundant after upgrading `generic-parachain` to Cumulus Parachain V1 in following grant work. 

### Changes
- Dependencies pointing to Rococo Branch to align with the parachain template
- `make_transfer` function implemented for the module to be used in `generic-token-dealer`
