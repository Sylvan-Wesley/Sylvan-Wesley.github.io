# This is just basically an excerpt from Dr Muhan Zhang's work GEORCG

Recent advances in molecular generative models
have demonstrated great promise for accelerating
scientific discovery, particularly in drug design.
However, these models often struggle to gener-
ate high-quality molecules, especially in condi-
tional scenarios where specific molecular proper-
ties must be satisfied. In this work, we introduce
GeoRCG, a general framework to improve molec-
ular generative models by integrating geometric
representation conditions with provable theoret-
ical guarantees. We decompose the generation
process into two stages: first, generating an infor-
mative generating a molecule conditioned on the representa-
tion. Compared with single-stage generation, the
easy-to-generate representation in the first stage
guides the specificquality molecule in a goal-oriented way. Lever-
aging EDM and SemlaFlow as base generators,
we observe significant quality improvements in
unconditional molecule guused QM9 and GEOM-DRUG datasets. More
notably, in the challenging conditional molecular
generation task, our framework achieves an av-
erage 50% performance improvement over stageof-the-art approaches, highlighting the superiority
of conditioning on semantically rich geometric
representations. Furthermore, with such repre-
sentation guidance, the number of diffusion steps
can be reduced to as small as 100 while largely
preserving the generation quality achieved with
1,000 steps, thereby significantly reducing the gen-
eration iterations needed. Code is available at
https://github.com/GraphPKU/GeoRCG.
