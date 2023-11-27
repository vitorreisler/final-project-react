# final-project-react

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
