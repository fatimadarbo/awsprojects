# AWSProjects
# [ ] Create a list of AWS Service Inventory 

# 1) The list you'll create will be empty intially 
MyAWSservlist = [ ]

# 2) Populate the list using insert or append with the AWS services 
MyAWSservlist.insert("EC2")
MyAWSservlist.insert("Lambda")
MyAWSservlist.insert("Cloud9")
MyAWSservlist.insert("Elastic Beantalk")
MyAWSservlist.insert("SQS")
MyAWSservlist.insert("CloudTrail")
MyAWSservlist.insert("SNS")
MyAWSservlist.insert("DynamoDB")
MyAWSservlist.insert("S3")

# 3) Print the list and the length of the list
print(len(MyAWSservlist))


# 4) Remove two specific services from the list by name or by index
MyAWSservlist.remove("EC2") [1]
MyAWSservlist.remove("Cloud9") [3]

# 5) Print the new list and the new length of the list
print(len(MyAWSservlist)
