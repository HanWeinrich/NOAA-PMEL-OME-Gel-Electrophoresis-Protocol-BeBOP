---
#MIOP terms
methodology_category: Gel electrophoresis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols
purpose: electrophoresis [OBI:0600053]
analyses: electrophoresis [OBI:0600053]
geographic_location: North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024]
environmental_medium: sea water [ENVO:00002149], tissue [UBERON:0000479], planktonic material [ENVO:01000063]
target: PCR product [OBI:0000406]
creator: Shannon Brown, Han Weinrich, Kenna Dailey 
materials_required: agarose gel electrophoresis system [OBI:0001134]
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 165
personnel_required: 1
language: en
issued: 2025-11-06
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies

# FAIRe terms
pcr_method_additional: Quality was validated via confirmation of a product on a gel
amp_vis_method: gel electrophoresis
detection_criteria: visible band on the gel
---

# NOAA PMEL OME Gel Electrophoresis Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-05-22|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-05-22|
| Kenna Dailey  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0008-5542-5336 |2025-05-22|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
|D2 and D3-14 Horizonal Electrophoresis Systems User Manual| [Operating and Maintenance Manual 7007320 Rev. 1](https://assets.thermofisher.com/TFS-Assets/LED/manuals/D21305~.pdf)| Rev. 1|2012-09-10| External|

### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-06-04 | Initial release |
| 1.0.0 | 2025-11-06 | Minor revisions to author list and safety guidelines |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|CICOES| Cooperative Institute for Climate, Ocean, and Ecosystem Studies|
|DNA| Deoxyribonucleic acid |
|EtOH| Ethanol|
|NOAA|National Oceanic and Atmospheric Administration|
|OME| Ocean Molecular Ecology|
|PCR  | Polymerase chain reaction  |
|PPE | Personal protective equipment |
|PMEL |Pacific Marine Environmental Laboratory|
|RO| Reverse osmosis|
|TAE | Tris Acetate |
|UV| Ultraviolet|
|UW| University of Washington

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
|Agarose gel| The matrix used to separate DNA fragments by size during gel electrophoresis.|
|Band| The visible groupings of DNA fragments in a gel after electrophoresis, representing molecules of similar size.
|Comb| A plastic piece with multiple prongs inserted into liquid agarose to create wells.|
| DNA ladder| A mixture of DNA fragments of known sizes, used as a reference to estimate the sizes of unknown DNA fragments in the gel. |
|Electrophoresis| A laboratory technique that applies an electric field to a gel matrix to separate molecules (such as DNA) by size. This is also used to determine if amplification of DNA was successful.|
| GelRed| A fluorescent nucleic acid stain that binds to DNA and allows it to be visualized under UV or blue light. |
| Gel rig| A device that holds the agarose gel and buffer solution, equipped with electrodes to apply an electric field for DNA migration. |
|Loading dye | A solution containing tracking dyes that migrate through the gel to indicate electrophoresis progress.|
| Gel reader| An instrument used to visualize DNA bands after electrophoresis by illuminating the gel with UV or blue light.|


## BACKGROUND

### Summary

Gel electrophoresis is commonly used to assess PCR product yield and PCR amplification success. This gel electrophoresis protocol is used by the NOAA PMEL Ocean Molecular Ecology (OME) Group.

### Method Description and Rationale

Gel electrophoresis is a technique used to separate DNA based on its size and charge. When an electric field is applied, DNA molecules migrate through a gel matrix, with smaller molecules moving faster than larger ones. This allows for the size separation of DNA molecules within a mixture - aggregating DNA fragments of similar size and enabling their visualization and identification. The gel is typically stained with a dye and illuminated with UV light to visualize the separated molecules. A DNA ladder containing quantized fragments at set sizes is often run alongside DNA to aid in categorizing DNA fragment aggregations ("bands") by size.

We intentionally chose this protocol as the methodology is widely selected for its simplicity, reproducibility, and ability to provide clear, accurate results. It is an accessible and cost-effective technique commonly used in molecular biology labs.

### Spatial Coverage and Environment(s) of Relevance

While this gel electrophoresis protocol itself is not directly tied to a specific geographic region, it has been used to assess the quality of amplification of DNA from samples collected in diverse environments, including coastal and oceanic stations in the Northeastern Pacific Ocean, Bering Sea, and Arctic Ocean. The DNA analyzed using this method may originate from surface ocean (epipelagic biome) to near-bottom (benthic biome) environments, covering a range of habitats from coastal to offshore regions.

### Personnel Required

One person with molecular biology experience.

### Safety

This protocol uses bleach and ethanol, both of which are classified as hazardous chemicals. Appropriate PPE must be worn, and standard safety procedures should be followed to avoid skin and eye exposure.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique, pipetting small volumes, and running a gel reader) is required to conduct this protocol.

