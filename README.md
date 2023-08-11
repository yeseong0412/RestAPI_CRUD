# RestAPI_CRUD

- Base URL : localhost:8080/guestbook

- Post : localhost:8080/guestbook | 
Example JSON 
    {
      "title" : "testTitle",
      "content" : "testContent" , 
      "writer" : " TestUser"
    }

- GET : localhost:8080/guestbook/{id}
  
- GET : localhost:8080/guestbook/list

- PUT : localhost:8080/guestbook | 
Example JSON
    {
        "gno" : 1,
        "title" : "PutTestTitle",
        "content" : "PutTestContent"
    }

- Delete : localhost:8080/guestbook/{id}
  
