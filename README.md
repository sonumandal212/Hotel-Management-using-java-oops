# Hotel-Management-using-java-oops
This Hotel Management tool is designed to streamline various hotel operations. It allows users to store customer information, book rooms across four different categories, order food for specific rooms, cancel room bookings, and generate bills. Additionally, it provides details about room features and availability. The program is menu-driven and continues running until the user chooses to exit. To maintain data consistency, file handling is employed to save the hotel's current status (including customer details, booked rooms, and food orders) to a file upon program termination. This ensures that when the program restarts, it can read from the file and restore the previous state. File writing operations are handled in a separate thread to allow parallel execution. A custom exception is raised if an attempt is made to book a room that is already occupied. Comprehensive exception handling is implemented to manage any unexpected errors effectively.

Key Topics Covered:
- Classes and Objects
- Inheritance
- File Handling with Objects
- ArrayList
- Implementing Interfaces
- Custom Exceptions and Exception Handling
