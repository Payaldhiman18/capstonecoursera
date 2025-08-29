
Unit Tests for the API:

The API has dedicated unit tests covering all endpoints, ensuring correct responses for different inputs, including edge cases.

Unit Tests for the Model:

The model includes unit tests for prediction outputs, input validation, and performance on test datasets.

Unit Tests for Logging:

Logging mechanisms are tested to confirm that relevant events, errors, and warnings are correctly captured.

Single Script Execution for All Unit Tests:

All unit tests can be executed using a single command (pytest or equivalent), and they pass successfully, ensuring end-to-end test coverage.

Performance Monitoring Mechanism:

Performance metrics such as latency, throughput, and model accuracy are monitored using automated scripts or dashboards. Alerts are triggered if metrics deviate from expected thresholds.

Isolation of Read/Write Tests from Production:

Tests involving data read/write operations are isolated from production models and logs to avoid interfering with live systems. Mock databases or temporary directories are used.

API Functionality Verification:

The API provides predictions as expected. Users can query predictions for a specific country or aggregate results for all countries combined.

Automated Data Ingestion:

Data ingestion is implemented as a reusable function or script, facilitating automation and reproducibility in the workflow.

Multiple Model Comparison:

Different models were trained and evaluated, comparing metrics such as accuracy, F1-score, and inference speed to identify the best-performing model.

EDA Using Visualizations:

Exploratory Data Analysis included multiple visualizations (histograms, scatter plots, correlation matrices) to understand data distribution and feature relationships.

Containerization with Docker:

The entire solution, including API, model, and supporting scripts, is containerized within a Docker image for reproducible deployment across environments.

Model vs. Baseline Visualization:

A visual comparison of the selected model against a baseline model was performed, showing improvements in performance metrics and supporting informed decision-making.
