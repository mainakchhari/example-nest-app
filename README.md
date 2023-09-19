# example-next-app

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app). This can be used as a starter-kit or template for a Next.js project using [`shadcn-ui`](https://ui.shadcn.com/docs/installation/next).

## Getting Started

Run the development server with `yarn dev`. Refer to `shadcn-ui` [documentation](https://ui.shadcn.com/docs)

## Features/Notes

- This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font
- Dark mode is auto-enabled if the user's system is set to dark mode
- This project uses [`shadcn-ui`](https://ui.shadcn.com/docs/installation/next) bootstrapped with `npx shadcn-ui@latest init`. Please refer to [issue](https://github.com/shadcn-ui/ui/issues/755) if using `src` folder as project root
- As an example, a dashboard is displayed as the home page. This dashboard is built using [`examples/dashboard`](https://ui.shadcn.com/examples/dashboard) as reference
- **IMPORTANT**: This project has "output: export" configured in next.config.js. Please change to standalone as per your usecase
