# Artificial-Intelligence-In-Bioinformatics-Project-2

The project was divided into two parts: Part I and Part I. I answered the following questions. 

Part I
1) Complete Biological Central Dogma

Nucleotide sequence containing a gene
1 cgcgcgtcgg cgccgctgcc aaccccgctc tgcgatctcg ggccctcccg gcacccgctc
61 gccgtcccgc tccgggctgt ccttgctgcg agggccgccg cgcccgccgt ctccctcagc
121 cctcttgtct ggccgccggg ccgcggcggg cgagagcagc cggaggagga gccgcagcca
181 ggaggcggcg gccggagccc atggcgtaca gtcaaggagg cggcaagaag aaagtgtgct
241 actattatga cggtgatatc gggaattatt attacggcca gggtcatccc atgaagcccc
301 ataggatccg gatgactcat aacttgcttc taaattatgg tttataccga aaaatggaaa
361 tatataggcc tcataaggcc actgctgaag aaatgacaaa ataccacagt gatgagtata
421 tcaagtttct acgatcaata aggccagata acatgtcaga gtatagtaag cagatgcaga
481 gatttaatgt cggagaagac tgtccagtgt tcgatggact ctttgagttt tgtcagctct
541 ccaccggtgg ctcagttgct ggggccgtga agctgaaccg tcaacagact gacatggctg
601 tcaactgggc gggaggactg caccacgcca agaagtcaga ggcctcagga ttctgctacg
661 ttaatgacat tgtgcttgct gtcctcgagc tactgaaata tcatcagaga gtcttatata
721 ttgacataga catccaccat ggtgatggtg ttgaggaagc tttttataca acagatcgcg
781 tgatgaccgt ctcattccat aaatacggag aatactttcc tggaacagga gacttgaggg
841 atattggtgc tggaaaagga aagtactacg ctgtcaactt tcccatgagg gacggtatag
901 atgacgagtc atatggacag atatttaagc ctataatctc aaaagtgatg gagatgtacc
961 agccgagcgc ggtggtgctg cagtgtggcg ctgactccct ctctggtgac aggctgggct
1021 gcttcaacct aactgtcaaa ggtcacgcta aatgtgtaga agtagtgaaa acttttaact
1081 tgccgttgct gatgcttggc ggaggtggct acacaatccg gaatgttgct cgatgttgga
1141 cgtatgagac tgcagttgcc cttgattgtg aaattcccaa tgagttgcca tataatgatt
1201 acttcgagta ttttggacca gacttcaaac tgcatattag tccctcaaac atgacaaacc
1261 agaacactcc agaatatatg gaaaagataa aacagcgttt atttgaaaat ctgcgaatgt
1321 taccacatgc gcctggtgtt caaatgcaag ctattccaga agatgctgtt catgaagaca
1381 gtggtgatga ggatggagaa gaccctgaca agagaatttc tattcgagca tcagacaagc
1441 ggatagcttg tgatgaagag ttctcagatt ctgaggatga aggtgaagga ggtcgtagga
1501 atgtcgctga tcataagaag ggagccaaaa aagccaggat tgaggaagac aagaaggagg
1561 cggaggacaa gaggacagat gttaaggaag aagacaaatc caaggacaat agtggtgaga
1621 aaacagacac caaaggagcc aaatcagaac aactcaacaa cccttgaatt tgactcccca
1681 accttaggaa cctcgaaaag tgagacgatt ctgggataag aaaccttcgc tgtttgagga
1741 agtttggctt cattttatac tgttttggca tggactgtat ttattttcaa aatggcttgt
1801 ttttggtttt ccttggcaag ttttattgtg agtttttcta attatgaagc aaattttttt
1861 ccaccatgct ttatgtgatt gtatttaaat tgatgtgtta ttatgtcaaa aaaaaaaaac
1921 cggatctatt aaagaaacaa ttggcctttc tgagctgatt tttccatctt ttgtaattat
1981 ctttattaaa aaattgtact tggatggtct tctgtctgtt tattatgaag gcttgtttcc
2041 aagcccgact gtgagactgg agcataccca tggtgatttc agtggcagag accctctcac
2101 tgagtctgta cgtgcttact ggctctaaca ggtatttcct atttcaataa aaatgacacc
 2161 atgtcacctt gtatagttaa aaaaaaaaaa aaaaa
 
