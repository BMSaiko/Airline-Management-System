# Airline Management System

A comprehensive Java application for managing airline operations including flights, aircraft, passengers, and crew members.

## Features
- Flight management (add, remove, search)
- Aircraft registration and details
- Passenger booking management
- Crew member management
- Data persistence with file storage
- Advanced search and analytics
- Input validation and error handling

## Requirements
- Java 8 or higher
- No external dependencies required

## Installation
1. Clone the repository
2. Compile all Java files
3. Run `Main.java`

## Usage
The application provides a console-based menu system with the following options:
1. Add flight
2. Remove flight
3. Search flights
4. Find flight with most passengers in date range
5. Show passenger list for flights on specific date
6. Modify flight passenger list
7. Calculate average passengers in date range
8. Total passengers in date range
9. Save to file
10. Load from file
0. Exit

## Project Structure
src/
├── org/companhiaaerea/
│ ├── Main.java
│ ├── Voo.java
│ ├── Aviao.java
│ ├── Aeroporto.java
│ ├── Passageiro.java
│ ├── Tripulante.java
│ ├── Pessoa.java
│ └── utils/
│ ├── Console.java
│ ├── Data.java
│ └── File.java


## Data Storage
Data is saved in the user's home directory under `~/companhia_aerea/` with `.voos` extension.