### Time Needed to Execute the Procedure

Preparation of a single 100-well (large) gel takes about 60 minutes. The run time of a large gel is 90 minutes plus the 5-10 minutes required to read the gel. In total, ~160 minutes. Additional gels can be run simultaneously without greatly increasing the time required.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For one large gel (96 samples plus 4 ladder wells)

| DESCRIPTION                              | PRODUCT NAME AND MODEL                              | MANUFACTURER            |  QUANTITY                                                                                                                                                       | REMARK |
| ---------------------------------- | -------------------------- | -------------- | -------------------------------------------| -------- |
| **Durable equipment** |  |  |  |  |
| Scale | Velab VE-CB500 balance scale | Uline | 1 | Can be substituted with generic |
| Small gel rig | EasyCast B1A mini gel electrophoresis System | Thermo Scientific | 1 | One gel rig is acceptable, but having multiple can expedite the protocol. This rig is used when there are fewer than 22 samples. |
| Medium gel rig | Owl D2 wide-gel electrophoresis system | Thermo Scientific | 1 | One gel rig is acceptable, but having multiple can expedite the protocol. This rig is used when there are between 22-44 samples. |
| Large gel rig | Owl D3-14 horizontal gel electrophoresis system | Thermo Scientific | 1-2 | Can be subsituted with generic. This rig is used when there are more than 44 samples. |
| Power supply | EC 300 XL power supply | Thermo Scientific | 1 | Can be substituted with generic |
|Large gel caster | D3-CST-14 External Gel Caster | Thermo Scientific | 1 | Can be substituted with generic if it fits the large rig. For large rig only.|
|Medium gel caster | D2-CST External Gel Caster | Thermo Scientific | 1 | Can be substituted with generic if it fits the medium rig. For medium rig only.|
| Pipettor: 20 - 200 μL | Pipetman P200L | Gilson | 1 | Can be substituted with any accurate pipettor |
| Pipettor: 0.5-10 μL | Pipetman P10L | Gilson | 1 | Can be substituted with any accurate pipettor |
| Plate spinner | Salad spinner | Cuisinart | 1 | Can be substituted with generic or plate centrifuge |
| Foil roller | Rubber roller | Generic | 1 |  |
| Wash bottles | Safety wash bottle 500 mL for ethanol and bleach | VWR | 2 | Can be substituted with generic, but recommend purchasing different colored bottles for each reagent. Must be sterilized before use. |
| 1000 mL Pyrex | 1000 mL round media storage bottle, screw cap | Pyrex | 2 | One for fresh 1x TAE and one for used 1x TAE; can be substituted with generic type 1, Class A borosilicate glass bottle with thermal and chemical resistance |
| 500 mL Pyrex | 500 mL round media storage bottle, screw cap | Pyrex | 1 | Can be substituted with generic type 1, Class A borosilicate glass bottle with thermal and chemical resistance |
| Heat resistant gloves | High temperature oven gloves | Generic | 1 |  |
| 1000 mL graduated cylinder | 1000 mL graduated cylinder | Generic | 1 | Can be substituted with generic; for making 1X TAE |
| Gel reader | UVP GelStudio | Analytikjena | 1 | Can be substituted with generic |
| **Optional Equipment**|  |  |  |  |
| Pipettor: 0.15-10 μL | Pipetman P10L | Gilson | 1 | For use with non-filtered tips |
| 10 μL pipette tips | TipOne 10 μL XL natural graduated pipette tips | USA Scientific | 1 | Non-filtered |
| 8-channel multichannel pipetter: 1-10 μL | Pipetman multichannel P8X10 | Gilson | 1 | Can be substituted with generic; not required but reduces protocol time |
|PCR plate rack | PCR tube rack for 0.2 mL micro-tubes | Fisher Scientific | 1 | Can be substituted with generic |
| 10 μL non-filter pipette tips | TipOne pipette tips 10 μL XL graduated | USA Scientific | 12 | Can be subsituted with generic |
| **Consumable equipment** |  |  |  |  |
| Lab notebook |  | Generic | 1 | Dedicated lab notebook for the space |
| Kimwipes | Delicate task wipes | Kimtech | 5 wipes | Can be substituted with generic; must be lint-free |
| Nitrile gloves | Powder free nitrile gloves | Fisher Scientific | 8 pairs | Can be subsituted with generic nitrile gloves |
| 200 μL pipette tips | TipOne RPT filter tips 200 μL graduated | USA Scientific | 4 | Can be subsituted with generic; must be sterile and filtered |
| 10 μL filter pipette tips | TipOne RPT filter tips 10 μL graduated | USA Scientific | 96 | Can be subsituted with generic; must be sterile and filtered |
| Writing utensils | Sharpies and pen | Generic | 2 | Dedicated to the lab space |
| PCR Aluminum Foil | Adhesive sterile PCR foil seals | VWR | 1 | Can be subsituted with generic; must be sterile |
| Parafilm | M lab film | Parafilm | 50 cm |  |
| 1.5 mL tube | Snap cap DNA LoBind 1.5 mL tubes, PCR-clean | Eppendorf | 1 | Can be substituted with generic |
| PCR tube strips | PCR 8-Strip Clear Tubes, PCR-clean | Fisher Scientific | 1 | Can be substituted with generic |
| Weigh boat | Polystyrene sterile weight dishes | Generic | 1 |  |
| **Chemicals** |  |  |  |  |
| Agarose | Molecular biology grade Agarose LE | Hoefer | 1.5 g |  |
| 50X TAE buffer | Tris acetate buffer | Quality Biological | 20 mL |  |
| RO water | Reverse osmosis water | Generic | 980 mL |  |
| GelRed | GelRed nucleic acid gel stain 10,000X in water | Biotium | 15 μL | GelRed is light sensitive and should be stored in a dark place |
| Ladder | 100 bp DNA ladder | GeneRuler | 2.8 μL |  |
| RNA/DNA-free water | UltraPure™ DNase/RNase-free distilled water | Invitrogen | 192 μL |  |
| 6X loading dye | DNA gel loading dye (6X) | ThermoFisher Scientific | 116 μL |  |
| 70% EtOH | Molecular grade ethanol | Generic | 20 mL |  |
| 10% bleach | Hypochlorite bleach | Clorox | 10 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

