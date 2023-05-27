# Project 1
Ronard Nyongkah

### Project Description

This project gets you facts about your favorite player. Like their height, weight, team ect. All that needs to be done is for you to enter the players name.

## API Description

- The API I'm using is https://www.balldontlie.io/home.html#getting-started

- This is an example of me testing the API
``` js
$.ajax("https://www.balldontlie.io/api/v1/players/?search=lebron")
.then((response)=>{
    console.log(response)
    console.log(response.data)
    let firstName = response.data[0].first_name
    let lastName = response.data[0].last_name
    console.log(`The Goat, ${firstName} ${lastName} has been summoned`)
})
 ```
### Mockup
