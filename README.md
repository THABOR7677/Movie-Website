# 🎬 Movie Website

Welcome to the **Movie Website**! This project is a web application that allows users to browse popular movies, search for movies, and save their favorites. It uses the [TMDB API](https://www.themoviedb.org/) to fetch movie data and provides a seamless user experience.

---

## ✨ Features

- **Browse Popular Movies**: Discover the latest and most popular movies.
- **Search Movies**: Search for movies by title.
- **Add to Favorites**: Save your favorite movies to a personalized list.
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices.
- **Dynamic Movie Details**: View movie posters, titles, and release years.

---

## 🚀 Live Demo

Check out the live demo of the project: [Movie Website Live Demo](#)  
*(Replace with your actual deployment link, e.g., Netlify, Vercel, or GitHub Pages)*

---

## 🛠️ Technologies Used

- **Frontend**:
  - React.js
  - React Router (for navigation)
  - Context API (for state management)
  - CSS (for styling)
- **Backend**:
  - TMDB API (for movie data)
- **Tools**:
  - Vite (for fast development)
  - Git (for version control)
  - GitHub (for hosting the repository)

---

## 📂 Project Structure

Here’s an overview of the project structure:
movie-website/
├── public/ # Static assets
├── src/ # Source code
│ ├── assets/ # Images and icons
│ ├── components/ # Reusable components (e.g., MovieCard, NavBar)
│ ├── contexts/ # React Context for state management
│ ├── css/ # CSS files for styling
│ ├── pages/ # Page components (e.g., Home, Favorites)
│ ├── services/ # API utility functions
│ ├── App.jsx # Main application component
│ └── main.jsx # Entry point
├── .gitignore # Files to ignore in Git
├── index.html # Main HTML file
├── package.json # Project dependencies
├── README.md # Project documentation (you are here!)
└── vite.config.js # Vite configuration


---

## 🔧 Installation

Follow these steps to set up the project locally:

1. **Clone the Repository**:
   ```bash
   [git clone https://github.com/your-username/movie-website.git
   cd movie-website](https://github.com/THABOR7677/Movie-Website.git)

Install Dependencies:

bash
Copy
npm install
Set Up Environment Variables:

Create a .env file in the root directory.

Add your TMDB API key:

env
Copy
VITE_TMDB_API_KEY=your_api_key_here
Run the Development Server:

bash
Copy
npm run dev
Open the App:
Visit http://localhost:5173 in your browser.

🌐 Running the Project in Your Browser
To load and open the project in your personal browser, follow these steps:

Clone the Repository (if you haven't already):

bash
Copy
git clone https://github.com/your-username/movie-website.git
cd movie-website
Install Dependencies:

bash
Copy
npm install
Set Up Environment Variables:

Create a .env file in the root directory.

Add your TMDB API key:

env
Copy
VITE_TMDB_API_KEY=your_api_key_here
Start the Development Server:

bash
Copy
npm run dev
Open in Your Browser:

Once the development server is running, open your browser.

Go to the following URL:

Copy
http://localhost:5173
You should now see the Movie Website running in your browser!

📸 Screenshots
(Add screenshots of your project here. For example:)

Home Page
Home Page

Favorites Page
Favorites Page

💡 How It Works
Fetching Movie Data:

The app uses the TMDB API to fetch popular movies and search results.

Example API call:

javascript
Copy
const response = await fetch(`https://api.themoviedb.org/3/movie/popular?api_key=${API_KEY}`);
State Management:

The MovieContext manages the state of favorite movies using React Context API.

Favorites are stored in localStorage for persistence.

Dynamic Routing:

React Router is used to navigate between the Home and Favorites pages.

🤝 Contributing
Contributions are welcome! If you’d like to contribute to this project, follow these steps:

Fork the repository.

Create a new branch:

bash
Copy
git checkout -b feature/your-feature-name
Commit your changes:

bash
Copy
git commit -m "Add your message here"
Push to the branch:

bash
Copy
git push origin feature/your-feature-name
Open a pull request.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

🙏 Acknowledgments
Thanks to TMDB for providing the movie data API.

Inspired by Netflix and other streaming platforms.


---

### **How to Use**
1. Copy the entire Markdown code above.
2. Open your GitHub repository.
3. Create a new file named `README.md`.
4. Paste the code into the file.
5. Replace placeholders (e.g., `your-username`, `your_api_key_here`, screenshots, etc.) with your actual information.
6. Commit the changes.
