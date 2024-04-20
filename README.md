# Stratos: The Future of General Aviation 🚀

Welcome to the official public GitHub repository for Stratos, an innovative iOS app designed for general aviation enthusiasts. This repository is a resource hub showcasing our development practices, sample code, and the frameworks we use. Dive into our demos and explore the architecture and technology behind Stratos.

Stratos is now available on the App Store on iPhone and iPad! Click [here](https://apple.co/3U8506K) to download it.

![Demo1](/screenshots/gif1.gif)
![Demo2](/screenshots/gif2.gif)
![Demo3](/screenshots/gif3.gif)

## Table of Contents 📚
- [I - Introduction](#i---introduction-)
- [II - Tech Stack](#ii---tech-stack-)
- [III - Features](#iii---features-)
- [IV - Code Samples](#iv---code-samples-)
- [V - Contact](#vi---contact-)

## I - Introduction 🌟
Stratos is a mobile app designed to allow pilots and aviation enthusists alike, to explore new airports to fly to, log flight tracks, assess their flying performance, and connect with aviators locally and around the world. This repository provides insights into the app's creation, featuring our approaches to coding, design, and functionality.

## II - Tech Stack 💻

Stratos combines modern software engineering practices and cutting-edge technologies to deliver a robust and efficient application for general aviation enthusiasts. Below is an overview of the technology stack used in developing Stratos:
### i - Frontend
  - **SwiftUI & UIKit**: Primarily built with SwiftUI (95%) for its modern, declarative syntax that simplifies UI development, complemented by UIKit (5%) for specific UI components not yet fully available in SwiftUI.
  - **External Dependencies via SPM**:
    - **Firebase**: Utilized for backend services, real-time database, and user authentication.
    - **KingFisher**: Swift library for downloading and caching images from the web.
    - **RevenueCat**: Manages in-app subscriptions and purchasing processes.
    - **GoogleSignIn**: Provides authentication services linked to Google accounts.
  
  - **Apple Frameworks**:
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

### vi - Planning and Managing Work
- **Feature Prioritization**: Uses a dynamic framework, assessing user feedback, market trends, and feasibility to guide feature selection aligned with user needs.
- **Agile Development Practices**: Employs agile methodologies like sprint planning and stand-ups to enhance flexibility and continual adaptation in our development process.
- **Cost-Benefit Analysis**: Performs cost-benefit analyses to efficiently allocate resources and prioritize high-impact features.
- **Roadmap Development**: Keeps a clear, regularly updated product roadmap that communicates planned features and timelines to stakeholders.

### vii - Maintainability and Version Control
- **Robust Code Management**: Adheres to industry best practices, with well-documented, logically structured, and regularly refactored code ensuring scalability and ease of maintenance.
- **Advanced Version Control with GitHub**: Utilizes GitHub for robust version control, enhancing team collaboration through effective branch management and seamless CI/CD pipeline integration.

## III - Features 🛠️
### i - Explore Airports and Nearby Activities 🌍

[<img src="/screenshots/1.png" alt="Map" width="20%">](#)
[<img src="/screenshots/2.png" alt="Map" width="20%">](#)
[<img src="/screenshots/10.png" alt="Map" width="20%">](#)

- **Intelligent Map**: Explore airports in detail globally with our advanced map feature, designed to help you plan your next adventure efficiently.
- **Advanced Filters**: Filter the airports you want to land at.
- **Nearby Activity Filters**: Find airports by amenities like Restaurants, Museums, Parks, and Beaches, making it easier to plan your visits.  
- **Cross Country Generator**: Select the distance radius to display airports within your desired flying range, ideal for exploring new destinations.
- **Community Comments**: Add and read comments on airports to share experiences and tips with the global aviation community, enhancing collaborative knowledge and support.
- **Favorites and Visited Airports**: Visualize your frequented and favorite airports, sparking ideas for your next flights.

### ii - Flight Tracking ✈️

[<img src="/screenshots/3.png" alt="Flight" width="20%">](#)
[<img src="/screenshots/4.png" alt="Flight" width="20%">](#)
- **Precision Flight Logging**: Focus on flying the plane and log flight tracks after you've landed using our automated flight track finder technology.
- **Pilot Debriefs and Journals**: Turn every flight into a learning opportunity with detailed pilot debriefs and journals.
- **Historical Flight Logs**: Log old flights tracks dating from 2011 onwards.

### iii - Performance Analysis 📊 

[<img src="/screenshots/11.png" alt="Performance" width="20%">](#)
[<img src="/screenshots/12.png" alt="Performance" width="20%">](#)
[<img src="/screenshots/13.png" alt="Performance" width="20%">](#)
[<img src="/screenshots/14.png" alt="Performance" width="20%">](#)

- **Pilots Statistics**: Easily access key pilot statistics directly from your profile, and view the same stats on other pilots' to compare performances and learn from peers. 
- **Performance Analytics**: Monitor your flying improvement over time with our advanced analytics tools.
- **Hours and Distance Chart**: Track the total nautical miles flown and distances covered in different time frames, providing a comprehensive view of your flying activities over periods.
- **Pilot Score Analytics**: Detailed analytics breaking down your pilot performance scores, helping you identify strengths and areas for improvement based on a variety of flight parameters.
- **Aircraft Analytics**: Analyze specific metrics related to each aircraft you fly, including usage frequency, performance efficiency, and maintenance needs.
- **Airport Analytics**: View statistics on the airports you’ve visited, categorized by type and frequency, to understand your travel patterns and favorite destinations.


### iv - Social Community Platform for Aviators 🌐
[<img src="/screenshots/6.png" alt="Performance" width="20%">](#)
[<img src="/screenshots/5.png" alt="Social" width="20%">](#)
[<img src="/screenshots/9.png" alt="Social" width="20%">](#)

- **Flight Sharing**: Share your logged flights with your friends and the aviation community on a public feed (if you chosse to), showcasing your aviation journey and experiences.
- **Global Connections**: Make connections with pilots and aviation enthusiasts worldwide.
- **Local Meetups**: Discover and connect with pilots in your area to enhance your local aviation community.
- **Secure Communication**: Enjoy secure, private communications with end-to-end encrypted chat.

## IV - Code Samples 📝

Stratos source code is not open source, but if interested in my work please reach out and I'll be happy to share some of the Swift, Python or TypeScript code with you.

## VI - Contact 📬
For more information on this product, please reach out at [contact@stratos-fly.com](mailto:contact@stratos-fly.com).

Project Link: [https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git](https://github.com/LouisBensard/Stratos-iOSAppCode-Swift-PUBLIC.git)
