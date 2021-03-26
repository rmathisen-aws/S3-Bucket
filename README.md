# S3 Bucket

With S3, you do not have to choose a region. \
When you create Buckets within S3, you have to pick the region that the bucket is created in. \
Because S3 uses a Global Namespace, you don't have to select a region when using the console.

**Create an S3 Bucket:**\
S3 → Buckets → Create Bucket 

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
**To View the Bucket's Amazon Resource Name (ARN):** \
Click on the Bucket → Properties \
ARN - uniquely references 1 resource in AWS (resource identifier)
![image](https://user-images.githubusercontent.com/80132085/112653438-ccbf7b80-8e24-11eb-8856-f27a3dc8273d.png)

\
**Upload Objects to S3 Bucket:** \
