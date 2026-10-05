# contract-protocol

Lean 4 proofs of the fabric's networking service levels: saturation, waypoint bounds and the abyssal SLA.

## What it is for

The proofs state what the fabric's network can promise, and an implementation that disagrees with a proof here is the one to change. It requires the shared primitive types, the authorization core and the spatial oracle as Lake packages. The production library is the build gate; a research library beside it holds proofs that are not gated.

## Build

```sh
lake build
lake build Research
```

## Licence

MIT; see LICENSE.
