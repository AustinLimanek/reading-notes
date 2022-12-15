# Class 37

[Journal Home](README.md)

Current Readings:

1. [Introduction to Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/Welcome.html)
2. [S3 with Amplify](https://docs.amplify.aws/lib/storage/getting-started/q/platform/android/)

## Reading Notes

### Introduction to Amazon S3

Amazon Simple Storage Service (Amazon S3) is an object storage service that offers a range of storage classes designed for different use cases. It also provides management features so that you can optimize and configure access to your data to meet your specific business, organizational, and compliance requirements. Amazon S3 offers a range of storage classes designed for different use cases, such as S3 Standard for frequent access, S3 Standard-IA or S3 One Zone-IA for infrequently accessed data, and S3 Glacier Instant Retrieval, S3 Glacier Flexible Retrieval, and S3 Glacier Deep Archive for archival purposes.

It also offers storage management features such as S3 Lifecycle, S3 Object Lock, S3 Replication, and S3 Batch Operations. Amazon S3 also offers access management features such as S3 Block Public Access, AWS Identity and Access Management (IAM), bucket policies, and Amazon S3 access points. It is also compliant with the Payment Card Industry Data Security Standard (PCI DSS).

### S3 with Amplify

The Amplify Storage category is an interface for managing user content for an app in public, protected, or private storage buckets. The Amplify CLI helps users create and configure the storage buckets for their app. The Amplify AWS S3 Storage plugin leverages Amazon S3. To set up and configure an application with Amplify Storage, the user needs to provision backend storage, install Amplify libraries, initialize Amplify Storage, and then complete a simple upload file example. The user must also have an Android application targeting Android API level 24 or above.

## Things I want to know more about

After working on the lab I still don't know how to access image files from S3. I seem to only be able to do this when using a hard-coded string, which is very strange.

&copy; 2022, NoMichi
