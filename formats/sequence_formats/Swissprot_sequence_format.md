---
title: Swissprot sequence format
layout: default
---

Description
-----------

The following is an example of Swissprot "flat" format, the only swissprot format flavor that BioPerl is capable of parsing as of version 1.5.1.

Swissprot also releases an XML formatted database.

Example
-------

```
ID   MA32_HUMAN     STANDARD;      PRT;   282 AA.
AC   Q07021;
DT   01-FEB-1995 (Rel. 31, Created)
DT   01-FEB-1995 (Rel. 31, Last sequence update)
DT   01-OCT-2000 (Rel. 40, Last annotation update)
DE   COMPLEMENT COMPONENT 1, Q SUBCOMPONENT BINDING PROTEIN, MITOCHONDRIAL
DE   PRECURSOR (GLYCOPROTEIN GC1QBP) (GC1Q-R PROTEIN) (HYALURONAN-BINDING
DE   PROTEIN 1) (PRE-MRNA SPLICING FACTOR SF2, P32 SUBUNIT) (P33).
GN   GC1QBP OR HABP1 OR SF2P32 OR C1QBP.
OS   Homo sapiens (Human).
OC   Eukaryota; Metazoa; Chordata; Craniata; Vertebrata; Euteleostomi;
OC   Mammalia; Eutheria; Primates; Catarrhini; Hominidae; Homo.
OX   NCBI_TaxID=9606;
RN   [1]
RP   SEQUENCE FROM N.A., AND SEQUENCE OF 74; 76-93 AND 208-216.
RC   TISSUE=FIBROBLAST;
RX   MEDLINE=94085792; PubMed=8262387;
RA   Honore B., Madsen P., Rasmussen H.H., Vandekerckhove J., Celis J.E.,
RA   Leffers H.;
RT   "Cloning and expression of a cDNA covering the complete coding region
RT   of the P32 subunit of human pre-mRNA splicing factor SF2.";
RL   Gene 134:283-287(1993).
RN   [2]
RP   SEQUENCE OF 5-282 FROM N.A., AND SEQUENCE OF 74-114.
RX   MEDLINE=91309150; PubMed=1830244;
RA   Krainer A.R., Mayeda A., Kozak D., Binns G.;
RT   "Functional expression of cloned human splicing factor SF2: homology
RT   to RNA-binding proteins, U1 70K, and Drosophila splicing regulators.";
RL   Cell 66:383-394(1991).
RN   [3]
RP   SEQUENCE FROM N.A., AND PARTIAL SEQUENCE.
RX   MEDLINE=94253723; PubMed=8195709;
RA   Ghebrehiwet B., Lim B.L., Peerschke E.I., Willis A.C., Reid K.B.;
RT   "Isolation, cDNA cloning, and overexpression of a 33-kD cell surface
RT   glycoprotein that binds to the globular 'heads' of C1q.";
RL   J. Exp. Med. 179:1809-1821(1994).
RN   [4]
RP   X-RAY CRYSTALLOGRAPHY (2.25 ANGSTROMS).
RX   MEDLINE=99199225; PubMed=10097078;
RA   Jiang J., Zhang Y., Krainer A.R., Xu R.-M.;
RT   "Crystal structure of human p32, a doughnut-shaped acidic
RT   mitochondrial matrix protein.";
RL   Proc. Natl. Acad. Sci. U.S.A. 96:3572-3577(1999).
CC   -!- FUNCTION: NOT KNOWN. BINDS TO THE GLOBULAR "HEADS" OF C1Q THUS
CC       INHIBITING C1 ACTIVATION.
CC   -!- SUBCELLULAR LOCATION: MITOCHONDRIAL MATRIX.
CC   -!- SIMILARITY: BELONGS TO THE MAM33 FAMILY.
CC   -!- CAUTION: WAS ORIGINALLY (REF.1 AND REF.2) THOUGHT TO BE A PRE-MRNA
CC       SPLICING FACTOR THAT PLAYS A ROLE IN PREVENTING EXON SKIPPING,
CC       ENSURING THE ACCURACY OF SPLICING AND REGULATING ALTERNATIVE
CC       SPLICING.
CC   --------------------------------------------------------------------------
CC   This SWISS-PROT entry is copyright. It is produced through a collaboration
CC   between  the Swiss Institute of Bioinformatics  and the  EMBL outstation -
CC   the European Bioinformatics Institute.  There are no  restrictions on  its
CC   use  by  non-profit  institutions as long  as its content  is  in  no  way
CC   modified and this statement is not removed.  Usage  by  and for commercial
CC   entities requires a license agreement (See [`http://www.isb-sib.ch/announce/`](http://www.isb-sib.ch/announce/)
CC   or send an email to license@isb-sib.ch).
CC   --------------------------------------------------------------------------
DR   EMBL; L04636; AAA16315.1; -.
DR   EMBL; M69039; AAA73055.1; -.
DR   EMBL; X75913; CAA53512.1; -.
DR   PIR; JT0762; JT0762.
DR   PIR; S44104; S44104.
DR   PDB; 1P32; 06-APR-99.
DR   MIM; 601269; -.
KW   Mitochondrion; Transit peptide; 3D-structure.
FT   TRANSIT       1     73       MITOCHONDRION.
FT   CHAIN        74    282       COMPLEMENT COMPONENT 1, Q SUBCOMPONENT
FT                                BINDING PROTEIN.
SQ   SEQUENCE   282 AA;  31362 MW;  2F747FA73BB1314B CRC64;
     MLPLLRCVPR VLGSSVAGLR AAAPASPFRQ LLQPAPRLCT RPFGLLSVRA GSERRPGLLR
     PRGPCACGCG CGSLHTDGDK AFVDFLSDEI KEERKIQKHK TLPKMSGGWE LELNGTEAKL
     VRKVAGEKIT VTFNINNSIP PTFDGEEEPS QGQKVEEQEP ELTSTPNFVV EVIKNDDGKK
     ALVLDCHYPE DEVGQEDEAE SDIFSIREVS FQSTGESEWK DTNYTLNTDS LDWALYDHLM
     DFLADRGVDN TFADELVELS TALEHQEYIT FLEDLKSFVK SQ
//
```
