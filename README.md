# CSV import check examples

Before importing supplier data, check the header, identify the fields that make a row unique, and compare the export with an earlier file. This repository gives you a small fictional example for trying that workflow. It does not contain the paid kit.

| Sample | What to look for |
|---|---|
| [Previous export](samples/previous.csv) | Starting data with one row per SKU. |
| [Received file](samples/received.csv) | A renamed price header, a duplicate SKU and a blank price. |
| [Corrected example](samples/corrected.csv) | A cleaned comparison case: one addition, one removal and one change. |

1. Decide which columns the destination expects and identify the key.
2. Check both files separately. A missing value is different from a zero.
3. Review differences before importing. A file passing your checks does not guarantee the destination will accept it.

Use the [free browser check and field guide](https://vat-csv-import-guide.frozengem1.chatgpt.site/#quick-check) to try the example without uploading the data. For recurring exports, the [CSV Import Audit Kit page](https://vat-csv-import-guide.frozengem1.chatgpt.site/csv-import-audit.html?from=github) explains the local Python tool and its Gumroad purchase option.

Victoria Ops Tools is a project of Victoria Advanced Technologies. All sample records in this repository are invented.
