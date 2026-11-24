# EcoTrack - AI-Powered Carbon Footprint & Sustainability Management Platform

EcoTrack is a collaborative sustainability management project developed as part of the Infosys Springboard Internship 7.0 (B3), Group 1.

The platform brings together carbon footprint tracking, emission calculations, sustainability goals, challenges, and environmental analytics through an integrated application structure.

## Project Information

- **Program:** Infosys Springboard Internship 7.0 (B3)

- **Team:** Group 1

- **Duration:** August 14 - October 20, 2026

- **Repository Maintainer and Integration Contributor:** Harshan Karthikeyan

## My Contributions

- Contributed to frontend development and UI improvements.

- Assisted with interface design, color selection, and visual consistency.

- Participated in frontend coding and shared implementation approaches.

- Integrated the available frontend, backend, and sustainability dashboard source code into a unified repository.

- Resolved project configuration and frontend build issues.

- Tested the integrated application components.

This repository is an integration and consolidation of collaborative project work. It does not claim ownership of the original team's development history or work authored by other contributors.

## Project Structure

```text
EcoTrack_Group1/
|-- backend/
|-- frontend/
|-- dashboard/
|-- .gitignore
|-- LICENSE
|-- README.md
```

## Technology Stack

**Main Application**

- React.js

- JavaScript

- HTML5 and CSS3

- Vite

**Backend**

- Node.js

- Express.js

- MongoDB

- Mongoose

- JWT Authentication

- bcrypt.js

**Analytics Dashboard**

- React

- TypeScript

- Recharts

- Tailwind CSS

- Framer Motion

## Main Features

- User registration and authentication

- Carbon activity tracking

- CO2 emission calculations

- Category-wise emission monitoring

- Weekly and monthly emission analytics

- Personal sustainability goals

- Environmental challenges

- User profile management

- Sustainability analytics dashboard

Note: The separate analytics dashboard currently uses its own sample data and is not represented as a live-connected extension of the main backend.

## Original Source Repositories and Attribution

The integrated components originated from collaborative project repositories:

- **Main EcoTrack application - Dharmendra Chaurasiya:**  

  https://github.com/ChaurasiyaDharmendra/EcoTrack

- **Sustainability analytics dashboard - Varsha:**  

  https://github.com/Varsha-5-2006/eco-impact-dashboard

Original development history and authorship belong to their respective contributors. This repository maintains the integrated project structure and documents subsequent integration work.

## Local Setup

### 1. Clone this repository

```bash

git clone https://github.com/harshan2005/EcoTrack_Group1.git

cd EcoTrack_Group1

```

### 2. Backend setup

```bash

cd backend

npm install

```

Create a `.env` file using `.env.example` as a reference.

Configure:

```env

PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secure_jwt_secret

RESEND_API_KEY=your_resend_api_key

FROM_EMAIL=your_verified_sender_email

```

Start the backend:

```bash

npm run dev

```

A valid MongoDB connection is required.

### 3. Main frontend setup

Open another terminal:

```bash

cd frontend

npm install

```

Create `.env.local`:

```env

VITE_API_URL=http://localhost:5000/api

```

Start the frontend:

```bash

npm run dev

```

### 4. Dashboard setup

Open another terminal:

```bash

cd dashboard

npm install

npm run dev

```

Use the local URL provided by Vite.

## Security

- Never commit `.env` or `.env.local` files.

- Never expose database connection strings or API keys.

- Use `.env.example` files as configuration templates.

- Keep credentials in local environment variables or deployment secrets.

## License

This repository retains the existing MIT License. Refer to the `LICENSE` file for the applicable terms.



