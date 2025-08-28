# fitNessTracker
Here’s a sample README.md for your fitNessTracker project, listing the technologies used and giving a starter structure. You can further customize it with specific instructions or features as needed.

---

# fitNessTracker

A web application to help users track and manage their fitness journey, workouts, and progress. This project focuses on user-friendly design and interactive features to make fitness tracking simple and effective.

## Features

- Log daily workouts and activities
- Monitor fitness progress over time
- User-friendly dashboard
- Responsive design for mobile and desktop

## Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/raysoham067/fitNessTracker.git
   ```

2. **Environment variables**
   - Create `server/.env` with:
     ```env
     MONGODB_URL=your_mongodb_connection_string
     JWT=your_jwt_secret
     PORT=8080
     ```
   - Optionally create `client/.env` with:
     ```env
     REACT_APP_API_URL=http://localhost:8080/api
     ```

3. **Install dependencies and run**
   - In one terminal:
     ```bash
     cd server
     npm install
     npm run dev
     ```
   - In another terminal:
     ```bash
     cd client
     npm install
     npm start
     ```

The client is configured to proxy `/api` to the server on `http://localhost:8080`.


## Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

## License

This project is licensed under the MIT License.

---

Let me know if you want to add more detailed instructions, screenshots, or other sections!
