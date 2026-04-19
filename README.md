# 🚀 YouTube Song Finder

![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Domain](https://img.shields.io/badge/Domain-Web%20Development%20%7C%20API-green)

---

## 📌 Overview

This project is a web-based application that allows users to search for **multiple songs simultaneously on YouTube**.

Unlike traditional searching, it:
- Fetches results for up to **50 songs at once**  
- Displays thumbnails, titles, and direct video links  
- Generates a **YouTube playlist automatically**  

---

## ❓ Problem Statement and Inspiration

Suppose you have a list of your favourite songs and want to create a YouTube playlist.  
You would need to search each song individually and add it manually.

This:
- Consumes time  
- Requires repetitive effort  
- Becomes frustrating  

---

## 💡 Solution

This web application solves the problem by:

- Allowing users to search **up to 50 songs at once**  
- Automatically fetching top YouTube results  
- Generating a **playlist instantly**  
- Providing direct video access  

---

## 📈 Impact

- Saves significant time and effort  
- Improves music discovery experience  
- Simplifies playlist creation  
- Provides smooth and efficient workflow  

---

## 🌐 Live Demo

👉 https://lalitkhror.github.io/YouTube-Song-Finder/

---

## 🎯 Objective

Automate multi-song search and playlist creation:

**Song Input → API Call → Fetch Videos → Display Results → Generate Playlist**

---

## 🧠 Algorithm & Processing Flow

### Pipeline:
Input Songs → Validation → API Calls → Fetch Data → Process Results → Display → Playlist Generation  

---

## 🖥️ User Interface & Working

### 🔹 Web Interface

<!-- First image full width -->
<img src="Webpage Interface/Webpage1.png" style="width:100%;"/>

<br><br>

<!-- 2x2 grid -->
<table>
<tr>
<td align="center">
<img src="Webpage Interface/Webpage2.png" style="width:100%; height:220px; object-fit:contain;"/>
</td>
<td align="center">
<img src="Webpage Interface/Webpage3.png" style="width:100%; height:220px; object-fit:contain;"/>
</td>
</tr>

<tr>
<td align="center">
<img src="Webpage Interface/Webpage4.png" style="width:100%; height:220px; object-fit:contain;"/>
</td>
<td align="center">
<img src="Webpage Interface/Webpage5.png" style="width:100%; height:220px; object-fit:contain;"/>
</td>
</tr>
</table>

- Clean and responsive UI  
- Easy navigation with About & Contact sections  

---

### 🔹 Sample Input

<img src="Results/Sample Input.png" style="width:100%;"/>

- Users enter song names separated by commas  
- Supports up to 50 songs  

---

### 🔹 Output Results

<img src="Results/Output Results.png" style="width:100%;"/>

- Displays:
  - Thumbnail  
  - Title  
  - Watch button  

---

### 🔹 Copy Playlist Link

<img src="Results/Output Playlist Link Copy.png" style="width:100%;"/>

- Copies playlist URL to clipboard  

---

### 🔹 Generated Playlist

<img src="Results/Output Playlist.png" style="width:100%;"/>

- Opens all songs in a YouTube playlist  
- Supports shuffle and loop  

---

## 📂 Project Structure

```
YouTube-Song-Finder
│
├── Results
│ ├── Output Playlist Link Copy.png
│ ├── Output Playlist.png
│ ├── Output Results.png
│ └── Sample Input.png
│
├── Webpage Interface
│ ├── Webpage1.png
│ ├── Webpage2.png
│ ├── Webpage3.png
│ ├── Webpage4.png
│ └── Webpage5.png
│
├── index.html
├── style.css
├── script.js
├── logo.png
├── about.png
├── contact.png
├── favicon.png
└── README.md

```
---

## 📦 Tech Stack

- HTML  
- CSS  
- JavaScript (Vanilla JS + DOM Manipulation)  
- Bootstrap  
- YouTube Data API v3  

---

## 🔍 Use Cases

- Bulk song search  
- Playlist creation  
- Music discovery  
- Quick YouTube navigation  

---

## ⚠️ Limitations

- Dependent on YouTube API quota  
- No caching of results  

---

## 🔮 Future Work

- Backend integration (Node.js)  
- Secure API handling  
- AI-based recommendations  
- UI improvements  

---

## 🏁 Conclusion

This project eliminates the inefficiency of manual YouTube searching by enabling batch song searches and automatic playlist creation, significantly improving user experience.

---

## 👨‍💻 Author

Academic Project  
Focus: Web Development + API Integration + DOM Manipulation
