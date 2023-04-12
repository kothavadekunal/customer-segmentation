# customer-segmentation
Segment customers visiting shopping mall based on the Invoice data.

### Approach
* Calculated the Recency,Frequency & Monetary metrics for the customers based on the invoices generated.
  * Recency - The freshness of the customer activity be it purchases or visits e.g. time since last visit or engagement at the mall.
  * Frequency - The frequency of customer transactions or visits.e.g total number of transactions between visits.  
  * Monetary - The intention of the customer to spend or purchasing popwer of the customer.e.g Total transaction value.
* Classified the customers based on RFM score into
  1. Passerby customers - Customers who are not after anything in particular. only buy what might catch their attention.
  2. Loyal customers - customers who shop regularly and love this shopping mall
  3. New customers - customers who enjoy their last visit to shop and may come back if they find out more about what this mall has to offer
  4. Out-of-town customers - They were once loyal customers, but they move to new place and find a closer shopping mall
  5. Students - Customers who visit the store often but they dont spend much
  6. Dissatisfied customers - They spend a lot on shopping, but the previous purchase didnt suit them
  7. Soon-to-be loyal customers - they are 'soon-to-be' loyal customers if the previous purchase suited them and the mall catches their attention

![Segmentation](https://github.com/kothavadekunal/customer-segmentation/blob/main/segmentation.png?raw=true)


