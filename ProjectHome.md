Data access is often the bottleneck as the fast processors of today often consume data more quickly than memory system can supply. LIDO improves performance by optimizing the data access. It aim to support following transformations for C code:
1. structure layout transformation including structure peeling, structure splitting, field reordering.
2. array layout transformation including array transposition, array flattening.
3. overlaying arrays to reduce cache footprint.
4. replacing constant array of regular value patterns with simple loops.
LIDO is based on CIL, http://manju.cs.berkeley.edu/cil/.
LIDO is written in O'Caml.