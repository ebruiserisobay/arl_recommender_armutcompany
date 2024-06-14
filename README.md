
# ARL Association Rule Learning (Armut Company)

##  Business Problem

Armut,largest online service platform in Turkey, brings together service providers and service recipients. It provides easy access to services such as cleaning, remodeling and transportation with a few taps on your computer or smartphone. A product recommendation system was created with Association Rule Learning using a data set that includes service users and the services and categories that these users have received.

##  About Dataset

The dataset consists of services taken by customers and the categories of these services.
Each purchased service includes date and time information.

* **UserId:** Customer number

* **ServiceId:** Anonymized services for each category. (Example: A sofa cleaning service under the cleaning category)

  A ServiceId can be found under different categories and represent different services under different categories.
  (Example: The service with CategoryId 7 and ServiceId 4 is radiator cleaning, while the service with CategoryId 2 and ServiceId 4 is furniture assembly)

* **CategoryId:** Anonymized categories. (Example: cleaning, moving, renovation categories.

* **CreateDate:** The date the service was purchased
