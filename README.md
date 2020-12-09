# Amazon Web Services and EMR
In this labsheet we will deploy and run a simple MapReduce program onto AWS using Elastic MapReduce (EMR).
Please refer to the official [AWS getting started guide](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-gs.html) for details.

Currently there is no free tier version of EMR but you can apply to get AWS credits through [AWS Educate](https://aws.amazon.com/education/awseducate/) as a student.

## Setting up a Cluster
The key steps are as follows:
1. Develop your processing app (and identify your data)
2. Upload yoru application onto Amazon S3
3. Create an S3 bucket and an EC2 Key Pair
4. Configure and launch your EMR cluster
5. Monitor the cluster (optional), see [AWS manual](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-manage-view.html)
6. Retrieve output (on S3 or HDFS)

# Google DataProc
An alternative managed Hadoop MapReduce cloud service that is recently catching up with AWS is Google Cloud DataProc.
You can avail of 300$ credits as a new user when you sign in.
