# HOW TO HOST A STATIC WEBSITE IN AWS WITH TECH-KELVIN #
## My first hands on project as a DevOps engineer ##

### Please find outlined below the recommended steps for executing this project, accompanied by supplementary visual documentation for reference ###

1. **Create an S3 bucket, the following steps will guide you**
+ *Type S3 bucket on the search bar inside your AWS console*
+ *A page would pop up click on S3 bucket*
+ *click on create bucket*
+ *Input your bucket name (domain)*
+ *Unblock all public access*
+ *Disable bucket versioning*
+ *Enable bucket key*
+ *In object ownership (choose ACLs disabled)*
+ *Then click on create bucket*

2. **Uploading your files**
+ *Click on the created bucket*
+ *Click on upload*
+ *Choose the files to be added*
+ *Click on upload*
  
3. **To generate a policy, click on the bucket you just created to open it**
+ *For your policy, go to permision and generate bucket policy*
+ *After generationg your policy, go to property*
+ *Click on edit static website hosting and enable websit hosting*
+ *Check the "host a static website" option*
+ *Save the index document type as "index.html"*
+ *Error document is optional, you can leave it or type "error.html" and save changes*
![Web capture_21-6-2023_224044_s3 console aws amazon com](https://github.com/kelvind627/Class-Project/assets/136044631/888207c0-c99a-437d-861e-b697de0ec52d)




