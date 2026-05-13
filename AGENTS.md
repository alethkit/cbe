# CBE Agent Instructions

- CBE is derived from QBE.
- The project goal is categorical/proof-artifact infrastructure, not QBE's original minimal-backend goal.
- Preserve inherited QBE behavior unless a task explicitly says otherwise.
- Keep `master` as upstream/QBE baseline.
- Do CBE work on `cbe`; in Codex Cloud, the checked-out task branch may be called `work`, and that is acceptable.
- Prefer small, reviewable commits.
- Every behavior-changing patch must include either a test or a clear manual validation command.
- Do not introduce external dependencies without justification.
- Keep C code style close to existing QBE style unless a new subsystem clearly needs a different style.
- New semantic/provenance code should be isolated under clearly named files rather than tangled into backend code.
