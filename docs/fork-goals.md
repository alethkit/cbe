# CBE fork goals

CBE is a QBE-derived compiler IR laboratory.

It is not governed by QBE's original minimal-backend objective. The goal is to
use a small real compiler backend as a substrate for:

- categorical program representation;
- block-argument SSA normalization;
- olog-shaped schema export;
- proof-obligation generation;
- semantic provenance;
- artifact invalidation after edits.

Initial technical targets:

1. Preserve the ability to build the inherited QBE backend.
2. Add machine-readable IR export.
3. Normalize QBE phi-node SSA into block-argument SSA.
4. Export an olog/categorical-database-shaped artifact graph.
5. Generate structural proof obligations.
6. Track stale facts, obligations, and certificates after program edits.
