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

click Add Files → select any files you want to Upload \
Notice the option to Add Folder. \
Remember, S3 is a Flat Structure. This doesn't actually create a folder. It creates a file, which emulates a folder.

![image](https://user-images.githubusercontent.com/80132085/112654937-4ad05200-8e26-11eb-9fd5-ccbc5a91dc84.png)

We won't be enabling bucket versioning for this lab. This will be covered later on.

![image](https://user-images.githubusercontent.com/80132085/112655733-1610ca80-8e27-11eb-93da-9914df381f6f.png)

Additional Upload Options

Storage Class: Standard (by default)

Upload

\
**Create a Folder & Upload Files:**

![image](https://user-images.githubusercontent.com/80132085/112656614-f4fca980-8e27-11eb-9dc2-2e1a33bc8787.png)

Remember, S3 is a Flat Structure. This doesn't actually create a folder. It creates a file, which emulates a folder.

![image](https://user-images.githubusercontent.com/80132085/112656736-11004b00-8e28-11eb-8be5-0455cc1b5c9c.png)

Name the Folder → Create Folder

![image](https://user-images.githubusercontent.com/80132085/112657127-781dff80-8e28-11eb-90c3-8d70a4360fe8.png)

This doesn't actually create a folder called "archive". It creates an Object with this name.

![image](https://user-images.githubusercontent.com/80132085/112657574-f37fb100-8e28-11eb-9058-a383352d7fcc.png)

Click archive/ → Upload → Add Files → select files → Upload

\
**Viewing these Uploaded Files:**

![image](https://user-images.githubusercontent.com/80132085/112658415-c1bb1a00-8e29-11eb-857f-c14476f060a6.png)

![image](https://user-images.githubusercontent.com/80132085/112658951-4d34ab00-8e2a-11eb-9c39-f2431b0ddffe.png)

Click on any of these uploaded files, and open the Object URL in a New Tab. \
You are presented an "AccessDenied" error. You are trying to access this Object with no Authentication. \
You are trying to access this as an Unauthenticated User. \
All S3 Objects & S3 Buckets are Private by default. 

You won't be able to access this object without authenticating to AWS, unless you grant Public access to this object.

Close that error tab

![image](https://user-images.githubusercontent.com/80132085/112659292-9ab11800-8e2a-11eb-90af-953444675a01.png)

To view your file, \
Object Actions → Open

Notice your URL contains the Authentication! \
YOU are now accessing this object as yourself with your user permissions. \
You, as the S3 creator, and the Root User have these permissions.

\
\
**Clean Up Time!!**

![image](https://user-images.githubusercontent.com/80132085/112660119-799cf700-8e2b-11eb-9f1f-af5bd4f24e18.png)

Cleaning up is a 2 step Process: \
Empty the Bucket \
Delete the Bucket














