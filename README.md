# GCP Image Processing

This is part of qwiklab where Apache Spark on Cloud Dataproc is used to distribute a computationally intensive image processing task onto a cluster of machines

Steps followed:

    1. Created a virtual Machine instance
    2. Installed the required software (sbt and Scala)
    3. Created a GCS bucket and collected images
    4. Created a DataProc cluster
  <img width="370" alt="cloud" src="https://user-images.githubusercontent.com/47410643/79624178-102a4980-80ee-11ea-9993-927451587314.PNG">

    5. The job was submitted to cloud DataProc
    6. When the job was completed, the images were stored in the bucket created.
    
 <img width="890" alt="cloud" src="https://user-images.githubusercontent.com/47410643/79624444-9a26e200-80ef-11ea-86e1-4a538e7791b8.PNG">
