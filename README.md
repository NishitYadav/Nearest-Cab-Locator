# Nearest Cab Finder

This project is a solution to find cab drivers within a 50 km proximity using GPS coordinates. It extracts and converts latitude and longitude data from a JSON file, converts these coordinates from degrees to radians, and applies the Great Circle Distance formula to calculate the distance between the user's location and each cab.

## Project Description

- **Developed a solution to find cab drivers within a 50 km proximity using GPS coordinates**: The system identifies cabs that are within a specified distance from the user's current location.
- **Extracted and converted latitude and longitude data from customers.json**: The project parses a JSON file to obtain the GPS coordinates of both the user and available cabs.
- **Converted coordinates from degrees to radians for both the user and cabs**: This conversion is necessary for the mathematical calculations involved in the Great Circle Distance formula.
- **Applied the Great Circle Distance formula to calculate the distance between the user’s location and each cab**: The formula is used to determine the shortest path over the Earth's surface, providing an accurate distance measurement between two points.

## Features

1. **Extract GPS Coordinates**: 
   - Parse the `customers.json` file to extract latitude and longitude data for the user and cabs.

2. **Coordinate Conversion**: 
   - Convert the extracted GPS coordinates from degrees to radians.

3. **Distance Calculation**: 
   - Apply the Great Circle Distance formula to calculate the distance between the user's location and each cab.
   - Identify and list cabs that are within a 50 km radius of the user's location.

### Prerequisites

- A C++ compiler (e.g., GCC, Clang, Visual C++)
- A JSON library for C++ (e.g., nlohmann/json)


