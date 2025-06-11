# Private Events

Private Events is a Ruby on Rails application designed to function as a private version of Eventbrite. It allows users to create events, manage user signups, and track attendance. This project demonstrates the implementation of many-to-many relationships in Rails while requiring careful management of foreign keys and class names.

## Features

- **Event Creation**: Users can create events with a specific date and location.
- **Event Attendance**: Users can attend multiple events, and each event can have multiple attendees.
- **Event Management**: Organizers can manage attendees for their events.

## Models and Relationships

- **User**: Represents a user of the application. A user can create events and attend multiple events.
- **Event**: Represents an event with attributes such as date and location. An event can be attended by multiple users.