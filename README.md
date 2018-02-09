# generic-eda-notebook
Generic Exploratory Data Analysis

See preview: [Generic EDA Jupiter Notebook](https://github.com/benji/generic-eda-notebook/blob/master/generic_eda.ipynb)


----
## 1. Define a schema.yaml for your data

    id: Id
    target: SalePrice
    columns:
      1stFlrSF:
        type: NUMERIC
      2ndFlrSF:
        type: NUMERIC
      3SsnPorch:
        type: NUMERIC
      Alley:
        categories:
        - NA
        - Grvl
        - Pave
        type: CATEGORICAL
        meaningful_order: true
    (...)


----
## 2. Launch the notebook
    jupiter notebook
