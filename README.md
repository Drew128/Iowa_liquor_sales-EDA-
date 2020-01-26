# Iowa_liquor_sales-EDA-
Exploratory Data Analysis on public dataset from BigQuery

<p>After running the very first chapter you will see a link to Google authorisation</p>
<p>Successfully authorised on thouse page you'll get a sequence of symbols</p>
Copy it and return to colab page, to paste it into thouse field with link
If you see printed "Authenticated" you can continue
In the next chapter you'll see something like this:
      ```    
      %%bigquery --project project_id df
      SELECT 
        *
      FROM `bigquery-public-data.iowa_liquor_sales.sales`
      ```
Please replace "project_id" with your Project ID from your GCP console (https://console.cloud.google.com/)

Now you can continue, to executing the file

