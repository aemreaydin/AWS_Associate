# EC2 - Elastic Compute Cloud

## What is EC2?
A webservice that provides secure, resizable compute capacity
in the cloud. Designed to make web-scale cloud computing easier 
for developers.

## EC2 Options
* On Demand - Pay a fixed rate by the hour, no commitments
* Reserved - 1-3 year commitments, significant discount on the hourly charge
* Spot - Bid whatever price you want for the instance
* Dedicated Hosts - Physical EC2 server dedicated for your use. Can help reduce costs
by allowing you to use your existing server-bound software licenses.

|Family   |Speciality   |Use case   |
|---|---|---|
|F1|Field Programmable Gate Array|Genomics research, financial analytics, real-time video processing|
|I3|High Speed Storage|NoSQL DBs, Data Warehousing etc.|
|G3|Graphics Intensive|Video Encoding / 3D Application Streaming|
|H1|High Disk Throughput|MapReduce-based workloads, distributed file systems such as HDFS|
|T2|Lowest Cost, General Purpose|Web Servers, Small DBs|
|D2|Dense Storage|File servers/Data Warehousing/Hadoop|
|R4|Memory Optimized|Memory Intensive Apps/DBs|
|M5|General Purpose|Application Servers|
|C5|Compute Optimized|CPU Intensive Apps/DBs|
|P3|Graphics/General Purpose GPU|Machine Learning, Bitcoin Mining|
|X1|Memory Optimized|SAP HANA/Apache Spark|

##### F I G H T D R M C P X

## What is EBS - Elastic Block Storage
Allows you to create storage volumes and attach them to Amazon EC2 instances.
Are placed in a specific availability zone and replicated to protect the user from the
failure of a single component.

## EBS Volume Types
* General Purpose SSD(GP2)
    * Price/Performance Balance
    * Ratio of 3 IOPS for GB with up to 10000 IOPS.
    
* Provisioned IOPS(IO1)
    * Designed for I/O intensive applications
    * Use if you need more than 10000 IOPS.
    * Can provision up to 20000 IOPS per volume.
    
* Throughput Optimized HDD(ST1)
    * Big data, data warehouses, log processing
    * Cannot be a boot volume

* Cold HDD(SC1)
    * The lowest cost storage for infrequently accessed workloads
    * File server
    * Cannot be a boot volume
    
* Magnetic(Standard)
    * Legacy
    * The lowest cost per GB of all EBS volumes that is bootable.
    * Ideal for workloads where data accessed infrequently.
    
