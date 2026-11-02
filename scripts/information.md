Bronze Bucket Name - yt-data-pipeline-ravi-bronze-ap-south-1-dev
Silver Bucket Name - yt-data-pipeline-ravi-silver-ap-south-1-dev
Gold Bucket Name -  yt-data-pipeline-ravi-gold-ap-south-1-dev

Script Bucket - yt-data-pipeline-ravi-script-ap-south-1-dev

SNS ARN - arn:aws:sns:ap-south-1:206986907456:yt-data-pipeline-alerts-dev:ca39176c-03e9-4a87-9f68-64b77dcf569c

Glue Bronze - yt_pipeline_bronze_dev
Glue Silver - yt_pipeline_silver_dev
Glue Gold -  yt_pipeline_gold_dev


--bronze_database yt_pipeline_bronze_dev
--bronze_table raw_statistics
--silver_bucket yt-data-pipeline-ravi-silver-ap-south-1-dev
--silver_database yt_pipeline_silver_dev
--silver_table clean_statistics

--silver_database yt_pipeline_silver_dev
--gold_bucket yt-data-pipeline-ravi-gold-ap-south-1-dev
--gold_database yt_pipeline_gold_dev