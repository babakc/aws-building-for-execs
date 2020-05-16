+++
title = "Step by Step"
weight = 2
+++

1. To begin, navigate to **AWS Personalize** and start by creating a Dataset group named {{<copypaste id="tooltiptext0" text="orders-team#">}} 
2. Once the dataset group is created, we need to upload 3 sets of data in CSV format, which the Octank data team has prepared:

    - Purchase history for each user. Call the dataset {{<copypaste id="tooltiptext1" text="user-purchase-history-team#">}} and leave the schema details as is. The schema details dictate what the structure of your data file looks like. After clicking **Next**, call the dataset import name  {{<copypaste id="tooltiptext2" text="import-purchase-history-team#">}} and specify the S3 location as {{<copypaste id="tooltiptext3" text="s3://codingforexecs/extract/personalize/items-by-user/">}}. Leave the IAM Service Role as default and select **Finish**.

    - User information, including optional demographic information. Call the dataset {{<copypaste id="tooltiptext4" text="users-team#">}} and leave the schema details as is. After clicking **Next**, call the dataset import name {{<copypaste id="tooltiptext5" text="import-users-team#">}} and specify the S3 location {{<copypaste id="tooltiptext6" text="s3://codingforexecs/extract/personalize/users/">}}. Leave the IAM Service Role as default and select **Finish**.

    - Item data. Call the dataset {{<copypaste id="tooltiptext7" text="items-team#">}} and leave the schema details as is. After clicking **Next**, call the dataset import name {{<copypaste id="tooltiptext8" text="import-items-team#">}} and specify the S3 location {{<copypaste id="tooltiptext9" text="s3://codingforexecs/extract/personalize/items/">}}. Leave the IAM Service Role as default and select **Finish**.

3. The data is now being imported and prepared to train your machine learning model, as per the screenshot below. This is going to take a bit of time, so let’s come back to it after we’ve created our voice interface.

![activity-1](/images/activity-2-01.png)