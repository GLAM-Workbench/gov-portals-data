# GLAM datasets from government data portals

Current version: [v1.0](https://github.com/GLAM-Workbench/gov-portals-data/releases/tag/v1.0)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13958899.svg)](https://doi.org/10.5281/zenodo.13958899)

This dataset contains information about open access datasets made available by Australian GLAM organisations through government data portals. The dataset was created by harvesting data from state and national portals. The method is documented in [this notebook](https://glam-workbench.net/glam-data-portals/#harvesting-glam-data-from-government-portals) in the GLAM Workbench.

There are three files:

- `glam-datasets-from-gov-portals.csv`
- `glam-datasets-from-gov-portals-csvs.csv`
- `glam_datasets_from_gov_portals.md`

## `glam-datasets-from-gov-portals.csv`

This dataset contains details of all of the individual data files contained within datasets shared by GLAM organisations through government data portals.  It contains the following columns:

| Column | Contents |
|--------|----------|
`dataset_title` | name of the dataset
`publisher` | name of the GLAM organisation contributing the data
`author` | usually the same as `publisher` but can contain other information such as an email address
`dataset_issued` | date when this dataset was published
`dataset_modified` | date when this dataset was last modified
`dataset_description` | description of the dataset
`source` | the portal through which the dataset is published, eg: `data.qld.gov.au`
`info_url` | link to page providing more information
`start_date` | earliest date of data within this dataset
`end_date` | latest date of data within this dataset
`file_title` | title of data file within this dataset
`download_url` | link to download data file
`format` | format of data file, eg 'CSV'
`file_description` | description of data file
`file_created` | date when this data file was created
`file_modified` | date when this data file was last modified
`file_size` | size of the data file
`licence` | licence applied to data file

## `glam-datasets-from-gov-portals-csvs.csv`

This dataset contains details of all of the individual data files in CSV format contained within datasets shared by GLAM organisations through government data portals.  It contains the following columns:

| Column | Contents |
|--------|----------|
`dataset_title` | name of the dataset
`publisher` | name of the GLAM organisation contributing the data
`author` | usually the same as `publisher` but can contain other information such as an email address
`dataset_issued` | date when this dataset was published
`dataset_modified` | date when this dataset was last modified
`dataset_description` | description of the dataset
`source` | the portal through which the dataset is published, eg: `data.qld.gov.au`
`info_url` | link to page providing more information
`start_date` | earliest date of data within this dataset
`end_date` | latest date of data within this dataset
`file_title` | title of data file within this dataset
`download_url` | link to download data file
`format` | format of data file, eg 'CSV'
`file_description` | description of data file
`file_created` | date when this data file was created
`file_modified` | date when this data file was last modified
`file_size` | size of the data file
`licence` | licence applied to data file


## `glam_datasets_from_gov_portals.md`

This is [a markdown-formatted list of data files](https://github.com/GLAM-Workbench/gov-portals-data/blob/main/glam_datasets_from_gov_portals.md) grouped by publishing organisation and dataset.

