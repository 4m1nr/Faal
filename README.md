---

# This file is AI generated

# Faal

This project is a simple GUI application that fetches and displays poems and their interpretations from an API. The application is built using Java Swing for the GUI and Jackson for JSON parsing.

## Features

- Fetch a poem and its interpretation from a specified API.
- Display the fetched poem and interpretation in a user-friendly GUI.
- Option to go back to the main page and fetch another poem.

## Prerequisites

- Java Development Kit (JDK) 8 or higher
- Maven (for dependency management)

## Getting Started

### Clone the Repository

```bash
git clone https://github.com/4m1nr/Faal.git
cd Faal
```

### Build the Project

Use Maven to build the project and download dependencies.

```bash
mvn clean install
```

### Run the Application

After building the project, you can run the application using the following command:

```bash
java -jar target/Faal-1.0-SNAPSHOT.jar
```

## Usage

1. **Home Page:**
    - You will see a message asking you to make a wish.
    - Click on the "دریافت فال" (Get Faal) button to fetch a poem.

2. **Poem Page:**
    - The fetched poem and its interpretation will be displayed.
    - Click on the "بازگشت" (Back) button to return to the home page and fetch another poem.

## Code Structure

- **FaalGUI.java:** The main class that sets up the GUI and handles user interactions.
- **Faal.java:** The model class that maps the JSON response from the API.
- **pom.xml:** Maven configuration file for managing dependencies.

## API

The application fetches data from the following API endpoint:

```
https://faal.spclashers.workers.dev/api
```

## Dependencies

- **Jackson:** For parsing JSON responses.
- **Swing:** For building the GUI.

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.

---
