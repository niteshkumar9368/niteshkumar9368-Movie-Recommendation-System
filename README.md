# Movie Recommendation System Based on Your Mood  

A Python-based command-line application that recommends movies based on user-selected genres. The script scrapes IMDb to provide top movie titles for **Drama, Action, Comedy, Horror, and Crime** categories.  

---

## Features  
- Real-time recommendations by fetching top movies from IMDb based on genre.  
- Web scraping using BeautifulSoup for efficient data extraction.  
- Error handling to manage invalid inputs and request failures.  
- Lightweight, fast, and interactive command-line interface.  

---

## Technologies Used  
- **Python** – Core programming language  
- **Requests** – Fetching web content  
- **BeautifulSoup (bs4)** – Web scraping  
- **Regex (re)** – Extracting structured data  

---

## Installation  

### Prerequisites  
Ensure you have **Python 3.x** installed.  

### Steps  

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/your-username/movie-recommendation-mood.git
   cd movie-recommendation-mood
   ```

2. **Install Dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

---

## Usage  

Run the script:  
```bash
python movie_recommendation.py
```

Enter a genre when prompted:  
```
Enter a genre (Drama, Action, Comedy, Horror, Crime): Action
```

### Example Output:  
```
Top Movies:
1. The Dark Knight
2. Mad Max: Fury Road
3. Gladiator
...
```

---

## Available Genres  
| Genre   |  
|---------|  
| Drama   |  
| Action  |  
| Comedy  |  
| Horror  |  
| Crime   |  

---

## Contributing  

Contributions are welcome! To contribute:  

1. **Fork** the repository  
2. **Create a new branch** (`git checkout -b feature-name`)  
3. **Commit your changes** (`git commit -m "Added new feature"`)  
4. **Push to the branch** (`git push origin feature-name`)  
5. **Open a Pull Request**  

---

## License  

This project is licensed under the **MIT License**.  

---

Feel free to star this repository if you find it useful!  

