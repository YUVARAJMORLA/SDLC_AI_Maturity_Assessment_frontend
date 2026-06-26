# SDLC AI Maturity Assessment - Frontend Client

This repository contains the frontend Next.js 14 client application for the SDLC Maturity Assessment. It provides the user interface for taking audits, viewing analytics charts, and managing recommendations.

## Prerequisites

- **Node.js** v18+

## Setup and Installation

1. **Clone or Download the Repository**
   Ensure this is placed in its own directory.

2. **Install Dependencies**
   Run the following command in the root of the frontend folder:
   ```bash
   npm install
   ```

3. **Configure Environment Variables**
   Create a `.env.local` file in the root of the frontend directory and point it to your backend API URL:
   ```env
   NEXT_PUBLIC_API_URL=http://localhost:3001
   ```

4. **Start the Development Server**
   ```bash
   npm run dev
   ```
   Open [http://localhost:3000](http://localhost:3000) with your browser to see the application.

5. **Production Build**
   To build the application for production:
   ```bash
   npm run build
   ```
   And to start the production server:
   ```bash
   npm start
   ```

## Project Structure

- `src/app/` - React pages and routing (App Router)
- `src/app/components/` - Shared UI elements (layout, charts, etc.)
- `src/app/context/` - AuthContext to manage sessions and API headers
- `public/` - Static assets
- `next.config.mjs` - Next.js configuration and proxy rewrites
- `.gitignore` - Standard Next.js git ignore settings
