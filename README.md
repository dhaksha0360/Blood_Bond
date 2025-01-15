Blood Bond

An AI-driven mobile application that connects blood donors and recipients in real-time. Built using React Native, Expo, Firebase, and Python, Blood Bond simplifies the process of finding blood donors, saving lives, and fostering a stronger donor-recipient network.

Features

->Real-Time Blood Request Matching: Uses AI to match donors and recipients instantly.

->Search Nearby Donors: Locate available donors nearby based on geolocation.

->Donor & Recipient Profiles: View donor/recipient details, including blood type, location, and availability.

->Push Notifications: Notify donors instantly when a request is made.

->Secure Data Management: Firebase ensures secure storage of user data.

Tech Stack

->Frontend: React Native with Expo

->Backend: Firebase (Cloud Firestore, Firebase Authentication)

->AI Integration: Python for matching algorithms and analytics

->State Management: React Native’s Context API


Installation

Follow these steps to set up and run the project locally using Expo:
1. Clone the repository:

https://github.com/dhaksha0360/Blood_Bond.git

2. Install dependencies:

npm install  

3. Set up Firebase:
   
->Create a project in Firebase Console.

->Add your app and download the google-services.json file for Android or GoogleService-Info.plist for iOS.

->Place the file in the appropriate directories (assets folder or root based on your configuration).

->Enable Firebase Authentication and Cloud Firestore.


5. Start the app using Expo:
   
   npx expo start

7. Run on your device:
   
->Scan the QR code displayed in the terminal or browser using the Expo Go app (available on iOS and Android).
