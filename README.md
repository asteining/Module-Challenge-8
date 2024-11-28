# Vehicle Management CLI Application

# Description
1. This TypeScript-based Command-Line Interface (CLI) application allows users to manage different types of vehicles, including cars, motorbikes, and trucks. Users can create vehicles, perform actions on them, and utilize specific features like towing for trucks and wheelies for motorbikes.

2. The application is designed to showcase Object-Oriented Programming (OOP) principles, such as inheritance and polymorphism, while also leveraging TypeScript's type safety. It provides a practical example of extending and interacting with complex class hierarchies.

# Features
Create Vehicles:
1. Car
2. Motorbike
3. Truck

Perform Actions:
1. Start the vehicle
2. Accelerate or decelerate.
3. Turn left or right.
4. Stop the vehicle.
5. Print vehicle details.
6. Truck-Specific Actions:
7. Tow another vehicle if it is within the towing capacity.
8. Motorbike-Specific Actions:
9. Perform a wheelie.

Vehicle Details:
1. View comprehensive details of each vehicle, including VIN, make, model, year, weight, top speed, and wheel specifications.


# Installation
Prerequisites:
1. Node.js (v18.x or later recommended)
2. npm (Node Package Manager)

Steps
1. Clone the Repository
    -git clone <git@github.com:asteining/Module-Challenge-8-AramisSteininger.git>
    -cd <repository-folder>

2. Install Dependencies:
    -npm install

3. Compile the TypeScript Code  
    -npx tsc

4. Run the Application:
    -node dist/index.js

# How to Use
1. Launch the CLI
    -node dist/index.js

2. Menu Options
Create a New Vehicle:
Choose to create a car, truck, or motorbike:
Follow prompts to input vehicle details (e.g., color, make, model, etc.):
Default wheels are created for cars and trucks if none are provided:

3. Perform an Action on an Existing Vehicle
Select a vehicle from the preloaded or created vehicles:
Choose actions like start, accelerate, print details, or vehicle-specific features (e.g., towing, wheelie).

4. Exit:

Quit the application.

# Future Enhancements
1. Add persistence to save and reload vehicles between sessions.
2. Extend vehicle functionality (e.g., add fuel efficiency or maintenance tracking).
3. Implement user authentication to manage individual vehicle collections.


Feel free to reach out for any questions or feedback on this project!