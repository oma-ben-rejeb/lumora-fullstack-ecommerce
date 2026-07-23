# LUMORA — Full-Stack Premium E-commerce

A complete legal e-commerce demonstration for premium workspace, lighting, furniture, audio and lifestyle products.

## Included

- Premium responsive customer storefront
- Realistic remote product photography
- Three.js 3D hero and GSAP animations
- Product search, filters, sorting, wishlist and product details
- Persistent cart with quantity controls
- Full checkout flow and order creation
- Customer registration, JWT login and order history
- Admin dashboard with revenue chart
- Product create/edit/delete
- Order status management
- Inventory reduction after checkout
- Node.js, Express, REST API, JWT and bcrypt
- JSON persistence database for an easy demonstration
- Dark/light mode and mobile interface

## Start

```bash
npm install
npm start
```

Open `http://localhost:3000`.

## Demo accounts

Admin: `admin@lumora.demo` / `admin123`

Customer: `customer@lumora.demo` / `demo123`

The first successful login hashes the plain demonstration password with bcrypt.

## Payment safety

Checkout is a demonstration. It creates an order but does not charge a real card and never sends or stores card details. Connect an authorized hosted payment provider such as Stripe Checkout or PayPal for production.

## Production upgrade

For a live store, replace the JSON database with PostgreSQL or MongoDB, add HTTPS, rate limiting, secure cookies, transactional email, cloud image storage, backups, monitoring and a production payment provider.

## Images

The storefront uses remote Unsplash URLs. Internet access is required to display them. Replace them with your own licensed product photography before commercial publication.
