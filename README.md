# Day 3 - REST API with Express.js

This is my Day 3 backend project from *Sheryians Coding School, where I learned how to build REST APIs using **Express.js* and handled *POST requests* using req.body.

---

## 📚 Topics Covered

- What are REST APIs?
- HTTP methods: GET, POST, PATCH, DELETE
- Ways to send data in requests:
  - req.body
  - req.query
  - req.params
- Used Postman to test POST routes
- Stored data in memory (array of notes)

---

## 🚀 How to Run

```bash
npm install
node server.js
npx nodemon server.js


---

📫 POST Route Created

Route	Method	Description

/notes	POST	Add a new note (title, description)


Send JSON like this in Postman:

{
  "title": "test_title",
  "description": "test-description"
}

📤 Response:

{
  "message": "note added successfully",
  "notes": [...]
}


---

📌 Output Tools Used

VS Code

Postman for API testing



---

🧠 What I Learned

REST API structure

Use of req.body with express.json()

API response format using res.json()

How to send and receive JSON data from client to server



---

🔗 GitHub: https://github.com/Jitendrasinghgurjar/backend-day3
