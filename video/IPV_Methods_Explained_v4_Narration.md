---
output:
  word_document:
    reference_docx: "C:/Users/yerid/Documents/reference_doc.docx"
---

**IPV_Methods_Explained_v4.mp4: Narration Script**

Version 1. 1 November 2026. Working file generated from the storyboard of the video. Every passage below is the text spoken in the state that carries its number.

Pause of 0.8 seconds after each passage, except the two key findings, which are preceded by silence and spoken more slowly.

**Chapter 1. Why this study**

**Slide 1 (s01). Intimate partner violence in pregnancy-associated violent deaths**

*A study of the National Violent Death Reporting System, 2019 to 2023*

s01.1 (starts at 0:00). We made this video to present a study that the three of us, Mario Morales, Egoitz Laparra, and Maeve Wallace, carried out at the University of Arizona. We read the death investigation narratives of women who died by violence during pregnancy or within a year after it, and we asked how often those deaths were related to intimate partner violence.

s01.2 (starts at 0:25). We organized this account in five parts, from why we did the study to the work we planned next.

Source line on screen: Morales, Laparra and Wallace, manuscript, 2026

**Slide 2 (s02). Three leading causes of death during and after pregnancy**

*Why this study*

s02.1 (starts at 0:32). In our study, a pregnancy-associated violent death was a homicide, a suicide, or a drug overdose during pregnancy or within one year after it.

s02.2 (starts at 0:44). For decades, research from many states and from national vital statistics, including studies by Wallace and colleagues and by Margerison and colleagues, had identified homicide, suicide, and drug overdose as leading causes of death during pregnancy and the first year postpartum in the United States.

Source line on screen: Manuscript, Introduction

Citations on screen: Wallace and colleagues, 2016 and 2021; Margerison and colleagues, 2022; Wallace and Jahn, 2025

**Slide 3 (s03). Intimate partner violence runs through all three**

*Why this study*

s03.1 (starts at 1:06). Earlier research had linked intimate partner violence to each of the three.

s03.2 (starts at 1:12). In a multisite study by Campbell and colleagues, women abused by a partner faced a higher risk of being killed by that partner.

s03.3 (starts at 1:22). And work by Campbell and colleagues and by Zivin and colleagues found partner problems and abuse common among pregnancy-associated suicides and drug deaths.

s03.4 (starts at 1:33). Despite this evidence, how often violence by a partner contributed to these deaths remained uncertain, because the data used to count them were not designed to capture it.

Source line on screen: Manuscript, Introduction

Citations on screen: Homicide: Campbell and colleagues, 2003.  Suicide and drug deaths: Campbell and colleagues, 2021; Zivin and colleagues, 2024

**Slide 4 (s04). One death, three sources, one record**

*Why NVDRS*

s04.1 (starts at 1:46). We used the National Violent Death Reporting System, known as NVDRS. As Blair and colleagues described, it linked the death certificate, the coroner or medical examiner report, and the law enforcement report of every violent death in the participating states.

s04.2 (starts at 2:06). Its abstractors recorded whether intimate partner violence was related to each death. But the coding manual restricted that field to homicides and legal interventions.

s04.3 (starts at 2:18). So the structured record of partner violence in suicides and in deaths of undetermined intent was nearly empty, and studies that relied on it described homicides well and other deaths poorly.

Source line on screen: Manuscript, Introduction

Citations on screen: Blair and colleagues, 2016; NVDRS Web Coding Manual, version 6.1, CDC, 2025

**Slide 5 (s05). The narratives held what the fields missed**

*What reading the narratives had shown*

s05.1 (starts at 2:32). When other research teams read the narratives instead, they found partner violence that the structured fields had missed.

s05.2 (starts at 2:41). Among young people, Graham and colleagues found that narrative review identified nearly half of the deaths related to intimate partner violence that established coding would have missed.

s05.3 (starts at 2:54). In suicides across 43 states, a validated classifier built by Kafka and colleagues found partner violence that the structured fields did not record.

s05.4 (starts at 3:06). But these efforts examined one manner of death at a time, and the one study of pregnant women, by Lucea and colleagues, examined homicides alone.

Source line on screen: Manuscript, Introduction

Citations on screen: Graham and colleagues, 2022; Kafka and colleagues, 2023 and 2024; Lucea and colleagues, 2026

**Slide 6 (s06). Two developments made a fuller count possible**

*Why now*

s06.1 (starts at 3:17). Two developments made a fuller count possible. The pregnancy checkbox had been on every US death certificate since 2018, which allowed national identification of deaths during pregnancy and the postpartum period.

