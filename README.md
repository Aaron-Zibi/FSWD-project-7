# JCT FSWD – Project 7: SneakRush 👟

End-to-end fullstack e-commerce platform for sneakers, built as the final project of the Full Stack Web Development course @ JCT.

## 🚀 Features

- **Authentication** — JWT-based login/register with role management (admin / user)
- **Product catalog** — browse sneakers by size, filter, search
- **Shopping cart & orders** — full checkout flow
- **Stripe integration** — embedded payment (test mode)
- **Admin dashboard** — manage orders, products, promotions
- **Reviews system** — users can leave product reviews
- **Promotions** — promo codes and discount management

## 🛠️ Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | React 19, Vite, React Router, Axios |
| Payment | Stripe (react-stripe-js) |
| Backend | Node.js, Express |
| Database | MySQL 2 |
| Auth | JWT, bcryptjs, cookies |

## 📁 Project Structure

```
├── client/          # React + Vite frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── App.jsx
│   └── package.json
└── server/          # Express API
    ├── routes/
    ├── database/
    ├── app.js
    └── server.js
```

## ⚙️ Setup

### Backend
```bash
cd server
npm install
# Create a .env file (see .env.example)
npm run dev
```

### Frontend
```bash
cd client
npm install
npm run dev
```

## 🎓 Context

Final Project — Full Stack Web Development course @ [JCT (Jerusalem College of Technology)](https://www.jct.ac.il)

**Author:** [Aaron Zibi](https://github.com/Aaron-Zibi)
