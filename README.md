# TightBindingCode
Some codes for efficiently building tight-binding model Hamiltonian.

============================================================

**20211111**
- Upload *SlaterKoster.wl*

  *SKpara\[A, B, vec\]* is a function to generate the Slater-Koster parameter describing the hopping integral from atomic orbital B to orbital A connected by vecter vec.

**20251010**
- In previous version, if typeA = { $d_{yz}$, $d_{zx}$, $d_{xy}$ } and typeB = $d_{3z^2-r^2}$ or vice versa, the SK parameters are wrong. Now this bug now has been fixed.
- A sign typo in typeA = typeB = $d_{x^2-y^2}$ has been corrected.  