s06.2 (starts at 3:34). And statistical methods had become available that combined a classifier's labels for every death with human readings of a random sample of deaths. Every classifier makes mistakes, so counting its labels alone would push an estimate up or down. These methods, which Egami and colleagues called design-based supervised learning, compared the classifier with the human readings on the sampled deaths, measured how far off it was on average, and corrected the classifier's count by that average error, so its mistakes did not end up in the final number.

s06.3 (starts at 4:11). Our data covered deaths from 2019 to 2023, years in which the checkbox was in national use.

Source line on screen: Manuscript, Introduction and Methods

Citations on screen: Egami and colleagues, 2023

**Slide 7 (s07). Three aims and one hypothesis**

*Purpose*

s07.1 (starts at 4:21). Our first aim was to estimate the proportion of pregnancy-associated homicides, suicides, and deaths of undetermined intent related to intimate partner violence, using two independent readings of the death narratives.

s07.2 (starts at 4:37). We hypothesized that this proportion would exceed the share of deaths in which NVDRS abstractors had recorded intimate partner violence in the structured field.

s07.3 (starts at 4:49). Our second aim was to evaluate whether a machine learning classifier, trained on that reading, could reproduce it across all deaths.

s07.4 (starts at 4:59). Our third aim was to describe which mental health, substance use, and legal circumstances co-occurred with intimate partner violence.

Source line on screen: Manuscript, Introduction

**Chapter 2. What we did**

**Slide 8 (s08). Who was in the study**

*What we did: the cohort*

s08.1 (starts at 5:09). We used the NVDRS Restricted Access Database for deaths from 2019 to 2023, obtained from CDC under a data sharing agreement.

s08.2 (starts at 5:22). The cohort included female decedents aged 10 to 44 years whose death certificate pregnancy checkbox recorded pregnancy at death, within 42 days before death, 43 days to one year before death, or at an unspecified time. The upper age limit reduced false-positive checkbox entries, which a validation study by Catalano and colleagues had found concentrated at older ages.

s08.3 (starts at 5:52). Deaths were homicides, suicides, deaths of undetermined intent, or unintentional firearm injuries, 1,391 deaths in all. Unintentional firearm deaths were fewer than 10, so we combined them with deaths of undetermined intent in every table.

s08.4 (starts at 6:13). Circumstances were known for 1,180 of the deaths. The others lacked the structured fields that our sampling and models required, so the primary analysis used the 1,180.

Source line on screen: Manuscript, Methods and Table 1

Citations on screen: Upper age limit: Catalano and colleagues, 2020

**Slide 9 (s09). Two narratives for most deaths**

*What we did: the text*

s09.1 (starts at 6:28). For most deaths, NVDRS held two short narratives. One came from the coroner or medical examiner, and one came from law enforcement.

s09.2 (starts at 6:40). A coroner or medical examiner narrative existed for 94.2 percent of the 1,391 deaths, and a law enforcement narrative for 79.8 percent.

s09.3 (starts at 6:53). Under the data sharing agreement, no narrative ever left our encrypted, authorized computers.

Source line on screen: Manuscript, Table 1

**Slide 10 (s10). What counted as intimate partner violence**

*What we did: the outcome*

s10.1 (starts at 7:01). Our outcome was intimate partner violence as a precipitating or contributing factor in the death. We followed the CDC uniform definitions of Breiding and colleagues, which named physical, sexual, and psychological violence, coercive control, and stalking by a current or former intimate partner.

s10.2 (starts at 7:23). We distinguished it from violence by other family members, and from contact with a partner that involved no violence.

s10.3 (starts at 7:32). We recorded each death as related, not related, or uncertain. In the primary analysis, uncertain readings counted as not related, and in a sensitivity analysis, they counted as related.

s10.4 (starts at 7:48). For homicides, we could see whether a suspect was a current or former partner, but the narrative decided the code.

Source line on screen: Manuscript, Methods

Citations on screen: CDC uniform definitions: Breiding and colleagues, 2015

**Slide 11 (s11). A stratified random sample of 400 deaths**

*What we did: the sample*

s11.1 (starts at 7:56). We read a stratified random sample of 400 of the 1,180 deaths with known circumstances.

s11.2 (starts at 8:05). Homicides were split by whether abstractors had recorded intimate partner violence, and suicides by whether they had recorded an intimate partner problem. Deaths of undetermined intent formed their own group. This gave the sample enough deaths of each kind to train a classifier.

s11.3 (starts at 8:25). Some groups were sampled more heavily than others, so each coded death stood for the deaths of its group in proportion to the group's size, the weighting of Horvitz and Thompson. That was how our weighted proportions described all 1,180 deaths rather than the 400 we read.

