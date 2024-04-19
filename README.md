# Stratos: The Future of General Aviation 🚀

Welcome to the official GitHub repository for Stratos, an innovative iOS app designed for general aviation enthusiasts. This repository is a resource hub showcasing our development practices, sample code, and the frameworks we use. Dive into our demos and explore the architecture and technology behind Stratos.

## Table of Contents 📚
- [I - Introduction](#i---introduction-)
- [II - Tech Stack](#ii---tech-stack-)
- [III - Features](#iii---features-)
- [IV - Code Samples](#iv---code-samples-)
- [V - Contributing](#v---contributing-)
- [VI - Contact](#vi---contact-)

## I - Introduction 🌟
Stratos is a mobile app designed to allow pilots and aviation enthusists alike, to explore new airports to fly to, log flight tracks, assess their flying performance, and connect with aviators locally and around the world. This repository provides insights into the app's creation, featuring our approaches to coding, design, and functionality.

## II - Tech Stack 💻

Stratos combines modern software engineering practices and cutting-edge technologies to deliver a robust and efficient application for general aviation enthusiasts. Below is an overview of the technology stack used in developing Stratos:
### i - Frontend
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

### ii - Backend
- **Firebase & Google Cloud Platform (GCP)**: Serves as the backbone for the app's server-side operations including data storage, server functions, backups, API security and hosting.
- **TypeScript Cloud Functions**: Extensively used for writing scalable and efficient server-side logic hosted on GCP, enhancing backend functionality and security.

### iii - Data Engineering and Machine Learning
- **Python**: The primary language used for all data engineering and machine learning tasks, enabling sophisticated data analysis and the development of recommendation systems.
  - **Pandas** and **NumPy**: For data manipulation and numerical operations.
  - **SciPy** and **Scikit-Learn**: Employed for advanced data analysis and machine learning tasks.
  - **TensorFlow**: Used for developing and training deep learning models.
  - **PyTorch**: Also employed for building and training advanced neural network models.
 
### iv - Messaging & Security
- **Native Messaging**: Built from the ground up, our messaging feature is fully native and supports end-to-end encryption with 2048-bit keys, ensuring private and secure communication among users.
- **Secure Data Handling with GCP**: Utilizing Google Cloud Platform's robust security features, Stratos ensures that all user data, including flight logs, photos, and personal information, is stored securely. GCP's encryption mechanisms automatically encrypt all data before it is written to disk with no additional action required from the user, providing strong protection against data breaches.
- **Compliance and Data Integrity**: GCP compliance certifications ensure that Stratos meets rigorous privacy and security standards required for aviation and data protection regulations. This includes continuous monitoring and automatic updates to respond to potential security threats efficiently.

### v - Performance Monitoring and User Feedback
- **Google Analytics**: Monitors user engagement and app performance to gather insights that help improve user experience.
- **Firebase Crashlytics**: Provides real-time monitoring and reporting of app crashes to swiftly identify, prioritize, and resolve stability issues, ensuring a smoother user experience.
- **User Feedback**: Currently collected via email surveys to understand user satisfaction and collect suggestions directly from users.

## vi - Planning and Managing Work
- **Feature Prioritization**: Uses a dynamic framework, assessing user feedback, market trends, and feasibility to guide feature selection aligned with user needs.
- **Agile Development Practices**: Employs agile methodologies like sprint planning and stand-ups to enhance flexibility and continual adaptation in our development process.
- **Cost-Benefit Analysis**: Performs cost-benefit analyses to efficiently allocate resources and prioritize high-impact features.
- **Roadmap Development**: Keeps a clear, regularly updated product roadmap that communicates planned features and timelines to stakeholders.

## vii - Maintainability and Version Control
- **Robust Code Management**: Adheres to industry best practices, with well-documented, logically structured, and regularly refactored code ensuring scalability and ease of maintenance.
- **Advanced Version Control with GitHub**: Utilizes GitHub for robust version control, enhancing team collaboration through effective branch management and seamless CI/CD pipeline integration.

## III - Features 🛠️
### i - Explore Airports and Nearby Activities 🌍
- **Intelligent Map**: Explore airports globally with our advanced map feature, designed to help you plan your next adventure efficiently.
  - ![Intelligent Map Screenshot](path/to/intelligent_map_screenshot.jpg)
  
- **Airport Filters**: Find airports by amenities like Restaurants, Museums, Parks, and Beaches, making it easier to plan your visits.
  - ![Airport Filters Screenshot](path/to/airport_filters_screenshot.jpg)
  
- **Favorites and History Visualization**: Visualize your frequented and favorite airports, sparking ideas for your next flights.
  - ![Favorites Visualization Screenshot](path/to/favorites_visualization_screenshot.jpg)

### ii - Flight Tracking and Performance Analysis ✈️
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

### iii - Social Networking for Aviators 🌐
- **Global Connections**: Make connections with pilots and aviation enthusiasts worldwide.
  - ![Global Connections Screenshot](path/to/global_connections_screenshot.jpg)
  
- **Local Meetups**: Discover and connect with pilots in your area to enhance your local aviation community.
  - ![Local Meetups Screenshot](path/to/local_meetups_screenshot.jpg)
  
- **Secure Communication**: Enjoy secure, private communications with end-to-end encrypted chat.
  - ![Secure Communication Screenshot](path/to/secure_communication_screenshot.jpg)


## IV - Code Samples 📝

Stratos source code is proprietary but you can find code samples of the app here: 
- [Swift Code Samples](/Code/Swift/)
- [Python Code Samples](/Code/Python/)
- [TypeScript Code Samples](/Code/TypeScript/)

## V - Contributing 🤝

We welcome contributions to the Stratos project. Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## VI - Contact 📬
For more information on this project, please reach out at [contact@stratos-fly.com](mailto:contact@stratos-fly.com).

Project Link: [https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git](https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git)
