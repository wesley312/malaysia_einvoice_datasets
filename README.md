# Malaysia E-Invoice Related Data
Collection of datasets related to Malaysia E-Invoice implementation.

## 🔍 Data Files
This project provides the following data files:
| File Name | Description |
| --- | --- |
| `einvoice_request_portal.csv` | Collection of website, portal for buyer to request e-invoice from. |
| `einvoice_platform.csv` | Collection of e-invoice platform, system, or service providers. |

## 📖 Documentation & Validation
All data files should contain a corresponding schema/metadata file describing the dataset structure for automated validation.
These are the standard we adhere to 
| File Type | Standard |
| --- | --- |
| `csv` | [W3C Metadata Vocabulary for Tabular Data](https://www.w3.org/TR/2015/REC-tabular-metadata-20151217/) |

### How to validate
#### `csv` file
- Using `csvw` Python package
```sh
# Install csvw using pip
pip install csvw
# Run validation
csvwvalidate FILENAME-metadata.json

# If using uv, you may run validation directly
uvx --from csvw csvwvalidate FILENAME-metadata.json
```
- Using web based validator: [CSVLint.io](https://csvlint.io/).

## 👥 Contribution
We welcome contributions. Follow these guidelines when adding new datasets or schemas:
1. New Datasets:
    - Open an issue with a title like "Add Dataset: DATASET_NAME".
    - Ensure the data is clean.
    - Schema/metadata file is a must.
2. Schema Change:
    -  Open an issue with a title like "Change Schema: DATASET_NAME".
3. Adding or Update Data to Existing Dataset:
    - Open a pull request with a checklist: [ ] Schema Validated, [ ] Data Quality Check Passed.

## 📘 How to Use
You can directly download the file from this repository. You need to credit back to us and make clear that the data is available under the Open Database License.

Example of attribution notice:
> Data from [Malaysia E-invoice Datasets](https://github.com/wesley312/malaysia_einvoice_datasets), licensed under [ODbL](https://opendatacommons.org/licenses/odbl/1-0/).

## 📄 License
This dataset is licensed under the Open Database License (ODbL) version 1.0. See the [LICENSE.md](./LICENSE.md) file for the full text or read the official license [here](https://opendatacommons.org/licenses/odbl/1-0/).