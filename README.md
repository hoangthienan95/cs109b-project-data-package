# cs109b-project-data-package

Dependencies:
`conda install -c conda-forge intake`
`pip install intake-nested-yaml-catalog`

- Data can be organized in different ways in different catalogs. Data can be organized differently from file system
- One source of truth so no overwrite data by accident
- Versioning data
- Same API throughout, baked in explicit assumptions/extra arguments to load the data
- No more copying paths around multiple times in notebooks
- Access to data without having to download it
