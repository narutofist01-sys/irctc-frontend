# IRCTC Pathfinder Frontend

A modern, high-performance React 19 + TypeScript web application built with Vite and Tailwind CSS for Indian Railways train availability, booking optimization, and split-station route discovery.

## Features

- **Fast & Responsive UI**: Built with React 19, TypeScript, and Vite.
- **Smart Result Hierarchy**: Displays confirmed tickets first, followed by trains sorted strictly from lowest to highest waiting list (`WL 1`, `WL 3` ... `WL 100+`).
- **On-Demand Split Stations Search**: Dedicated button and in-results banner to discover break-journey connections via major interchange hubs (Bareilly, Moradabad, Kanpur, Banaras, Prayagraj, etc.) when direct trains are full.
- **Interactive Modals**: Train schedule viewer with platform halts, coach layout visualizer, fare breakdown, and ticket watchdogs.
- **Interactive Train Canvas**: Ambient Three.js particle canvas and realistic 3D moving train visualizer.

## Setup & Running

### 1. Requirements
- Node.js 18+
- npm

### 2. Installation
```bash
npm install
```

### 3. Environment Variables
Copy `.env.example` to `.env`:
```bash
cp .env.example .env
```
Set your backend URL:
```env
VITE_API_URL=http://localhost:8000
```

### 4. Development Server
```bash
npm run dev
```

### 5. Production Build
```bash
npm run build
```
