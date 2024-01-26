
# HandiGo: A Rideshare App for the Visually Impaired

## Overview
HandiGo is a innovative rideshare application designed specifically for the visually impaired. By leveraging beacon technology, the app facilitates seamless communication between the passenger's and driver's devices, ensuring passengers can easily locate their ride through vibration and audio cues. The application aims to enhance mobility and independence for visually impaired users, making ridesharing a more accessible and secure experience.

## Demo Video
This is a demo video I created: [Demo Video](https://www.youtube.com/watch?v=xUSWCPBwAzY)

## Motvation
The inception of HandiGo was driven by a desire to make ridesharing a more inclusive and accessible service for everyone, especially for those who are visually impaired. Traditional ridesharing apps rely heavily on visual cues for navigation and driver-passenger coordination, which can be a significant barrier for visually impaired users. I was once struggling to find the location of my Uber driver in a busy area, and so I was wondering how those with visual impairments try to navigate situations like these. This project aims to bridge that gap by leveraging beacon technology to provide an intuitive, non-visual interface that guides users to their ride through audio and haptic feedback.

My motivation stems from a broader commitment to enhancing mobility and independence for individuals with visual impairments. By integrating advanced technology with thoughtful design, HandiGo seeks to empower users, offering them a safer, more reliable, and accessible transportation option. This project is not just about improving the ridesharing experience; it's about fostering inclusivity, promoting independence, and enhancing the quality of life for visually impaired individuals.

## Key Features

### Beacon Technology
- Utilizes iBeacon technology to send and receive signals between the driver and passenger.
- Provides real-time directional feedback through audio and vibration alerts, guiding passengers to their ride.

### User Interface
- **AcceptRideView:** Initiates the ride acceptance process, integrating beacon signals to alert passengers of a nearby ride.
- **DriverView & PassengerView:** Custom interfaces tailored to the needs of drivers and passengers, focusing on simplicity and accessibility.
- **RideStartedView:** Displays ride status and provides relevant information once the ride commences.
- **RideView:** Offers a minimalistic view related to the ride details, enhancing user experience with straightforward functionality.

### Accessibility Focused
- Designed with accessibility at its core to support visually impaired users in navigating and interacting with the app effortlessly.

## Getting Started

### Prerequisites
- iOS 13.0 or later
- Xcode 11 or later
- Swift 5

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/ofarrag9/HandiGo.git
   ```
2. Open `BeaconRideShare.xcodeproj` in Xcode.
3. Build and run the application on your 2 different devices.

## How to Contribute
Contributions are welcome! Here's how you can help:
1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.
