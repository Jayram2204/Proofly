# Proofly — Verifiable Credentials Demo

Proofly is a **client-side React demo** that allows colleges to mint verifiable certificates, and students to securely view them. Certificates can be verified instantly via a hash or QR code. This demo is fully **client-side** but structured to be **blockchain-ready** for future integration with Aptos or other smart contract platforms.

## Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Future Improvements](#future-improvements)
- [License](#license)

## Features

### College View
- Mint certificates with student info, course, title, details, and issue date.
- Generate SHA256 hash for verification.
- Search and filter certificates by student name, ID, course, title, or hash.
- Print or export certificates as PDF with QR codes.

### Student View
- Securely access certificates using Student ID.
- View all issued certificates.
- Copy shareable links or open verification page directly.
### Verification
- Certificates can be verified via a URL query parameter (`?verify=<hash>`).
- QR code generated for each certificate for easy verification.

### UI & Animations
- TailwindCSS for a polished UI.
- Framer Motion for smooth animations.

## Demo

Landing page with role selection:

- **College:** Mint certificates.
- **Student:** View your certificates.

Certificates include:

- Hash and QR code.
- Print/PDF option.
- Copyable share link.
- Verified badge.

## Technologies

- **React** (CRA or Vite)
- **Lucide-React** (icons)
- **QRCode.react** (QR code generation)
- **Framer Motion** (animations)
- **TailwindCSS** (optional styling)
- **LocalStorage** (client-side data persistence)

---

## Installation

1. Clone the repository:
git clone https://github.com/your-username/proofly.git
cd proofly
npm install
npm start
Open http://localhost:3000 to see the demo.
