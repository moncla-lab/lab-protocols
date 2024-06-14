# IVT Preparation
New *in-vitro* transcripts are prepared for use as standards in qRT-PCR assays. They are derived from pre-existing plasmids containing a target sequence. Restriction enzymes are used to digest the plasmids, then various phenol-chloroform and ethanol washes purify the final RNA transcript. The product's concentration is then measured and diluted appropriately for use in qRT-PCR.
> Note: This protocol is based on recommendations from the Megascript manual, so for questions or troubleshooting, see that guide.
## Materials:
  ### Plasmid Digest:
   - Plasmid
   - Appropriate restriction enzyme
  ### Proteinase K incubation
   - Proteinase K, 20 mg/mL (Promega MC5005)
   - 15% SDS
  ### Phenol/Chloroform Extraction and Precipitations
   - Phenol/chloroform/isoamyl alcohol (25:24:1)
   - Chloroform
   - Pellet paint NF co-precipitant (Novagen/EMD #70748)
   - 3M NaOAc, pH 5.2 (provided in Pellet Paint kit)
   - 100% ethanol (molecular grade)
   - 70% ethanol (molecular grade)
   - Isopropanol (molecular grade)
   - RNase Out (Invitrogen #10777-019)
  ### Transcription Reaction
   - MEGAscript T7 transcription kit (Ambion #1333)
   - TURBO DNase, 2 U/uL (Ambion #2238) - comes with T7 Megascriptkit
  ### Spin Column Purification (optional)
   - Mini Quick Spin RNA columns (ROCHE #11814427001)
## Protocol:
  ### Plasmid Digest
   1. Digest ~2ug in a 30uL reaction. Calculate volume needed for 2ug according to concentration of starting plasmid. Digest with the appropriate enzyme (BamHI for SIV plasmid p239 gag_Lifson, HindIII for ZIKV plasmid 700-1500 #3302-5, etc.) Example reactions:
```math
2ug = 2000ng
```
```math
(833 ng/uL)(V1) = 2000ng
```
```math
V1 = (2000ng/833ng/uL) = 2.40096 uL
```
```math
MP: 748 ng/uL * V1 = 2000 ng
```
```math
V1 = (2000ng/748ng/uL) = 2.67 uL
```
```math
HA: 812.3 ng/uL * V1 = 2000 ng
```
```math
V1 = (2000ng/812.3ng/uL) = 2.46 uL
```

| SIV | | Volume|
|-----:|-----------| ---- |
|Plasmid DNA | Concentration 833 ng/uL | 2.4 uL |
|Buffer E | 10x | 3 uL |
|Enzyme | BamHI | 3uL |
| DEPC water | | 18.6 uL |
| BSA (1:10 of stock) | 1 ug/uL | 3 uL |

  2. Allow plasmid to digest at 37°C for ~ 3-4 hours.
  3. Heat inactivate reaction at 65°C for 15 minutes (the temperature and time is specific per enzyme), then add 1uL 15% SDS and 1.5uL proteinase K (20mg/mL). *Since our SDS was very old, I ordered more, which is prepared as a 10% solution. This can be used as 20x (so for a 30uL digest, use 1.5uL).*
  4. Incubate for 30 minutes at 50°C. During incubation, prepare a 1% agarose gel.
  5. Run ~ 5uL of the digest alongside an uncut plasmid on 1% agarose gel to confirm the digest was complete.
### Phenol/Chloroform Extraction
 1. Transfer restriction digestion product to a 1.5mL tube.
 2. Dilute product by adding 175uL water - toal volume 200uL. This provides a more workable amount of product for extraction steps.
 3. Add 200uL of phenol/chloroform.
 4. Vortex for 1 minute.
 5. Spin at top speed for 2 minutes.
 6. Transfer upper aqueous layer to a fresh tube.
 7. Add 200uL of Chloroform.
 8. Vortex for 1 minute.
 9. Spin at top speed for 2 minutes.
 10. Trasfer upper aqueous layer to a fresh tube.
### Ethanol Precipitation
 1. Thaw pellet paint NF co-precipitant and 3 M Na Acetate, pH 5.2, and bring to room temperature.
 2. Add 2uL pellet paint to sample, followed by 0.1 volume (~20uL) 3 M Na Acetate, pH 5.2.
 3. Add 2 volumes (400uL) of EtOH (100% molecular biology grade). Vortex briefly. Incubate at room temperature for 2 minutes.
 4. Spin sample in microcentrifuge at top speed for 5 minutes.
 5. A dark blue pellet should be visible at the bottom of the tube. Remove as much of the supernatant as possible, without disturbing the pellet.
 6. Wash pellet with 1mL 70% EtOH. Vortex briefly. Spin as in Step 4.
 7. Wash pellet with 1mL 100% EtOH. Vortex briefly. Spin as in Step 4.
 8. **Remove supernatant. Dry pellet in vacuum centrifuge or at 90°C on a heat block.**
 9. Resuspend pellet in deionized water (20-50uL is recommended). You will use ~1ug of this template in the in-vitro transcription reaction.
 10. Quantify linearized DNA using Nanodrop.
 11. Store sample in the freezer at -20°C overnight.
### Transcription Reaction
1. Thaw the frozen reagents: Place the RNA Polymerase Enzyme Mix on ice, and vortex the 10X Reaction Buffer until it is completely in solution.
2. Once thawed, store the ribonucleotides on ice, **but keep the 10X ReactionBuffer at room temperature** while assembling the reaction.
3. All reagents should be microfuged briefly before opening to prevent loss and/or contamination of material that may be present around the rim of the tube.
4. Assemble transcription reaction **at room temperature**. Add reagents in the order shown in the table below. You will use ~1ng linear template DNA (calculate according to cencentration from Nanodrop).
5. Mix thoroughly. Flick the tube or pipette the mixture up and down gently, and then microfuge the tube briefly  to collect the reaction mixture at the bottom of the tube.
6. Incubate at 37°C for 4 hours.
7. Add 1uL of TURBO DNase and mix well.
8. Incubate at 37°C for 15 minutes. Proceed immediately to next steps.
Example reaction:

| Component | Volume |
|----------:|--------|
| ATP solution | 2 uL |
| CTP solution | 2 uL |
| GTP solution | 2 uL |
| UTP solution | 2 uL |
| 10X reaction buffer | 3 uL |
| 1ug linear template DNA | 10 uL |
| DEPC water | 7 uL |
| Enzyme mix | 2 uL |
| Total Volume | 30 uL |

### Phenol/Chloroform Extraction and Isopropanol Precipitation
 1. Transfer transcription product to 1.5mL tube.
 2. Add 115uL water and 15uL Ammonium Acetate Stop Solution and mix thoroughly.
 3. Add 160uL of phenol/chloroform/isoamyl alcohol.
 4. Vortex for 1 minute.
 5. Spin at top speed for 2 minutes.
 6. Transfer upper aqueous layer to a fresh tube.
 7. Repeat steps 3-6.
 8. Add 160 uL of isopropanol.
 9. Vortex for 1 minute.
 10. Spin at top speed for 2 minutes.
 11. Transfer upper aqueous layer to a fresh tube.
 12. Add 160uL of isopropanol.
 13. Mix, let sit at room temperature for 2-5 minutes.
 14. Spin at top speed for 10 minutes.
 15. Pipette off supernatant and dissolve pellet in 100uL of water containing RNase-out.
### Calculate Concentration of Transcript
1. Test the transcript three times using the Nanodrop and the Qubit. We have determined that the Qubit is more sensitive and accurate than the Nanodrop, so this is the one we have been using for calculations.
2. Determine the molecular weight of the transcript using an online calculator (here is a good one: [Northwestern U](http://biotools.nubic.northwestern.edu/OligoCalc.html)).
3. Calculate the concentration using this formula:
-  Copy Eq/µl= (concentration in ng/µl)(6.022 × 1023 copy Eq/mol)/(molecular weight in g/mol)(1 × 109 ng/g)
4. **Dilute transcript using DEPC water with RNase out to desired concentration (3 x 108 copy Eq/uL) and store in single-use aliquots at -80°C.**
### Characterization
1. Test the IVT by standard qRT-PCR procedure. Test multiple independent dilution series in duplicate. Ideally, you will test the new IVT alongside the old IVT to directly compare their performance within the same qRT-PCR assay.
2. Run IVT on Bioanalyzer to confirm the size of the RNA and that there is a single band.


