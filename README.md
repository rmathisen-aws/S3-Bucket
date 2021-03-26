# S3 Bucket

With S3, you do not have to choose a region. \
When you create Buckets within S3, you have to pick the region that the bucket is created in. \
Because S3 uses a Global Namespace, you don't have to select a region when using the console.

**Create an S3 Bucket:**\
S3 → Buckets → Create Bucket 

![image](https://user-images.githubusercontent.com/80132085/112653538-e82a8680-8e24-11eb-8ec3-4a3a4c33f512.png)

Bucket Name: koalacampaign922 \
Naming Rules: **Globally Unique**, all lowercase letters, numbers, dots(.), and hyphens(-), no underscores, \
start with a lowercase letter or number, can't be IP Formatted (192.168.5.4), can't begin with xn--

Region: us-east-1 

Copy settings from existing bucket: \
If you have any existing buckets, and you want to copy the settings from those buckets, then click "Choose Bucket" to copy these settings.

All Buckets by default are Private. \
Uncheck "Block all public access" and acknowledge that you accept all responsibility

Create Bucket

\
**To View the Bucket's Amazon Resource Name (ARN):**

![image](https://user-images.githubusercontent.com/80132085/112653438-ccbf7b80-8e24-11eb-8856-f27a3dc8273d.png)

Click on the Bucket → Properties \
ARN - uniquely references 1 resource in AWS (resource identifier)

\
**Upload Objects to S3 Bucket:**

![image](https://user-images.githubusercontent.com/80132085/112654458-cda4dd00-8e25-11eb-8e99-b4da5b9f135a.png)

Select Bucket → Objects → Upload


![image](https://user-images.githubusercontent.com/80132085/112654680-05138980-8e26-11eb-8221-e5a8c362da25.png)

click Add Files → select any files you want to Upload

![image](https://user-images.githubusercontent.com/80132085/112654937-4ad05200-8e26-11eb-9fd5-ccbc5a91dc84.png)

We won't be enabling bucket versioning for this lab. This will be covered later on.

![image](https://user-images.githubusercontent.com/80132085/112655733-1610ca80-8e27-11eb-93da-9914df381f6f.png)

Additional Upload Options

Storage Class: Standard (by default)

Upload


























