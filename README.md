# **roommate**

**Roommate Finder** is a web app that helps users find compatible roommates. Built with **React** and **Node.js**, it offers user profiles, compatibility matching, roommate listings, real-time chat, and agreement forms. The app is responsive and easy to use, making roommate hunting simple and efficient.


## **Features**

* **User Registration, Login & Profile Management**
  Secure sign-up/login and detailed user profiles with preferences.

* **Compatibility Matching**
  Personalized compatibility forms to find the best roommate matches.

* **Roommate Listings**
  Browse, search, and view detailed listings with photos.

* **Real-time Chat**
  Communicate instantly with matched roommates using live chat.

* **Agreement Forms**
  Create and manage roommate contracts securely within the app.

* **Inbox & Notifications**
  Manage messages and receive notifications seamlessly.

* **Geolocation & Interactive Maps**
  View roommate locations on interactive maps powered by **Leaflet**, with browser-based geolocation support for nearby searches.

* **Responsive Design**
  Fully responsive layout optimized for both mobile and desktop users.

## **Technologies Used**

**Frontend:** React, JSX, CSS
**Backend:** Node.js, Express
**Database:** MongoDB (for user data, profiles, listings)
**Authentication:** JWT-based user login and registration
**Real-time Communication:** WebSocket or Socket.io for chat
**File Uploads:** Multer middleware for profile and listing images
**Deployment Tools:** Vite for frontend bundling

## **APIs**

* **User API:** Register, login, update profile
* **Listing API:** Create, read, update, delete roommate listings
* **Compatibility API:** Submit and retrieve compatibility preferences
* **Chat API:** Real-time messaging between users
* **Agreement API:** Manage roommate agreements
* **Upload API:** Handle image uploads for profiles and listing

## **Technologies & 3rd Party APIs Used**

### **Frontend**

* **React** (JSX) for UI
* **Bootstrap** & **React-Bootstrap** for styling and responsiveness
* **Leaflet** & **React-Leaflet** for interactive maps showing roommate locations
* **Emoji Picker React** for emojis in chat and forms
* **Axios** for HTTP requests
* **Socket.io-client** for real-time chat
* **jsPDF** & **jsPDF-autotable** for PDF generation (agreements)
* **Pusher-js** for real-time event broadcasting (optional push notifications)
* **Vite** for frontend bundling and development

### **Backend**

* **Node.js** & **Express** for API and server
* **MongoDB** (via Mongoose) for data storage
* **JWT** (jsonwebtoken) for secure authentication
* **Multer** for file uploads
* **Socket.io** for real-time chat backend
* **Pusher** for real-time events (optional)
* **bcryptjs** for password hashing
* **dotenv** for environment variables
* **OpenAI SDK** for AI-powered features (chatbot, recommendations, compatibility analysis)
* **CORS** middleware
* **Axios** for server-side HTTP calls

