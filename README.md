Gocart-E-CommerceApp

  <h1>🛒 GoCart</h1>

  <p>
    A multi-vendor e-commerce platform built with Next.js and Tailwind CSS — enabling multiple sellers to run their own stores on a single, unified marketplace.
  </p>

  🔗 **Live Demo:** [gocart-ecommerce.vercel.app](https://gocart-ecommerce-1fotxu35i-ihtiramkhan9798s-projects.vercel.app)

</div>


 📖 Table of Contents

- [✨ Features](#-features)
- [🛠️ Tech Stack](#️-tech-stack)
- [🚀 Getting Started](#-getting-started)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)


✨ Features

- **Multi-Vendor Marketplace** — Multiple sellers can register, create their own stores, and manage their own products independently.
- **Customer Storefront** — A clean, responsive interface for customers to browse products, view individual stores, and make purchases.
- **Shopping Cart & Orders** — Full cart functionality with order placement and order history tracking.
- **Vendor Dashboard** — Sellers can add, edit, and manage their products, and view their own store's orders.
- **Admin Panel** — Platform administrators can approve new vendor stores, manage coupons, and oversee the marketplace.
- **Coupons & Discounts** — Admins can create and manage discount coupons for customers.
- **Dynamic Store Pages** — Each vendor gets their own shareable storefront (`/shop/[username]`).


 🛠️ Tech Stack

- **Framework:** [Next.js](https://nextjs.org/) 15
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **UI Icons:** Lucide React
- **State Management:** Redux Toolkit
- **Deployment:** [Vercel](https://vercel.com/)


 🚀 Getting Started

Clone the repository and install dependencies:

```bash
git clone https://github.com/ihtiramkhan9798/Gocart-E-CommerceApp.git
cd Gocart-E-CommerceApp
npm install
```

Set up your environment variables by creating a `.env.local` file in the root directory (see your project's required keys — e.g. database URL, auth keys, etc.).

Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the app running locally.


 📁 Project Structure

```
gocart-main/
├── app/
│   ├── (public)/        # Customer-facing pages
│   ├── admin/            # Admin dashboard
│   ├── store/             # Vendor dashboard
│   ├── shop/[username]/  # Individual vendor storefronts
│   ├── product/[productId]/
│   ├── cart/
│   └── orders/
├── components/
├── public/
└── package.json


 🤝 Contributing

Contributions are welcome! If you'd like to improve GoCart:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to your branch (`git push origin feature/your-feature`)
5. Open a Pull Request



 📜 License

This project is licensed under the MIT License.




  Built with ❤️ using Next.js
Made by Ihtiram Khan
