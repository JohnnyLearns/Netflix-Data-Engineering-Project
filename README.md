# Netflix-Data-Engineering-Project
This project implements a Netflix analytics pipeline using dbt, Snowflake, and AWS.

##  Overview  
- **Tutorial-based:** Adapted from a YouTube tutorial on data engineering with dbt, Snowflake, and AWS.  
- **Pipeline Highlights:**  
  - Raw ingestion and staging layers (dbt models)  
  - Dimensional modeling (dim tables and fact tables)  
  - Snapshots to track historical changes  
  - Data testing for quality assurance  
- **Tech Stack:**  
  - **dbt** for modeling & transformations  
  - **Snowflake** as the data warehouse  
  - **AWS** (S3) for data storage/processing  
  - **Git/GitHub** for version control and documentation
    
##  Project Structure

```text
netflix-dbt/
├── models/
│   ├── staging/        # source models from raw data
│   ├── dim/            # dimension tables
│   ├── fct/            # fact tables
│   └── snapshots/      # snapshot models
├── seeds/
│   └── genome-tags.csv # static CSV seed file
├── macros/
│   └── custom_key.sql  # custom macro
├── dbt_project.yml     # dbt config
└── README.md           # docs
```

##  Learning Outcomes  

- **Orchestrated raw-to-dimension modeling** using dbt  
- **Applied multiple materializations**, including view, table, and snapshot  
- **Implemented historical tracking** with dbt snapshots  
- **Built robust data testing and documentation layers**  
- **Organized project structure** following analytics engineering best practices

Inspired by Darshil Parmar
