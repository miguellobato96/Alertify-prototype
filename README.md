# Alertify Prototype

Alertify is an Android personal safety app prototype focused on emergency alerts, real-time location sharing, trusted contacts, and fast SOS activation.

The project was developed as an academic prototype by Magic Engineering and awarded 1st place at the TechVenture Challenge EET.

## Status

This repository contains the original Android prototype.

A new version of Alertify is being planned with a stronger architecture, including a dedicated backend and native mobile applications.

## Features

- SOS activation flow with a sliding gesture
- Emergency alerts to trusted contacts
- Real-time location sharing
- SOS contacts management
- Google Maps integration for location display and navigation
- Nearby safe locations using map-based services
- Local user/contact storage using SQLite

## Technologies

- Java
- Android SDK
- SQLite
- Google Maps API
- Gradle
- Android Studio

## Installation

### Prerequisites

- Android Studio 2022.1 or higher
- Android SDK configured
- Google Maps API key
- Android emulator or physical Android device

### Setup

Clone the repository:

```bash
git clone https://github.com/miguellobato96/Alertify-prototype.git
```

Open the project in Android Studio.

Sync Gradle dependencies.

Add your Google Maps API key to the existing API key placeholder in `AndroidManifest.xml`.

Build and run the application on an emulator or physical Android device.

## How It Works

1. The user creates an account or logs in.
2. The user adds trusted SOS contacts.
3. The user activates SOS through the app interface.
4. The app shares emergency information and live location with configured contacts.
5. The user can view map-based information and nearby safe locations.

## Project Context

This project was developed as a prototype for personal safety use cases, especially situations where fast alert activation and location sharing can help users feel safer during night outings or vulnerable situations.

The prototype helped validate the concept and led to the project winning 1st place at the TechVenture Challenge EET.

## Team

Developed by:

- Miguel Lobato
- Guilherme Louro
- Rafael Gusmão

## License

This project is proprietary. The source code is publicly visible for portfolio and review purposes only.

Commercial use, redistribution, public deployment, and derivative works are not permitted without prior written permission from the authors.

See [LICENSE](./LICENSE) for details.