## STANDARD OPERATING PROCEDURE


### Preparation

To minimize the risk of cross-contamination, this protocol should be carried out in a dedicated space for post-PCR product handling, separate from areas designated for low-biomass bench work. Equipment should not be shared between spaces.

The benches and equipment should be wiped down with 10% bleach, followed by 70% EtOH. This cleaning procedure ensures the removal of potential contaminants, maintaining the integrity of the results. Additionally, it is recommended to use dedicated pipettes, filter tips, and other consumables specific to post-PCR.

#### Loading Dye

Prepare several PCR tube strips of working stock dye and store in the fridge. Add 60 μL dye + 100 μL RNA/DNA-free water to the tube strip, creating a diluted dye mixture.

#### Ladder

Ladder can be pre-made by adding 14 μL 100 bp ladder + 80 μL RNA/DNA-free water + 14 μL dye to a 1.5 mL tube (store in fridge). Carefully label ladder tube with date, initials, and contents. A single-use ladder can also be prepared before loading.

* **Single-Use Ladder**: 0.7 μL ladder + 4 μL RNA/DNA free water + 0.7 μL 6x dye

#### 1X TAE Buffer

Enough 1x TAE buffer - both for filling the gel rig and for making the gel - is required before beginning the procedure. To make 1000 mL of 1x TAE, mix 50x TAE buffer with RO water in a 1:50 concentration. For example, 20 mL 50x TAE + 980 mL of RO water in a 1000 mL Pyrex.

