# Design: How To Migrate Cluster Across Regions     :Feature:


---

How to migrate cluster across regions with minimum impact?  

---

Similar Posts:  
-   [Concepts For System Design](https://architect.dennyzhang.com/design-concept)
-   Tag: [#systemdesign](https://architect.dennyzhang.com/tag/systemdesign)

---

How to migrate cluster across regions with minimum impact?  
-   Migrate clustered system to another region with minimized impact? (Related reading: [here](https://docs.atlas.mongodb.com/move-cluster/))

    Declare the possible issues first: 
       dataset is big
       WAN latency
       unexpected defects in app or procedure
       etc