s11.4 (starts at 8:45). This weighting rested on knowing each death's chance of being drawn, which the random sample guaranteed.

Source line on screen: Manuscript, Methods

Citations on screen: Horvitz and Thompson, 1952

**Slide 12 (s12). Two independent readings of every sampled death**

*What we did: the coding*

s12.1 (starts at 8:53). We read the coroner or medical examiner and law enforcement narratives of all 400 deaths twice, in two readings done independently, so that neither reading could influence the other.

s12.2 (starts at 9:07). We used a written codebook, after a training round and a pilot of 50 deaths.

s12.3 (starts at 9:13). Where the two readings disagreed, we settled the case together in a joint adjudication.

s12.4 (starts at 9:20). We measured agreement with Cohen's kappa, which corrected the share of matching codes for the agreement two readings would reach by chance. Our prespecified target was 0.80.

Source line on screen: Manuscript, Methods

**Slide 13 (s13). What the classifier learned from**

*What we did: the classifier*

s13.1 (starts at 9:34). Next, we trained a classifier, a program that learned from the 400 deaths we had coded which features of a record went with intimate partner violence. The slide reads from left to right, from what the classifier read, to the kinds of classifier we compared, to the number it produced.

s13.2 (starts at 9:54). For each death, it read three kinds of information. The first was the words of the two narratives, weighted so that words that set one narrative apart from others counted more. The second was a set of yes-or-no flags for phrases such as strangulation or separation. The third was facts that NVDRS had already coded, such as whether a suspect was a partner and which substances were found. The three were joined into one row of numbers for each death.

s13.3 (starts at 10:27). We compared four families of classifiers, which differed mainly in the shape of the rule they learned. Regularized logistic regression and a linear support vector machine each drew a single dividing line between related and unrelated deaths. The first gave each feature a weight and added up the weighted features, and the second placed the line as far as possible from both groups. A random forest and gradient-boosted trees instead combined many decision trees, each a sequence of yes-or-no questions. The forest averaged many trees grown independently, whereas boosting added trees one after another, each correcting the errors of the ones before.

s13.4 (starts at 11:15). Each classifier returned a probability from 0 to 1 for every death. We calibrated these probabilities within the training folds, so that they could be read as frequencies. Among deaths given a probability of about 0.70, for example, about 70 in 100 were related in our reading. Related and unrelated deaths were given equal weight in training, so neither answer won simply by being more common.

Source line on screen: Manuscript, Methods

Citations on screen: Tibshirani, 1996; Cortes and Vapnik, 1995; Breiman, 2001; Friedman, 2001; Niculescu-Mizil and Caruana, 2005

**Slide 14 (s14). Keeping the test honest**

*What we did: testing the classifier*

s14.1 (starts at 11:46). Deaths from 2019 to 2022 were used to choose the model family and its settings, by nested five-fold cross-validation, the approach Cawley and Talbot recommended. Nested meant that the deaths used to judge a model were kept apart from those used to tune it.

s14.2 (starts at 12:06). The coded deaths from 2023 were locked away until a single final test.

s14.3 (starts at 12:13). To pass, the classifier had to meet seven prespecified thresholds at once. The first two were sensitivity and specificity. Sensitivity was the share of the deaths we had read as related to partner violence that the classifier also labeled related, and it had to be at least 0.65. Specificity was the share of the deaths we had read as not related to partner violence that the classifier also labeled not related, and it had to be at least 0.80.

s14.4 (starts at 12:46). The other five covered different qualities. The F1 score, at least 0.65, balanced finding related deaths against avoiding false alarms. The area under the curve, at least 0.75, measured how well the classifier ranked related deaths above unrelated ones, where 0.5 is a coin flip. Kappa, at least 0.50, measured agreement with our reading beyond chance. The Brier score, at most 0.20, and the expected calibration error, at most 0.10, measured how far its probabilities were from what we found. We set these limits ourselves before testing, because no published standard fixes them.

s14.5 (starts at 13:37). Because the 2023 test set was small, we also estimated the performance of the whole model-building procedure by nested cross-validation of all 400 coded deaths, repeating every step inside each fold, and we examined errors by manner of death, age group, and race and ethnicity.

Source line on screen: Manuscript, Methods

Citations on screen: Cawley and Talbot, 2010; area under the curve: Hanley and McNeil, 1982

**Slide 15 (s15). From 400 readings to all 1,180 deaths**

*What we did: Aim 1 statistics*

s15.1 (starts at 13:58). Our primary estimate was the weighted proportion of the 1,180 deaths related to intimate partner violence, based on our reading.

