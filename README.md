# ![Kadragraph Media Logo](public/logo.png).

# Kadragraph Media - Official Website

Welcome to the official repository for the Kadragraph Media website. This project is a modern, high-performance web application built to showcase our portfolio, services, and creative vision.

## About Kadragraph Media

Kadragraph Media is a creative agency focused on delivering premium visual storytelling and digital experiences. We specialize in:

- **Videography & Photography**: Capturing moments with cinematic excellence.
- **Creative Strategy**: Building brands with purpose and vision.
- **Motion Design**: Bringing ideas to life through dynamic animation.
- **Web Development**: Crafting immersive and responsive digital platforms.

Our mission is to combine artistic integrity with technical precision to elevate brands and narratives.

## Technology Stack

This project is built on a robust, scalable stack designed for performance and flexibility:

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **CMS**: [Payload CMS 3.0](https://payloadcms.com/) (Beta / Latest)
- **Database**: PostgreSQL
- **Styling**: Tailwind CSS + Custom CSS Variables
- **Language**: TypeScript
- **Deployment**: Vercel (Production), GitHub (Source Control)

## Getting Started

### Prerequisites

- Node.js (v18 or later)
- pnpm (Authoritative package manager)
- PostgreSQL database instance

### Installation & Development

1.  **Clone the repository:**
    ```bash
    git clone git@github.com:samuelrolandvroom/kadragraph-web.git
    cd kadragraph-web
    ```

2.  **Install dependencies:**
    ```bash
    pnpm install
    ```

3.  **Environment Setup:**
    - Copy `.env.example` to `.env`.
    - Configure your `DATABASE_URI` (PostgreSQL) and `PAYLOAD_SECRET`.

4.  **Run the development server:**
    ```bash
    pnpm dev
    ```
    - The website will be available at `http://localhost:3000`.
    - The Admin Panel is at `http://localhost:3000/admin`.

## Project Structure

- `src/app`: Next.js App Router pages and layouts.
- `src/collections`: Payload CMS collection definitions.
- `src/components`: Reusable UI components and blocks.
- `src/blocks`: Layout blocks for the page builder.
- `public`: Static assets.

## Contributing

This repository is private property of Kadragraph Media. Access is restricted to authorized team members.

1.  **Branching Strategy:**
    - `main`: Production-ready code. Deploys to Vercel.
    - `dev`: Active development branch.

2.  **Workflow:**
    - Create feature branches from `dev`.
    - Submit Pull Requests to `dev` for review.
    - `dev` is merged to `main` for releases.

---

&copy; 2026 Kadragraph Media. All rights reserved.
