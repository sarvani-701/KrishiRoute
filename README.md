# KrishiRoute

### Smart Agricultural Market Optimization Platform

KrishiRoute is a full-stack web application that helps farmers identify the most profitable mandi for selling their produce. The platform compares crop prices, transportation costs, and travel distance to estimate net profit and recommend the best selling location.

Developed as part of the **AjraSakha Hackathon 2026** under the problem statement **"Krishi-Route: Profit & Logistics Optimizer."**

---

## The Problem

Many farmers sell their crops at the nearest mandi without comparing prices at nearby markets. While another mandi may offer a better selling price, transportation costs make it difficult to determine whether the trip is actually more profitable.

KrishiRoute helps farmers compare multiple markets based on both revenue and logistics costs, enabling informed and profit-driven selling decisions.

---

## Features

* Real-time mandi price retrieval using Agmarknet data
* Nearby market discovery based on user location
* Transportation cost estimation based on distance and vehicle type
* Net profit calculation across multiple mandis
* Route visualization using Mapbox
* Interactive profit comparison dashboards using Recharts
* Structured input system for crop type, quantity, vehicle, and location
* Identification of the most profitable selling destination

---

## Tech Stack

### Frontend

* React.js
* TypeScript
* JavaScript
* Recharts

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### APIs & Services

* Mapbox API
* Agmarknet Data

---

## How It Works

1. Enter crop details, quantity, vehicle type, and location.
2. The platform identifies nearby agricultural markets.
3. Market prices are retrieved and compared.
4. Transportation costs are estimated.
5. Net profit is calculated for each mandi.
6. Results are visualized through interactive charts and maps.
7. The platform recommends the most profitable market.

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/sarvani-701/KrishiRoute.git
```

### Install Dependencies

```bash
cd frontend
npm install

cd ../backend
npm install
```

## Environment Variables

### Backend (.env)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
AGMARKNET_BASE_URL=https://api.agmarknet.gov.in/v1
```

### Frontend (.env)

```env
VITE_MAPBOX_TOKEN=your_mapbox_access_token
```

### Run the Project

```bash
# Frontend
cd frontend
npm run dev

# Backend
cd backend
npm run dev
```

---

## Project Highlights

* Developed a full-stack agricultural decision-support platform using React, Node.js, Express.js, and MongoDB.
* Integrated Agmarknet market data and Mapbox geospatial services for location-aware market analysis.
* Implemented profit estimation algorithms combining crop prices, transportation costs, and distance calculations.
* Built interactive visualizations using Recharts to support data-driven selling decisions.

---

## Future Enhancements

* Historical mandi price trend analysis
* Ride-sharing recommendations for farmers
* Price volatility alerts
* Fuel-cost-aware transportation estimation

---

Developed as part of the AjraSakha Hackathon 2026.