#### Gel Rig Set-Up

Gather the appropriate gel combs depending on the number of samples being loaded. There should be a well for each sample, along with at least 2-4 spaces for ladder (2 ladder wells per row of samples is recommended).

Squeeze the gel tray into the corresponding rig or external gel caster (depending on the size and brand of the rig). Make sure gaskets are snug and not kinked or extruded; use 1x TAE to wet and lubricate if needed. Ensure that the gel tray is on a flat surface and level.


### Making a Gel

To make a 1% agarose gel:

1. Measure an appropriate volume of 1x TAE using a 1000 mL graduated cylinder and add to a clean 500 mL Pyrex. Use a scale to measure agarose on a weigh boat. Add agarose to 1x TAE, then swirl to mix in agarose before heating. Quantities of TAE and agarose will vary depending on the size of the rig used. 

| Rig size | 1x TAE | Agarose|
| ----- | ----- | ----|
| Small | 60 mL  | 0.6 g
| Medium |  80 mL | 0.8 g|
| Large | 150 mL | 1.5 g|

2. Microwave the Pyrex with TAE and agarose mixture on high until it begins boiling. Put on heat-resistant gloves, remove the Pyrex from the microwave, and swirl gently. Heat until the mixture is completely dissolved with no visible particles - this may take multiple rounds. Do not allow the mixture to remain at a boil for more than 30 seconds, as the mixture may boil over the rim of the Pyrex.
3. Allow agarose mixture to cool to touch temperature (i.e., cool enough to hold comfortably or ~55 °C). Large gels take 20-25 minutes. Swirl occasionally to prevent gel from congealing around the edges of the container. If necessary, cooling can be expedited by running the exterior of the Pyrex under cool water after 10 minutes. 
4. Remove GelRed from dark storage and spin down if needed. Add GelRed to cooled agarose mixture using a 0.5-10 μL or 20-200 μL pipette, depending on rig size. Swirl into the solution.

| Rig size | GelRed | 
| ----- | ----- | 
| Small | 6.0 µL GelRed | 
| Medium |  8.0 µL GelRed | 
| Large | 15 µL GelRed | 

5. Pour into the gel rig, place appropriate gel combs, and allow to solidify for 20-30 min. Rinse Pyrex with water 2-3 times to prevent residual gel from solidifying inside. 

6. Once the gel is solidified, gently remove the gel tray from the mold or position in the tray and place the gel into the gel rig.
7. Fill rig with 1x TAE. Ensure 1x TAE is completely covering the gel. Remove combs gently.


**Note:** 1X TAE used in the gel rig can be reused multiple times. Used 1X TAE can be left in the gel rig for several days if covered between uses to prevent dust and contaminant deposition. Before extended gaps between uses (more than a few days), return used TAE to a 500 mL pyrex bottle. Replace 1X TAE once it turns blue or if it becomes filled with particulates. Used 1x TAE should not be used to make new agarose gels.

### Loading a Gel

1. Load ladder lanes by pipetting 5.4 μL of pre-made ladder into each corresponding ladder well or following the recipe for a single-well ladder preparation.
    * For large gels, we place a ladder in each corner (4 in total). 
     * Non-filtered pipette tips can be used **only** for this step, as there is no PCR product.

2. Spin down the PCR plate, double-checking how many wells are filled with PCR product and checking for evaporation.

