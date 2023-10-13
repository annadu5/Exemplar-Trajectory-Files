# DCD Trajectory Files

- [0401GE0606](https://annadu.s3.amazonaws.com/charmm/dcd/aua_cg_a_6x6x6_ge__charmm_openmm__all-dcd-95.dcd)
- [0201CNT1512](https://annadu.s3.amazonaws.com/charmm/dcd/CNT_15WB_6M__charmm_openmm__all-dcd-100.dcd)
- [0423GE0806](https://annadu.s3.amazonaws.com/charmm/dcd/detach_test_8x8x8_3_TEMP335K__charmm_openmm__all-dcd-37_1-335k_11-350k_14-360k.dcd)
- [0129GE1006](https://annadu.s3.amazonaws.com/charmm/pdb/GE10_8WB_TM_3OM__charmm_openmm__step_50_single_frame_128.pdb)
- [0131GI1006](https://annadu.s3.amazonaws.com/charmm/pdb/GI10_8WB_TM_3OM__charmm_openmm__128_graphite_helical_step48.pdb)
- [0114GE2012](https://annadu.s3.amazonaws.com/charmm/dcd/graphene_20x20x20_6mers__charmm_openmm__all-dcd-6.dcd)

# File Description
| File | Temperature | Templatizing Material | Templatizing Material Size (Angstrom) | Oligomer Sequence	| Key Endpoint	| Start Frame	| End Frame
| ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| 0401GE0606 | 303 | Graphene | 6x6x6 | AUA CG A | Oligomer bridging via carbon sheet structures, with RNA dimers and trimers forming bonds on both sides of the graphene templatizing material. This simulation also demonstrated  elongation, where multiple oligonucleotides formed a Van der Waals bond along the sugar phosphate backbone, showing the possibility for the formation of long chain oligonucleotides. | 240 | 496
| 0201CNT1512 | 303 | Carbon Nanotube | 15x15x15 | AUA CG A AUA CG A | Oligomer attachment and translation on the surface carbon nanotube. The oligonucleotides form in a parallel manner to the surface of the CNT, thus showing that, like montmorillonite, CNT on its own, with a large, flat surface, is not an ideal templatizing material to facilitate polymer growth. | 100 | 1000
| 0423GE0806 | 350 | Graphene | 8x8x8 | AUA CG A | A dimer dissociated from a complex involving a 5-mer oligonucleotide. This detachment event occurred due to an increase of temperature in the CHARMM simulations, emulating temperature cycles in the natural environment. This demonstrates that a hyper-saturated solution of oligonucleotides could have formed in an environment such as a warm little pond. | 100 | 130
| 0129GE1006 | 303 | Graphene | 10x10x10 | AUA CG A | Two oligonucleotides bonding to a graphene sheet. The dimers are in close proximity and could potentially lead to double-strandedness in future frames. | 20 | 58
| 0131GI1006 | 303 | Graphite | 10x10x10 | AUA CG A | One oligonucleotide bonding to the surface the other bonding to the side then translating to the surface of the graphite sheet. | 240 | 510
| 0114GE2012 | 373 | Graphene | 20x20x20 | AUA CG A AUA CG A | Translating across surface of the graphene templatizing sheet. | 28 | 60
