# Committed dataset

**Source dataset:** SciFact, BEIR packaging

**Selection:** Complete BEIR SciFact corpus, queries and published relevance splits, converted from JSONL/TSV to CSV.

**Data license:** [CC BY 4.0 claims/annotations; ODC-By 1.0 abstracts](https://github.com/allenai/scifact/blob/master/LICENSE.md). This applies to the data, independently of the project code.

## Sources

- https://github.com/allenai/scifact
- https://public.ukp.informatik.tu-darmstadt.de/thakur/BEIR/datasets/scifact.zip
- https://raw.githubusercontent.com/allenai/scifact/master/LICENSE.md

## CSV files

| File | Rows | Bytes |
|---|---:|---:|
| [corpus.csv](raw/corpus.csv) | 5,183 | 7,840,459 |
| [queries.csv](raw/queries.csv) | 1,109 | 104,728 |
| [qrels_train.csv](raw/qrels_train.csv) | 919 | 13,582 |
| [qrels_test.csv](raw/qrels_test.csv) | 339 | 5,049 |

Attribution: David Wadden and the Allen Institute for AI SciFact team; Semantic Scholar S2ORC for abstracts; BEIR authors for benchmark packaging. Source identifiers and split-specific qrels are preserved. Relevant evidence may support or refute a claim; the relevance labels do not themselves encode truth.

The CSV files contain published observations or their documented format conversion; no training records were invented. Source formats and raw CSV exports are distinguished by the manifest. File checksums and schemas are recorded in [csv-manifest.json](csv-manifest.json).
