## Category-Theoretic Background (Minimal)

### Idempotent endofunctors
A functor \(S : C \to C\) is idempotent if \(S^2 \cong S\).  
Such functors represent stabilization: applying them twice yields no further change.

### Non-faithful functors
A functor \(\Pi : C \to O\) is non‑faithful if distinct morphisms in \(C\) may be identified in \(O\).  
This models information loss under observation.

### Natural transformations
A natural transformation  
\[
\eta : \Pi \circ S \Rightarrow S_O \circ \Pi
\]  
compares “stabilize then observe” with “observe then coarse‑grain.”

Invertibility of \(\eta_X\) expresses commutation.  
Non‑invertibility expresses mismatch.

### Full subcategories
A full subcategory \(R \subseteq C\) contains all morphisms between its objects.  
Persistence of non‑commutation under restriction ensures that the mismatch is structural, not accidental.

This minimal categorical machinery suffices to express horizons, evaporation, Page behavior, and islands.
