# Airline Management System

A Java desktop application for managing airline operations and passenger bookings. The system provides separate interfaces for airline managers and passengers, covering flight administration, aircraft management, flight search, and ticket reservations.

## Features

### Passenger
- Register and log in to an account
- Search and filter flights by departure, destination, and departure time
- Purchase tickets in Economy or Business class
- View purchased tickets and booking history
- View and update profile information

### Manager
- Manage flights and aircraft
- Create and edit flight schedules
- View registered passengers
- View passenger ticket bookings
- Manage account information

## Technologies

- **Java** — application logic
- **Java Swing** — graphical user interface
- **SQLite** — persistent data storage
- **JDBC** — database connectivity
- **JUnit** — unit testing

## Architecture

The application follows a layered structure to separate responsibilities:

- **Model:** Represents core entities such as users, flights, planes, and tickets.
- **Repository:** Handles database operations and data persistence.
- **Service:** Implements application logic and coordinates operations.
- **View:** Provides the graphical user interface for passengers and managers.

## Getting Started

### Requirements
- Java Development Kit (JDK)
- SQLite JDBC driver

### Running the Application

1. Clone the repository:
   ```bash
   git clone https://github.com/deniznal/Airline-Management-System.git
   ```
2. Open the project in an IDE such as IntelliJ IDEA.
3. Ensure the SQLite JDBC driver is included in the project dependencies.
4. Run `src/Main.java`.

The application initializes its SQLite database (`ams.db`) and creates the required tables when a database connection is established.

## Default Manager Account

You can log in using the default manager credentials:

- **Email:** `admin@ams.com`
- **Password:** `admin`

