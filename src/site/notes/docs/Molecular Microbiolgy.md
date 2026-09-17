---
{"dg-publish":true,"permalink":"/docs/molecular-microbiolgy/","tags":["flashcards"],"dg-note-properties":{"tags":["flashcards"],"Subject":["Microbiology"]}}
---


## **Master Glossary & Key Terms**

* **Nucleotide:** The fundamental building block of nucleic acids, consisting of a nitrogenous base, a pentose sugar, and a phosphate group.  
* **Nucleoside:** A molecule composed solely of a nitrogenous base and a pentose sugar, lacking the phosphate group.  
* **Central Dogma:** The directional flow of genetic information: DNA → (Transcription) → mRNA → (Translation) → Protein.  
* **Gene:** The fundamental unit of genetic information; a specific sequence of nucleotides in DNA that encodes for a particular function or protein.  
* **Euchromatin:** Loosely packed, lightly stained, and transcriptionally active chromatin (contains active genes).  
* **Heterochromatin:** Tightly packed, darkly stained, and transcriptionally inactive/silent chromatin.  
* **Okazaki Fragments:** Short, discontinuous fragments of DNA synthesized on the lagging strand during DNA replication.  
* **Ribozymes:** Catalytic RNA molecules that function like enzymes (e.g., rRNA in peptide bond formation, RNase P).  
* **Wobble Hypothesis:** The concept that a single tRNA can recognize more than one codon because the pairing between the 5' base of the anticodon and the 3' base of the codon is not strictly bound by standard base-pairing rules.  
* **VNTR (Variable Number Tandem Repeats):** Short chain DNA repeats aligned in tandems; the primary basis for DNA Fingerprinting.  
* **Amplicon:** The final amplified product of a Polymerase Chain Reaction (PCR).  
* **Processivity:** The ability of an enzyme (like DNA Polymerase) to remain attached to its template and continuously catalyze reactions without falling off.

---



### Module 1: Chemistry of Nucleic Acids

Nucleic acids (DNA and RNA) are polymers of nucleotides.

