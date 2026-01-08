# Technical Case – Dadosfera

This repository contains the technical case developed for the Dadosfera selection process, demonstrating an end-to-end data lifecycle using the Dadosfera platform.

## Dataset
NYC Taxi Trip Records – Yellow Taxi

## Project Scope
The project follows the data lifecycle approach, covering ingestion, exploration, data quality, and analytical visualization.


## Item 0 – Project Planning

The project planning was organized using a Kanban board in Jira, following agile principles and a Kanban-based workflow.

Below is a snapshot of the Kanban board used during the project execution.

![Kanban: Technical Case - Dadosfera](docs/jira_kanban.png)


## Item 1 – Dataset Selection and Description

### Dataset Description
For this technical case, the **NYC City Taxi Trip Records** dataset was selected. This dataset is publicly available and contains detailed information about taxi trips performed in New York City.

Each record represents a single taxi trip, including attributes related to time, location, distance, passenger count, and fare values.

---

### Dataset and Volume
The NYC Taxi dataset contains **millions of records**, therefore fully complying with the requirement of having more than **100,000 records**, as specified in the case instructions.

---

### Domain Representation
The dataset represents the **urban mobility and transportation domain**, allowing analyses related to operational behavior, temporal patterns, and revenue distribution. This makes it suitable for demonstrating an end-to-end analytical data workflow within the proposed scenario.

This dataset was selected among the examples suggested in the case description.


## Item 2 – Data Integration

### Ingestion Asset
An ingestion asset was created using the **Novo arquivo** option available in the *Coletar > Importar arquivos* module.

The dataset was imported in Parquet format.

**Ingestion Asset Details:**
- **Name:** nyc_taxi_trip_records
- **Description:** manual ingestion of NYC Taxi Trip Records dataset

---

### Dataset Upload
After the upload process, the dataset became available as a table within the Dadosfera environment.

![Dataset successfully uploaded and available](docs/dadosfera_dataset_ingestion.png)

---

### Initial Validation
After ingestion, a basic validation was performed to confirm successful loading, correct schema recognition, and data availability for downstream analysis.

The dataset is ready for the exploration and cataloging phase.

![Dataset preview and record count confirmation](docs/dadosfera_dataset_preview.png)


