# StyleHub E-commerce Platform

A modern e-commerce platform for men's and women's clothing built with Next.js, TypeScript, Tailwind CSS, and MongoDB.

## Features

- **User Authentication**: Secure login and registration with NextAuth.js
- **Product Catalog**: Browse products by category, filter, and search
- **Shopping Cart**: Add products to cart, update quantities, and checkout
- **User Dashboard**: View order history and manage account details
- **Admin Dashboard**: Manage products, orders, and users
- **Responsive Design**: Fully responsive UI for all devices
- **Animations**: Smooth animations with Framer Motion
- **Favorites/Wishlist**: Add products to favorites or wishlist

## Tech Stack

- **Frontend**: Next.js, TypeScript, Tailwind CSS, React Icons
- **State Management**: React Context API
- **Animations**: Framer Motion
- **Backend**: Next.js API Routes
- **Database**: MongoDB with Mongoose
- **Authentication**: NextAuth.js
- **Form Handling**: React Hook Form
- **API Requests**: Axios
- **Notifications**: React Hot Toast

## Getting Started

### Prerequisites

- Node.js 14.x or later
- npm or yarn
- MongoDB (local or Atlas)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/stylehub-ecommerce.git
   cd stylehub-ecommerce
   ```

2. Install dependencies

4. Start the development server:


5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

### MongoDB Setup

#### Local MongoDB

1. Install MongoDB:
   - Windows: Download and install from [MongoDB website](https://www.mongodb.com/try/download/community)
   - macOS: `brew install mongodb-community`
   - Linux: Follow [MongoDB installation guide](https://docs.mongodb.com/manual/administration/install-on-linux/)

2. Start MongoDB service:
   - Windows: `net start MongoDB` (Run as Administrator)
   - macOS: `brew services start mongodb-community`
   - Linux: `sudo systemctl start mongod`

3. Verify MongoDB is running:
   ```bash
   node scripts/check-mongodb.js
   ```
## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [MongoDB](https://www.mongodb.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [React Icons](https://react-icons.github.io/react-icons/)

## Troubleshooting

### MongoDB Connection Issues


