# Gazebo-Build-My-World 

This project encompasses the creation of a Gazebo world, models, and a C++ plugin as part of the requirements for the 'Build My World' project.

## Project Structure

The project directory is structured as follows:
- **world:** Contains the Gazebo world file.
- **model:** Includes a custom structure and an object model.
- **script:** Holds the C++ plugin code.
- **CMakeLists.txt:** Configuration file for building the project.

### Building
- **House with Walls:** Designed structure stored in the model directory meeting the specified criteria.
  - Different from the sample simulation world.
  - Single floor with adequate space for robot navigation.
  - Includes at least one feature and one color.

### Modeling
- **Object Design using Model Editor:** Created an object stored in the model directory following the criteria.
  - Different from the sample simulation world.
  - Object links connected through joints.

### Gazebo World
- **Multiple Models in Gazebo World:** Created a unique Gazebo world stored in the world directory.
  - Different from the sample simulation world.
  - Contains the structure model.
  - Includes two instances of the object model.
  - Incorporates one model from the Gazebo online library.

### World Plugin
- **C++ World Plugin:** Developed a C++ plugin stored in the script directory.
  - Created a CMakeLists.txt file in the main project directory.
  - The plugin prints a "Welcome to [Your Name]'s World!" message.

## Getting Started

To explore the project:
1. Clone this repository.
2. Open the project in Gazebo to view the custom world and models.
