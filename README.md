# Ceramica

Ceramica is a full-stack Node.js-based e-commerce web application built for selling ceramic products. It features product management, user authentication, order processing, and an admin dashboard.

## Features

- User authentication (login/register)
- Product listing and detail pages
- Shopping cart and order placement
- Admin dashboard for managing products and orders
- Image upload and static content serving

## Technologies Used

- **Backend:** Node.js, Express
- **Database:** MongoDB
- **Authentication:** Passport.js
- **Templating/Frontend:** JSX components
- **File structure:** MVC architecture

## Project Structure

```
ceramica-main/
│
├── app.js                       # Main application entry point
├── package.json                # Dependencies and scripts
├── config/                     # DB and Passport configurations
├── components/                # React/JSX components (admin UI)
├── middleware/                # Custom middleware logic
├── models/                    # Mongoose models for DB
├── public/                    # Static files (images, CSS, JS)
├── routes/                    # Express route definitions
├── views/                     # Server-rendered templates
├── .gitignore                 # Git exclusions
└── LICENSE                    # Project license
```

## Getting Started

### Prerequisites

- Node.js (v14+ recommended)
- MongoDB (local or cloud instance)

### Installation

```bash
git clone https://github.com/your-username/ceramica.git
cd ceramica-main
npm install
```

### Environment Setup

Create a `.env` file in the root directory with the following:

```env
MONGODB_URI=mongodb://localhost:27017/ceramica
SESSION_SECRET=your_secret_key
PORT=3000
```

### Running the Application

```bash
npm start
```

Visit `http://localhost:3000` in your browser.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
