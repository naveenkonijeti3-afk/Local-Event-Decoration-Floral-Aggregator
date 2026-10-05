# EventBloom — Local Event Decoration & Floral Aggregator

A complete beginner-friendly full-stack project.

## Features
- Responsive homepage
- Vendor/service cards
- Search by keyword
- Filter by category and location
- Vendor ratings and starting prices
- Booking request form
- Express REST API
- SQLite database
- Booking data stored permanently in `data/events.db`
- Simple admin/demo API: `GET /api/bookings`

## Project structure
```text
event-decoration-floral-aggregator/
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── data/
├── package.json
├── server.js
└── README.md
```

## Run on a computer
Install Node.js first.

```bash
npm install
npm start
```

Open:
`http://localhost:3000`

## API endpoints
- `GET /api/vendors`
- `GET /api/vendors?category=Floral%20Decoration`
- `GET /api/vendors?location=Tirupati`
- `POST /api/bookings`
- `GET /api/bookings`

## Render deployment
1. Upload this project to GitHub.
2. Create a Render Web Service.
3. Build Command: `npm install`
4. Start Command: `npm start`
5. Environment: Node
6. Deploy.

### Important for production
SQLite is excellent for learning/local development, but for a real marketplace on Render use PostgreSQL (or another persistent managed database), because a normal deployed service should not rely on local files for permanent database storage.

## Next upgrades
- Vendor login/signup
- Customer login/signup
- Admin dashboard
- Vendor dashboard
- Image uploads
- Online payments
- WhatsApp booking notifications
- Reviews and ratings
- Google Maps
- PostgreSQL
- JWT authentication
- Separate vendor profiles
