# VELLUNA - Molecular Fragrance E-Commerce Platform

## 1. Executive Summary
[cite_start]VELLUNA is a cutting-edge e-commerce platform for a luxury molecular fragrance brand[cite: 33]. [cite_start]The platform combines immersive 3D visualization with sophisticated e-commerce functionality to create a unique brand experience centered around the "Laboratory of the Liminal" concept[cite: 34].

### Target Metrics
* [cite_start]**First Contentful Paint:** < 1.5s [cite: 43]
* [cite_start]**Time to Interactive:** < 3.5s [cite: 44]
* [cite_start]**Lighthouse Score:** 90 [cite: 45]
* [cite_start]**Accessibility:** WCAG 2.1 AA Compliance [cite: 38]

## 2. Technology Stack
The platform utilizes a modern frontend architecture optimized for performance and 3D rendering:

* [cite_start]**Core Framework:** React 18.2.0 with TypeScript 5.3.3 [cite: 73, 74]
* [cite_start]**Build Tool:** Vite 5.0.12 [cite: 75]
* [cite_start]**3D Engine:** Three.js 0.162.0 & React Three Fiber 8.15.12 [cite: 79, 80]
* [cite_start]**State Management:** Zustand 4.5.0 with Local Storage Persistence [cite: 85, 86]
* [cite_start]**Styling & Animation:** TailwindCSS 3.4.1 & Framer Motion 10.16.16 [cite: 89, 91]

## 3. Core Modules
[cite_start]The application is divided into distinct, lazy-loaded modular sections[cite: 640]:
* [cite_start]**Hero Module:** Landing section featuring scroll animations and dynamic 3D bottle visualization[cite: 225, 226].
* [cite_start]**Collection Module:** Persistent product display grid drawing from established fragrance arrays[cite: 228, 230].
* [cite_start]**Cart Module:** Persistent shopping cart management using Zustand[cite: 232, 234].

## 4. Installation & Setup
[cite_start]To run the VELLUNA platform locally, ensure you have Node.js >= 18.0.0 installed[cite: 171].

\`\`\`bash
# Clone repository
git clone https://github.com/zoozee-cpu/velluna.git

# Install dependencies
npm install

# Copy environment variables
cp .env.example .env

# Start development server
npm run dev
\`\`\`

## 5. Deployment
Deployment is handled automatically via CI/CD pipelines. [cite_start]Any push to the `main` branch triggers an automated build and deployment process[cite: 890, 893].

* [cite_start]**Production Environment:** `velluna.com` [cite: 944]
* [cite_start]**Staging Environment:** `staging.velluna.com` [cite: 944]
