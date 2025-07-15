# Book Management App

A simple book management application built with **React** and **React Router**, allowing users to manage a book list, add/edit/delete books, and view detailed information for each book.

---
<img width="692" height="432" alt="image" src="https://github.com/user-attachments/assets/c58f158c-aab5-4b18-9d75-4082412fe1e8" />

## Technologies Used

- [React](https://reactjs.org/)
- [React Router v6](https://reactrouter.com/en/main)
- [Bootstrap](https://getbootstrap.com/)
- Custom styling with `SCSS`

---

## Folder Structure

```bash
book-management-app/
├── public/
├── src/
│   ├── components/
│   │   └── Header.js
│   ├── pages/
│   │   ├── BookList.js
│   │   ├── BookDetail.js
│   │   ├── AddBook.js
│   │   └── EditBook.js
│   ├── router/
│   │   └── AppRouter.js
│   ├── styles.scss
│   └── index.js
├── package.json
└── README.md
```

---

## Installation & Running

```bash
git clone https://github.com/your-username/book-management-app.git
cd book-management-app
npm install
npm start
```

The app will be running at: [http://localhost:3000](http://localhost:3000)

---

## Notes

- Currently, this app **does not use any backend/API**. All data is stored temporarily in component state (or `localStorage` if implemented).
- It can be extended to work with Firebase, MongoDB, or any custom REST API.

---

