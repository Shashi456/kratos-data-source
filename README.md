# kratos-data-source

**Pre-processing required.**

json
  - [categories](https://github.com/abhay-iy97/kratos-data-source/tree/master/categories): data segregated per category per country.
  - [keywords](https://github.com/abhay-iy97/kratos-data-source/tree/master/keywords): keyword based data.
  - [sources](https://github.com/abhay-iy97/kratos-data-source/tree/master/sources): data segregated by language per news source.
  - [topHeadlines](https://github.com/abhay-iy97/kratos-data-source/tree/master/topHeadlines): top headlines of every country.

article
  - same first-level file structure as json. Differs in deeper structure as it contains the articles per url in the files mentioned within the folders above.
    - For instance, json/topHeadlines has a json called **us.json** which has 70 urls. 
    - article/topHeadlines has a directory called **us** which would have 70 .txt files for the 70 urls. 
