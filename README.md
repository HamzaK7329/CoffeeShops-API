# CoffeeShops-API
This Flask-based application serves as a versatile API for managing cafe data. It offers endpoints for retrieving random cafes, all cafes, and searching for cafes by location. Users can also add new cafes, update cafe prices, and delete cafes as needed. Leveraging SQLAlchemy for efficient database management, the API ensures seamless interaction with cafe data.

The API provides several key functionalities:

1. Random Cafe Selection: The /random endpoint allows users to retrieve a random cafe from the database, providing details such as name, location, amenities, and more.

2. Browse All Cafes: The /all endpoint returns a JSON array containing details of all cafes stored in the database, facilitating comprehensive browsing of available options.

3. Search by Location: Users can search for cafes based on location using the /search endpoint. Simply provide the desired location as a query parameter to retrieve cafe details if available.

4. Add New Cafe: With the /add endpoint, users can add new cafes to the database by providing relevant details such as name, location, amenities, and coffee price.

5. Update Cafe Prices: Cafe prices can be updated using the /update-price/<cafe_id> endpoint, allowing users to modify pricing information as needed.

6. Delete Cafes: The /report-closed/<cafe_id> endpoint enables users to remove cafes from the database, providing enhanced data management capabilities.

Additionally, the API includes basic security measures. Certain operations, such as deleting cafes, require authentication via an API key (TopSecretAPIKey) to ensure authorized access.

By combining functionality with simplicity and security, this Cafe API offers a robust solution for managing cafe data, catering to various use cases and facilitating seamless integration into diverse applications.
