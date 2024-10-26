# SynSemClass

This is the central repository for the SynSemClass project, which aggregates the source code from all related repositories created under this initiative.

## About SynSemClass

**SynSemClass** is an event-type ontology in multiple languages. The project attempts to create specifications and definitions of a hierarchical event-type ontology, populated with words denoting events or states (primarily verbs, verbal nouns, and adjectives, but also any other single- or multiword units denoting events or states). It links its entries or "classes" (and the words that evoke them) to several existing lexical resources that exist and has, to some extent, similar goals; such linking allows for both theoretical and practical comparison and use of the resources.

## Quick Links to the Current Version of SynSemClass

- [the browser](https://lindat.mff.cuni.cz/services/SynSemClass50/),
- [the search tool](https://lindat.mff.cuni.cz/services/SynSemClassSearch/?version=synsemclass5.0),
- [data (ZIP/XML)](http://hdl.handle.net/11234/1-5230),
- [documentation, publications](https://ufal.mff.cuni.cz/synsemclass).

## How to Cite Us

- Please see the individual repositories for their corresponding publications for citations.
- Or, please select one of the [publications from this list on the documentation page](https://ufal.mff.cuni.cz/synsemclass) most relevant to your work.
- If unsure, the canonical publication for this project is [Urešová et al. (2020)](https://aclanthology.org/2020.globalex-1.2/):

```
@inproceedings{uresova-etal-2020-synsemclass,
    title = "{S}yn{S}em{C}lass Linked Lexicon: Mapping Synonymy between Languages",
    author = "Uresova, Zdenka  and
      Fucikova, Eva  and
      Hajicova, Eva  and
      Hajic, Jan",
    editor = "Kernerman, Ilan  and
      Krek, Simon  and
      McCrae, John P.  and
      Gracia, Jorge  and
      Ahmadi, Sina  and
      Kabashi, Besim",
    booktitle = "Proceedings of the 2020 Globalex Workshop on Linked Lexicography",
    month = may,
    year = "2020",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2020.globalex-1.2",
    pages = "10--19",
    language = "English",
    ISBN = "979-10-95546-46-7",
}
```

## License

Copyright 2024 Institute of Formal and Applied Linguistics, Faculty of Mathematics and Physics, Charles University, Czech Republic.

This Source Code Form is subject to the terms of the [Mozilla Public License, v. 2.0](LICENSE). If a copy of the MPL was not distributed with this file, You can obtain one at [http://mozilla.org/MPL/2.0/](http://mozilla.org/MPL/2.0/).

Please see the individual repositories for additional licensing.

The [data](http://hdl.handle.net/11234/1-5230) is released under [CC BY-NC-ND 4.0](https://creativecommons.org/licenses/by-nc-nd/4.0/).

## How to Get this Source Code

You can either clone the related repository/repositories individually, for example, to clone just the [SynSemClassSearch](https://github.com/ufal/SynSemClassSearch):

```sh
git clone https://github.com/ufal/SynSemClassSearch
```

Or you can clone the entire project, including all the related repositories as submodules, each in a subdirectory:

```sh
git clone --recurse-submodules https://github.com/ufal/SynSemClass/
```

## Repositories under SynSemClass

- [SynSemClassSearch](https://github.com/ufal/SynSemClassSearch): a [Search Tool](https://lindat.mff.cuni.cz/services/SynSemClassSearch/) for the SynSemClass ontology.
- [synsemclass_ml](https://github.com/strakova/synsemclass_ml): source code for machine learning for the SynSemClass project. Also accompanies [Straková et al. (2023)](https://aclanthology.org/2023.law-1.9/).

## Acknowledgements

## Contact

- [Zdeňka Urešová](https://ufal.mff.cuni.cz/zdenka-uresova) `uresova@ufal.mff.cuni.cz` is in charge of the SynSemClass project,
- [Jan Hajič](https://ufal.mff.cuni.cz/jan-hajic) `hajic@ufal.mff.cuni.cz` is the PI of LINDAT/CLARIAH-CZ and of the LuSyD project and coordinates the expansion work on the lexicon,
- [Jana Straková](https://ufal.mff.cuni.cz/jana-strakova) `strakova@ufal.mff.cuni.cz` is in charge of this repository.

