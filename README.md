# Expense Tracker

A modern, real-time expense tracking application built with React, Firebase, and Tailwind CSS. Track your income and expenses with a clean, responsive interface and secure Google authentication.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![React](https://img.shields.io/badge/React-18.x-61dafb.svg)
![Firebase](https://img.shields.io/badge/Firebase-Latest-orange.svg)

## ✨ Features

- 🔐 **Secure Authentication** - Google Sign-In integration
- 💰 **Transaction Management** - Add, view, and delete income/expenses
- 📊 **Real-time Updates** - Instant data synchronization across devices
- 🎨 **Modern UI** - Clean, responsive design with Tailwind CSS
- 🔥 **Firebase Backend** - Cloud Firestore for data storage
- 📱 **Fully Responsive** - Works seamlessly on all devices

## 🚀 Demo

[Live Demo](#) _(Add your deployed link here)_

## 📸 Screenshots

_(Add screenshots of your application here)_

## 🛠️ Tech Stack

- **Frontend:** React.js, Vite
- **Styling:** Tailwind CSS
- **Backend:** Firebase (Authentication & Firestore)
- **State Management:** React Context API
- **Hooks:** Custom hooks for transaction management

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- A [Firebase](https://firebase.google.com/) account

## ⚙️ Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Jeevanm2004/expense-tracker.git
   cd expense-tracker
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up Firebase**
   - Create a new Firebase project at [Firebase Console](https://console.firebase.google.com/)
   - Enable Google Authentication
   - Create a Firestore Database
   - Copy your Firebase configuration

4. **Configure environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   ```

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   
   Navigate to `http://localhost:5173`

## 📁 Project Structure

```
expense-tracker/
├── public/
├── src/
│   ├── components/
│   │   ├── AddTransaction.jsx
│   │   ├── Balance.jsx
│   │   ├── TransactionHistory.jsx
│   │   └── TransactionItem.jsx
│   ├── context/
│   │   ├── AppReducer.js
│   │   └── GlobalState.jsx
│   ├── hooks/
│   │   ├── useAddTransaction.js
│   │   ├── useGetTransactions.js
│   │   └── useGetUserInfo.js
│   ├── pages/
│   │   ├── auth/
│   │   └── expense-tracker/
│   ├── config/
│   │   └── firebase-config.js
│   ├── App.jsx
│   └── main.jsx
├── .env
└── package.json
```

## 🎯 Usage

1. **Sign In** - Click the "Sign in with Google" button
2. **View Balance** - See your current balance at the top
3. **Add Transaction** - Enter description and amount, select type (income/expense)
4. **View History** - See all your transactions listed below
5. **Delete Transaction** - Click the delete button on any transaction to remove it

## 🔮 Future Enhancements

- [ ] Edit existing transactions
- [ ] Filter transactions by date range
- [ ] Sort transactions (by date, amount, type)
- [ ] Export transactions to CSV/PDF
- [ ] Budget setting and alerts
- [ ] Data visualization with charts
- [ ] Dark mode toggle
- [ ] Multiple currency support

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👤 Author

**Jeevan M**

- GitHub: [@Jeevanm2004](https://github.com/Jeevanm2004)
- Portfolio: [jeevanm-portfolio.netlify.app](https://jeevanm-portfolio.netlify.app)
- LinkedIn: [linkedin.com/in/jeevanabhi](https://www.linkedin.com/in/jeevanabhi)

## 🙏 Acknowledgements

- [React Documentation](https://reactjs.org/)
- [Firebase Documentation](https://firebase.google.com/docs)
- [Tailwind CSS](https://tailwindcss.com/)
- [Vite](https://vitejs.dev/)

---

⭐ Star this repository if you found it helpful!
