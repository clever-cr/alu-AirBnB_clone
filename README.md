# AirBnB Project

This is a command-line interface (CLI) application for managing a simplified version of the AirBnB booking platform. The application allows users to create, update, and delete various objects such as states, cities, places, amenities, reviews, and users.

## Command Interpreter

The command interpreter is the main component of the AirBnB project. It provides a command-line interface for interacting with the application and performing various operations on the objects.

### How to Start

To start the command interpreter, follow these steps:

1. Clone the AirBnB project repository to your local machine.
2. Navigate to the project directory.
3. Open a terminal or command prompt in the project directory.
4. Run the following command to start the command interpreter:

```bash
$ ./console.py
```

### How to Use

Once the command interpreter is running, you can enter commands and arguments to perform different operations. The general syntax for a command is as follows:

```
command_name [arguments]
```

Here are some example commands you can use:

- **Create**: Create a new object
  ```
  (hbnb) create State
  (hbnb) create City name="San Francisco" state_id="state_id_value"
  ```

- **Show**: Display information about a specific object
  ```
  (hbnb) show Place 1234-1234-1234
  ```

- **Update**: Update attributes of an existing object
  ```
  (hbnb) update User 9876-9876-9876 name="John Doe"
  ```

- **Destroy**: Delete an object
  ```
  (hbnb) destroy Review 5678-5678-5678
  ```

- **All**: Display information about all objects or objects of a specific class
  ```
  (hbnb) all
  (hbnb) all User
  ```

- **Quit**: Exit the command interpreter
  ```
  (hbnb) quit
  ```

For more details on available commands and their usage, you can use the `help` command within the interpreter.

### Examples

Here are some examples of using the command interpreter:

1. Creating a new state:
   ```
   (hbnb) create State name="California"
   ```

2. Updating a place's attributes:
   ```
   (hbnb) update Place 1234-1234-1234 name="Cozy Apartment" price_by_night=100
   ```

3. Displaying information about all amenities:
   ```
   (hbnb) all Amenity
   ```

4. Deleting a user:
   ```
   (hbnb) destroy User 9876-9876-9876
   ```

5. Quitting the command interpreter:
   ```
   (hbnb) quit
   ```

## Contributors

- Clever Umuhuza
- Arsene Karuretwa

Feel free to contribute to the project by submitting bug reports, feature requests, or pull requests to the GitHub repository.

## License

This project is licensed under the ALU License.
