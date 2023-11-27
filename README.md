# final-project-react

## Do not forget to do 
```npm i ``` at the start of the project

## HTTP Service
get(url)
Makes a GET request to the specified URL.

post(url, data)
Makes a POST request to the specified URL with the provided data.

put(url, data)
Makes a PUT request to the specified URL with the provided data.

patch(url, data)
Makes a PATCH request to the specified URL with the provided data.

delete(url)
Makes a DELETE request to the specified URL.

setCommonHeader(headerName, headerValue)
Sets a common header for all requests.

## User Functions
register(user)
Registers a new user.

login(credentials)
Logs in a user and stores the authentication token.

logout()
Logs out the current user and removes the authentication token.

updateUser(id, update)
Updates user information based on the provided ID.

deleteUser(id)
Deletes a user based on the provided ID.

patchUserBusinessStatus(id)
Patches the business status of a user based on the provided ID.

getAllUsers()
Gets a list of all users.

getUserById(id)
Gets user information based on the provided ID.

getUser()
Gets the current user information. (Note: Synchronous function)

getJWT()
Gets the authentication token.

## Card Function
getAllCards()
Fetches all cards.

getAllMyCards()
Fetches user-specific cards.

createCard(newCardObj)
Creates a new card with the provided details.

likeCard(cardId)
Likes a card based on the provided card ID.

deleteCard(cardId)
Deletes a card based on the provided card ID.
a
getCardById(cardId)
Fetches details of a card based on the provided card ID.

updateCard(cardId, updatedCard)
Updates a card based on the provided card ID and updated details.

## User Authentication Context
AuthContextProvider
The AuthContextProvider component wraps your application components and provides the authentication context to them. It includes the following:

user: The current authenticated user.
login(credentials): A function to log in a user.
logout(): A function to log out the current user.
useAuth
The useAuth hook allows you to access the authentication context within your components. It returns an object with the following properties:

user: The current authenticated user.
login(credentials): A function to log in a user.
logout(): A function to log out the current user.

## Search Context
SearchContextProvider
The SearchContextProvider component wraps your application components and provides the search context to them. It includes the following:

search: The current search query.
cards: The list of all cards.
cardToShow: The filtered list of cards based on the search query.
handleClick(): A function to filter cards and navigate to the search results page.
handleChange(e): A function to update the search query.
useSearch
The useSearch hook allows you to access the search context within your components. It returns an object with the following properties:

search: The current search query.
cards: The list of all cards.
cardToShow: The filtered list of cards based on the search query.
handleClick(): A function to filter cards and navigate to the search results page.
handleChange(e): A function to update the search query.

## Like Context
LikeProvider
The LikeProvider component wraps your application components and provides the like context to them. It includes the following:

likedCards: The list of liked cards.
addFavorite(cardId): A function to add a card to the liked list.
removeFavorite(cardId): A function to remove a card from the liked list.
useLike
The useLike hook allows you to access the like context within your components. It returns an object with the following properties:

likedCards: The list of liked cards.
addFavorite(cardId): A function to add a card to the liked list.
removeFavorite(cardId): A function to remove a card from the liked list.
