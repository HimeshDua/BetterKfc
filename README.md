# BetterKFC

![BetterKfc Logo](images/horse-logo.png)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/HimeshDua/BetterKfc)](https://github.com/HimeshDua/BetterKfc/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/HimeshDua/BetterKfc)](https://github.com/HimeshDua/BetterKfc/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/HimeshDua/BetterKfc)](https://github.com/HimeshDua/BetterKfc/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/HimeshDua/BetterKfc)](https://github.com/HimeshDua/BetterKfc/pulls)

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Installation](#installation)
5. [Development](#development)
6. [Deployment](#deployment)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

BetterKFC is a modern, fast, and cleaner remake of the official KFC Pakistan website. The goal is simple: deliver a **significantly more polished, responsive, and performance‑focused user experience** than the original site. No clutter. No slow-loading components. Just a sleek UI, clean animations, and optimized ordering flows.

Live Demo: **[https://betterkfc.vercel.app](https://betterkfc.vercel.app)**

This project is intended for learning, UI/UX improvement practice, and showcasing modern frontend engineering patterns.

## Features

* **Modern UI redesign** inspired by the original KFC PK site but optimized for usability
* **Fully responsive** across all breakpoints
* **Faster navigation** using Next.js routing + prefetching
* **Menu browsing experience** with cleaner product cards
* **Reusable components** with a scalable folder structure
* **Improved accessibility** with semantic HTML and screen‑reader labels
* **Performance‑focused images** using Next.js Image component
* **Dark mode ready** (architecture supports theme expansion)

## Tech Stack

* **Next.js 14 (App Router)**
* **TypeScript**
* **TailwindCSS** for styling
* **ShadCN UI** for components
* **Framer Motion** for animations
* **Vercel** for deployment

## Installation

Clone the repo:

```bash
git clone https://github.com/HimeshDua/BetterKfc.git
cd BetterKfc
```

Install dependencies:

```bash
npm install
```

Run locally:

```bash
npm run dev
```

The app will be available at:

```
http://localhost:3000
```

## Development

### Directory Structure

```
app/
  ├─ components/
  ├─ menu/
  ├─ layout.tsx
  └─ page.tsx
public/
src/
```

### Environment Variables

No sensitive env vars are required for basic development.

### Scripts

```bash
npm run dev     # start dev server
npm run build   # production build
npm run start   # start production server
```

## Deployment

The project is fully optimized for **Vercel**, but any Node-based hosting can run it.

Deploy to Vercel:

```bash
vercel
```

Or use GitHub → Vercel auto-deployment.

## Contributing

PRs are welcome! You can contribute by:

* improving UI/UX
* optimizing performance
* adding animations
* cleaning up existing components
* reporting issues

## License

BetterKFC is licensed under the **Apache License 2.0**. See the [LICENSE](LICENSE) file for details.

---

If you like the project, consider starring the repository — it helps the project grow!
