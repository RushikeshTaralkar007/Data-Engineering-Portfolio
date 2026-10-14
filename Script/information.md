
# Bronze Bucket Name - yt-data-pipeline-bronze-rushi
# Silver Bucket Name - yt-data-pipeline-silver-rushi
# Gold Bucket Name - yt-data-pipeline-gold-rushi

# Script Bucket Name - yt-data-pipeline-script-rushi



# SNS ARN : arn:aws:sns:ap-south-1:799953230332:yt-data-pipeline-alerts


###  This Is Database In Glue ###

# Glue Bronze - yt-pipeline-bronze-database

# Glue Silver - yt-pipeline-silver-database

# Glue Gold - yt-pipeline-gold-database


# Youtube API = AIzaSyBuuXwM-s0ngcXsDoPIiD5FHaq_i4pWQDI



### Bronze To Silver (ETL jobs)

# bronze database : - yt-pipeline-bronze-database
# bronze_table : - raw_statistics
# Silver Bucket : - yt-data-pipeline-silver-rushi
# Silver database : -  yt-pipeline-silver-database
# silver table : - clean_statistics


### Silver To Gold (ETL jobs)

# silver_database : yt-pipeline-silver-database

# gold_bucket : yt-data-pipeline-gold-rushi

# gold_database : yt-pipeline-gold-database