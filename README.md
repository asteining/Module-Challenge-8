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

Car:
1. Print vehicle details.

Truck-Specific Actions:
1. Tow another vehicle if it is within the towing capacity.

Motorbike-Specific Actions:
1. Perform a wheelie.

Vehicle Details:
1. View comprehensive details of each vehicle, including VIN, make, model, year, weight, top speed, and wheel specifications.


# Installation
Prerequisites:
1. Node.js (v18.x or later recommended)
2. npm (Node Package Manager)


Clone the Repository
1. -git clone <git@github.com:asteining/Module-Challenge-8-AramisSteininger.git>
2. -cd into correct folder

Install Dependencies:
1. -npm install

Compile the TypeScript Code: 
1. -npx tsc

Run the Application:
1. -npm start

# How to Use
Launch the CLI
1. -npm start

Menu Options:
1. Create a New Vehicle
2. Choose to create a car, truck, or motorbike:
3. Follow prompts to input vehicle details (e.g., color, make, model, etc.):
4. Default wheels are created for cars and trucks if none are provided:

Perform an Action on an Existing Vehicle
1. Select a vehicle from the preloaded or created vehicles:
2. Choose actions print details, or vehicle-specific features (e.g., towing, wheelie).

Exit:
1. Quit the application.

# Future Enhancements
1. Add persistence to save and reload vehicles between sessions.
2. Extend vehicle functionality (e.g., add fuel efficiency or maintenance tracking).
3. Implement user authentication to manage individual vehicle collections.


Feel free to reach out for any questions or feedback on this project!