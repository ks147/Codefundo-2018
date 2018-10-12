# Codefundo-2018
                        <Title>
Natural disasters can have a life-altering impact on the individuals and families fortunate enough to survive them. How well the impact of a disaster event is absorbed has much to do with the intensity of the impact and the level of preparedness and resilience of the subject impacted.Keeping this in mind there is a lot of scope in increasing the level of  preparedness for a disaster which is why we’ve decided to make a project focusing on improving current frameworks for dealing with the aftermath of such horrific events.

In case of floods , there is need for the distribution of  relief material in the immediate aftermath and this needs to be done in the most efficient manner possible so as to reduce time ,effort and manpower all of which are precious resources in such a crisis. 

With our project we aim   
1. To find the best nodes for distribution and storage of relief material based on
   parameters such as -	
     - Population density of surrounding regions
     - Altitude,so as to stay above the flood-hit regions
2. To create a website that informs people in affected areas about the nearest centre for help.
   The reasons for creating this website are
      - The webpage would be minimal as the data connection in a flood might be quite bad 
        thus allowing people with even 2G to access important information
      - It would also allow government authorities about the people at a particular help centre thus allowing them to manage their                 resources efficiently based on the demand.
      - We plan on making the website using Django.

We aim to achieve this by using the K-means clustering algorithm where we use the above mentioned parameters and partition the area under the affected state into a grid (districts as defined by the government) we use the census population data to get population in each grid element and then run the K-means clustering algorithm to find the best nodes for relief camps.

                   
