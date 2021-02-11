# robofriends
Created using react framework. All the information are like image src, name , email id are fetched from the APIs listed below - 
1. The image is fetched from https://robohash.org/
2. The detail lists like name, email list are fetched from - https://jsonplaceholder.typicode.com/users

The App is fetching data from the APIs and listing according to it. It also has search field which gives the result according to the user input. There is a scroll bar wrapper around the card lists which helps user to easily view all the cards in small devices.

Components that are used are -
1. Card - To create a design of single card consist of an image, name heading and an email id.
2. CardList - It uses to group all the cards generated according to the info fetched from the API.
3. ScrollBar - Wrapper around the CardList to help user to easily view the cards if the the number of card is high.
4. SearchField - It provides a way for the user to give the input which then filter the cards.
5. Error Boundry - To keep track if any error occured then displayed it to the screen, but mostly it is more useful in production but not in development.

Smart Components or Containers that are used - 
1. App - Comprises of all the components and help to communicate between the search field input and the card component.

