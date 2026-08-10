# Industrial Waste CO₂ Mineralization

A research portfolio documenting an experimental process for recovering calcium from steelmaking and cement wastes and converting captured CO₂ into precipitated calcium carbonate (CaCO₃).

## Project overview

Steel and cement production generate large mineral residues containing calcium-bearing phases. This project investigated whether those residues could serve as secondary calcium resources for indirect CO₂ mineralization.

The experimental route combined acid extraction, staged pH-swing purification, alkaline CO₂ capture, and carbonation. The work focused on the chemical and process conditions governing calcium recovery, impurity removal, CO₂ absorption, and CaCO₃ precipitation.

> **Scope:** This repository presents my experimental and process-engineering contribution. Detailed raw data and partner-confidential information are not published here.

## Research objective

To develop and assess an aqueous process that:

- extracts calcium from industrial mineral wastes;
- removes dissolved metal impurities by controlled pH adjustment;
- captures CO₂ in an alkaline solution; and
- precipitates stable CaCO₃ from purified calcium-rich liquor.

## Materials investigated

| Industrial residue | Source sector | Role in the study |
|---|---|---|
| Basic oxygen furnace (BOF) slag | Steelmaking | Calcium extraction and mineralization |
| Blast-furnace (BF) slag | Ironmaking | Calcium extraction screening |
| Ladle slag | Secondary steelmaking | Calcium extraction screening |
| Cement-kiln dust (CKD) | Cement production | Calcium extraction and mineralization |

## Process route

![Experimental process flow for indirect CO₂ mineralization](figures/process-flow.png)

[View the editable SVG version](figures/process-flow.svg)

The complete research concept also considered reagent regeneration by electrodialysis. That regeneration step is part of the wider process concept and is not presented here as completed experimental work.

## Experimental programme

### 1. Calcium extraction

Organic and inorganic extraction agents were screened to understand the trade-off between calcium recovery and dissolution of competing elements. Temperature, contact time, reagent concentration, and solid-to-liquid ratio were evaluated.

For BOF slag, a selected condition of **2 M HCl, 80 °C, and 30 min** produced **91% calcium extraction**. The result established a high-recovery basis for the downstream purification study.

### 2. pH-swing purification

The leachate contained calcium together with dissolved impurities. NaOH was added in controlled stages so that metals with lower hydroxide solubility precipitated before the calcium-rich solution entered carbonation.

This stage was treated as a separation problem, not simply as pH adjustment: impurity removal had to be increased without causing excessive calcium loss.

### 3. CO₂ capture

CO₂ was absorbed into recirculating NaOH solution to form a carbonate-rich liquor for the mineralization step. Gas flow, liquid volume, NaOH concentration, and circulation rate were examined.

A high-concentration condition using **20 L of 2 M NaOH at 3 L min⁻¹** achieved **more than 97% CO₂ capture**, but required approximately **5 t NaOH per t CO₂**. A lower-concentration condition using **10 L of 0.5 M NaOH at 3 L min⁻¹** reduced demand to approximately **0.98 t NaOH per t CO₂**. This comparison exposed the central recovery-versus-reagent-consumption trade-off.

### 4. Carbonation

The purified calcium-rich liquor was mixed with the carbonate-rich absorbent to precipitate CaCO₃. Product formation was verified using complementary solid and liquid analytical methods.

Tests using 1 L of purified solution produced approximately **1.80 g CaCO₃ from the steel-derived route** and **1.94 g CaCO₃ from the cement-derived route**, with approximately **95% precipitation performance** under the selected conditions.

## Selected findings

| Process stage | Selected result | Engineering interpretation |
|---|---:|---|
| BOF-slag extraction | 91% Ca extracted | Strong calcium recovery was possible under the selected HCl condition |
| CO₂ absorption | >97% capture | High capture was achievable, but reagent intensity remained a scale-up constraint |
| Reduced-caustic absorption | ~0.98 t NaOH/t CO₂ | Lower NaOH concentration substantially improved reagent demand |
| Carbonation | ~95% precipitation | Purified leachate could be converted into a solid carbonate product |
| Theoretical mineralization potential | 79.15 kg CO₂/t BOF slag; 85.30 kg CO₂/t CKD | Feed composition controlled the upper limit of CO₂ storage |

## Analytical methods

The experimental programme used:

- X-ray fluorescence (XRF) for bulk elemental composition;
- X-ray diffraction (XRD) for crystalline phases;
- inductively coupled plasma optical emission spectroscopy (ICP-OES) for dissolved metals;
- scanning electron microscopy with energy-dispersive X-ray spectroscopy (SEM-EDS) for morphology and local composition;
- thermogravimetric analysis (TGA) for carbonate-product assessment; and
- gas analysis for CO₂ capture measurements.

## My contribution

I designed and conducted laboratory experiments across extraction, purification, CO₂ capture, and carbonation; interpreted solid and liquid analytical results; developed process mass-balance and scale-up calculations; identified reagent consumption as a major deployment constraint; and communicated the findings through technical reporting, industrial-partner meetings, and conference presentation.

This work received **third place in the UKCCSRC Early Career Researcher poster competition**.

## Repository structure

This repository is being developed as a transparent research portfolio. Planned additions include:

```text
industrial-waste-co2-mineralization/
├── README.md
├── figures/
│   └── process-flow.png
├── data/
│   └── selected-non-confidential-results.csv
├── analysis/
│   └── mass-balance-and-performance-calculations
└── docs/
    └── methods-and-research-summary
```

## Limitations

The reported work was conducted at laboratory scale. The results do not by themselves establish commercial feasibility. Further development should address reagent regeneration, water demand, solids handling, impurity management, continuous operation, and validation at larger scale.

## Author

**Abbas Rajaei**  
Chemical Engineer | Process Development, Decarbonization, and Industrial Operations  
[GitHub profile](https://github.com/abbasrajaei)
