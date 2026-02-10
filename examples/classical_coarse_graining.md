## Classical Coarse-Graining as a Minimal Commutative/Non-Commutative Test

This example shows that non‑commutation is not inherently quantum; it arises whenever stabilization preserves distinctions that observation removes.

### Categories
- **C**: finite sets with deterministic maps  
- **O**: coarse‑grained partitions of sets

### Stabilization
Let \(S\) refine a configuration by adding stable labels:
\[
S(X)=X\times\{0,1\}
\]
with the projection forgetting the second coordinate as the counit.  
This is idempotent: applying \(S\) twice adds no new structure.

### Observation
Let \(\Pi\) collapse elements into equivalence classes:
\[
\Pi(X)=X/{\sim}.
\]
This is non‑faithful: distinct elements may be identified.

### Observable stabilization
Let \(S_O\) refine observable classes (e.g., splitting one class into two).

### Comparison
\[
\eta_X:\Pi(SX)\to S_O(\Pi X)
\]

### Non‑invertibility
If stabilization distinguishes two elements that \(\Pi\) identifies, then:
- \(\Pi(SX)\) contains distinctions  
- \(S_O(\Pi X)\) does not  

Thus \(\eta_X\) is not invertible.  
This shows that black‑hole‑type non‑commutation can occur even in purely classical systems.
