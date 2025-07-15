# CardDates

A full stack web app to remind users when their cards (credit/debit, IDs, etc.) are about to expire. Users can add cards, see upcoming expirations, and receive notifications.

## Structure

- `client/`: React frontend
- `server/`: Node.js/Express backend

## Getting Started

1. Install dependencies in both `client` and `server` folders.
2. Configure environment variables (see `.env.example` in `server/`).
3. Run both servers (see below).

## Development

### Backend

```bash
cd server
npm install
npm run dev
```

### Frontend

```bash
cd client
npm install
npm start
```

## Usage

- Visit http://localhost:3000
- Register a new user and log in
- Add cards and see expiration status

## Roadmap

- [x] Basic CRUD for cards
- [x] User authentication
- [ ] Email notifications
- [ ] Mobile integration (React Native)# carddates
