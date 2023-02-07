# PWS

PWS is a parallel corpus of the Winograd schemata for seven languages including Hungarian. Find additional information about the original dataset and the translations [here](https://cs.nyu.edu/~davise/papers/WinogradSchemas/WS.html).
The Hungarian translation is also available [here](https://github.com/nytud/HuWS).



## Sources

PWS contains translations of the Winograd schemata for the following languages:

* English (the original dataset)
* Hungarian
* French
* Portuguese
* Mandarin
* Japanese
* Russian

## Format

PSW is stored in a `tsv` file, where the header shows the field names. The fields are for the sentences, the snippets, the two alternative answers and the correct answer for the languages, respectively.
In the case of the English schemata the source is indicated. In the case of translations, if available, the name of the translator is presented.

Japanese and Portuguese translations are provided in two versions: one preserves the English proper names, while the other contains proper names of the target language. Schemata containing proper names are stored in both versions in the parallel corpus as well. In these cases the first column of the laguage (`sentence_jap`, `snippet_jap`, `answer1_jap`, `answer2_jap`, `correct_answer_jap` and `sentence_por`, `snippet_jap`, `answer1_jap`, `answer2_jap`, `correct_answer_jap`) contains the version with English names, the second column (`sentence_jap2`, `snippet_jap2`, `answer1_jap2`, `answer2_jap2`, `correct_answer_jap2` and `sentence_por2`, `snippet_jap2`, `answer1_jap2`, `answer2_jap2`, `correct_answer_jap2`) contains the schemata with Portuguese or Japanese names. Sentences that does not contain any proper names are stored only in the first column of the language.

## Citations

If you use PWS, please cite:



If you use the original Winograd schemata or any of the translations, please cite:

```bibtex
@inproceedings{levesque2012winograd,
  title={The Winograd Schema Challenge},
  author={Levesque, Hector and Davis, Ernest and Morgenstern, Leora},
  booktitle={Thirteenth International Conference on the Principles of Knowledge Representation and Reasoning},
  year={2012},
  organization={Citeseer}
}
```

If you use the Hungarian translation, please cite additionally:

Vadász, N., & Ligeti-Nagy, N. (2022). Winograd schemata and other datasets for anaphora resolution in Hungarian, Acta Linguistica Academica, 69(4), in press.
```
@article{vadaszligeti2022actawinograd,
      author = "Noémi Vadász and Noémi Ligeti-Nagy",
      title = "Winograd schemata and other datasets for anaphora resolution in Hungarian",
      journal = "Acta Linguistica Academica",
      year = "2022",
      publisher = "Akadémiai Kiadó",
      address = "Budapest, Hungary",
      volume = "69",
      number = "4",
      note = "In press."
}
```

Please find the citations to the French, Portuguese and Mandarin translations [here](resources.bib).


## License

PWS is available under CC-BY-SA 4.0 [licese](LICENSE).
