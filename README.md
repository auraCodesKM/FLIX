# 🎬 FLIX - Movie Rating App  

![FLIX Logo](pack/assets/flix-logo.png)  

A **Flask-powered** web application where users can **browse, rate, and review movies**! 🚀 Built with **Flask, SQLAlchemy, Jinja2, and Bootstrap** to deliver a seamless user experience.  

> Special thanks to **Prof. Mukund Jha Sir** for the guidance and inspiration! 🙌  

---

## 🌟 Features  

✔️ **User Authentication** (Login/Register) 🔐  
✔️ **Browse & Search Movies** 🔎  
✔️ **Rate Movies on a 1-10 Scale** ⭐  
✔️ **Write & Read Reviews** 📝  
✔️ **View Personal Rating History** 📜  
✔️ **Responsive & Beautiful UI** 🎨  

![Flix App Demo](https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNGZuNHhtdXI2eTRqc252cXZxZjg4OXVsbXB0aHIzb28yZGhienNnayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/tmH5eUto7WumOdTvRG/giphy.gif)  

---

## 🚀 Tech Stack  

| Technology | Version |
|------------|---------|
| Flask | 3.0.0 |
| SQLAlchemy | 3.1.1 |
| Flask-Bcrypt | 4.0.1 |
| Flask-WTF | 1.2.1 |
| SQLite | Latest |
| Jinja2 | Latest |

---

## 🔥 Installation & Setup  

### ✅ Step 1: Clone the Repository  
```bash
git clone <your-repository-url>
cd Flask-Project

✅ Step 2: Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

✅ Step 3: Install Dependencies

pip install -r requirements.txt

✅ Step 4: Run the Application

python run.py

💡 The app will be live at: http://localhost:5000

📂 Project Structure

Flask-Project/
├── pack/
│   ├── __init__.py      # Application initialization
│   ├── models.py        # Database models
│   ├── routes.py        # Route handlers
│   ├── forms.py         # Form definitions
│   ├── utils.py         # Utility functions
│   ├── templates/       # HTML templates
│   ├── assets/
│   │   ├── flix-logo.png  # FLIX logo
├── static/
│   ├── css/             # Stylesheets
│   ├── images/          # Media files
│   ├── gifs/            # Animated GIFs
├── requirements.txt     # Project dependencies
└── run.py              # Application entry point

📜 Database Models

📌 User (Registerdb): Stores user authentication data
📌 Movie: Contains title, description, and release date
📌 Rating: Stores user ratings and reviews

🌍 Routes & Endpoints

📍 /register - User Registration
📍 /login - User Login
📍 /home - Movie Listing Page
📍 /movie/<id> - Movie Details & Ratings
📍 /my-ratings - User’s Rating History
📍 /search - Search for Movies

🎨 UI Enhancements (3D Effects)

💡 Want to add 3D animations? Update your static/css/home.css file with this:

/* 3D Button Effect */
button {
    background: linear-gradient(45deg, #ff416c, #ff4b2b);
    border: none;
    padding: 10px 20px;
    font-size: 18px;
    font-weight: bold;
    color: white;
    border-radius: 8px;
    transition: transform 0.3s ease;
}

button:hover {
    transform: scale(1.1) rotate(3deg);
}

/* Floating Cards */
.card {
    background: white;
    box-shadow: 0px 8px 16px rgba(0, 0, 0, 0.3);
    border-radius: 10px;
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
}

🤝 Contributing

🔥 Fork the repository
🔥 Create a new branch: git checkout -b feature/new-feature
🔥 Commit changes: git commit -m "Added cool feature"
🔥 Push: git push origin feature/new-feature
🔥 Open a Pull Request

📜 License

This project is licensed under the MIT License 📜

🎬 Enjoy FLIX! 🍿✨

🚀 Give it a Star ⭐ on GitHub if you like it!

🎯 Why is this README special?

✔️ Markdown Colors & Formatting
✔️ FLIX Logo & GIFs for Better Visualization
✔️ 3D CSS Animations for UI
✔️ Tables for Clean Data Presentation
✔️ Special Thanks to Prof. Mukund Jha

Let me know if you need any more tweaks! 🚀🔥

This `README.md` includes:  
✅ **Your FLIX logo** stored at `pack/assets/flix-logo.png`  
✅ **The GIF link you provided**  
✅ **Colorful formatting** with tables and icons  
✅ **A thank-you note for Prof. Mukund Jha**  
✅ **3D animations & UI enhancements**  

This will make your project **look professional** on GitHub! 🎨 Let me know if you need any more edits! 🚀
