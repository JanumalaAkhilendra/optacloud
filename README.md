## Delivery Location App

This project provides a user interface for selecting and managing delivery locations using OpenStreetMap API. It includes features for:

Location Permission Request:
* Informative modal for location permission.
* Options to "Enable Location" or "Search Manually."
* Geolocation & Pin Selection:
* Interactive map with pin placement for precise location selection.
* "Locate Me" button for automatic location detection.

Delivery Address Form: 
* Detailed address input fields (House/Flat/Block No., Apartment/Road/Area).
* Address categorization (Home, Office, Friends & Family).

Address Management:
* List of saved addresses for easy selection.
* Address update and deletion functionality.
* Address search for recent or new locations.
* Backend (Node.js)


Clone the repository:

Bash
```
git clone <repository_url>
```
Install dependencies:

For Backend:
Bash
```
cd backend
npm install
```
For Frontend:
Bash
```
cd frontend
npm install
```

Configure environment variables:
Create a .env file in the backend directory for environment-specific variables (e.g., API keys, database credentials).
```
PORT=5000
DB_CONNECTION_STRING="Your MongoDB connection string"
```

Start the development server:

Bash
```
npm run dev
```
Running the Backend

Navigate to the backend directory:

Bash
```
cd backend
```

Start the server:
Bash
```
node server.js
```
you can see live demo [here](https://optacloud.vercel.app/)

<details>
  <summary>Screenshots </summary>

![Screenshot (415)](https://github.com/user-attachments/assets/371c115f-c64c-4963-aecd-6c6071b88efe)
![Screenshot (416)](https://github.com/user-attachments/assets/bbbff659-193c-4647-9ed7-ed35d7b69f8d)
![Screenshot (417)](https://github.com/user-attachments/assets/06ee4c5e-ab52-49c0-9126-23e5d4eeab76)
![Screenshot (418)](https://github.com/user-attachments/assets/051921ff-b3df-4d89-a820-185db561daed)
![Screenshot (419)](https://github.com/user-attachments/assets/5c8d86cf-a255-44b9-85b5-0be30e3680c6)


</details>

## Contributing

* Fork the repository
* Create your feature branch
* Commit changes
* Push to branch
* Create a pull request

Thank you for Visiting 💓, Make sure to give it a star 🌟