s15.2 (starts at 14:09). Because the sample was drawn without replacement and covered a large share of several groups, we computed 95 percent confidence intervals with a rescaled bootstrap that kept the finite population correction, with 1,000 replicates, following Rao and Wu and Preston. A bootstrap redrew the sample many times to see how much the estimate would vary, and the rescaling kept it from overstating that variation where much of a group was coded.

s15.3 (starts at 14:41). The same estimator gave proportions by manner of death, age group, race and ethnicity, pregnancy timing, year, and substances found at death. For adolescents, we used the interval of Korn and Graubard, which was built for small numbers of events in survey data.

Source line on screen: Manuscript, Methods

Citations on screen: Rao and Wu, 1988; Preston, 2009; Korn and Graubard, 1998

**Slide 16 (s16). A second estimate, corrected by our readings**

*What we did: the classifier-assisted estimate*

s16.1 (starts at 15:02). The classifier gave a second estimate of the same proportion. To produce it, we split the 1,180 deaths into five groups, or folds, trained the classifier on the coded deaths of four groups, used it to score the fifth, and rotated until every group had been scored. This step is called cross-fitting. It meant that no death was scored by a classifier that had learned from our reading of that death, because a classifier fits the deaths it learned from too closely, and the correction that follows would then miss part of its errors.

s16.2 (starts at 15:39). Then the coded deaths corrected the classifier's estimate. For each of them, we took our reading minus the classifier's probability, averaged these gaps with the sampling weights, and added that average gap to the classifier's average over all 1,180 deaths.

s16.3 (starts at 15:58). Because the 400 were drawn at random, this correction was right on average however imperfect the classifier was, and the more accurate the classifier, the narrower the interval. It rested on each death having a known chance of being coded, which our random sample guaranteed.

s16.4 (starts at 16:18). Our plan allowed this estimate only if the classifier met every threshold in 2023. The few deaths without a narrative took the value of the structured field.

Source line on screen: Manuscript, Methods

Citations on screen: Zrnic and Candes, 2024; Egami and colleagues, 2023; Breidt and Opsomer, 2017

**Slide 17 (s17). Circumstances that co-occurred with partner violence**

*What we did: Aim 3*

s17.1 (starts at 16:30). For our third aim, we fitted one logistic model for each domain of circumstances recorded by abstractors. The domains were mental health, substance use, and legal problems.

s17.2 (starts at 16:44). Models were adjusted for age, race and ethnicity, pregnancy timing, year, and the share of deaths at the same reporting site with each circumstance recorded, the approach of Mundlak. That share meant each odds ratio described an association within a site, rather than differences in recording practices between states.

s17.3 (starts at 17:08). Using predicted labels as if they were observed would bias odds ratios, as Keogh and colleagues showed, so the models used the same design-based approach on all 1,180 deaths. NVDRS recorded legal problems and suicide attempt history only for suicides and deaths of undetermined intent, so those models used those deaths alone.

s17.4 (starts at 17:34). Models with fewer than 10 events per predictor used the penalized regression of Firth, and standard errors were clustered by reporting site. We read every association as descriptive, because a cohort made only of deaths could not show what raised the risk of death.

Source line on screen: Manuscript, Methods

Citations on screen: Mundlak, 1978; Keogh and colleagues, 2020; Firth, 1993; MacKinnon and colleagues, 2023

**Slide 18 (s18). Sensitivity analyses and confidentiality**

*What we did: checks and protections*

s18.1 (starts at 17:54). We prespecified four sensitivity analyses. We counted uncertain readings as related, restricted the cohort to ages 10 to 39, restricted it to homicides and suicides, and bounded the proportion among all 1,391 deaths by counting every death without known circumstances first as unrelated and then as related.

s18.2 (starts at 18:21). To protect confidentiality, no cell of fewer than 10 deaths was shown, and complementary cells were suppressed so that no small count could be recovered by subtraction.

s18.3 (starts at 18:34). To check this, a program treated every hidden number as an unknown. Using every number we planned to release, in all the tables at once, it searched for the smallest and largest value each hidden number could take, first allowing fractions, which is linear programming, and then whole counts only, which is integer programming. If any hidden number could be deduced to lie between 1 and 9, the tables were changed before release.

Source line on screen: Manuscript, Methods

Citations on screen: Statistical disclosure control: Hundepool and colleagues, 2012

**Chapter 3. What we found**

**Slide 19 (s19). The 1,391 deaths**

*What we found: the cohort*

s19.1 (starts at 19:05). The cohort comprised 1,391 deaths. Of these, 736, or 52.9 percent, were homicides, 532, or 38.2 percent, were suicides, and 123, or 8.8 percent, were deaths of undetermined intent or unintentional firearm injury.

