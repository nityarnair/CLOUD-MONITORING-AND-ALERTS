# CLOUD-MONITORING-AND-ALERTS

**COMPANY** : CODTECH IT SOLUTIONS

**NAME** : NITYA R NAIR

**INTERN ID** : CT04DK556

**DOMAIN** :  CLOUD COMPUTING

**DURATION** : 4 WEEKS 

**MENTOR** : NEELA SANTOSH

#DESCRIPTION :
For this internship task, I was assigned to set up cloud monitoring and alerts for a cloud-based application using services like AWS CloudWatch, Google Cloud Monitoring, or Azure Monitor. I decided to use AWS CloudWatch along with an EC2 instance, as it’s straightforward to work with and well-documented for beginners.

I started by launching a simple Amazon EC2 instance using the free tier. I selected the t2.micro instance type and used the Amazon Linux operating system. Although I didn’t deploy a full application, the EC2 instance itself generates useful metrics like CPU usage, disk operations, and network traffic — all of which can be monitored using CloudWatch.

Once my EC2 instance was up and running, I headed over to AWS CloudWatch. CloudWatch automatically begins collecting basic metrics from EC2 instances, so I didn’t have to set up anything extra to start seeing data like CPU utilization. These metrics are updated every few minutes and can be used to identify how well the server is performing.

The main part of this task involved setting up an alert. I created a CloudWatch Alarm to notify me if the CPU usage goes above 80%. For the condition, I configured the alarm to trigger if the CPU utilization was greater than 80% for 1 out of 1 evaluation period, with each period set to 5 minutes. This means that if the instance CPU usage goes over 80% even once in a single 5-minute interval, the alarm would go off.

To get notified when this happens, I used AWS SNS (Simple Notification Service). I created a new SNS topic and subscribed to it with my email address. Once I confirmed the email subscription, the alarm was ready to send me an email alert if the condition was met. This kind of setup is super useful in real-life scenarios, where quick awareness of resource spikes can prevent bigger issues.

To complete the task, I also built a CloudWatch Dashboard to visualize the instance’s performance. I added graphs for CPU utilization, disk read/write, and network traffic. These widgets provided a live, visual representation of how my EC2 instance was behaving. Having a dashboard like this helps in continuously monitoring the health of cloud resources and spotting any abnormal activity quickly.

Overall, this task gave me hands-on experience with AWS monitoring tools. I learned how to monitor cloud infrastructure, create meaningful alerts, and build dashboards for performance visualization. This kind of setup is essential for any cloud-based project, especially when it comes to maintaining reliability and catching problems before they affect users. I now feel much more confident using CloudWatch and EC2 for cloud monitoring and will definitely apply this knowledge in future cloud or DevOps projects.

##OUTPUT :

![Image](https://github.com/user-attachments/assets/f9c08024-7905-4c40-b56b-a67e0f45559f)
