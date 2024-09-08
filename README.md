# Mapty - A Workout Tracker

This repository contains the code for **Mapty**, a web application that allows users to track and display their workouts on a map.

## Features

- **Map Visualization**:
  - Displays an interactive map using the Leaflet library, centered on the user's current location.
  - Moves the map to the location of each workout.
  
- **Workout Storage**:
  - Load workouts from local storage.
  - Store new workouts in local storage to persist across sessions.
  
- **Workout Creation**:
  - Submit new workouts with details such as type, distance, duration, and pace.
  - Display the new workout directly on the map.
  
- **Workout List**:
  - View a list of all saved workouts.
  - Click on any workout from the list to highlight its location on the map.

## Technologies Used

- **HTML**: Structure of the web page.
- **CSS**: Styling of the web page.
- **JavaScript**: Functionality and logic of the application.
- **Leaflet**: JavaScript library for creating interactive maps.

## Getting Started

### Clone the Repository:
```bash
git clone https://github.com/Drishti2003/mapty.git
```

### Navigate to the Project Directory:
```bash
cd mapty
```

### Open the Application:
Open the `index.html` file in your web browser.

## How to Use

1. **Grant Location Access**: The app will request access to your current location to center the map.
2. **Create a New Workout**: Click on the "Add New Workout" button.
3. **Enter Workout Details**: Input information such as workout type (running or cycling), distance, duration, and pace.
4. **Submit Workout**: Click "Submit" to save the workout.
5. **View Workouts**: Your saved workouts will appear in a list, and clicking on a workout will display its location on the map.

## Contributing

Contributions are welcome! If you’d like to contribute, please submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

