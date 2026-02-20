# Javenture
Javenture – Household Inventory Management Android App
Javenture is a native Android application built in Java that allows users to manage, organize, and track household inventory items. The app supports item tagging, barcode scanning, photo capture, sorting and filtering, and automatic total value calculation. It uses Firebase for backend services and includes automated UI testing for reliability.

Overview
Javenture helps users maintain a digital inventory of their personal belongings. Each item can store detailed information such as description, value, date acquired, serial number, tags, and photos.
This application is useful for:
Personal asset tracking
Insurance documentation
Household inventory management
Organization of valuable items

Features
Item Management
Add new inventory items
Edit and delete existing items
Store detailed item information:
Description
Make / Brand
Model
Serial number
Estimated value
Date of acquisition
Tags
Comments
Tagging System
Create custom tags
Assign multiple tags to items
Filter items by tag
Apply tags to multiple items using multi-select
Barcode and Serial Number Scanning
Scan barcodes using device camera
Automatically populate item information
Supports fast item entry
Photo Capture and Storage
Capture photos using camera
Attach photos to inventory items
View and manage item images
Sorting and Filtering
Users can sort items by:
Description
Make / Brand
Date
Estimated value
Tags
Users can filter items using:
Tags
Keywords
Date ranges
Make / description
Total Inventory Value Tracking
Automatically calculates total estimated value of all items
Updates dynamically as items are added, edited, or removed

Backend and Data Storage
This application uses Firebase services for cloud storage and authentication.
Firebase services used:
Firebase Authentication – user login and account management
Firebase Firestore / Realtime Database – item data storage
Firebase Storage – photo storage
This allows persistent, cloud-based inventory management.

Automated Testing
The project includes automated UI testing using Android Espresso.
Tested features include:
Adding items
Editing items
Multi-selection
Barcode scanning
Photo capture
Sorting and filtering
Total value calculation
User profile functionality
This ensures application reliability and correctness.

Project Structure
app/
├── main/
│   ├── java/com/example/javenture/     # Application source code
│   ├── res/                            # UI layouts and resources
│   └── AndroidManifest.xml
│
├── androidTest/java/com/example/javenture/
│   └── UI test cases (Espresso tests)
│
├── build.gradle.kts                   # Build configuration
├── google-services.json               # Firebase configuration
└── gradle/                            # Gradle build system


Technologies Used
Java
Android SDK
Firebase Authentication
Firebase Firestore / Realtime Database
Firebase Storage
Android Camera API
Espresso UI Testing Framework
Gradle Build System

How to Run
Requirements
Android Studio
Android SDK
Firebase project configuration
Steps
Clone the repository
git clone https://github.com/yourusername/javenture.git

Open in Android Studio
Add your Firebase configuration file:
google-services.json

Build and run on emulator or Android device

Screenshots
(Add screenshots here)
Example:
![Inventory Screen](screenshots/inventory.png)
![Add Item Screen](screenshots/add_item.png)


Learning Outcomes
This project demonstrates:
Native Android development using Java
Cloud backend integration with Firebase
Mobile UI design and architecture
Camera and barcode scanning integration
Automated UI testing using Espresso
Data management and filtering systems

Author
Yicheng Lin
Master of Computer Science – Visual Computing
Simon Fraser University

Future Improvements
Export inventory to CSV / PDF
Offline support with synchronization
Improved barcode auto-detection
Modern UI redesign using Jetpack Compose
Real-time multi-device sync

