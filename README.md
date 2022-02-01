# Phenethylamine: Von der Struktur zur Funktion (English)
A long-term project to digitise and translate Trachsel et al.'s seminal book "Phenethylamine: Von der Struktur zur Funktion" from German into English. The translation being the most important part, to date. 

## TODO
- [x] scan/photograph pages into JPEGs
- [x] rename images using page numbers
- [ ] OCR German text from images:
  - [x] pages 1-99
  - [x] pages 100-199
  - [x] pages 200-299
  - [x] pages 300-399
  - [ ] pages 400-499
  - [ ] pages 500-599
  - [ ] pages 600-699
  - [ ] pages 700-799
  - [ ] pages 800-899
  - [ ] pages 900-1003
- [ ] Translate German to English:
  - [ ] pages 1-99
  - [ ] pages 100-199
  - [ ] pages 200-299
  - [ ] pages 300-399
  - [ ] pages 400-499
  - [ ] pages 500-599
  - [ ] pages 600-699
  - [ ] pages 700-799
  - [ ] pages 800-899
  - [ ] pages 900-1003
- [ ] Molecule diagram images (PNG/JPEG):
  - [ ] pages 1-99
  - [ ] pages 100-199
  - [ ] pages 200-299
  - [ ] pages 300-399
  - [ ] pages 400-499
  - [ ] pages 500-599
  - [ ] pages 600-699
  - [ ] pages 700-799
  - [ ] pages 800-899
  - [ ] pages 900-1003
- [ ] Extract clean images from book (e.g. advertisements)
  - [ ] pages 1-99
  - [ ] pages 100-199
  - [ ] pages 200-299
  - [ ] pages 300-399
  - [ ] pages 400-499
  - [ ] pages 500-599
  - [ ] pages 600-699
  - [ ] pages 700-799
  - [ ] pages 800-899
  - [ ] pages 900-1003
- [ ] Resolve all translation problems in the Issues area of the project
- [ ] Compile in LateX
- [ ] Render PDFs:
  - [ ] link to/from book chapters
  - [ ] sections
  - [ ] English

## Nice-to-have TODO
- [ ] hyperlinks for references
- [ ] hyperlinks for chemistry terms and concepts
- [ ] PubChem links for compounds
- [ ] hyperlinks to profiles of authors/researchers

## Contributing!
### Translate pages into English
NOTE: take a look at [PR #2](https://github.com/aes256lamp/trachsel2013/pull/2) for inspiration for a properly organised contribution.


This is the primary goal of this project so getting English translations is high priority (instead of, say, extracting images).

Try to do one translation __per commit__.

You are encouraged to put multiple translation into one Pull Request (PR) so the project doesn't get overloaded with PRs.

Translation checklist:
* select a German page to translate (e.g. 0723.txt)
* ensure that the OCR text output in that file matches up **exactly** with the text in the image:
  * it's important to get German characters correct
  * it's __not so important__ to get subscripts and superscripts correct (they're secondary to the task of translation, and will be dealt with after translation is complete)
* translate the German into English
  * Google Translate has been doing quite fine with this task, so far. YMMV.
  * __try__ to preserve the white-space:
    * between paragraphs
    * at the start of paragraphs
* **if something doesn't quite translate** then mention this in the PR you create for your work.
* name the new file with "\_en" at the end. For example:
  * 0723_en.txt

### Make corrections to English translations
This is pretty simple. Have a look through the English translations and if you find anything that needs attention then make a GitHub Issue. **Follow the format of previous GitHub issues**. This helps the people reviewing your work :)

Alternatively, make a PR with the changes in them!

### Extracting images
The images in the book - things like advertisements, __not__ molecule diagrams - need cropping out and cleaning up.

Preferably they'd be in grayscale so that they appear properly in the PDF that will eventually be rendered. This means the image doesn't contain any coloured artifacts, that sort of thing.

Render them:
* in PNG or JPEG format
* high quality
* black and white (i.e. grayscale).

Name them:
* prefixed with the page number
* descriptively, as best you can. For example (refer to pages in book):
  * 0448_diet_pill_ad.jpg, 0448_redux_pill.jpg
  * 0441_buddha_on_scales.jpg, 0441_eskatrol.jpg, 0441_syndrox.jpg, 0441_tight_squeeze.jpg

### Molecular diagrams
The digital book will need ALL of the molecular diagrams present in the physical book .. that's a lot of diagrams!

As long as they look __95% like the original__ it doesn't matter how they're made. They could be cropped out as per the instructions for 'Extracting images' or made from scratch using something like ChemDraw or any number of online molecular diagram softwares.

Render them:
* in PNG or JPEG format
* high quality
* black and white.

