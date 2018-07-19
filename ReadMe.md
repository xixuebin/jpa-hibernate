https://www.callicoder.com/spring-boot-rest-api-tutorial-with-mysql-jpa-hibernate/

Git Address :

https://github.com/callicoder/spring-boot-mysql-rest-api-tutorial

##Test
Post localhost:8080/api/notes
{"title":"First Note", "content":"for Test"}
###Result
{
    "id": 1,
    "title": "First Note",
    "content": "for Test",
    "createdAt": "2018-07-19T11:01:05.932+0000",
    "updatedAt": "2018-07-19T11:01:05.932+0000"
}


##
Get localhost:8080/api/notes
###Result
[
    {
        "id": 1,
        "title": "First Note",
        "content": "for Test",
        "createdAt": "2018-07-19T11:01:05.000+0000",
        "updatedAt": "2018-07-19T11:01:05.000+0000"
    },
    {
        "id": 2,
        "title": "First Note2",
        "content": "for Test2",
        "createdAt": "2018-07-19T11:03:24.000+0000",
        "updatedAt": "2018-07-19T11:03:24.000+0000"
    }
]

##
Get localhost:8080/api/notes/1
##Result
{
    "id": 1,
    "title": "First Note",
    "content": "for Test",
    "createdAt": "2018-07-19T11:01:05.000+0000",
    "updatedAt": "2018-07-19T11:01:05.000+0000"
}

##
GET /api/notes
POST /api/notes
GET /api/notes/{noteId}
PUT /api/notes/{noteId}
DELETE /api/notes/{noteId}



##一个对多个
https://www.callicoder.com/hibernate-spring-boot-jpa-one-to-many-mapping-example/

##jpa-hibernate-tutorials
https://github.com/callicoder/jpa-hibernate-tutorials

##14-high-performance-java-persistence-tips
https://vladmihalcea.com/14-high-performance-java-persistence-tips/

##the-best-way-to-map-a-onetomany-association-with-jpa-and-hibernate
https://vladmihalcea.com/the-best-way-to-map-a-onetomany-association-with-jpa-and-hibernate/