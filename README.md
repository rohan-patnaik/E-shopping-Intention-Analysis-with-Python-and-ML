# E-shopping-Intention-Analysis-with-Python-and-ML
A ecommerce intention analysis for the customer using K means clustering(and tried other techniques).


Currently there are 3 clusters but after some consideration I went forward with 2 cluster groups(will be updated sometime later).


![image](https://user-images.githubusercontent.com/22250758/137958393-be1d2072-bae7-4032-9f39-117bfd8a0519.png)

Made use of the K-elbow method to determine the number of clustering groups for the mentioned dataset.


![image](https://user-images.githubusercontent.com/22250758/137957995-8ff56830-f688-49d8-b8c6-401ef5e24da9.png)

Here are the confusion matrices we created using the above data.

![image](https://user-images.githubusercontent.com/22250758/137958200-24cdcb96-1c89-4bfa-8e42-a6276bd203bc.png)

# Some observations : 
We can see that out of 10,422 failed incomes, 9,769 are grouped into uninterested customers or 94%. However, out of 937 successful incomes, only 284 are grouped as target customers or 15%. Also, the adjusted index score is not very high.


# Conclusion :
Looking at the plot createdwe can say that customers who spent more time on the website we took the data from are very less likely to leave it after viewing atleast a single page of it.
