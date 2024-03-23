Project Name- Petstore
BaseURL- https://petstore.swagger.io/v2
Authorization- Not required


Collection pet
Request 1 - POST Add a new pet to the store /pet
	Raw Data - required
Request 2 - PUT Update an existing pet /pet
  Raw Data - required
Request 3 - GET Find pet by status /pet/findbystatus
  Raw Data - not required
Request 4 - GET Find pet by petId /pet/{petId}
  Raw Data - Not required
Request 5 - POST Updates a pet in the store with pet data /pet/{petId}
  Raw Data - not required
Request 6 - DELETE deletes a pet 
  Raw Date - not required

Collection Store-
Request 1 - POST Place an order for a pet /store/order
	Raw Data - required
Request 2 - GET Find purchase order y id /store/order/{orderid}
  Raw Data - not required
Request 3 - DELETE Delete purchase order by id /store/order/{orderid}
  Raw Data - required
Request 4 - GET Return pet inventories by status /store/inventories
  Raw Data - Not required

Collection User-
Request 1 - POST Creates a list of users with the given input array /user/createWithArray
	Raw Data - required
Request 2 - Get the user by username /user/{username}
  Raw Data - not required
Request 3 - PUT Update user /user/{username}
  Raw Data - required
Request 4 - DELETE Delete user /user/{username}
  Raw Data - Not required
Request 5 - GET Logs user into system /user/login
  Raw Data - not required
Request 6 - GET Logs out current logged-in user session /user/logout
  Raw Date - not required
Request 7 - POST Create user /user
  Raw Data - required
