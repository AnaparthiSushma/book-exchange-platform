

# 📚 Book Exchange Web App

A full-stack web application where users can buy, sell, and exchange books with others. The app supports user authentication, live location fetching, and integration with the Google Books API to simplify book lookup.


### 🔗 Live Features

- 📌 Sign up, login, and manage your profile
- 📍 Automatically fetch user's live location via GPS
- 💰 Sell used books with price, image, and location
- 🛒 Purchase books listed by other users
- 🔄 Exchange books using search from Google Books API
- 📚 View and search for books available for exchange
- 📬 Email notifications 

## 🚀 Technologies Used

### Frontend:
- React.js
- Axios
- React Router
- CSS3

### Backend:
- Node.js
- Express.js
- MongoDB (Mongoose)
- Multer (image uploads)
- dotenv
- OpenCage Geocoder API (for reverse geolocation)
- Google Books API (for book search)


## 🛠️ Setup Instructions

### Prerequisites:
- Node.js & npm
- MongoDB (running locally or remotely)

---

### 📦 Clone the Repository

```bash
git clone https://github.com/AnaparthiSushma/book-exchange-platform.git
cd book-exchange-platform
````

---

### ⚙️ Backend Setup


cd backend


1. Create a `.env` file in the `/backend` directory and add your credentials:

```env
EMAIL_USER=YOUR_MAIL_ID
EMAIL_PASS=YOUR_EMAIL_PASSPHARSE
GOOGLE_BOOKS_API_KEY = YOUR_API_KEY
```

2. Start the server:

```bash
node server.js
```

> Make sure MongoDB is running locally or update the `mongoose.connect()` URLs accordingly.

---

### 💻 Frontend Setup

cd login-signup-app
npm start

The React app will run on `http://localhost:3000`



## 📷 Screenshots

> Add some screenshots of your app here for visual reference.
![Screenshot 2024-12-17 211522](https://github.com/user-attachments/assets/ecbd8037-ab71-4279-9655-abbe9d2d9547)
![Screenshot 2024-12-17 215845](https://github.com/user-attachments/assets/46f497c9-f25e-466f-a388-7f69c1e56aa1)
![Screenshot 2024-12-17 221442](https://github.com/user-attachments/assets/4bdb4d87-7744-4690-a89d-d36b2b8d7abe)
![Screenshot 2024-12-17 222912](https://github.com/user-attachments/assets/cdfe532b-e4c7-4a4e-b77a-57ae83b65230)
![Screenshot 2024-12-19 022016](https://github.com/user-attachments/assets/dfc58a2e-ac1b-4b58-b1bf-92b68719ac80)
![Screenshot 2024-12-19 022202](https://github.com/user-attachments/assets/131fe284-ef20-4836-bec2-b6b355fbf182)
![Screenshot 2024-12-19 022105](https://github.com/user-attachments/assets/79642bcb-defa-4cd6-bfc1-f799eaf20558)


## 🛡️ Security Tips

* Never commit `.env` files to GitHub
* Consider hashing passwords using `bcrypt`
* Use environment variables for all sensitive keys



## 📬 API Integrations

* **OpenCage Geocoding**: [https://opencagedata.com/](https://opencagedata.com/)
* **Google Books API**: [https://developers.google.com/books](https://developers.google.com/books)


Made with ❤️ by **Anaparthi Sushma Srivalli Gayathri**

