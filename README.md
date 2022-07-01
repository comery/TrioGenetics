# TrioGenetics


#### Motivation



#### how to estimate all spectrum of  heterozygosity between maternal and paternal haplotypes

##### sex chromosomes should be studied separately


##### what kinds of variants should be considered?



##### calculation method



#### best practises to detect different kinds of variants

Alignment

I recommend to use 'nucmer' to conduct alignment between maternal and paternal haplotypes, which is an appropriate tools to deal with highly similar sequences especially homo



##### SNV

```show-snps -rlTHC test.delta >test1.snp```

- show-snps -rlTHC test.1delta >test2.snp


##### Small indel



##### Large indel



##### rearrangement, inversion, translocation, inverted translocation


##### duplication, copy number variants



#### issues way to solve

- how to classify and define the variations clearly when they get overlapped?

- how to calculate the overall heterozygosity, how to deal with snp/indels within big SVs?
- how to define the CNV, unit length? how divergent between copies, local (tandem) or remote?
- the large indels which locate at the end of chromosome are caused by unplaced sequence?
- choose the best program and pratices