s19.2 (starts at 19:30). Nearly half of the women, 652 or 46.9 percent, were pregnant at the time of death. The other 739, or 53.1 percent, had been pregnant 43 days to one year before death, 576 or 41.4 percent, or within 42 days or at an unspecified time, 163 or 11.7 percent. And 497, or 35.7 percent, were younger than 25 years.

s19.3 (starts at 20:08). Circumstances were known for 1,180 deaths, 84.8 percent. A drug caused 168 of the deaths, 12.1 percent, and half of these drug overdose deaths were of undetermined intent.

Source line on screen: Manuscript, Results and Table 1

**Slide 20 (s20). How closely the two readings agreed**

*What we found: coding*

s20.1 (starts at 20:25). In the 400 coded deaths, the two readings agreed on 88.5 percent of classifications, with a kappa of 0.77, and a 95 percent confidence interval from 0.71 to 0.83.

s20.2 (starts at 20:43). That was substantial agreement on the scale of Landis and Koch, although below our prespecified target of 0.80.

s20.3 (starts at 20:53). One reading classified more deaths as related to intimate partner violence than the other, and joint adjudication resolved every disagreement.

Source line on screen: Manuscript, Results and Limitations

Citations on screen: Agreement scale: Landis and Koch, 1977

**Slide 21 (s21k). The main finding**

*What we found: the main finding*

s21k.1 (starts at 21:04). Now we come to the main finding of our study, the number we hope you take home.

s21k.2 (starts at 21:12). Nearly half. Of the 1,180 deaths with known circumstances, 45.8 percent were related to intimate partner violence.

Source line on screen: Manuscript, Results and Table 2

**Slide 22 (s21). Nearly half of the deaths were related to partner violence**

*What we found: Aim 1*

s21.1 (starts at 21:28). The weighted proportion of deaths with known circumstances related to intimate partner violence was 45.8 percent, with a 95 percent confidence interval from 43.2 to 48.4 percent.

s21.2 (starts at 21:44). This exceeded the share of deaths with intimate partner violence recorded in the structured field, which supported our hypothesis. That share was about 31 percent and came almost entirely from homicides. Our reading exceeded it by about 14 to 15 percentage points, with an interval of roughly 11 to 17 points, so our estimate was nearly one and a half times the share the field recorded. The field's exact share is not shown, under the confidentiality rules.

Source line on screen: Manuscript, Results and Table 2; Table 1

**Slide 23 (s21b). Homicides and suicides told different stories**

*What we found: by manner of death*

s21b.1 (starts at 22:19). Homicides and suicides told different stories, so we looked at each manner of death as far as the confidentiality rules allowed.

s21b.2 (starts at 22:28). Among the 592 homicides with known circumstances, abstractors had already recorded partner violence in the structured field for 61.8 percent.

s21b.3 (starts at 22:41). For suicides, the field recorded no partner violence, because the coding manual reserves it for homicides. But abstractors had recorded an intimate partner problem in 211 of the 483 suicides with known circumstances, and in our reading, half of those, 50 percent, with an interval from 39 to 61 percent, were related to partner violence. That alone meant that at least 22 percent of all suicides with known circumstances, from 17 to 27 percent, were related to partner violence.

s21b.4 (starts at 23:21). Among deaths of undetermined intent or unintentional firearm injury, 26 percent were related, from 22 to 31 percent, and two-thirds of the deaths of this manner were drug overdoses.

s21b.5 (starts at 23:36). Homicides and suicides together gave 47.7 percent, from 44.8 to 50.6. This combined figure has to be read with care, because homicides accounted for most deaths related to partner violence, so it says more about homicides than about suicides. We could not show an estimate for all homicides or for all suicides, because with the other released tables each would have revealed a count from 1 to 9.

Source line on screen: Manuscript, Results, Tables 1 and 2; Supplement 1, eTables 2 and 3; released stratum estimates

**Slide 24 (s22). How the estimate held up**

*What we found: sensitivity analyses*

s22.1 (starts at 24:08). Counting uncertain readings as related gave 48.7 percent, from 46.1 to 51.2. Restricting the cohort to ages 10 to 39 gave 46.4 percent, from 43.7 to 49.1.

s22.2 (starts at 24:28). Both changes moved the estimate up, not down. Uncertain readings added fewer than 3 percentage points, so they could not change the conclusion that nearly half of the deaths were related. And leaving out women aged 40 to 44, the ages at which Catalano and colleagues found checkbox errors concentrated, did not lower the estimate, so such errors did not inflate it.

