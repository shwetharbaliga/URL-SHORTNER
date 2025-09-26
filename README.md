# URL Shortener 🚀  

A simple but scalable **URL shortening service** inspired by [Karan Pratap Singh’s System Design Series](https://www.karanpratapsingh.com/courses/system-design/url-shortener).  
I followed the core ideas from his article and implemented the project on my own, extending it with additional features as I learn.  

---

## 📌 Features (Current & Planned)  
- Generate short URLs for long links (Base62 encoding).  
- Redirect short URLs to original destinations.  
- Basic API endpoints (shorten, redirect, delete).  
- Error handling for invalid/expired links.  

**Planned Enhancements:**  
- Database indexing & caching layer (Redis).  
- Rate limiting & abuse prevention.  
- URL analytics (number of hits, most popular).  
- Partitioning & replication strategies for scale.  
- Containerization with Docker.  

---

## 🛠️ Tech Stack
- **Backend:** Go
- **Database:** MongoDB
- **Cache (Planned):** Redis
- **Testing:** Postman, Go’s testing package

---

## 📂 Project Structure  
```plaintext
url-shortener/
 ┣ src/
 ┃ ┣ routes/
 ┃ ┣ controllers/
 ┃ ┣ models/
 ┃ ┗ utils/
 ┣ tests/
 ┣ README.md
 ┗ go.mod 
