# Setup Instructions

1. Login to your Google account, and open [Google Cloud Console](https://console.cloud.google.com/).

![setup_1](../images/setup_1.png)

2. Click on `My Project` button on the top left, select an existing project, or create a new project.

![setup_2](../images/setup_2.png)

3. Once a project is selected, choose to run queries with BigQuery in the welcome page.

![setup_3](../images/setup_3.png)

4. In the Explorer, click on `+ ADD`, scroll down and select `Public Datasets`.

![setup_4](../images/setup_4.png)

5. Search for "Cymbal Investments", and click on the result displayed. In the product details page, click on `VIEW DATASET`.

![setup_5.1](../images/setup_5.1.png)

![setup_5.2](../images/setup_5.2.png)

6. There is a table named "trade_capture_report". Click on the actions icon on the right, and select `Query`, which opens a new SQL workspace tab, along with a sample query. Run the query by clicking on the `Run` button.

```sql
SELECT * FROM `bigquery-public-data.cymbal_investments.trade_capture_report` LIMIT 1000
```

![setup_6.1](../images/setup_6.1.png)

![setup_6.2](../images/setup_6.2.png)

7. Now you should be able to play around with the dataset, using the SQL queries provided in this repository.
