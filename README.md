# BloodDonationApp
Blood Donation App

The Blood Donation App is a mobile application designed to connect blood donors with those in urgent need of blood. This app allows users to register as blood donors by providing essential information such as their name, blood type, and contact details. Individuals in need of blood donations can search for donors by blood type and location, making the process of finding compatible donors quick and efficient.

Key Features:
Donor Registration: Users can sign up as blood donors, entering necessary information that will be stored in the Firebase Firestore database.
Search for Donors: People in need of blood can search the database to find nearby donors based on blood type and location, making it easy to reach out to compatible donors.
Urgent Notifications: Notifications are sent to relevant donors when a new urgent case is registered that matches their blood type and location.
Informational Section: The app includes an informative page with details on the benefits, requirements, and conditions for blood donation, helping educate users on the importance of donating blood.
Location-Based Services: The app incorporates OpenStreetMap (OSM) for mapping features, allowing users to view and select locations for blood donation.
Technology Stack:
Frontend: Built with Flutter for a cross-platform, responsive design.
Backend: Utilizes Firebase for real-time data management and Firebase Cloud Messaging (FCM) for notifications.
Database: Firestore database is used for storing donor, recipient, and case information.
This app aims to simplify the blood donation process, making it easier for people in critical need of blood to find compatible donors quickly and securely.
