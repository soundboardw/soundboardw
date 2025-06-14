/* General */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    background-color: #121212;
    color: #ffffff;
}

/* Header & Navigation */
header {
    background-color: #1f1f1f;
    padding: 1rem 2rem;
    border-bottom: 1px solid #333;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo a {
    font-size: 1.8rem;
    font-weight: bold;
    color: #1DB954; /* Signature green color */
    text-decoration: none;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

.nav-links a {
    color: #ffffff;
    text-decoration: none;
    font-size: 1rem;
    transition: color 0.3s;
}

.nav-links a:hover {
    color: #1DB954;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 4rem 2rem;
    background: url('images/hero-bg.jpg') no-repeat center center/cover; /* Optional background image */
    background-color: #282828;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    color: #b3b3b3;
}

.search-container {
    margin-top: 2rem;
    display: flex;
    justify-content: center;
}

.search-container input {
    width: 50%;
    padding: 1rem;
    border: none;
    border-radius: 25px 0 0 25px;
    font-size: 1rem;
}

.search-container button {
    padding: 1rem 1.5rem;
    border: none;
    background-color: #1DB954;
    color: white;
    border-radius: 0 25px 25px 0;
    cursor: pointer;
    font-size: 1rem;
}

/* Categories */
.popular-categories, .latest-sounds {
    padding: 2rem;
    text-align: center;
}

.popular-categories h2, .latest-sounds h2 {
    font-size: 2rem;
    margin-bottom: 2rem;
    border-bottom: 2px solid #1DB954;
    display: inline-block;
    padding-bottom: 0.5rem;
}

.category-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 1.5rem;
}

.category-card {
    background-color: #1f1f1f;
    border-radius: 10px;
    overflow: hidden;
    cursor: pointer;
    transition: transform 0.3s;
}

.category-card:hover {
    transform: translateY(-10px);
}

.category-card img {
    width: 100%;
    height: 150px;
    object-fit: cover;
}

.category-card h3 {
    padding: 1rem;
    margin: 0;
}

/* Sound Grid */
.sound-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 1rem;
    text-align: left;
}

.sound-item {
    background-color: #282828;
    padding: 1rem;
    border-radius: 8px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.sound-item h4 {
    margin: 0;
    flex-grow: 1;
}

.play-btn, .download-btn {
    background: none;
    border: 1px solid #b3b3b3;
    color: #ffffff;
    width: 40px;
    height: 40px;
    border-radius: 50%;
    cursor: pointer;
    margin-left: 0.5rem;
    font-size: 1rem;
    transition: background-color 0.3s, border-color 0.3s;
}

.play-btn:hover {
    background-color: #1DB954;
    border-color: #1DB954;
}

.download-btn {
    text-decoration: none; /* For the <a> tag */
    display: inline-flex;
    align-items: center;
    justify-content: center;
}

.download-btn:hover {
    background-color: #535353;
    border-color: #535353;
}

/* Footer */
footer {
    background-color: #1f1f1f;
    color: #b3b3b3;
    text-align: center;
    padding: 2rem;
    margin-top: 2rem;
}

.footer-links a {
    color: #b3b3b3;
    text-decoration: none;
    margin: 0 0.5rem;
}

.footer-links a:hover {
    color: #ffffff;
}