* **Components of a Nucleotide:**  
	* **Nitrogenous Base:** Heterocyclic rings containing nitrogen.  
		* **Purines (Double-ring):** Adenine (A) and Guanine (G). Nitrogen positions at 1, 3, 7, 9
		* **Pyrimidines (Single-ring):** Cytosine (C), Thymine (T, found only in DNA), and Uracil (U, found only in RNA). Nitrogen positions at 1 and 3\.  
  * **Pentose Sugar:** 5-carbon sugar. RNA contains Ribose, while DNA contains 2-Deoxyribose (lacks oxygen at the 2' carbon position).  
  * **Phosphate Group:** Carries a negative charge, making nucleic acids acidic and negatively charged.  
* **Chemical Bonds:**  
	* **Glycosidic Bond (β-N-glycosidic):** Connects the 1' carbon of the pentose sugar to the nitrogenous base (N9 of Purines; N1 of Pyrimidines).
		![Pasted image 20260917115958.png\|462](/img/user/Attachments/Pasted%20image%2020260917115958.png)

	* **Phosphodiester Bond:** Forms the "backbone" of DNA. Connects the 3'-OH group of one nucleotide's sugar to the 5'-phosphate of another.  
	  * **Hydrogen Bond:** Connects complementary bases on opposite strands. A forms a double bond with T (or U in RNA); G forms a triple bond with C. G≡C bonds are stronger by \~50% and raise the melting temperature of DNA.  
* **Differences between DNA and RNA:**  
	* **DNA:** Double-stranded, stable, repository of genetic information, contains Thymine, 2-Deoxyribose sugar. Not destroyed by alkalis.  
	* **RNA:** Single-stranded, unstable, susceptible to hydrolysis by alkalis (due to the 2'-OH group), contains Uracil, Ribose sugar. Follows or doesn't follow Chargaff's rule arbitrarily.

### Module 2: DNA Structure, Properties & Packaging

* **Watson & Crick Double Helix Model (B-DNA):** The dominant physiological form. Features a right-handed double helix, antiparallel strands (5'-\>3' and 3'-\>5'), a diameter of 20 Å (2 nm), and a pitch (one complete turn) of 34 Å containing 10 base pairs (3.4 Å distance between each pair).  
* **Types of DNA:** A, B, C, D, E, and Z. A and B are right-handed. Z-DNA is left-handed. Base pairs per turn: B=10, A=11, Z=12.  
* **Hyperchromicity:** Denaturation (separation of DNA strands via heat/alkali destroying hydrogen bonds) leads to increased UV absorbance at 260 nm, known as the hyperchromic effect. Renaturation/Annealing reverses this.  
* **DNA Packaging:** To fit 2 meters of human DNA into a 10 μm nucleus, it is highly compacted into chromatin. The basic unit is the **Nucleosome**, comprising a core octamer of basic, positively-charged Histone proteins (rich in basic amino acids Arginine and Lysine) wrapped by the acidic, negative DNA strand.

### Module 3: DNA Replication


* **Key Properties:**  
	* **Semi-conservative:** Each newly formed double helix contains one old (parental) strand and one newly synthesized strand.  
	* **Semi-discontinuous:** The leading strand is synthesized continuously; the lagging strand is synthesized in fragments (Okazaki fragments).  
	* **Bidirectional:** Proceeds in both directions away from the Origin of Replication (Ori).  
	  * **Directionality:** Synthesis strictly occurs in the 5' → 3' direction.  
* **Origin of Replication:**  
	* **Prokaryotes:** Single origin called *OriC* (monorepliconic). DnaA-ATP recognizes a methylated GATC sequence (9-mer) and induces melting at the A-T rich 13-mer region. 
	* **Eukaryotes:** Multiple origins called *ARS* (Autonomously Replicating Sequences) firing simultaneously (polyrepliconic).  
* **Machinery & Enzymology (Prokaryotes vs. Eukaryotes):**  
	* **Helicase:** Breaks hydrogen bonds to unwind DNA. Prokaryotes: DnaB (loaded by DnaC loader). Eukaryotes: MCM 2-7 complex (loaded by Cdc6, Cdt1).  
	* **Single-Stranded Binding Proteins (SSB):** Prevents re-annealing of separated strands. (RPA in eukaryotes).  
	* **Primase(dna dependent rna polymerase):** An enzyme that acts as a starting signal for DNA replication. It builds a short RNA "primer" segment that DNA polymerase needs to begin copying the DNA. In bacteria (prokaryotes), this is done by an enzyme called DnaG, while in complex organisms (eukaryotes), a protein complex called DNA Pol α handles this, even starting the initial DNA synthesis.  
	  * **Main DNA Polymerase:** Requires template, primer, and free 3'-OH end.  
		* Prokaryotes: **DNA Pol III** (Main replicase; exists as a dimer connected by a Tau complex; highly processive).  
		* Eukaryotes: Demonstrates "Polymerase Switching." **DNA Pol ε** synthesizes the leading strand; **DNA Pol δ** synthesizes the lagging strand.  
	* **Sliding Clamp:** Enhances polymerase processivity. Prokaryotes: β-clamp (loaded by γ-complex). Eukaryotes: PCNA (loaded by RFC).  
	* **Primer Removal & Gap Filling:**  
		* Prokaryotes: **DNA Pol I** uses its unique 5' → 3' exonuclease activity to remove the RNA primer, and its 5' → 3' polymerase activity to fill the gap.  
		* Eukaryotes: **RNase H** removes RNA nucleotides; **FEN-1** (Flap Endonuclease) cuts the final phosphodiester bond linking RNA to DNA.  
	* **Ligase (Molecular Glue):** Seals remaining nicks by forming phosphodiester bonds.  
	* **Topoisomerase:** Relieves torsional stress (positive supercoiling) ahead of the replication fork by cutting and rejoining DNA.  
		* **Type I:** Cuts 1 strand, removes 1 twist, requires NO ATP.  
		* **Type II:** Cuts both strands, removes 2 twists, requires ATP. Example in prokaryotes: DNA Gyrase & Topo IV. Inhibited by the antibiotic Ciprofloxacin.



### **Module 4: DNA Repair Mechanisms**

* **Direct Repair:** E.g., Photo-reversal. **DNA Photolyase** removes UV-induced pyrimidine (T-T) dimers using light energy via Flavin and Pterin domains. Alkyltransferase directly removes methyl groups from Guanine.  
* **Mismatch Repair (MMR):** Repairs erroneous insertions post-replication.  
  * Prokaryotes: MutH recognizes the old (methylated) strand, MutS scans for errors, MutL links them. Exonuclease VII cuts, Pol III fills, Ligase seals.  
  * Eukaryotes: Homologs are MSH, MLH etc..  
* **Base Excision Repair (BER):** **Glycosylase** cleaves the N-glycosidic bond, leaving an AP site (Apurinic/Apyrimidinic). **AP Endonuclease** breaks the phosphodiester backbone. DNA Pol I (or II) fills the gap, and Ligase seals.  
* **Nucleotide Excision Repair (NER):** Removes bulky lesions (e.g., T-T dimers in non-photosynthetic organisms).  
  * Prokaryotes: **UvrABC complex**. UvrA & B detect damage. UvrC (endonuclease) cuts 8 nt away on the 5' side and 4-5 nt away on the 3' side. UvrD (helicase) removes the \~12 nt fragment. Pol I fills, Ligase seals.  
  * Eukaryotes: Analogs include XPA-XPG (e.g., XPC detects, XPB/XPD act as helicases in TFIIH, XPF/XPG act as nucleases).

### **Module 5: Transcription**

**RNA polymerase** is the key enzyme responsible for transcription, reading the DNA template to build a complementary RNA strand.
.
The synthesis of mRNA from a DNA template. Synthesis strictly occurs 5' → 3'. The DNA strand with identical polarity to mRNA is the **Coding / Sense (+) Strand**, and the read strand is the **Template / Antisense (-) Strand**.



* **Prokaryotic Transcription:**  
  1. Catalyzed by a single type of **RNA Polymerase**.  
  2. RNA Pol Core Enzyme (2α, β, β', ω) \+ **Sigma (σ) Factor** \= Holoenzyme. The Sigma factor recognizes the promoter, initiates melting, and determines specificity before detaching (e.g., σ⁷⁰ for housekeeping genes, σ³² for heat shock).  
  3. **Promoters:** Completely upstream. Contain \-10 box (Pribnow Box, melting region TATAAT) and \-35 box (recognition region TTGACA).  
  4. **Termination:**  
     * *Rho-dependent:* A hexameric Rho factor (helicase) binds the 'rut' sequence on mRNA, creating a mechanical jerk that breaks RNA-DNA bonds to dissociate the transcript.  
     * *Rho-independent:* Involves NusA/NusG proteins, forming a G-C rich hairpin loop in the mRNA followed by a weak A-U rich region, stalling and dissociating the polymerase.  
* **Eukaryotic Transcription:**  
  1. **RNA Polymerases:** Pol I (synthesizes rRNAs: 18S, 28S, 5.8S), Pol II (synthesizes mRNA, snRNA, siRNA, miRNA), Pol III (synthesizes tRNA, 5S rRNA).  
  2. **Promoter II:** Split between upstream and downstream of the start site. Contains a TATA box.  
  3. **General Transcription Factors (GTFs) for Pol II:** Order of assembly (Mnemonic: D, A, B, F, E, H).  
     * *TFIID:* Contains TBP (TATA-binding protein) that binds the minor groove and bends DNA.  
     * *TFIIH:* Has dual roles—Helicase (melts DNA) and Kinase (phosphorylates the 5th Serine of RNA Pol II's C-Terminal Domain (CTD) tail sequence YSPTSPS to initiate elongation).  
* **Post-Transcriptional Modifications (Eukaryotes only):** Convert pre-mRNA into mature mRNA.  
  1. **5' Capping (Co-transcriptional):** 7-methylguanosine is added via a 5'-5' triphosphate linkage by Guanylyl transferase and Methyl transferase. Prevents 5' exonuclease degradation and aids ribosome binding.  
  2. **3' Tailing (Post-transcriptional):** Cleavage specific proteins (CPSF, CStF) cut the mRNA. **Poly-A Polymerase (PAP)** adds a Poly-A tail (50-250 AMP units, template-independent). Aids transport, translation, and protection (bound by PABP).  
  3. **Splicing (Co-transcriptional):** Removal of non-functional Introns and ligation of Exons.  
     * *Major Splicing:* Uses the Spliceosome (snRNA \+ proteins). A 2'-OH from the Adenine in the branch point sequence attacks the 5' splice site (G) forming a 'Lariat' structure. Requires ATP.  
     * *Minor Splicing:* Follows identical mechanics but recognizes AU-AC splice sites instead of GU-AG.  
     * *Auto-Splicing:* Spliceosome-independent. Group I uses a free external GTP 3'-OH; Group II mimics major splicing mechanics intrinsically.  
     * *Trans-Splicing:* Splices exons from entirely different genes (e.g., in *Trypanosoma* causing sleeping sickness).  
     * *Alternative Splicing:* A single pre-mRNA is spliced in various patterns, generating thousands of distinct proteins from a single gene.

### **Module 6: Translation (Protein Synthesis)**

Decodes mRNA sequences (3-nucleotide codons) to assemble polypeptide chains on ribosomes.

* **tRNA (Transfer RNA):** Has an L-shaped functional 3D structure (Cloverleaf 2D model). Amino acids attach to the 3'-CCA sequence's Adenine (initially 2' or 3'-OH, settles on 3'-OH). This active form is called **Aminoacyl-tRNA**.  
* **The Ribosome:** Contains E (Exit), P (Peptidyl), and A (Aminoacyl/Arrival) sites.  
* **Phases of Translation:**  
  * **Initiation:**  
    * *Prokaryotes:* IF1 and IF3 block large subunit binding initially. IF2 (with GTP) brings Formyl-Methionine (fMet) tRNA directly to the **P-site**. Shine-Dalgarno sequence (AGGAGG) aligns mRNA.  
    * *Eukaryotes:* Initiates with Methionine at the Kozak sequence. Uses eIFs (e.g., eIF4G creates circular mRNA by linking cap and tail).  
  * **Elongation:** EF-Tu (Prokaryotes) / eEF1α (Eukaryotes) brings the next aminoacyl-tRNA to the A-site. EF-Ts / eEF1βγ regenerates EF-Tu. The **Peptidyl Transferase** enzyme—which is actually **23S rRNA** (Prokaryotes) or **28S rRNA** (Eukaryotes)—catalyzes peptide bond formation between amino acids. EF-G / eEF2 facilitates ribosome translocation.  
  * **Termination:** Stop codons (UAA, UAG, UGA) enter the A-site. They recruit Release Factors (RF1, RF2, RF3 in Prokaryotes) which hydrolyze the bond, releasing the polypeptide.  
* **Special Considerations:**  
  * *Selenocysteine (21st amino acid):* Coded by UGA (stop codon). Initially loads Serine on its tRNA, which is then biochemically converted to Selenocysteine.  
  * *Pyrrolysine (22nd amino acid):* Coded by UAG.  
  * *Wobble Hypothesis:* Reduces the required number of tRNAs below 61\. The 5' end of the tRNA anticodon can form non-standard pairs (e.g., Inosine pairs with U, C, or A) with the 3' end of the mRNA codon.  
* **Post-Translational Modifications:** Polypeptide chains undergo 3D folding (e.g., beta-pleated sheets). Faulty folding leads to amyloid diseases. Chemical additions (Glycosylation, Phosphorylation) regulate activity/stability.

### **Module 7: Gene Regulation (Operon Models)**

* **Lac Operon (Lactose Metabolism):**  
  * **Inducible:** Normally OFF. Turns ON only when lactose (food source) is present.  
  * *Mechanism:* Repressor protein intrinsically binds the Operator, blocking RNA Pol. Lactose (inducer) binds the repressor, inactivating it. Lac Z encodes β-galactosidase.  
  * *Catabolite Repression (Diauxic Growth):* Glucose is the preferred energy source. If both Glucose and Lactose are present, Glucose inhibits cAMP production, preventing CAP (Catabolite Activator Protein) from activating the operon, resulting in a dual-phase (diauxic) growth curve.  
  * *Mutation Scenarios:* Mutations designated "$O^c$" (Operator-constitutive) prevent repressor binding, resulting in continuous (constitutive) transcription regardless of repressor (I+) presence.  
* **Tryptophan (Trp) Operon (Biosynthesis):**  
  * **Repressible:** Normally ON. Turns OFF when Tryptophan is abundant.  
  * *Mechanism:* Tryptophan acts as a **co-repressor**, binding the apo-repressor to form a holorepressor that blocks the operator.  
  * *Attenuation:* Relies on translation speed closely following transcription. The Trp leader sequence forms hairpin loops: Low Trp causes ribosome stalling, leading to a 2-3 anti-terminator loop. High Trp avoids stalling, causing a 3-4 terminator loop.

### **Module 8: Molecular Biology Techniques**
[[docs/PCR\|PCR]]


* **Gel Electrophoresis:** Separates DNA/RNA based on charge and size.  
  * Negative DNA migrates to the positive electrode (Anode). Smaller fragments migrate faster/further.  
  * Matrix: Agarose gel (standard 1%; use 2-3% for smaller DNA/high resolution).  
  * Running Buffer: TAE (Tris Acetate EDTA) at pH 8.4.  
  * Visualization: DNA is heavy-loaded using Glycerol. **Ethidium Bromide (EtBr)**, a highly mutagenic intercalating agent, is embedded in the gel. It slips between DNA base pairs and fluoresces reddish-brown under UV light in a Gel Doc system.  
  * DNA Ladder is run parallel to estimate base-pair size.  
* **Blotting Techniques:** Transferring biological molecules from a gel to a stable membrane (nitrocellulose/nylon) via capillary action (using a sponge/buffer setup), followed by UV immobilization and radioactive/fluorescent labeled probing.  
  * Mnemonic: **SNOW DROP**  
    * **S**outhern Blot → **D**NA  
    * **N**orthern Blot → **R**NA  
    * **O** (ignore) → **O** (ignore)  
    * **W**estern Blot → **P**rotein  
    * **E**astern Blot $\\rightarrow$ Post-translational modifications  
* **DNA Fingerprinting:** Primarily relies on Variable Number Tandem Repeats (VNTRs)—short, highly repetitive sequences aligned in tandem, producing unique sequences for individual identification.

DNA fingerprinting, also known as DNA profiling, is a laboratory technique used to identify an individual by analyzing specific regions of their DNA that are unique to them.

While humans share over 99% of their genetic makeup, there are small, highly variable regions of DNA—known as Variable Number Tandem Repeats (VNTRs) or Short Tandem Repeats (STRs)—that differ significantly from person to person. By analyzing the number of times these specific sequences repeat, scientists can create a unique genetic "barcode" or profile for an individual.

**Key Uses of DNA Fingerprinting:**

* **Forensic Investigations:** Linking biological evidence (such as blood, hair, or saliva)   
* **Paternity and Family Testing:**   
* **Identification of Victims**  
* **Wildlife and Environmental Forensics**

---

## **Key Formulas, Rules, or Metrics**

* **Chargaff's Rule:** In dsDNA, Purines \= Pyrimidines ($A=T$, $G=C$). Does *not* apply to RNA.  
* **DNA Dimensions:**  
  * Width: 20 Å (2 nm).  
  * 1 Complete Helical Turn: 34 Å (3.4 nm).  
  * Distance between Base Pairs: 3.4 Å (0.34 nm).  
  * Number of Base Pairs per Turn in B-DNA: 10\.  
* **Genome Stats (Human):** Diploid cells contain 46 chromosomes comprising roughly 6 × 10⁹ base pairs. Total DNA length is ≈2 meters, packed in a ≈10 μm diameter nucleus.  
* **Spectrophotometry Absorbance Peak:** Nucleic acids heavily absorb UV light at 260 nm.  
* **Acid-Fast Staining:** Mentioned via *M. tuberculosis* diagnostics context. Uses 20% H₂SO₄ as a decolorizer. (Not central to molecular biology, but captured per requirements).  
* **Agarose Gel Standards:** Solidification requires 2-3% agarose. Standard gel running uses 1%. High-resolution gels for very tiny fragments require 3%.

---

## **Critical Nuances & Exceptions**

* **Taq Polymerase vs. Reverse Transcriptase:** Both are used in PCR modalities, but *Taq Polymerase* uses a DNA template to make DNA (stable at 98°C), whereas *Reverse Transcriptase* (found in Retroviruses like HIV) synthesizes DNA from an RNA template.  
* **Base Replacement:** RNA entirely lacks Thymine, replacing it exclusively with Uracil. The primary transcription template is solely the Anti-Sense (-) strand so that the resulting mRNA perfectly mimics the Coding (+) strand.  
* **RNA Sensitivity:** A critical structural limitation of RNA is its 2'-OH group on the ribose ring, which makes it highly susceptible to alkaline hydrolysis. DNA lacks this group, granting it superior stability.  
* **Enzyme Anomalies:**  
  * *DNA Pol I Exonuclease:* While DNA Pol III provides 3'→5' exonuclease proofreading, only **DNA Pol I** possesses the 5'→3' exonuclease activity required to strip RNA primers.  
  * *Ribozymes exception:* While all typical enzymes are proteins, ribozymes represent functional exceptions where RNA molecules function as catalytic enzymes.  
* **Amino Acid Exceptions:** Selenocysteine (21st amino acid) does not initially bind its own exclusive tRNA. Serine is loaded onto the specific tRNA first, then biochemically altered to Selenocysteine.  
* **Nucleophilic Attack Nuance in Splicing:** In major splicing, the catalytic nucleophilic attack is generated from the 2'-OH of the Adenine branch point. In autosplicing, external GTP uses its 3'-OH.