Name them:
* prefixed with the page number
* descriptively, as best you can. For example (refer to pages in book):
  * 0440_5_Amphetamin.png, 0440_6_Methamphetamin.png
  * 0451_34.png, 0451_35.png


## Table of Contents
```
1. 2-phenethylamine
   Digression: Natural substances with a phenethylamine basic structure

2. Amphetamine
  2.1. From the birth of an immortal substance
  2.2. Therapeutic use today
  2.3. Pharmacological effects of amphetamine
    2.3.1. Physiological effects of amphetamine
    2.3.2. On the central mechanism of action of amphetamine
    2.3.3. Interactions and poisoning
    2.3.4. The chirality determines the activity
  2.4. Clandestine production of amphetamine
  2.5. Amphetamine: a natural product?

3. Aryl-unsubstituted phenylalkylamines
  3.1. N-alkyl substituted phenylalkylamines
    3.1.1. Phenylisopropylamine (amphetamines)
      3.1.1.1. Methamphetamine
      3.1.1.2. More N-alkylamphetamines
    3.1.2. Phenethylamines
    3.1.3. Selection of some commercially successful substances
  3.2. N,N-dialkyl substituted phenylalkylamines
    3.2.1. N,N-dialkyl substituted phenylisopropylamines (amphetamines)
    3.2.2. N,N-dialkyl substituted phenethylamines
  3.3. N-hetero substituted phenylalkylamines
  3.4. Phenylalkylamines with heteroatoms incorporated into the side chain
  3.5. Phenylalkylamines with heteroatoms on the side chain
  Digression: Fluorine in medicinal chemistry
  3.6. α-substituted phenylalkylamines
  3.7. α,α-disubstituted phenylalkylamines
  3.8. β-substituted phenylalkylamines
  3.9. ß,ß-disubstituted Phenylalkylamines
  3.10. Phenylalkylamines with varied amino positions
  Digression: antidepressants
  3.11. Phenylalkyl cycloalkylamines
  Digression: amine oxidases
  3.12. Phenylalkylazacycloalkanes
    3.12.1. Aziridines
    3.12.2. Azetidines
    3.12.3. Five-membered azacycles
    3.12.4. Six-membered azacycles
      3.12.4.1. Piperidines
      3.12.4.2. Piperazine
      3.12.4.3. Morpholines
  3.13. Benzannulated cycloalkylamines
  3.14. Benzannulated azacycloalkanes
    3.14.1. Indoline and indole derivatives
    3.14.2. Tetrahydroisoquinolines
    3.14.3. Cyclophanes
  3.15. AMDA and descendants

4. Heteroarylalkylamines
  4.1. Pyrrolylalkylamines
    4.1.1. 1-pyrrolylalkylamines
    4.1.2. 2-pyrrolylalkylamines
    4.1.3. 3-pyrrolylalkylamines
  4.2. Furanylalkylamines
    4.2.1. 2-furanylalkylamines
    4.2.2. 3-furanylalkylamines
  4.3. Thienylalkylamines
    4.3.1. 2-thienylalkylamines
    4.3.2. 3-thienylalkylamines
  4.4. Selenienylalkylamines
  4.5. Tellurolylalkylamines
  4.6. Imidazolylalkylamines
    4.6.1. 1-imidazolylalkylamines
    4.6.2. 2-imidazolylalkylamines
    4.6.3. 4(5)-imidazolylalkylamines
  4.7. Oxazolylalkylamines
  4.8. Thiazolylalkylamines
  4.9. Isoxazolylalkylamines
  4.10. Isothiazolylalkylamines
  4.11. Pyridylalkylamines
    4.11.1. 2-pyridylalkylamines
    4.11.2. 3-pyridylalkylamines 
    4.11.3. 4-pyridylalkylamines 
  4.12. Diazinylalkylamines 
  Digression: Bioisosteres

5. Replacement of the aryl part by non-aromatic residues
  5.1. Alkylamines
  5.2. Alicyclic alkyl amines
  5.3. Metallocenes

6. Monosubstituted phenylalkylamines
  6.1. 2-substituted phenylalkylamines
    6.1.1. A couple of connections worth mentioning
    6.1.2. 2-substituted phenoxyalkylamines as beta blockers
  6.2. 3-substituted phenylalkylamines
    6.2.1. A couple of connections worth mentioning
    6.2.2. Fenfluramine and its derivatives
      6.2.2.1. The discovery of fenfluramine
      6.2.2.2. Mechanism of action and side effects of fenfluramine
      6.2.2.3. The 5-HT2C receptor and food intake
      6.2.2.4. More structural derivatives of fenfluramine
    6.2.3. Further 3-substituted phenylalkylamines
      6.2.3.1. Adrenergic connections
      6.2.3.2. Lean molecules mimic morphine
      6.2.3.3. Various
  6.3. 4-substituted phenylalkylamines
    6.3.1. Naturally occurring 4-substituted phenylalkylamines
    6.3.2. Overview of the 4-substituted phenylalkylamines
    6.3.3. The 4-methoxyphenylalkylamines
    6.3.4. Serotonergic Agents
    6.3.5. 4-substituted phenylalkylamines as 5-HT2A receptor antagonists
    6.3.6. Beta-keto functionalization (bk compounds)
    6.3.7. MAO inhibitors
    6.3.8. Anorectics
    6.3.9. Derivatives interacting with beta receptors
    6.3.10. Further modifications
  Digression: anorectics

7. Disubstituted phenylalkylamines
  7.1 2,3-disubstituted Phenylalkylamines
    7.1.1. Selection of some 2,3-disubstituted phenylalkylamines
  7.2. 2,4-disubstituted phenylalkylamines
    7.2.1. Selection of some 2,4-disubstituted phenylalkylamines
  7.3. 2,5-disubstituted phenylalkylamines
    7.3.1. The classic representatives 2C-H, 2,5-DMA and 4C-H
    7.3.2. N-alkylations
    7.3.3. Rigidizations of the 2,5-disubstituted phenylalkylamines
    7.3.3.1. Rigidization of the methoxy groups
    7.3.3.2. Rigidize the side chain
    7.3.3.3. Combined rigidization of the side chain and a methoxy group
    7.3.4. Replacement of the MeO groups
    7.3.5. Overview of further derivatives
    7.3.6. Various structural modifications
  Digression: Drug Discrimination
  7.4. 2,6-disubstituted phenylalkylamines
    7.4.1. 2,6-dimethoxyphenylalkylamines
    7.4.2. Other 2,6-disubstituted derivatives
  7.5. 3,4-disubstituted phenylalkylamines
    7.5.1. The importance of dopamine
    7.5.2. The importance of norepinephrine (noradrenaline)
    7.5.3. The importance of epinephrine (adrenaline)
    7.5.4. Overview of the simple 3,4-disubstituted phenylalkylamines without the 3,4-methylenedioxyphenylalkylamines
      7.5.4.1. A couple of derivatives worth mentioning
    7.5.5. Overview of the simple 3,4-methylenedioxyphenylalkylamines
    7.5.6. The unique MDMA
      7.5.6.1. Introduction
      7.5.6.2. The history and occurrence of MDMA
      7.5.6.3. Neural mechanisms of action, neurotoxicity and physiological side effects
      7.5.6.4. The enantioselectivity of MDMA
      7.5.6.5. The metabolism of MDMA
      7.5.6.6. And the (psycho) pharmacological effect as well enantioselectivity in Humans?
      7.5.6.7. MDMA as an entactogen - an independent class of substances
      7.5.6.8. The therapeutic potential of MDMA
    7.5.7. Further structural modifications of the 3,4-methylenedioxy derivatives
      7.5.7.1. N substitution
      7.5.7.2. Alkylation on the α-carbon
      7.5.7.3. Substitution at the β-carbon
      7.5.7.4. Modification of the dioxole group
      7.5.7.5. Moving the amino position
      7.5.7.6. Substituents on aromatics
      7.5.7.7. Modifications of the side chain
      7.5.7.8. Replacement of the aryl unit
      7.5.7.9. Miscellaneous
    7.5.8. Other 3,4-disubstituted arylalkylamines
  Digression: monoamine transporter
  7.6. 3,5-disubstituted phenylalkylamines
    7.6.1. Selection of some 3,5-disubstituted phenylalkylamines

8. Trisubstituted phenylalkylamines
  8.1. 2,3,4-trisubstituted phenylalkylamines
    8.1.1. A couple of connections worth mentioning
  8.2. 2,3,5-trisubstituted phenylalkylamines
  8.3. 2,3,6-trisubstituted phenylalkylamines
  8.4. 3,4,5-trisubstituted phenylalkylamines
    8.4.1. Mescaline: The mother of the psychedelic phenethylamines
      8.4.1.1. Chemistry of Mescaline
      8.4.1.2. Mescaline in humans and animals
      8.4.1.3. The subjective effects in humans
      8.4.1.4. The magic cactus from the New World becomes a psychedelic one catalyst for humanity
    8.4.2. N substitution in mescaline
    8.4.3. Variation of the chain length of mescaline and other α, ß modifications
    8.4.4. Heteroatoms on/in the side chain of mescaline
    8.4.5. Variation of the amino position in mescaline
    8.4.6. Deuteration of mescaline
    8.4.7. Rigid analogues of mescaline
    8.4.8. Mescaline analogues: alkoxy modifications in the aryl part
      8.4.8.1. Comments on the structure-activity relationships
      8.4.8.2. Homo scaline
      8.4.8.3. Meta-Scaline, Asymb-Scaline, Symb-Scaline and Tris-Scaline
    8.4.9. Mescaline analogues: alkylthio modifications in the aryl part (Thio-Scaline)
      8.4.9.1. Homo-4-thio scalins
      8.4.9.2. Homo-3-thio-scalins
      8.4.9.3. Thiometa scaline
      8.4.9.4. Thioasymb Scaline
      8.4.9.5. Thiosymb Scaline and Thiotris Scaline
    8.4.10. The 3C derivatives of the Scaline
    8.4.11. Further 3,4,5-trisubstituted derivatives
  8.5. 2,4,5-trisubstituted phenylalkylamines
    8.5.1. Interaction with the serotonin 5-HT2A receptor
    8.5.2. Definition of the 2C and 3C derivatives (terminology)
    8.5.3. 4-Alky dimethoxyphenethylamine (2C-R- or 2C-alkyl derivatives)
    8.5.4. 4-alkyl-2,5-dimethoxyamphetamine (DOR derivatives)
    8.5.5. 4-alkyloxy-2,5-dimethoxyphenethylamine (2C-O-derivatives)
    8.5.6. 4-alkyloxy-2,5-dimethoxyamphetamine (MRM derivatives)
    8.5.7. 4-alkylthio-2,5-dimethoxyphenethylamine (2C-T derivatives)
    8.5.8. 4-alkylthio-2,5-dimethoxyamphetamine (ALEPH derivatives)
    8.5.9. 4-halo-2,5-dimethoxyphenethylamine (2C-X derivatives)
    8.5.10. 4-halo-2,5-dimethoxyamphetamine (DOX derivatives)
    8.5.11. Further 4-heteroatom-substituted 2,5-dimethoxyphenethylamines
    8.5.12. Other 4-heteroatom-substituted 2,5-dimethoxyamphetamines
    8.5.13. 4-aryl-substituted 2,5-dimethoxyphenethylamines (2C-BI derivatives)
    8.5.14. The enantioselectivity of the 2,4,5-trisubstituted α-methylphenethylamines
    8.5.15. Comparison of the 2C and 3C derivatives
    8.5.16. And the 1C derivatives? 2,4,5-trisubstituted benzylamines
    8.5.17. Metabolism of the 2,4,5-trisubstituted phenylalkylamines
    8.5.18. Phenethylamine type psychedelics: what are their structural requirements?
    8.5.19. Lipophilicity and binding properties of the 2,4,5-trisubstituted phenylalkylamines at the 5-HT2A receptor
    8.5.20. Functional selectivity of the 2,4,5-trisubstituted phenylalkylamines
    8.5.21. Modification of the 2,5-dimethoxy substituents
    8.5.22. Further modifications of the 2,4,5-aryl substituents
    8.5.23. Aryl modifications to methylenedioxyphenylalkylamines
    8.5.24. 4C derivatives and α, α-disubstituted phenethylamines
    8.5.25. Substituents in the β position of 2,4,5-trisubstituted phenylalkylamines
    8.5.26. N-substitution of 2,4,5-trisubstituted phenylalkylamines
    8.5.27. Rigid analogues: via structural modification of the ligands towards a 5-HT2A receptor model
      8.5.27.1. Conformal investigations on the ethylamine side chain
      8.5.27.2. Conformational fixation of the MeO groups
      8.5.27.3. On the nomenclature of the alkyloxyrigidized phenylalkylamines
      8.5.27.4. A fatal step: from the laboratory directly into humans
    8.5.28. Other 2,4,5-trisubstituted phenylalkylamines
  8.6. 2,4,6-trisubstituted phenylalkylamines
    8.6.1. The pseudo-connections (Ψ-derivatives)
    8.6.2. Further 2,4,6-trisubstituted phenylalkylamines
    8.6.3. Rigidized 2,4,6-trisubstituted phenylalkylamines

9. Tetra-substituted phenylalkylamines
  9.1. 2,3,4,5-tetrasubstituted phenylalkylamines
  9.2. 2,3,4,6-tetrasubstituted phenylalkylamines
  9.3. 2,3,5,6-tetrasubstituted phenylalkylamines

10. 2,3,4,5,6-Pentasubstituted phenylalkylamines
  10.1. The search for potentially active substructures
  10.2. Overview of other penta-substituted derivatives
  10.3. Exotic phenylalkylamines in marine life
  Digression: Aspects of Molecular Pharmacology

Keyword index

Overview of the excursions
  Natural substances with a basic phenethylamine structure
  Fluorine in medicinal chemistry
  Antidepressants
  Amine oxidases
  Bioisosteria
  Anorectics
  Drug Discrimination
  Monoamine transporter
  Aspects of Molecular Pharmacology
```
