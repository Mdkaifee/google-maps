# Flutter Maps App

A Flutter application demonstrating Google Maps integration with location tracking, route drawing using Google Directions API, and distance calculation.

---

## Features

- Display Google Map centered on user's current location.
- Search and input start and destination addresses.
- Draw route polyline between two places using Google Directions API.
- Calculate and display the distance of the route.
- Show markers for start and destination locations.
- Zoom in/out controls.

---

## Getting Started

### Prerequisites

- Flutter SDK (>=3.8.1)
- A Google Cloud project with billing enabled.
- Google Maps API Key with the following APIs enabled:
  - Maps SDK for Android
  - Maps SDK for iOS
  - Directions API
  - Geocoding API

---

### Setup

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/flutter_maps_app.git
   cd flutter_maps_app
2. **Install dependencies**   flutter pub get

3. **Run the app**

   ```bash
   flutter run