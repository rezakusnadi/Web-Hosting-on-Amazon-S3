# Web-Hosting-on-Amazon-S3

Previously im hosted my portfolio on GitHub, but recently im find out about hosting on amazon s3 and try to utilize it.
before that what and why amazon s3, scalable, object storage service provided by Amazon Web Services (AWS). It allows users to store and retrieve any amount of data,
at any time from anywhere on the web. S3 is designed to be highly durable, secure, and cost effective.
To hosted its just need 30 to 45 minutes.



**First its to setup an s3 bucket on amazon web services**

Create s3 bucket after you signup for the amazon web services, and select your own unique bucket name, choose storage region any additional configurations for
storage management.
Picked the region nearest to you, for me was Singapore on ap-southeast1.
for the bucket names are globally unique, no one can use your bucket's name unless you delete the bucket

![image](https://github.com/user-attachments/assets/5956a521-fe8d-4b8d-81ad-9c478794de44)



**Upload Files to s3**

Uploaded two files to my bucket index.html and src/ that contain with jpg, css, js for the index.html to load
that the blueprints for your web

![upload src dan html](https://github.com/user-attachments/assets/833b7ef8-902f-41c3-b158-7566a0faed98)


**Static Web Hosting**

To make the web go public for everyone access it, configure static web hosting, hosting type, index document
ACL (Access Control List) is the set of rule that determine who can access or modify resource, file, objects or services. It helps to specify access to users or group


**Bukcet Endpoints**

When its enable, the S3 produces a bucket endpoint URL on properties, which user can access the website, its simple and cost-effective solution
for serving static content

![image](https://github.com/user-attachments/assets/2d9796ce-5c7a-479c-a80d-739e197f44a0)


**Set the Object to Publics**

dont forget to set all of your data to publics, because your uploaded file is private on default.
If you dont want this to show after click the URL

![eror msg](https://github.com/user-attachments/assets/7e301b54-960f-4ffe-8ed9-30253cc455fb)

**Make sure to set all of the object**

![image](https://github.com/user-attachments/assets/9f20ebcc-37bb-4283-94e6-a27c89350f83)

**Result**

![home ss](https://github.com/user-attachments/assets/3045b641-ecd2-43e0-869c-fe60d75e00d3)




