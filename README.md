# Regg.F.III Transcriptions
This repository contains material connected to the ongoing transcription project of the *Regeste Imperii - Regesta of Emperor Frederik III (1440-1493)* research office at the *Berlin-Brandenburg Academy of Sciences and Humanities*. It is a work-in-progress and contents may change at any given time without further notice.

The contents of this repository are provided by the [*Regesta Impoerii- Regesta of Emperor Frederik III (1440-1493)*](https://ri.bbaw.de/de) of the [*Berlin-Brandenburg Academy of Sciences and Humanities (BBAW)*](https://www.bbaw.de/). They were compiled and curated by [Frederik Skidzun](https://orcid.org/0009-0002-7712-4207).

## Contents
file name | description
--- | ---
transcription-rules.md | transcription rules for the Regg.F.III HTR projects at the BBAW
models (directory) | contains models trained for our projects

## Available Models
model name | base model | accuracy | type | transcription level | description
---|---|---|---|---|---
formelbuch_03.mlmodel | Tridis v2 | 98.8% | recognise | semi-diplomatic | trained for 37 epochs, lines: 2128, word tokens: 18217, chars: 110376
formelbuch_graphemic_01.mlmodel | Tridis v2 | 97,8% | recognise | graphemic | trained for 46 epochs, lines: 2,177, word tokens: 18,626, chars: 113,491
tridis_reggfr2.mlmodel | Tridis v2 | 92% | recognise | semi-diplomatic | developed for transcribing charters of Emperor Frederik III.
formelbuch_v0.mlmodel | tridis_regfr | 92.2% | recognise | semi-diplomatic | fromulary project
tridis_regfr.mlmodel | Tridis v2 | 92.6% | recognise | semi-diplomatic | charter transcriptions
Tridis_v2_Regg_FIII_3.mlmodel | Tridis v2 | 94.9 | recognise | semi-diplomatic | charter transcriptions
ubma_segment_regg_f_iii_v3.mlmodel | ubma_segmentation | 70.7% | segment | -- | --

## References

[Tridis v2](https://doi.org/10.5281/zenodo.13862096) (A. Torres Aguilar, V. Jolivet)

[ubma_segmentation](https://github.com/JKamlah/ubma-segmentation-ocr-model.git) (J. Kamlah)

## License
The contents of this repository are licensed under the CC BY 4.0 license.
