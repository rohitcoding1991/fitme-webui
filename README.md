# FitMe - Food Delivery Landing Page

A modern, responsive landing page for a food delivery application built with Next.js and React.

**Live Demo:** [https://fitme-webui.vercel.app/](https://fitme-webui.vercel.app/)

## Tech Stack

- **Framework:** [Next.js 16](https://nextjs.org/) with App Router
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **UI Library:** [React 19](https://react.dev/)
- **Styling:** [Tailwind CSS 4](https://tailwindcss.com/)
- **UI Components:** [Radix UI](https://www.radix-ui.com/) primitives with [shadcn/ui](https://ui.shadcn.com/)
- **Icons:** [Lucide React](https://lucide.dev/) & [React Icons](https://react-icons.github.io/react-icons/)
- **Carousel:** [Embla Carousel](https://www.embla-carousel.com/)
- **Forms:** [React Hook Form](https://react-hook-form.com/) with [Zod](https://zod.dev/) validation
- **Charts:** [Recharts](https://recharts.org/)
- **Theming:** [next-themes](https://github.com/pacocoursey/next-themes)
- **Deployment:** [Vercel](https://vercel.com/)

## Features

- Hero section with promotional content
- Food categories browsing
- Nearby restaurants discovery
- Recommended food items
- Restaurant search functionality
- Personalized recommendations
- Fully responsive design
- Modern UI with smooth animations

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- npm, yarn, pnpm, or bun

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/rohitcoding1991/fitme-webui.git
   cd fitme-webui
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   # or
   bun install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   # or
   bun dev
   ```

4. **Open your browser**

   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

## Available Scripts

| Command         | Description                              |
| --------------- | ---------------------------------------- |
| `npm run dev`   | Start development server                 |
| `npm run build` | Build the application for production     |
| `npm run start` | Start the production server              |
| `npm run lint`  | Run ESLint for code linting              |

## Project Structure

```
fitme-webui/
├── app/                    # Next.js App Router
│   ├── (home)/             # Home page route group
│   ├── layout.tsx          # Root layout
│   ├── page.tsx            # Home page
│   └── globals.css         # Global styles
├── common/                 # Shared components
│   ├── header/             # Navigation header
│   └── footer/             # Page footer
├── components/             # Feature components
│   ├── hero-section/       # Hero banner
│   ├── categories-section/ # Food categories
│   ├── nearby-restaurant-section/
│   ├── recommended-food-section/
│   ├── search-restaurant-section/
│   ├── personalized-section/
│   └── ui/                 # Reusable UI components
├── data/                   # Static data files
├── lib/                    # Utility functions
└── public/                 # Static assets
```

## Deployment

This project is deployed on [Vercel](https://vercel.com/). Any push to the `main` branch will trigger an automatic deployment.

To deploy your own instance:

1. Fork this repository
2. Import the project in [Vercel](https://vercel.com/new)
3. Deploy with default settings

## License

This project is open source and available under the [MIT License](LICENSE).
