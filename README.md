# Spring Data Elasticsearch

## Setting up Elasticsearch and Kibana
- Elasticsearch 
    - Starting elasticsearch in my local: .\'Program Files'\elasticsearch-7.10.1\bin\elasticsearch.bat
    - Default Elasticsearch PORT: 9200
    - Adding new instance: .\elasticsearch.bat -E path.data=[path.data] -E path.logs=[path.log]
- Kibana
    - Starting Kibana in my local: .\'Program Files'\kibana-7.10.1-windows-x86_64\bin\kibana.bat
    - Default Kibana PORT: 5601
    
## What is the project 
    Libariries in province
    Users
    Activity
    Books
    Libraries

## Goals of this Project:
 1. Show advance aggregates and qurries


## Controllers and endpoints:
    User
        - Favourite book of user
        - On average how long does a user keep a book

    Book
        - Most requested book
        - 
    
    Library
        Basically just a location that contains books

    Activity
        An activity done by a user action enum
        - CheckedIn
        - CheckedOut
        - Reserved
        - Date
        - Top Active User(s)
        - Least Active User(s)

#### TODO
1. Update UserService.java -> capture List<BookRecord>
2. Create the controllers from above and associated classes

Current Page: https://docs.spring.io/spring-data/elasticsearch/docs/4.1.2/reference/html/#elasticsearch.clients
https://www.elastic.co/guide/en/elasticsearch/client/java-rest/current/java-rest-overview.html