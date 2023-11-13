
# Rohdsilab

R package to install essential packages for the OHDSI Lab image. It may also be
used to quickly install the base packages for general work using the ohdsilab

```
install.packages("pak")
pak::pkg_install("roux-ohdsi/Rohdsilab")
```

R package imports:
  - tidyverse,
  - renv,
  - cli,
  - devtools,
  - remotes,
  - pak,
  - glue,
  - usethis,
  - janitor,
  - DatabaseConnector,
  - DBI,
  - keyring,
  - CDMConnector,
  - OHDSI/CohortGenerator,
  - OHDSI/CohortDiagnostics,
  - OHDSI/FeatureExtraction,
  - OHDSI/ROhdsiWebApi
