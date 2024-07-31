# README

## Details related to access to the data

- [x] Data user agreement

Dataset publicly available under the Creative Commons CC0 license after a grace period of 36 months.

- [x] Contact person

Edmund Wascher, IfADo, wascher@ifado.de, ORCID: 0000-0003-3616-9767
Daniel Schneider, IfADo, schneiderd@ifado.de, ORCID: 0000-0002-2867-2613
Patrick D. Gajewski, IfADo, gajewski@ifado.de, ORCID: 0000-0001-8240-1702
Stephan Getzmann, IfADo, getzmann@ifado.de, ORCID: 0000-0002-6382-0183

- [x] Practical information to access the data

The data are provided at OpenNeuro (dataset accession number: ds005385, DOI: https://doi.org/10.18112/openneuro.ds005385.v1.0.0) in BIDS format.

## Overview

- [x] Project name

Resting-state EEG activity before and after cognitive activity at baseline and a 5-years follow-up.

- [x] Year(s) that the project ran

2016-2024

- [x] Brief overview of the tasks in the experiment

Resting-state EEG (rs-EEG) is a non-invasive measure of the spontaneous electrical activity of the brain, measured while remaining still and relaxed, and without performing any assigned cognitive tasks. Changes in rs-EEG are associated with numerous psychiatric disorders, but also with normal aging and with factors such as fatigue and motivation. Analyses of longitudinal rs-EEG measurements in healthy subjects over the entire adult lifespan could help to better understand the underlying brain processes, their development across the lifespan, and differences in brain activity between healthy and clinically relevant groups. The data set is part of the Dortmund Vital Study (ClinicalTrials.gov Identifier: NCT05155397), a prospective study on the determinants of healthy cognitive aging. The experiments comprised the recording of resting-state EEG data before and after a 2-hour block of cognitive experimental tasks. There are baseline measurements and about 5-years follow-up measurements of a subsample of healthy adult participants (for more information, Gajewski et al., 2022, doi: 10.2196/32352).

- [x] Description of the contents of the dataset

The dataset consists of 64-channels resting-state EEG recordings of 608 participants aged between 20 and 70 years, measured for three minutes with eyes open and eyes closed before and after a 2-hour block of demanding cognitive experimental tasks. Additional follow-up measurements are available from 208 subjects who also took part in the baseline measurement. The baseline measurements took place between 2016 and 2023, the follow-up measurements at intervals of around 5 years, starting 2021. The years of the baseline and follow-up measurements are specified in the sub-xxx_sessions.tsv file for each subject. The procedure for this (ongoing) follow-up measurement is exactly the same as for the first measurement.

- [x] Independent variables

Information on Age, Sex, Handeness of the participants are provided.

- [x] Dependent variables

Spontaneous EEG Activity is measured.

- [ ] Control variables

n/a

- [x] Quality assessment of the data

The data was checked for completeness and includes the non-preprocessed raw EEG.

An estimate of the reliability of the rs-EEG data was provided by a study, in which the intra-class correlation (ICC) in absolute EEG alpha power (8-13 Hz) of all four recordings at the first measurement (session 1) was examined on selected frontal and parietal electrodes in a subgroup of 370 participants (Metzen et al., 2022, doi: 10.1007/s00429-021-02399-1). The ICC ranged between 0.92 and 0.94 in the eyes-closed condition and between 0.87 and 0.90 in the eyes-open condition, indicating good to excellent ratings of alpha power reliability. A recent analysis of the reliability of EEG microstate indicated good to excellent short-term retest-reliability of microstate durations, occurrences, and coverages in a subgroup of 583 participants, as well as good overall short, intermediate, and long-term re-test reliability of these microstate characteristics across session 1 and session 2, covering a period of more than half a year (Kleinert et al., 2024, doi: 10.1007/s10548-023-00982-9).

## Methods

### Subjects

The subject pool consists of participants in the Dortmund Vital Study and includes people of working age between 20 and 70 years. 61.8% of the subjects of the baseline measurement are female, 93.1% are right-handed. The participants reported to be healthy and free of medication that might affect their attention during the experimental sessions. In general, the study population can be considered as representative in terms of age distribution, genetics, cognitive performance parameters, and occupation, whereas there were differences in gender distribution and educational qualifications compared to the general population in Germany (for details, see Gajewski et al., 2022, doi: 10.2196/32352).

- [x] Information about the recruitment procedure

The participants were recruited from local companies, and public institutions, and through advertisements in newspapers and public media.

- [ ] Subject inclusion criteria (if relevant)
- [x] Subject exclusion criteria (if relevant)

Exclusion criteria were history of severe diseases, namely neurological diseases (such as dementia, Parkinson disease, or stroke); cardiovascular, oncological, and eye diseases; psychiatric and affective disorders; head injuries, head surgery, and head implants; use of psychotropic drugs and neuroleptics; limited physical fitness and mobility.

### Apparatus

The measurements took place in a quiet laboratory room while the subject was sitting. The resting-state EEG was recorded using a 64-channel elastic cap (actiCap system, Brain Products GmbH; Munich, Germany) arranged based on the 10-20 system with FCz electrode as on-line reference, and a BrainVision Brainamp DC amplifier and BrainVision Recorder software (BrainProducts GmbH). The EEG signal was recorded with 1000-Hz sampling rate and filtered online by a 250-Hz low-pass filter. Impedances were kept below 10 kOhm.

### Initial setup

After arriving at institute there was an introductory meeting to clarify the procedure and open questions, to explain the aim of the study, and to explain open questions regarding informed consent forms and anonymization of the data. In the next step the EEG cap was mounted, and the tasks explained. 

### Task organization

- [x] Was task order counter-balanced?

The resting-state EEG was always recorded first with the eyes closed and then with the eyes open.

- [x] What other activities were interspersed between tasks?

The resting-state EEG with eyes closed and eyes open was measured before and after a 2-hour block of cognitive tasks.

- [x] In what order were the tasks and other activities performed?

The cognitive block comprised five tasks on visual attention, vigilance, stimulus-response conflict processing, updating and statistical learning, and speech-in-noise perception and auditory selective attention. The tasks were carried out one after the other with short breaks (for details, see Gajewski et al., 2022, doi: 10.2196/32352).

### Task details

Recordings consists of resting-state EEG epochs measured for three minutes with eyes open and eyes closed before and after a 2-hour block of cognitive experimental tasks. During the resting-state EEG measurement, the subjects should sit quietly and relaxed.

### Additional data acquired

n/a

### Experimental location

The measurements took place at the Leibniz Research Centre for Working Environment and Human Factors at Dortmund University (IfADo) in Dortmund, Germany.

### Missing data

- Information on handeness is missing for two subjects.

### Notes

n/a

