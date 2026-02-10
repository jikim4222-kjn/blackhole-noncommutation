## Quantum Channels as a Toy Model of Non-Commutation

This example realizes the abstract framework inside finite‑dimensional quantum information.

### Categories
- **C**: finite‑dimensional quantum systems with CPTP maps  
- **O**: coarse‑grained observable descriptions (classical or operational)

### Stabilization
Fix a pointer basis $\{P_i\}$ and define the idempotent decoherence channel:

$$
S(\rho)=\sum_i P_i \rho P_i,\qquad S^2=S.
$$

### Observation
Let $\Pi$ be a partial trace over subsystem $B$:

$$
\Pi(\rho_{AB})=\mathrm{Tr}_B(\rho_{AB}).
$$

### Observable stabilization
Let $S_O$ be a coarse‑graining on subsystem $A$.

### Comparison map
The natural transformation

$$
\eta:\Pi\circ S \Rightarrow S_O\circ \Pi
$$

compares “decohere then trace” with “trace then coarse‑grain.”

### Non‑invertibility
If subsystem $B$ carries coherence that affects $S(\rho)$ but is erased by $\Pi$, then $\eta_X$ cannot be invertible.
