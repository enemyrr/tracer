# Tracer

Tracer is a Cursor IDE proxy designed to capture your API requests, show your current balance, and leverage anthropiccache for minimizing spend. It leverages custom API endpoint settings in Cursor to mimic the EXACT OpenAI endpoints and routes all requests via the proxy.

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can configure your Cursor IDE to use the custom API endpoint setting, ensuring that Tracer mimics OpenAI's API behavior exactly. As you edit the files, the proxy auto-updates with your changes.

## OpenAI Endpoint Simulation

Tracer intercepts requests intended for OpenAI, processes them through its proxy, and returns results seamlessly. This setup helps optimize your spending by leveraging anthropiccache effectively.

For more details, consult the source code and inline documentation.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
