# README

This is an API to get information on dogs.

To access the API, from the frontend, the main route you'll use is:

`http://localhost:3000/dog_search`

The path accepts two queries, a search query and an optional parameter to sort the list by a property:

`http://localhost:3000/dog_search?query="byron"&sort_field="breed"`

`name` is the default sort_field if nothing is specified.

It will render JSON as an array of dog objects. A dog object looks like:

```
  {
    name: "Fluffy",
    breed: "Miniature Schnauser",
    age: "347",
    size: "Immeasurable",
    phrase: "I am Fluffy, Destroyer of Worlds",
  }
```

Keep in mind that dog_search is the **only** endpoint on the API.

Good luck!
