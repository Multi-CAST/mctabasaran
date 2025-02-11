# Multi-CAST Tabasaran

## How to cite

If you use these data please cite
- the original source
  > Bogomolova, Natalia & Ganenkov, Dmitry & Schiborr, Nils N. 2022. Multi-CAST Tabasaran. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2207. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#tabasaran) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Tabasaran** ([taba1259](https://glottolog.org/resource/languoid/id/taba1259)) is a Nakh-Daghestanian (Caucasian) language from the Lezgic subbranch. Recent census data puts the number of speakers at about 120 000; [Campbell et al. (2017)](Source#cldf:campbell.etal2017) classify the language as vulnerable.

The texts in the Multi-CAST Tabasaran corpus were recorded by Natalia Bogomolova with the assistance of Dmitry Ganenkov in 2010, and subsequently transcribed, glossed, and translated by the former. The annotations with GRAID and RefIND were added by Nils Schiborr between 2019 and 2020. The five texts in this corpus are a mixture of traditional and biographical narratives.

The texts in this corpus (version 2207) have been time-aligned at the phone level for a [data set](https://doreco.huma-num.fr/languages/taba1259) in the [DoReCo project](https://doreco.huma-num.fr/).

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#tabasaran


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    47.8379,
                    42.0198
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            42.8379,
                            47.0198
                        ],
                        [
                            52.8379,
                            47.0198
                        ],
                        [
                            52.8379,
                            37.0198
                        ],
                        [
                            42.8379,
                            37.0198
                        ],
                        [
                            42.8379,
                            47.0198
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 18 | 66 | 11 | 2 | 1 | 6 | 0 | 0 | 0 | 0 | 104 |
| **⟨0.2⟩** | 38 | 67 | 9 | 0 | 2 | 15 | 0 | 0 | 0 | 0 | 131 |
| **⟨0.h⟩** | 174 | 268 | 21 | 13 | 9 | 8 | 0 | 1 | 0 | 0 | 494 |
| **⟨0.d⟩** | 6 | 18 | 0 | 1 | 0 | 0 | 1 | 0 | 0 | 0 | 26 |
| **⟨0⟩** | 13 | 3 | 0 | 93 | 1 | 1 | 0 | 1 | 0 | 1 | 113 |
| **⟨pro.1⟩** | 13 | 20 | 6 | 4 | 8 | 9 | 0 | 0 | 37 | 0 | 97 |
| **⟨pro.2⟩** | 13 | 19 | 7 | 2 | 5 | 5 | 0 | 0 | 28 | 3 | 82 |
| **⟨pro.h⟩** | 64 | 65 | 21 | 12 | 15 | 22 | 0 | 1 | 27 | 2 | 229 |
| **⟨pro.d⟩** | 3 | 3 | 0 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 7 |
| **⟨pro⟩** | 5 | 0 | 0 | 5 | 5 | 7 | 12 | 2 | 4 | 30 | 70 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 105 | 67 | 14 | 27 | 26 | 32 | 0 | 17 | 37 | 16 | 341 |
| **⟨np.d⟩** | 5 | 6 | 0 | 0 | 0 | 0 | 2 | 0 | 0 | 2 | 15 |
| **⟨np⟩** | 162 | 1 | 4 | 342 | 36 | 89 | 66 | 14 | 19 | 105 | 838 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 4 | 3 | 2 | 0 | 1 | 3 | 0 | 3 | 3 | 0 | 19 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 13 | 0 | 0 | 30 | 1 | 4 | 3 | 53 | 0 | 3 | 107 |
| | 636 | 606 | 95 | 532 | 110 | 201 | 84 | 92 | 155 | 162 | 2673 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 869 |
| **⟨#⟩** | 514 |
| **totals** | 1383 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)