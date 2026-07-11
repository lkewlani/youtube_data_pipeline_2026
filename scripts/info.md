Bronze layer S3 bucket name - yt-data-pipeline-ap-south-1-bronze
Silver layer S3 bucket name - yt-data-pipeline-ap-south-1-silver
Gold layer S3 bucket name - yt-data-pipeline-ap-south-1-gold

S3 bucket name - Scripts- yt-data-pipeline-ap-south-1-script

SNS ARN - arn:aws:sns:ap-south-1:521029941166:yt-data-pipelines-alerts-dev:68690917-2845-490e-b2ad-72e5b0c5ea6c

Glue Database:
yt_pipeline_bronze_dev
yt_pipeline_silver_dev
yt_pipeline_gold_dev


--bronze_database yt_pipeline_bronze_dev
--bronze_table raw_statistics
--silver_bucket yt-data-pipeline-ap-south-1-silver
--silver_database yt_pipeline_silver_dev
--silver_table cleaned_statistics

