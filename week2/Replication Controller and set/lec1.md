# Replication Controllers and Replication Set

**Controllers**: are brain behind kubernetes. They're processes that monitor objects and respond accordingly.


**Why we Need Replica controller**: Due to some error in pod or application crashes , user not able to access application, To prevent user from accessing application, we would like to have more than one pod at a time. It also provide high availabiltity, Load Balancing and Scaling. 


There are two terms are used for replication 
1. Replication Controller (old Method)
2. Replica Set (New and Recommended)

**Replication Controller** : 