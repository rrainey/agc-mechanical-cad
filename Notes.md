Over time the AGC Block II DSKY had multiple versions. There's also different variants installed in the CSM and LEM.

For now, I am focusing on modeling the versions used in the Apollo 17 CSM DSKY (see https://www.ibiblio.org/apollo/2014999-181.html)

I'm collecting notes and questions regarding each drawing set that I used to create this model.

### 1006387D - INDICATOR, ALARM

The inner constructon of this assembly is not fully documented in the AGC drawings. I'm generating an "exact" version based on the drawing, and a "reconstructed" version that would be based on building a simulated version from
modern parts.

Portions of the connector at the back of the part remain to be modeled.

On the back, there's a channel marked "0.615 MIN" (B3) - a more reasonable value of 0.515 MIN has been used in the model.

### 2004699A - COVER

There are apparently two variants of this part, but the drawing does not call out these variants. The drawing depicts a part with a "short window" -- intended for the Status and Warning light assembly, however a 2004699-001 version is also called out for the E/L & Cover Assembly (2003988B). 
The Status cover assembly(2003897C) calls for either part 2004699-000 or 2004699-001, depending on the variant of the assembly. Based on the two assembly drawing referencing 2004699, one can guess that
the -000 variant has the "short window" and -001 is the "tall window". It's not difficult to reconstruct the part geometry for the tall window, but I'm wondering why it is missing in the source part drawing.

### 2004746-001 INDICATOR, DIGITAL (THERMAL-VAC)  (a.k.a. 1006315G)

This is the E/L display indicator for the DSKY. The drawing indicated 2004647 is just a relabeled Block I part, 1006315-001. 1006315G includes dimensions of the E/L display elements and the outline of the assembly, but lacks
details on the internals. The Gorton fonts used in this model originates from Eugene

### 2004932 JACKING SCREW

Both variants are modeled. The modeling of the threading at the tip of the screw isn't quite accurate.
