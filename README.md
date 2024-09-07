# cymbal-investments

Google Cloud BigQuery Public Dataset - Cymbal Investments
<br><br>
Please refer to the instructions [here](./docs/setup_instructions.md) for setting up BigQuery dataset and workspace.

## Project Structure

```log
├── data/
├── docs/
├── images/
├── src/
└── cymbal_investments_visualization.pbix
```
* `data/` stores the sample dataset and all query results for further evaluation & visualization.
* `docs/` includes project documents such as setup instructions.
* `images/` stores all the image files to be displayed by the documents.
* `src/` contains SQL (BigQuery) source codes for generating result datasets. Each file contains a single query that could be run on Google Cloud workspace.
* `cymbal_investments_visualization.pbix` is the Power BI source file for results visualization.
