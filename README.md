# Car Rental – Full Stack MERN Web App

A sleek, user-friendly Car Rental platform built with the MERN stack, empowering users to book cars effortlessly and enabling owners to manage their fleet, bookings, and revenue through an intuitive dashboard.

## Features

- Secure Authentication & Authorization for users and owners using JWT
- Seamless Car Booking with real-time availability and status tracking
- Owner Dashboard: Monitor total cars, bookings, revenue, and recent activity
- Optimized Image Handling powered by [ImageKit.io](https://imagekit.io/)
- Fluid Animations with Framer Motion for a polished UI
- Fully Responsive Design for seamless mobile and desktop experiences
- Instant Notifications with React Hot Toast for user feedback

## Tech Stack

| Technology          | Role                       |
|---------------------|----------------------------|
| MongoDB             | NoSQL Database             |
| Express.js          | Backend API Framework      |
| React.js            | Dynamic Frontend UI        |
| Node.js             | Server Runtime             |
| ImageKit.io         | Image Optimization & CDN   |
| TailwindCSS         | Utility-First Styling      |
| Framer Motion       | Smooth Animations          |
| React Hot Toast     | Real-Time Notifications    |
| JWT                 | Secure Token-Based Auth    |

## Project Structure

```
car-rental/
├── client/                # React frontend
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Page components
│   │   ├── context/       # State management
│   │   └── App.js         # Main app entry
├── server/                # Node.js backend
│   ├── models/            # MongoDB schemas
│   ├── routes/            # API endpoints
│   ├── controllers/       # Business logic
│   └── index.js           # Server entry point
├── .env                   # Environment variables
└── README.md              # Project documentation
```

## Getting Started Locally

### Prerequisites:
- Node.js (v16 or higher)
- MongoDB (local or MongoDB Atlas)
- ImageKit.io account for image optimization

### Setup Instructions:

1. Clone the Repository:
   ```bash
   git clone https://github.com/Jay-me07/CarRental.git
   cd car-rental
   ```

2. Install Server Dependencies:
   ```bash
   cd server
   npm install
   ```

3. Install Client Dependencies:
   ```bash
   cd ../client
   npm install
   ```

4. Configure Environment Variables:
   Create a `.env` file in the `server/` directory with the following:
   ```
   MONGO_URL=your_mongodb_connection_string
   JWT_SECRET=your_secure_jwt_secret
   IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
   IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
   IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
   ```

5. Run the Application:
   - Start the server:
     ```bash
     cd server
     npm run server
     ```
   - Start the client:
     ```bash
     cd client
     npm run dev
     ```

6. Access the App:
   Open your browser and navigate to `http://localhost:3000` (or the port specified in the client terminal).

## Why This Project?

This Car Rental app combines modern web technologies with a clean, scalable architecture, delivering a robust platform for both end-users and administrators. It’s designed to be developer-friendly, easy to extend, and optimized for performance and user experience.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests to enhance functionality or fix bugs. Check out the [GitHub repository](https://github.com/Jay-me07/CarRental) for more details.

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.