s22.3 (starts at 24:55). The 211 deaths without known circumstances lacked the structured information that our sampling required, so they were left out. Counting every one of them as unrelated gave 38.9 percent among all 1,391 deaths. When we read the narratives available for them, few were related to partner violence, so the proportion among all 1,391 deaths was likely close to that value.

Source line on screen: Manuscript, Results and Table 2

Citations on screen: Checkbox errors at older ages: Catalano and colleagues, 2020

**Slide 25 (s23). Highest among women who died while pregnant**

*What we found: by characteristic*

s23.1 (starts at 25:26). The proportion was higher among women who were pregnant at the time of death, 52.1 percent, than among those who died 43 days to one year after pregnancy, 41.8 percent.

s23.2 (starts at 25:41). It was 50 percent among adolescents aged 10 to 19, and 39 percent among women aged 35 to 44.

s23.3 (starts at 25:51). And it showed no consistent trend from 2019 to 2023.

Source line on screen: Manuscript, Results and Table 3

Citations on screen: Adolescent interval: Korn and Graubard, 1998

**Slide 26 (s24). Less often related when an opioid was found**

*What we found: substances*

s24.1 (starts at 25:57). Deaths with an opioid found at death were less often related to intimate partner violence, 24 percent, than deaths with a stimulant but no opioid, 57 percent, or with no drug found, 55 percent.

Source line on screen: Manuscript, Results and Table 3

**Slide 27 (s25). What the structured field captured, and what it missed**

*What we found: the structured field*

s25.1 (starts at 26:15). Among the 592 homicides with known circumstances, abstractors recorded intimate partner violence in 366, or 61.8 percent, and in 326, or 55.1 percent, a suspect was a current or former partner.

s25.2 (starts at 26:35). To check the field itself, we also read 150 deaths that were not among the 400, half drawn from deaths with a partner signal in the structured data and half from deaths without one. Whenever the field said that partner violence was involved, both of our readings agreed.

s25.3 (starts at 26:55). But the field missed many deaths. Of the deaths we read as related, it had flagged about three in four, 76 percent in one reading and 81 percent in the other, so it missed 24 percent and 19 percent, including suicides, for which the field records no partner violence.

Source line on screen: Manuscript, Results; Supplement 1, eTables 3 and 4

**Slide 28 (s26). How the classifier performed**

*What we found: Aim 2*

s26.1 (starts at 27:17). Of the four families, gradient-boosted trees ranked first and were selected, and they met every prespecified threshold in the 2023 test set. The individual 2023 values were withheld because one cell held fewer than 10 deaths.

s26.2 (starts at 27:36). In nested cross-validation of all 400 coded deaths, the procedure had a sensitivity of 0.73, a specificity of 0.90, a positive predictive value of 0.84, and an area under the curve of 0.91.

s26.3 (starts at 27:56). In plain terms, of every 100 deaths we read as related, the classifier found about 73 and missed about 27. Of every 100 deaths we read as unrelated, it correctly left out about 90. Of every 100 deaths it flagged, about 84 were related in our reading. And given one related and one unrelated death, it gave the higher score to the related death about 91 times in 100, where 50 would be a coin flip, as Hanley and McNeil explained. A sensitivity of 0.13 instead would have meant missing about 87 of every 100 related deaths. Because even this classifier missed about a quarter, we did not count its labels alone, and our readings corrected it.

s26.4 (starts at 28:49). The other three families performed similarly, error rates by subgroup, where reportable, ranged from 14 to 22 percent, and the classifier's cross-fitted predictions agreed with our reading for 84 percent of deaths, with a kappa of 0.67.

Source line on screen: Manuscript, Results and Table 4; Supplement 1, eTables 5 and 6

Citations on screen: Area under the curve: Hanley and McNeil, 1982

**Slide 29 (s27k). The second key finding**

*What we found: the second key finding*

s27k.1 (starts at 29:09). And here is the second key finding.

s27k.2 (starts at 29:14). Applied to all 1,180 deaths and corrected with our readings, the classifier estimated that 44.6 percent were related to intimate partner violence, almost the same as our own reading. This means that a classifier checked against a random sample of human readings could let surveillance systems read every narrative rather than a sample.

Source line on screen: Manuscript, Results and Table 2; Conclusions

**Slide 30 (s27). The classifier reproduced our estimate**

*What we found: two estimates*

s27.1 (starts at 29:46). Side by side, the two estimates almost coincided, 44.6 percent from the classifier, with an interval from 41.9 to 47.3 percent, and 45.8 percent from our reading.

