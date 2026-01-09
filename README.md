

# IOT-Based Local Bus Navigation System

IoT-based real-time local bus tracking and navigation system using GPS, web interfaces, and admin dashboards for passengers and operators.

## Table of Contents

- [Features](#features)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Admin Panel](#admin-panel)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)


## Features

- Real-time GPS bus location tracking
- Passenger-friendly web navigation interface
- Admin dashboard for route management and monitoring
- Responsive design for mobile and desktop
- Live updates via IoT modules (NodeMCU/ESP8266)


## Project Structure

```
IOT_BASED_LOCAL_BUS_NAVI_SYSTEM/
├── Admin_file/          # Admin dashboard files
├── CSS_file/            # Stylesheets and UI components
├── index_file/          # Main web interface (index.html)
├── README.md            # Project documentation
└── [other IoT firmware] # Hardware code (if applicable)
```


## Installation

1. Clone/download the repository
2. Open `index_file/index.html` in a web browser
3. Connect IoT hardware (NodeMCU + GPS module) to WiFi network
4. Configure API endpoints in admin panel for real-time data sync

## Usage

- **Passengers**: Visit main page to search routes and track buses live
- **Admins**: Access Admin_file dashboard to manage routes, buses, and alerts
- View responsive map interface styled via CSS_file components


## Admin Panel

Located in `Admin_file/` directory. Features:

- Bus location monitoring
- Route scheduling
- User analytics
- System alerts and notifications


## Technologies

| Component | Technologies |
| :-- | :-- |
| Frontend | HTML, CSS, JavaScript |
| Backend | Node.js/PHP (assumed) |
| IoT Hardware | ESP8266/NodeMCU, GPS Module |
| Styling | Custom CSS (CSS_file) |
| Mapping | Leaflet.js/Google Maps API |

## Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request


*Built for local bus navigation in Mūdbidri, Karnataka. Deployed with IoT for reliable public transport tracking.*

