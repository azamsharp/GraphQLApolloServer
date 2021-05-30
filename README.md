# GraphQL Apollo Server

A custom GraphQL server implemented in NodeJS using the Apollo framework. This project exposes movies and genres queries, as well as the mutation for the movies. Both movies and genres are hardcoded and not saved in the database. This project is part of my new upcoming course "GraphQL for iOS". You can follow me on Twitter @azamsharp to get the latest updates regarding the course.  


### Live URL: 

https://morning-ridge-93242.herokuapp.com/

### Query Example 

```
# Write your query or mutation here

query {
  movies {
    id 
    title 
    poster 
    genre 
  }
}

```

### Query Result 

```
{
  "data": {
    "movies": [
      {
        "id": "1",
        "title": "Lord of the Rings",
        "poster": "https://m.media-amazon.com/images/M/MV5BYTM3ZmU1NTAtYjViYy00ZmJlLWE1NjgtNWI2OTllMGZmZTVkXkEyXkFqcGdeQXVyMjMyNTkxNzY@._V1_SX300.jpg",
        "genre": "Fiction"
      },
      {
        "id": "2",
        "title": "Batman: The Killing Joke",
        "poster": "https://m.media-amazon.com/images/M/MV5BMTdjZTliODYtNWExMi00NjQ1LWIzN2MtN2Q5NTg5NTk3NzliL2ltYWdlXkEyXkFqcGdeQXVyNTAyODkwOQ@@._V1_SX300.jpg",
        "genre": "Fiction"
      },
      {
        "id": "3",
        "title": "Superman: The Animated Series",
        "poster": "https://m.media-amazon.com/images/M/MV5BNDgzOWJjOTMtZjY4ZS00MGRkLTk0YTMtM2E3ZGQyYmMyYzkzXkEyXkFqcGdeQXVyMTA1OTEwNjE@._V1_SX300.jpg",
        "genre": "Animated"
      },
      {
        "id": "4",
        "title": "Lego: The Adventures of Clutch Powers",
        "poster": "https://m.media-amazon.com/images/M/MV5BMjQ1NzM2MDE2Nl5BMl5BanBnXkFtZTcwNjg4NDcxMw@@._V1_SX300.jpg",
        "genre": "Animated"
      }
    ]
  }
}
```

