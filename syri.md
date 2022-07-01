## the length of structural varitations

#### large indels
```text
pat_chr1_1_121900482	85259	85259	A	ACACA	mat_chr1_1_121786238	85917	85921	INS350	SYN1	INS	-
```
the position is 1-based, so the length of this variant (INS) is calculated by:

```abs(query_end - query_start) + 1```