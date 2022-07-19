GraphQL Playground with a Star Wars db: https://graphql.github.io/swapi-graphql/?

Here's a yt tutorial where the following playground is being used: https://www.youtube.com/watch?v=omSpI1Nu_pg

Example queries:

A sample query: - Return all characters name and hair colr and a list of all movie titles they were playing in
query {
  allPeople {
    people {
      
      name,
      hairColor,
      filmConnection {
        films {
          title
        }
      }  
    }
  }
}
https://graphql.github.io/swapi-graphql/?query=query%20%7B%0A%20%20allPeople%20%7B%0A%20%20%20%20people%20%7B%0A%20%20%20%20%20%20%0A%20%20%20%20%20%20name%2C%0A%20%20%20%20%20%20hairColor%2C%0A%20%20%20%20%20%20filmConnection%20%7B%0A%20%20%20%20%20%20%20%20films%20%7B%0A%20%20%20%20%20%20%20%20%20%20title%0A%20%20%20%20%20%20%20%20%7D%0A%20%20%20%20%20%20%7D%20%20%0A%20%20%20%20%7D%0A%20%20%7D%0A%7D



Click here to see all datasets available to interact with:
![image](https://user-images.githubusercontent.com/105798603/179770837-b164dc8f-f391-4e83-a76f-2fcc47911daa.png)

![image](https://user-images.githubusercontent.com/105798603/179770941-eaeb6c51-66c6-414c-82bf-e9626c307538.png)



How to see all fields of a dataset?

Click here:
![image](https://user-images.githubusercontent.com/105798603/179771563-5e099c48-43e9-46d0-bd05-c009c2751a36.png)

Then here:
![image](https://user-images.githubusercontent.com/105798603/179771784-bf1eeab5-f4d0-427f-94ad-7a84db337207.png)

and here you have all fields that an object contains:
![image](https://user-images.githubusercontent.com/105798603/179772079-43a1acf4-905f-4b55-b678-3a37ca3c9cad.png)

