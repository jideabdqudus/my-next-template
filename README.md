# Next.js Bootstrapped Template

A modern, opinionated Next.js template with TypeScript, Tailwind CSS, and essential tooling pre-configured.

## Features

- ⚡️ Next.js 14 with App Router
- 🔒 TypeScript for type safety
- 💨 Tailwind CSS for styling
- 🎨 Tailwind CSS Animations
- 🧩 Radix UI primitives
- 🔍 ESLint for code linting
- ✨ Prettier for code formatting
- 📱 Responsive design ready
- 🎯 Pre-configured components with class-variance-authority

## Getting Started

```bash
# Clone this template
git clone <your-repo-url>

# Install dependencies
npm install

# Start development server (runs on port 3005)
npm run dev
```

Visit [http://localhost:3005](http://localhost:3005) to see your application.

## Project Structure

```
├── src/              # Application source code
├── public/           # Static assets
├── components.json   # Shadcn UI components config
├── config.ts         # Global configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json    # TypeScript configuration
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Suggested Improvements

1. Consider adding:
   - Husky for git hooks
   - Jest/Vitest for testing
   - React Query for data fetching
   - Zod for schema validation
   - State management (e.g., Zustand/Jotai)
   - API route examples
   - Environment variables validation

2. Security enhancements:
   - Add security headers
   - CSP configuration
   - Rate limiting for API routes

3. Developer experience:
   - Add VSCode settings and recommended extensions
   - Include common component patterns
   - Add Storybook for component documentation

## License

MIT

## Author

Jide Abdul-Qudus