s27.2 (starts at 30:02). The classifier's estimate was 1.2 percentage points lower, with an interval for the difference from minus 3.0 to 0.5.

Source line on screen: Manuscript, Results and Table 2

**Slide 31 (s28). A pattern created by mixing manners of death**

*What we found: Aim 3*

s28.1 (starts at 30:13). For our third aim, the clearest results came from suicides and deaths of undetermined intent, the deaths in which abstractors recorded these circumstances more often. Within them, no mental health circumstance was associated with partner violence. The adjusted odds ratios were 1.00 for a current diagnosed mental health problem, 1.06 for depressed mood, 0.63 for current treatment, with an interval that included 1, and 1.07 for a history of suicide attempts.

s28.2 (starts at 30:51). Across all manners together, the same circumstances looked very different. Current treatment for a mental health or substance use problem, with an adjusted odds ratio of 0.51, and other substance problems, with 0.44, were associated with lower odds of partner violence, and without adjustment all three mental health circumstances had odds ratios below 1.

s28.3 (starts at 31:19). We do not read these pooled values as a finding about women. Abstractors recorded mental health circumstances more often in suicides than in homicides, and homicides accounted for most deaths related to partner violence. Pooled together, a mental health circumstance mostly marked a suicide, so the odds ratio fell below 1. This is the pattern known as Simpson's paradox, which Hernan, Clayton, and Keiding showed disappears when the analysis follows the causal structure of the data, and Knol and VanderWeele recommended reporting associations within each group.

s28.4 (starts at 32:00). Two caveats remain. Other substance problems could not be estimated reliably within manners of death, so we cannot tell how much of that association also came from mixing manners, and associations within a manner are still descriptive, because partner violence can itself shape whether a death is a homicide or a suicide. No model of homicides alone could be shown, and the legal circumstances could not be reported because some cells held too few deaths.

Source line on screen: Manuscript, Results, Discussion and Table 5

Citations on screen: Hernan, Clayton and Keiding, 2011; Knol and VanderWeele, 2012

**Chapter 4. What it means**

**Slide 32 (s29). What the findings add**

*What it means*

s29.1 (starts at 32:33). We found that intimate partner violence was related to nearly half of these deaths, 45.8 percent of those with known circumstances.

s29.2 (starts at 32:43). Abstractors recorded partner violence in 61.8 percent of homicides, but the coding manual left the field nearly empty for suicides, and our reading found it in at least 22 percent of suicides. In our validation sample, the structured field missed roughly one in five deaths that we read as related. Kafka and colleagues likewise found partner violence in suicides that the structured fields did not record.

s29.3 (starts at 33:14). Our findings extended earlier work to pregnancy and the postpartum period and to all manners of violent death in a single cohort, and they suggested that counts of maternal deaths related to partner violence that relied on structured fields alone were underestimates.

s29.4 (starts at 33:33). The classifier labeled all 1,180 deaths and, through the design-based correction, produced an estimate about as precise as our own. The design-based approach mattered as much as the classifier, because it let our readings correct the classifier's errors rather than inherit them.

Source line on screen: Manuscript, Discussion

Citations on screen: Kafka and colleagues, 2024

**Slide 33 (s30). Where prevention might reach women**

*What it means for prevention*

s30.1 (starts at 33:54). Partner violence was most common among women who died while pregnant, two-thirds of whom died by homicide. For many women, pregnancy was a period of regular contact with prenatal care, and in 2025 the US Preventive Services Task Force recommended that clinicians screen women of reproductive age, including those who are pregnant and postpartum, for intimate partner violence.

s30.2 (starts at 34:22). Deaths with an opioid were less often related to partner violence, 24 percent. But 85 percent of the drug overdose deaths of undetermined intent involved an opioid, and only 26 percent of deaths of that manner were related, well below the 45.8 percent overall, so the difference largely follows the manner of death under which most opioid deaths were classified. Even so, one in four deaths with an opioid was related to partner violence. Stone and Rothman found partner violence frequent among people who use opioids, and Drew and colleagues showed drug overdose emerging as the leading cause of death during pregnancy and the postpartum period, so screening for partner violence could be part of overdose prevention.

s30.3 (starts at 35:14). The odds ratios below 1 with all manners pooled came from mixing homicides and suicides, and they offer no evidence of protection. Within suicides and deaths of undetermined intent, a mental health diagnosis, depressed mood, or treatment did not signal a lower chance that a death was related to partner violence.

Source line on screen: Manuscript, Discussion and Table 1; Supplement 1, eTable 2

Citations on screen: US Preventive Services Task Force, 2025; Stone and Rothman, 2019; Drew and colleagues, 2026; Hernan and colleagues, 2011

