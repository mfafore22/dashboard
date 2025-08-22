# Next.js Dashboard Application

This is a modern dashboard application built with Next.js 15, featuring a complete authentication system, dashboard analytics, and invoice management capabilities.

## Features

- 🔐 Authentication with NextAuth.js
- 📊 Dashboard overview with revenue analytics
- 💼 Customer management
- 📋 Invoice creation and management
- 🎨 Modern UI with Tailwind CSS
- 🔍 Search functionality
- 📱 Fully responsive design

## Tech Stack

- **Framework:** Next.js 15.4
- **Styling:** Tailwind CSS
- **Authentication:** NextAuth.js
- **Database:** PostgreSQL with Postgres.js
- **Form Validation:** Zod
- **Icons:** HeroIcons
- **UI Components:** Custom components with clsx for conditional styling

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/mfafore22/dashboard.git
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

3. Set up environment variables:
   Create a `.env.local` file in the root directory and configure your environment variables.

4. Run the development server:
   ```bash
   pnpm dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `/app` - Main application routes and API endpoints
  - `/dashboard` - Dashboard related pages and components
  - `/login` - Authentication pages
  - `/lib` - Utility functions and data handling
  - `/ui` - Reusable UI components

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

This project is open-source and available under the MIT License.

## Learn More

To learn more about the technologies used in this project:

- [Next.js Documentation](https://nextjs.org/docs)
- [TailwindCSS Documentation](https://tailwindcss.com/docs)
- [NextAuth.js Documentation](https://next-auth.js.org)
