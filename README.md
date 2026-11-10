# Bulgarian–Romanian MWE Dictionary

A linked bilingual (Bulgarian–Romanian) computational lexicon of multiword expressions (MWEs). Entries are described on several linguistic levels (lexical, morphological, syntactic, semantic and stylistic) following one uniform set of principles for both languages.

The lexicon is derived from the Bulgarian and the Romanian wordnets and covers verbal MWEs. The Bulgarian and Romanian expressions are counterparts, or translation equivalents, of each other.

## Overview

- **Two self-contained monolingual lexicons.** The Bulgarian and the Romanian data are described according to the same principles and features, but each language forms a lexicon of its own that can be developed independently.
- **Cross-lingual links.** Each entry carries the technical information needed to link it to its counterpart in the other language. As in aligned wordnets, the links are established through English as a pivot.
- **Rich, multi-level description.** Each entry has lexical, morphological (inflectional and derivational), syntactic (including word order), semantic and stylistic information.
- **PARSEME classification.** Verbal MWEs are classified according to the typology developed by the PARSEME community ([Savary et al. 2018](https://doi.org/10.5281/zenodo.1471591); [PARSEME annotation guidelines, edition 1.1](https://typo.uni-konstanz.de/parseme/)). The types applicable to Bulgarian and Romanian are verbal idioms (VID), light-verb constructions (LVC.full and LVC.cause) and inherently reflexive verbs (IRV).
- **Language-specific features.** The shared description accounts for what the two languages have in common (they belong to different language families) while still allowing language-specific features to be recorded.
- **Extensible.** The framework can be expanded to further levels of linguistic description and to other languages.

## Origin

The resource builds on the proof of concept presented in [Leseva et al. (2020)](https://aclanthology.org/2020.clib-1.11/): compiling a multilingual MWE resource from information extracted from the Bulgarian, the Romanian and the Princeton wordnets, together with additional language resources and automatic procedures. It also draws on joint work on verbal MWEs in the two wordnets ([Barbu Mititelu et al. 2019](https://aclanthology.org/W19-5102/)). The uniform description and the lexicon are presented in [Leseva et al. (2024)](https://doi.org/10.5281/zenodo.10998635).

It was developed by researchers from the Institute for Bulgarian Language "Prof. Lyubomir Andreychin" (Bulgarian Academy of Sciences) and the Romanian Academy Research Institute for Artificial Intelligence (RACAI).

## Data format

CSV

## How to cite

If you use the resource, please cite:

Svetlozara Leseva, Verginica Barbu Mititelu, Ivelina Stoyanova & Mihaela Cristescu. 2024. A uniform multilingual approach to the description of multiword expressions. In Voula Giouli & Verginica Barbu Mititelu (eds.), *Multiword expressions in lexical resources: Linguistic, lexicographic, and computational perspectives* (Phraseology and Multiword Expressions 6), 73–116. Berlin: Language Science Press. DOI: [10.5281/zenodo.10998635](https://doi.org/10.5281/zenodo.10998635)

```bibtex
@incollection{leseva2024uniform,
  author    = {Leseva, Svetlozara and Barbu Mititelu, Verginica and Stoyanova, Ivelina and Cristescu, Mihaela},
  title     = {A uniform multilingual approach to the description of multiword expressions},
  booktitle = {Multiword expressions in lexical resources: Linguistic, lexicographic, and computational perspectives},
  editor    = {Giouli, Voula and Barbu Mititelu, Verginica},
  series    = {Phraseology and Multiword Expressions},
  number    = {6},
  pages     = {73--116},
  publisher = {Language Science Press},
  address   = {Berlin},
  year      = {2024},
  doi       = {10.5281/zenodo.10998635}
}
```

## Related publications

Svetlozara Leseva, Verginica Barbu Mititelu & Ivelina Stoyanova. 2020. [It Takes Two to Tango – Towards a Multilingual MWE Resource](https://aclanthology.org/2020.clib-1.11/). In *Proceedings of the Fourth International Conference on Computational Linguistics in Bulgaria (CLIB 2020)*, 101–111. Sofia, Bulgaria: Department of Computational Linguistics, IBL – BAS.

Verginica Barbu Mititelu, Ivelina Stoyanova, Svetlozara Leseva, Maria Mitrofan, Tsvetana Dimitrova & Maria Todorova. 2019. [Hear about verbal multiword expressions in the Bulgarian and the Romanian wordnets straight from the horse's mouth](https://aclanthology.org/W19-5102/). In *Proceedings of the Joint Workshop on Multiword Expressions and WordNet (MWE-WN 2019)*, 2–12. Florence, Italy.

Agata Savary et al. 2018. [PARSEME multilingual corpus of verbal multiword expressions](https://doi.org/10.5281/zenodo.1471591). In Stella Markantonatou, Carlos Ramisch, Agata Savary & Veronika Vincze (eds.), *Multiword expressions at length and in depth: Extended papers from the MWE 2017 workshop*, 87–147. Berlin: Language Science Press. DOI: [10.5281/zenodo.1471591](https://doi.org/10.5281/zenodo.1471591)
 

*Annotation guidelines of the PARSEME shared task on automatic identification of verbal MWEs – edition 1.1.* PARSEME: <https://typo.uni-konstanz.de/parseme/>

## License

This resource is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
