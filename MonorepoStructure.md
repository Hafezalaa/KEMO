

kemo/
├── client/ # Frontend (React)
│ ├── public/
│ ├── src/
│ │ ├── assets/
│ │ ├── components/
│ │ │ ├── ui/
│ │ │ ├── layout/
│ │ │ ├── auth/
│ │ │ ├── products/
│ │ │ ├── cart/
│ │ │ ├── checkout/
│ │ │ └── admin/
│ │ ├── pages/
│ │ │ ├── Home.jsx
│ │ │ ├── Shop.jsx
│ │ │ ├── ProductDetails.jsx
│ │ │ ├── Cart.jsx
│ │ │ ├── Checkout.jsx
│ │ │ ├── OrderSuccess.jsx
│ │ │ ├── Login.jsx
│ │ │ ├── Register.jsx
│ │ │ ├── Profile.jsx
│ │ │ ├── Orders.jsx
│ │ │ ├── Contact.jsx
│ │ │ └── NotFound.jsx
│ │ ├── hooks/
│ │ ├── services/
│ │ │ ├── api.js
│ │ │ ├── auth.service.js
│ │ │ ├── product.service.js
│ │ │ ├── order.service.js
│ │ │ └── payment.service.js
│ │ ├── store/
│ │ ├── utils/
│ │ ├── App.jsx
│ │ └── main.jsx
│ ├── .env.example
│ └── package.json
│
├── server/ # Backend (Node.js + Express)
│ ├── src/
│ │ ├── config/
│ │ │ ├── db.js
│ │ │ └── env.js
│ │ ├── models/
│ │ │ ├── User.js
│ │ │ ├── Product.js
│ │ │ ├── Category.js
│ │ │ ├── Order.js
│ │ │ ├── Review.js
│ │ │ └── Coupon.js
│ │ ├── routes/
│ │ │ ├── auth.routes.js
│ │ │ ├── user.routes.js
│ │ │ ├── product.routes.js
│ │ │ ├── category.routes.js
│ │ │ ├── order.routes.js
│ │ │ ├── payment.routes.js
│ │ │ ├── shipping.routes.js
│ │ │ └── contact.routes.js
│ │ ├── controllers/
│ │ │ ├── auth.controller.js
│ │ │ ├── user.controller.js
│ │ │ ├── product.controller.js
│ │ │ ├── order.controller.js
│ │ │ ├── payment.controller.js
│ │ │ ├── shipping.controller.js
│ │ │ └── email.controller.js
│ │ ├── services/
│ │ │ ├── EmailService.js
│ │ │ ├── PaymentService.js
│ │ │ ├── ShippingService.js
│ │ │ ├── CloudinaryService.js
│ │ │ └── TokenService.js
│ │ ├── middleware/
│ │ │ ├── auth.middleware.js
│ │ │ ├── role.middleware.js
│ │ │ ├── error.middleware.js
│ │ │ ├── rateLimit.middleware.js
│ │ │ └── validators/
│ │ ├── utils/
│ │ └── server.js
│ ├── .env.example
│ └── package.json
│
├── .env.example
├── .gitignore
├── README.md
└── package.json # Root scripts