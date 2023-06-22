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
![image](https://github.com/kelvind627/Class-Project/assets/136044631/18765234-7d5d-4885-9cc8-ceeb1f2e73b8)

4. **To access your website page**
+ *Navigate to your bucket and click on it*
+ *Click on properties*
+  *Scroll down and click on the website url*
![20230622_002614](https://github.com/kelvind627/Class-Project/assets/136044631/d7b89e84-16b8-4a2a-bee3-60688280686d)

5. **Next step is to configure your route 53**
+ *Navigate to your AWS search bar and type in route 53*
+ *Click on create hosted zone*
+ *Input your domain name*
+ *Description is optional*
+ *Make hosted zone public*
+ *Click on create hosted zone*
+ *Go to the website where you purchased your domain and carry out the necessary configuration for the name servers*
+ *click on update and let it to update*
![image](https://github.com/kelvind627/Class-Project/assets/136044631/851e83e3-f2f4-49b0-8800-dfe360fafcf8)
![image](https://github.com/kelvind627/Class-Project/assets/136044631/fa37fb49-a589-4c60-8321-e745a59bd75d)

6. **Next is to create a certificate manager**
+ *Type in certificate manager on your AWS search bar*
+ *Navigate to certificate manager and click on request*
+ *Click on "request a public certificate" and click next*
+ *Input your domain name*
+ *In Validation method, choose DNS as it's faster*
+ *Click on requet*
+ *Copy out CNAME Name and CNAME value*
![image](https://github.com/kelvind627/Class-Project/assets/136044631/fcf96bfb-6766-43ae-8d99-b2ff77d1e5c6)


  





