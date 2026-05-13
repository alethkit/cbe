# CBE: Categorical Backend Experiment

CBE is a QBE-derived compiler IR laboratory for categorical program
representation, semantic provenance, proof-obligation generation, and artifact
invalidation.

It is not trying to preserve QBE's original minimal-backend goals.

## Origin

CBE is derived from QBE, the Quick Backend compiler:

- https://c9x.me/compile/
- git://c9x.me/qbe.git

QBE is distributed under the MIT license. See `LICENSE`.

The original upstream README has been preserved as `README.qbe-upstream`.

## Initial goals

- Ingest QBE IL.
- Normalize phi-node SSA into block-argument SSA.
- Export an olog-shaped categorical database instance.
- Generate structural proof obligations.
- Track dependency provenance and invalidation after edits.

## Build

Run:

    make
