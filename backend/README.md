## Routes

`GET /users` \
`[{ "pk": 2345678, "fname" : "jeff", "lname" : "bezos", "email" : "jeffbezos@gmail.com", }]`

`GET /users/:id` \
`{ "pk": 2345678, "fname" : "jeff", "lname" : "bezos", "email" : "jeffbezos@gmail.com", }`

`POST /users` \
`PATCH /users/:id` \
`DELETE /users/:id` \

`GET /postings` \
`GET /postings/:id` \
`POST /postings` \
`PATCH /postings/:id` \
`DELETE /postings/:id` \

## Models

#### User

- pk
- fName
- lName
- email
- rating?
- (comments)

#### Posting

- pk
- poster (fk)
- course
- description
- rate
<!--

#### Rating

- tutor (fk)
- rater (fk)
- score -->
