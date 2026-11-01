# Intimate Partner Violence in Pregnancy-Associated Violent Deaths

**Narrative coding and machine learning in the National Violent Death Reporting System, 2019 to 2023**

Mario Morales, PhD, MPP, MA; Egoitz Laparra, PhD; Maeve E. Wallace, PhD, MPH
University of Arizona

This repository accompanies a manuscript in preparation for journal submission. It describes the study, its methods and its main results, and holds a narrated explainer video in English and Spanish. The analysis was presented at the APHA 2026 Annual Meeting (Injury Control and Emergency Health Services, Late Breaker Presentations, abstract 603379, 2 November 2026).

- Analysis plan registered before any estimate was computed: Open Science Framework, [doi:10.17605/OSF.IO/3TJHR](https://doi.org/10.17605/OSF.IO/3TJHR)
- Status: manuscript in preparation; results may be refined before publication. The published article will be linked here.

## Explainer video

| Language | File | Length |
|---|---|---|
| English | [`video/IPV_Methods_Explained_v4.mp4`](video/IPV_Methods_Explained_v4.mp4) | 40 min 38 s |
| Spanish (Mexico) | [`video/IPV_Methods_Explained_v4_ES.mp4`](video/IPV_Methods_Explained_v4_ES.mp4) | 43 min 09 s |

Full narration scripts, with the start time of every passage: [`video/IPV_Methods_Explained_v4_Narration.md`](video/IPV_Methods_Explained_v4_Narration.md) (English) and [`video/IPV_Methods_Explained_v4_Narracion_ES.md`](video/IPV_Methods_Explained_v4_Narracion_ES.md) (Spanish). The video explains every method in plain language, cites the studies it builds on, and lists full references at the end. No death narrative and no count below 10 appears in it.

## Background

Homicide, suicide, and drug overdose are leading causes of death during pregnancy and the first year postpartum in the United States, and intimate partner violence (IPV) is a risk factor for each. The National Violent Death Reporting System (NVDRS) links death certificates with coroner or medical examiner and law enforcement reports, but its structured IPV field is restricted to homicides by the coding manual, so it is nearly empty for suicides and deaths of undetermined intent.

## Aims

1. Estimate the proportion of pregnancy-associated homicides, suicides, and deaths of undetermined intent related to IPV, by reading the death investigation narratives.
2. Evaluate whether a machine learning classifier trained on that reading can reproduce it for all deaths.
3. Describe the mental health, substance use, and legal circumstances that co-occur with IPV.

## Design and methods

- **Data.** NVDRS Restricted Access Database, 2019 to 2023, obtained from the Centers for Disease Control and Prevention under a data sharing agreement. Female decedents aged 10 to 44 years whose death certificate pregnancy checkbox indicated pregnancy at death or within 1 year before death: 1,391 deaths, 1,180 with known circumstances (primary analysis).
- **Outcome.** IPV as a precipitating or contributing factor in the death, following the CDC uniform definitions (physical, sexual, or psychological violence, coercive control, or stalking by a current or former partner).
- **Sample and reading.** A stratified random sample of 400 of the 1,180 deaths; both narratives of each sampled death read twice, independently, with joint adjudication of disagreements. Weighted proportions describe all 1,180 deaths; 95% CIs by a rescaled bootstrap for stratified sampling without replacement.
- **Classifier.** Four families (regularized logistic regression, linear support vector machine, random forest, gradient-boosted trees) trained on weighted words and two-word sequences, phrase indicators, and structured variables; nested cross-validation; the 2023 deaths locked for a single test against seven prespecified thresholds.
- **Classifier-assisted estimate.** Design-based supervised learning: cross-fitted predictions for all deaths, corrected by the weighted difference between the human reading and the predictions in the random sample, which keeps the estimate unbiased however imperfect the classifier.
- **Circumstances.** One logistic model per domain, adjusted for age, race and ethnicity, pregnancy timing, year, and the share of deaths at the same reporting site with the circumstance; associations are descriptive.
- **Confidentiality.** No cell below 10 deaths; complementary suppression; a joint audit of all released tables by linear and integer programming.

## Main results

- IPV was related to **45.8%** (95% CI, 43.2%-48.4%) of the 1,180 deaths with known circumstances, exceeding the share recorded in the structured field (hypothesis supported).
- The proportion was highest among women who died while pregnant: 52.1% (95% CI, 48.3%-56.1%).
- In a validation sample of 150 further deaths, every death with IPV recorded in the structured field was IPV-related in both readings, but the field missed roughly 1 in 5 of the deaths read as IPV-related, including suicides.
- The selected classifier (gradient-boosted trees) met every prespecified threshold in the 2023 test; in nested cross-validation of all 400 coded deaths, its area under the curve was 0.91 (95% CI, 0.88-0.93).
- Applied to all 1,180 deaths and corrected with the human readings, the classifier estimated **44.6%** (95% CI, 41.9%-47.3%), 1.2 percentage points below the reading-based estimate.
- Reading the narratives of the 211 deaths without known circumstances identified further IPV-related deaths; across all 1,391 deaths, the proportion was less than 1 percentage point above 38.9%.

Confidentiality rules under the data sharing agreement prevent separate estimates for all homicides, all suicides, and racial and ethnic groups. All results are those of the manuscript in preparation and may be refined before publication.

## Repository contents

```
README.md          this description
CITATION.cff       how to cite this work
LICENSE            license of the text and video
video/             explainer videos (English, Spanish) and their narration scripts
```

The analysis code will be added with synthetic example data, because NVDRS records are available only to approved researchers under a data sharing agreement.

## Data availability

NVDRS Restricted Access Database data are available from the CDC to approved researchers under a data sharing agreement. This repository contains no NVDRS record, narrative, or count below 10.

## Ethics

The University of Arizona Institutional Review Board determined that this analysis of deidentified records of deceased persons is not human subjects research (STUDY00008360).

## Funding

Eunice Kennedy Shriver National Institute of Child Health and Human Development, award 2R01HD096070 (principal investigator, Dr. Wallace). The content is solely the responsibility of the authors and does not necessarily represent the official views of the National Institutes of Health.

## How to cite

Morales M, Laparra E, Wallace ME. Intimate partner violence in pregnancy-associated violent deaths: narrative coding and machine learning in the National Violent Death Reporting System. Manuscript in preparation; 2026. Analysis plan: doi:10.17605/OSF.IO/3TJHR.

## Contact

Mario Morales, Department of Health Promotion Sciences, Mel and Enid Zuckerman College of Public Health, University of Arizona, Tucson, AZ (mariomorales@arizona.edu).

## License

Text and videos: Creative Commons Attribution 4.0 International (CC BY 4.0). See [`LICENSE`](LICENSE).