**Slide 34 (s31). The limits we name**

*What it does not establish*

s31.1 (starts at 35:37). We named our limits openly. First, the pregnancy checkbox missed 38.2 percent of confirmed pregnancies in a four-state validation study by Catalano and colleagues, so our cohort did not include every pregnancy-associated violent death, and how this affected the proportion was unknown.

s31.2 (starts at 35:59). Second, narratives described partner violence only when investigators learned of it and wrote it down, so our estimate was more likely an underestimate than an overestimate.

s31.3 (starts at 36:12). Third, agreement between our two readings fell short of our target, although counting uncertain readings as related changed the estimate by less than 3 percentage points.

s31.4 (starts at 36:26). Fourth, the 211 deaths without known circumstances were left out of the primary estimate, which therefore describes the deaths with known circumstances.

s31.5 (starts at 36:37). Fifth, protecting confidentiality prevented estimates for all homicides, for all suicides, and for racial and ethnic groups, which limited what we could say about disparities. With a cohort of this size, the rules that protect the people in these records meant that many of the breakdowns and sensitivity analyses we had planned could not be published, a lesson that shaped how we designed our next study.

s31.6 (starts at 37:06). Sixth, the individual 2023 test values were withheld, and the cross-validated metrics described the model-building procedure rather than the single locked model.

s31.7 (starts at 37:18). Finally, a cross-sectional design restricted to deaths allowed only descriptive associations.

Source line on screen: Manuscript, Limitations

**Chapter 5. What is next**

**Slide 35 (s32). Where the work goes from here**

*What is next*

s32.1 (starts at 37:26). We prespecified an extension that would add pregnancies identified in the narratives of decedents whose checkbox was not marked. It was not yet complete when we finished this analysis, and we planned to report it separately.

s32.2 (starts at 37:42). That question led to our next study. In a proposal to the National Institutes of Health, we planned to measure how many pregnancies the checkbox misses among female decedents of reproductive age, by reading the same kind of narratives, and to test the classifier in a better way.

s32.3 (starts at 38:01). Before computing any estimate, we registered our analysis plan on the Open Science Framework, and we listed every departure from it in the supplement to our manuscript.

s32.4 (starts at 38:14). We planned to deposit the analysis code in the study's GitHub repository with synthetic example data, because NVDRS records were available only to approved researchers under a data sharing agreement, and to link the manuscript there once it was published.

Source line on screen: Manuscript, Methods, Limitations and Data Sharing Statement; Supplement 1, eTable 1; R03 proposal to NIH, 2026

**Slide 36 (s32b). What we changed for the next study**

*What is next: a better test*

s32b.1 (starts at 38:32). In this study, we held out the deaths of 2023 for one final test. But that year held few coded deaths, so its individual results could not even be shown. In our next study, we changed the plan.

s32b.2 (starts at 38:48). We planned to divide all the coded records into folds, train the classifier on all folds but one, test it on the one left out, and rotate, so that every coded record serves once as a test case. Every choice the classifier depends on would be made inside the training folds, never by looking at test results.

s32b.3 (starts at 39:11). Because the coded records form a stratified sample, we planned to weight the test results by each record's chance of being read, so that the reported performance describes all records and not only the ones we read.

s32b.4 (starts at 39:26). And because few cases fall in each group, we planned to name three comparisons in advance, describe the rest, and report a comparison as indeterminate where the data cannot support it.

Source line on screen: R03 proposal to the National Institutes of Health, Research Strategy, 2026

**Slide 37 (s32r). Studies cited in this video (1 of 2)**

*References*

s32r.1 (starts at 39:40). The studies we cited in this video are listed here and on the next screen, with their full references.

Source line on screen: Full references, with the DOI where one exists

**Slide 38 (s32s). Studies cited in this video (2 of 2)**

*References*

s32s.1 (starts at 39:48). The list of references continues here.

Source line on screen: Full references, with the DOI where one exists

**Slide 39 (s33). Thank you**

*Credits*

s33.1 (starts at 39:52). This study was carried out by Mario Morales, Egoitz Laparra, and Maeve Wallace, at the University of Arizona.

s33.2 (starts at 40:01). We used the NVDRS Restricted Access Database, obtained from the Centers for Disease Control and Prevention under a data sharing agreement. The University of Arizona Institutional Review Board determined that the analysis was not human subjects research.

s33.3 (starts at 40:20). The work was supported by the Eunice Kennedy Shriver National Institute of Child Health and Human Development, award 2R01HD096070, with Dr. Wallace as principal investigator. Thank you for watching.

Source line on screen: Manuscript, title page and Article Information
