#Expense Tracker

A full-stack expense tracking application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. This application helps users track their income and expenses, categorize transactions, and visualize their spending patterns.



![Screenshot 2024-11-08 115748](https://github.com/user-attachments/assets/0606b25e-481c-4434-84d7-fce200bb1670)# MERN 

![Screenshot 2024-11-08 115557](https://github.com/user-attachments/assets/a2d4c450-4e93-4dbb-bfd5-fd5ba32acf16)

![Screenshot 2024-11-08 115621](https://github.com/user-attachments/assets/494cee2e-fa55-45af-8760-c978fa504d31)

![Screenshot 2024-11-08 115748](https://github.com/user-attachments/assets/0a374450-71f5-470d-ba0e-1c6d476b91b8)



## Features

- 📱 User-friendly interface for managing transactions
- 💰 Track both income and expenses
- 🏷️ Categorize transactions
- 📊 Visual representation of spending patterns
- 📅 Filter transactions by date
- 🔒 Secure user authentication
- 📱 Responsive design for all devices

## Prerequisites

Before running this application, make sure you have the following installed:
- Node.js (v14.0.0 or later)
- MongoDB
- npm or yarn package manager

## Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/MERN-Expense-Tracker.git
cd MERN-Expense-Tracker
```

2. Install dependencies for both backend and frontend
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Create a `.env` file in the backend directory with the following variables:
```env
MONGODB_URI=your_mongodb_connection_string
PORT=5000
JWT_SECRET=your_jwt_secret
```

## Running the Application

1. Start the backend server
```bash
cd backend
npm run dev
```

2. Start the frontend development server
```bash
cd frontend
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
MERN-Expense-Tracker/
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── utils/
│   │   └── App.js
│   └── package.json
└── README.md
```

## API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Login user

### Transactions
- `GET /api/transactions` - Get all transactions
- `POST /api/transactions` - Create new transaction
- `PUT /api/transactions/:id` - Update transaction
- `DELETE /api/transactions/:id` - Delete transaction

## Technologies Used

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT Authentication
- dotenv

### Frontend
- React.js
- React Router
- Context API
- Axios
- Chart.js
- Tailwind CSS

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://reactjs.org/)
- [Node.js Documentation](https://nodejs.org/)

## Support

For support, email your-email@example.com or open an issue in this repository.