3. Cover the PCR plate rack with parafilm. Gently push parafilm into divots on the PCR plate rack to create wells for dye. This is an optional step, but it helps ensure samples stay separate.
4. Use a 0.5-10 μL pipette to pipette 3.2 μL of diluted dye mixture onto parafilm. Prepare one drop of dye for each sample being loaded.
    * A multichannel pipette can be used for this step.
    * Non-filtered pipette tips can be used **only** for this step. If using these tips, it is recommended to also use a dedicated pipette.

5. Pull back the foil of the PCR plate. We pull back three columns at a time to prevent cross-contamination and evaporation. Pipette 2 μL PCR product into the dye, mix by pipetting up and down ~4 times.

6. Load gel (5.2 μL total). Begin loading with A1 (leftmost well in your first row, next to the ladder well). If using a multichannel pipette, go column by column in the PCR plate, starting with A1 through H1. This will fill every other well. 
    * Gently lower the tip below the surface of the buffer, hovering at the entrance of the well, and slowly dispense the sample into the well without piercing the gel.
   * Change pipette tips between samples to prevent contamination.

### Running a Gel


1. Place the lid securely on the gel rig. DNA is negatively charged and will migrate toward the positive electrode during electrophoresis. Ensure that the gel is oriented correctly. Commonly, the red cable connects to the positive electrode and the black cable connects to the negative electrode.

3. Set power supply to 65 volts (5V per cm) and run for 45-90 minutes, pending gel size.

**Gel Electrophoresis Program**: 

| Rig size | Voltage | Duration |
| ----- | ----- | ----- |
| Small | 40 | 45 minutes |
| Medium | 50 | 60 minutes |
| Large | 65 | 90 minutes|

### Reading a Gel

This methodology is specific to the Analytikjena UVP GelStudio reader.

1. Power on the gel reader. Open the door, pull out the shelf, and then shift the UV plate slightly forward to add gel. Push the UV plate back into position and close the door.
    * Large gels may run off the glass area of the plate; start with the gel shifted to the right.
3. Open VisionWorks software and click on DNA Gel Electrophoresis.
4. On the right side of the screen, click the light and turn on the UV/Blue light. Then click filters, and turn on Ethidium Bromide (EtBr). Return to the camera.
5. Next, use the camera to live view on manual to view the gel. Suggest playing with exposure (seconds) and settings under the lens tab (i.e., brightness). This allows you to see what looks best for taking a photo for subsequent annotation of the gel. 

5. Take a photo by clicking the camera icon in the bottom right corner.
    * To save the photo, go to File, then Export for Publication. Save as PNG. Saving as a JPEG or TIFF reduces resolution or leads to issues with brightness, respectively. 
    * Add to the corresponding folder and name appropriately.
    * If a large gel runs off the screen that you capture two photos (i.e., the full gel).
    
6. Use a spatula to scoop gel off of reader, and dispose of the complete gels. Wipe down the gel reader with a kimwipe. 
7. Rinse the rig with freshwater. Recommend performing a more extensive wash every ~2 weeks. The gel tray should be washed and wiped down after every use.

### Basic Troubleshooting Guide

**Issue 1**: Bubble present in the gel

**Solution**: You can use a pipette tip to gently push the bubble to the edge of the gel so it does not interfere with reading the gel.

**Issue 2**: No bands visible

**Solutions**: There could be various reasons for no bands being visible in the gel.
* Pipetting error
    * Double-check technique; make sure the tip is inside the well when dispensing.
    * Verify that the correct volume of sample and loading dye was used. 
    * Ensure DNA was properly mixed with loading dye before loading.
* Gel issue
    * Ensure GelRed was added at the proper concentration.
    * Keep GelRed protected from light to prevent degradation.
* Gel reader settings
    * Confirm that the correct light source (UV or Blue) and filter (EtBr) are being used.
    * Adjust the exposure settings to improve band visibility.

**Issue 3**: No ladder visible

**Solution**: The most likely reason for no ladder being visible is due to a possible lack of adding GelRed when preparing the agarose. 
