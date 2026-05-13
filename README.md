# Food Ordering

A food ordering app built with React and React Router. Users browse a restaurant menu, add dishes to cart, and go through a checkout flow — with client-side routing for a smooth single-page experience.

## Features

- Multi-page navigation with React Router v6
- Menu browsing with item details and pricing
- Add to cart and quantity controls
- Cart summary and checkout page
- Persistent cart state across route changes

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React 18 |
| Routing | React Router v6 |
| State | React Context API |
| Styling | CSS Modules |
| Bundler | Create React App |

## Getting Started

```bash
git clone https://github.com/ronikdedhia/Food-Ordering.git
cd Food-Ordering
npm install
npm start
```

App runs at `http://localhost:3000`

## Project Structure

```
src/
├── pages/            # Home, Menu, Cart, Checkout
├── components/       # MealItem, CartIcon, Header
├── store/            # CartContext and cart-actions
└── App.js
```

## License

MIT
