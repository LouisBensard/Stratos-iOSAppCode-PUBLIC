# Stratos: The Future of General Aviation 🚀

Welcome to the official GitHub repository for Stratos, an innovative iOS app designed for general aviation enthusiasts. This repository is a resource hub showcasing our development practices, sample Swift and Python code, and the frameworks we use. Dive into our demos and explore the architecture and technology behind Stratos.

## Table of Contents 📚
- [Introduction](#introduction)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Code Samples](#code-samples)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction 🌟
Stratos is tailored for pilots and aviation enthusiasts to explore new airports to fly to, log flight tracks, assess their flying performance, and connect with aviators locally and around the world. This repo provides insights into the app's creation, featuring our approaches to coding, design, and functionality.

## Tech Stack 💻

The Stratos app combines modern software engineering practices and cutting-edge technologies to deliver a robust and efficient application for general aviation enthusiasts. Below is an overview of the technology stack used in developing Stratos:

### Frontend
  #### Mobile Application
  - **SwiftUI & UIKit**: Primarily built with SwiftUI (95%) for its modern, declarative syntax that simplifies UI development, complemented by UIKit (5%) for specific UI components not yet fully available in SwiftUI.
  - **External Dependencies via SPM**:
    - **Firebase**: Utilized for backend services, real-time database, and user authentication.
    - **KingFisher**: Swift library for downloading and caching images from the web.
    - **RevenueCat**: Manages in-app subscriptions and purchasing processes.
    - **GoogleSignIn**: Provides authentication services linked to Google accounts.
  
  #### Apple Frameworks
  - **MapKit**: Integrates map functionality to display and interact with geographical data.
  - **Swift Charts**: Used for creating custom interactive charts and data visualizations.
  - **CryptoKit**: Handles cryptographic operations, supporting the app’s end-to-end encryption feature.
  - **Security**: Ensures secure storage of sensitive user data.
  - **CoreData**: Manages the app’s data model and local storage.
  - **CoreLocation**: Provides location data services to enable geo-specific features.
  - **SafariServices**: Used to integrate web content securely within the app.
  - **TipKit**: Assists in generating tipping content, specific scenarios, and local advice.

### Backend Services
- **Firebase & Google Cloud Platform (GCP)**: Serve as the backbone for the app's server-side operations including data storage, server functions, and hosting.
- **TypeScript Cloud Functions**: Extensively used for writing scalable and efficient server-side logic hosted on GCP, enhancing backend functionality and security.

### Data Engineering and Machine Learning
- **Python**: The primary language used for all data engineering and machine learning tasks, enabling sophisticated data analysis and the development of recommendation systems.
  - **Pandas** and **NumPy**: For data manipulation and numerical operations.
  - **SciPy** and **Scikit-Learn**: Employed for advanced data analysis and machine learning tasks.
  - **TensorFlow**: Used for developing and training deep learning models.
  - **PyTorch**: Also employed for building and training advanced neural network models.
 
### Messaging & Security

- **Native Messaging**: Built from the ground up, our messaging feature is fully native and supports end-to-end encryption with 2048-bit keys, ensuring private and secure communication among users.
- **Secure Data Handling with GCP**: Utilizing Google Cloud Platform's robust security features, Stratos ensures that all user data, including flight logs, photos, and personal information, is stored securely. GCP's encryption mechanisms automatically encrypt all data before it is written to disk with no additional action required from the user, providing strong protection against data breaches.
- **Compliance and Data Integrity**: GCP compliance certifications ensure that Stratos meets rigorous privacy and security standards required for aviation and data protection regulations. This includes continuous monitoring and automatic updates to respond to potential security threats efficiently.

## Performance Monitoring and User Feedback
- **Google Analytics**: Monitors user engagement and app performance to gather insights that help improve user experience.
- **User Feedback**: Currently collected via email surveys to understand user satisfaction and collect suggestions directly from users.

## Planning and Managing Work

- **Feature Planning**: Managed through a prioritized list of features alongside a cost-benefit analysis for each, ensuring effective resource allocation and strategic development.

## Maintainability and Version Control

- **Code Organization**: The codebase is neatly organized, lean, and well-documented. It is meticulously refactored and segmented into appropriate files and folders.
- **Version Control**: Managed through GitHub, providing robust tools for source code management and collaborative development.

---


## Features 🛠️

### Explore Airports and Nearby Activities 🌍

- **Intelligent Map**: Explore airports globally with our advanced map feature, designed to help you plan your next adventure efficiently.
  - ![Intelligent Map Screenshot](path/to/intelligent_map_screenshot.jpg)
  
- **Airport Filters**: Find airports by amenities like Restaurants, Museums, Parks, and Beaches, making it easier to plan your visits.
  - ![Airport Filters Screenshot](path/to/airport_filters_screenshot.jpg)
  
- **Favorites and History Visualization**: Visualize your frequented and favorite airports, sparking ideas for your next flights.
  - ![Favorites Visualization Screenshot](path/to/favorites_visualization_screenshot.jpg)

### Flight Tracking and Performance Analysis ✈️

- **Precision Flight Logging**: Utilize your plane’s transponder data to log flights with unmatched accuracy.
  - ![Precision Flight Logging Screenshot](path/to/precision_flight_logging_screenshot.jpg)
  
- **Post-Flight Track Finder**: Focus on your flight experience without hassle; log your flights post-flight.
  - ![Post-Flight Track Finder Screenshot](path/to/post_flight_track_finder_screenshot.jpg)
  
- **Flight Debriefs and Journals**: Turn every flight into a learning opportunity with detailed debriefs and journals.
  - ![Flight Debriefs Screenshot](path/to/flight_debriefs_screenshot.jpg)
  
- **Performance Analytics**: Monitor your flying improvement over time with our advanced analytics tools.
  - ![Performance Analytics Screenshot](path/to/performance_analytics_screenshot.jpg)
  
- **Historical Flight Logs**: Access comprehensive views of your flying history since 2011.
  - ![Historical Flight Logs Screenshot](path/to/historical_flight_logs_screenshot.jpg)

### Social Networking for Aviators 🌐

- **Global Connections**: Make connections with pilots and aviation enthusiasts worldwide.
  - ![Global Connections Screenshot](path/to/global_connections_screenshot.jpg)
  
- **Local Meetups**: Discover and connect with pilots in your area to enhance your local aviation community.
  - ![Local Meetups Screenshot](path/to/local_meetups_screenshot.jpg)
  
- **Secure Communication**: Enjoy secure, private communications with end-to-end encrypted chat.
  - ![Secure Communication Screenshot](path/to/secure_communication_screenshot.jpg)


## Code Samples 📝

Stratos source code is proprietary but you can find code samples of the app here: 

- [Swift Code Samples](/Code/Swift/)
- [Python Code Samples](/Code/Python/)
- [TypeScript Code Samples](/Code/TypeScript/)

## Contributing 🤝

We welcome contributions to the Stratos project. Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Contact 📬
For more information on this project, please reach out at [contact@stratos-fly.com](mailto:contact@stratos-fly.com).

Project Link: [https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git](https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git)