a) There exists a gene in this sequence, use the translate tool at
http://au.expasy.org/tools/dna.html to find the most likely protein product.
i. Paste the protein sequence into your assignment and indicate which frame you
used.
ii. Why are there 6 possible frames? Hint: the longest sequence Met -> Stop will
be the correct outcome.
iii. Translate the first 50 nucleotide sequence to protein sequence using a python
script 

b) Given an unknown nucleotide sequence in Q1a
i. Which tool would you use to figure out which protein and organism does the
sequence closely match with an justify?
ii. What organism was your sequence most closely matching?
iii. Give a brief summary on the function of the closely matching protein?
2) Biological Sequence alignment. 
3) a) Calculate the alignment score for different alignments and indicate the best possible
aligned sequence for the following sequence:
ACCTAGCTAG
ACCCACCGGG
Use Match: +1, Mismatch:-1 and Indel: -2
i. Show all possible alignments and their scores
ii. Which is the best possible alignment? State the reason.
b) Carry out a Multiple Sequence Alignment (MSA) for the protein Thyroxine 5- deiodinase. Use the UniProt (http://www.uniprot.org/) database for retrieving the
protein sequence of Thyroxine 5-deiodinase. The protein sequences from the following organisms must be included in your MSA.
1) Homo sapiens (Human)
2) Rattus norvegicus (Rat)
3) Bos taurus (Bovine)
4) Ovis aries (Sheep)
5) Xenopus laevis (African clawed frog)
Notes:
Use only the reviewed sequences from the database. This can be done by selecting ‘Reviewed’ under the heading ‘filter by’ at the left hand corner of the results page in UniProt.
Use Clustal Omega for MSA (http://www.ebi.ac.uk/Tools/msa/clustalo/)
i. Provide the FASTA sequences retrieved in your report (5 sequences retrieved
from UniProt).
ii. Show the coloured alignment obtained from ClustalO in your report.
iii. What do you think about the alignment? Give a brief discussion on the
alignment results.
iv. Display the phylogenetic tree and discuss the relationship.
3) Hidden Markov Model (10 marks)
Consider the following HMM, which models an intronic sequence with GC rich regions. The model consists of 9 states:
The states and transition probabilities are indicated in the following diagram:


The emission probabilities for the non-silent states are as follows:

Base S1 S2 S3 S4 S5 S6 S7
A 0 0.5 0.25 0.40 0.25 0 0.30
C 0 0 0.25 0.15 0.25 0.40 0.20
G 1 0 0.20 0.30 0.05 0.30 0.50
T 0 0.5 0.30 0.15 0.45 0.30 0

Please answer the following questions:
i. What is the probability of observing GATTAG along the state path p?
=START-S1-S3-S2-S4-S5-S7 -END?
ii. What is the probability of seeing GTAAG, given the current HMM? (Show
the steps of your calculation.)
iii. What is the probability of seeing GTACGG, given the current HMM? 
Stateyour observation

4) Next Generation sequencing 
Using Galaxy find out the highest number of SNPs in chromosome 12.
i. Display the results acquired after sorting showing the SNP count and state the
highest number of SNP per exon.
ii. Select top 5 exons with highest number of SNPs and display the result.
iii. Also, provide screenshots of the whole process as shown in tutorial with your
name are role number in the files generated.
Note: While renaming the files please use your name


Part II: Presentation of a research topic.
 Deep Learning and Bioinformatics.
