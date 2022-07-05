# Jojajovai Guarani-Spanish Parallel Corpus

Jojajovai is a Guarani-Spanish parallel corpus of about 30,000 sentence pairs, structured as a set of different sources.
This corpus is the result of a collaboration between Guarani MT researchers from Universidad de la República, Uruguay; Universidad Nacional de Itapúa, Paraguay; Universidade Tecnológica Federal do Paraná, Brazil; Universidad de Granada, Spain; and Universitat Oberta de Catalunya, Spain.

## Characteristics

The corpus is structured as a collection of subsets from different sources, further split into training, development and test sets.
A sample of sentences from the test set was manually annotated by native speakers in order to incorporate meta-linguistic annotations about the Guarani dialects present in the corpus and also the correctness of the alignment and translation.

We hope this data could be used not only to train machine translation systems, but also to test them and analyze the results with different levels of granularity according to the different subsets.

Source    | Pairs  | Train  | Dev   | Test
:--------:|:------:|:------:|:-----:|:-----:
abc       | 16,492 | 11,550 | 2,470 | 2,472
anlp      |  2,000 |      - |   996 | 1,004
blogs     |  2,444 |  1,712 |   361 |   371
hackaton  |    513 |    359 |    77 |    77
libro_gn  |  1,423 |    992 |   215 |   216
libro_td  |  1,016 |    711 |   153 |   152
seminario |  2,179 |  1,535 |   322 |   322
spl       |  4,788 |  3,348 |   720 |   720
Total     | 30,855 | 20,207 | 5,314 | 5,334

The file `jojajovai_all.csv` contains the data of the corpus.

## Annotations

Three native annotators were given a sample of sentence pairs from each set, are were asked to indicate the _dialect_ of the Guarani sentences (standard Guarani, Jopara, Jehe'a, or other possibilities), and to categorize the _correctness_ of the translation pair, with the following options:
- A: The sentences in the pair correspond completely.
- B: The Spanish sentence has more information.
- C: The Guarani sentence has more information.
- D: The sentences do not match.

The file `jojajovai_sample_annotations.csv` contains the annotations of the sample.

## Using the Data

If you use this dataset, please cite:

Luis Chiruzzo, Santiago Góngora, Aldo Alvarez, Gustavo Giménez-Lugo, Marvin Agüero-Torales, Yliana Rodríguez. (2022). _Jojajovai: A Parallel Guarani-Spanish Corpus for MT Benchmarking._ Proceedings of the 13th Language Resources and Evaluation Conference, LREC 2022.

You can contact us by [email at pln@fing.edu.uy](mailto:pln@fing.edu.uy).
