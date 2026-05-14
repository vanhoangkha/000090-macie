---
title : "Create Custom data identifiers"
date: 2024-01-01
weight : 3
chapter : false
pre : " <b> 3. </b> "
---

#### Create Custom data identifiers

1. Access the **Macie** console

    - Select **Create job**

![Macie](/images/2/0001.png?featherlight=false&width=90pc)

2. Perform job configuration, the first step is **Choose S3 bucket**

   - Select **Select specific buckets**
dx
![Macie](/images/2/0002.png?featherlight=false&width=90pc)

3. Select **S3 bucket**, we have created.

![Macie](/images/2/0003.png?featherlight=false&width=90pc)

4. Next step, execute **Review S3 bucket**.

![Macie](/images/2/0004.png?featherlight=false&width=90pc)

5. Implement **Refine the scope**

   - Select **Include existing objects**
   - Select **One-time job**
   - Select **Next**

![Macie](/images/2/0005.png?featherlight=false&width=90pc)

6. Configure **Object criteria**

   - Select **File name extensions**
   - Enter **```csv```**
   - Select **Include**

![Macie](/images/2/0006.png?featherlight=false&width=90pc)

7. Select **Next**

![Macie](/images/2/0007.png?featherlight=false&width=90pc)

8. Execute **Select managed data identifiers**

   - Select **All**
   - Select **Next**

![Macie](/images/2/0008.png?featherlight=false&width=90pc)

9. Create **Manage custom identifiers**

![Macie](/images/2/0009.png?featherlight=false&width=90pc)

10. In the **Custom data identifiers** interface, select **Create**.

![Macie](/images/2/00010.png?featherlight=false&width=90pc)

11. For **Name**, enter **```EmpID```**

    - **Regular expression**, enter **```[a-z][2][0-9][4]```**

![Macie](/images/2/00011.png?featherlight=false&width=90pc)

12. Select **Submit**

![Macie](/images/2/00012.png?featherlight=false&width=90pc)

13. Create **Custom data identifiers** successfully.

![Macie](/images/2/00013.png?featherlight=false&width=90pc)