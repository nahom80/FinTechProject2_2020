# Google Big Query Basics - Reddit example
#### Sources; 
    https://towardsdatascience.com/scrape-reddit-data-using-python-and-google-bigquery-44180b579892
    https://google-cloud-python.readthedocs.io/en/0.32.0/bigquery/usage.html
    https://cloud.google.com/docs/authentication/getting-started
    https://www.blendo.co/blog/access-data-google-bigquery-python-r/
    https://cloud.google.com/bigquery/docs/bigquery-storage-python-pandas
    
### Python installs
    pip install google-cloud
    pip install --upgrade google-cloud-bigquery
    
### Authentication
OAuth with Google Projects JSON
    
    You need to setup a service account for the particular project associated with the BigQuery discussed here:
    https://towardsdatascience.com/scrape-reddit-data-using-python-and-google-bigquery-44180b579892
    
    After getting familiar with using BigQuery from the example above start by clicking the link below. It will guide you on how to setup a service account and download a JSON file associated with it. Make sure you specify the proper project name ( Your google project name ) as well as the permissions
    
    https://console.cloud.google.com/apis/credentials/serviceaccountkey?_ga=2.139442999.543651156.1586710225-978365429.1586617633

after downloading the JSON make it available ( the path ) to your script via environmental var.

![](Images\BigQueryTut01.png)
    
    