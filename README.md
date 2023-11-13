## Backend details 
This is the Backend for the AI-Buddy chrome extension. Made using Vercel AI SDK, Hugging face AI model and Next JS Api routing feature in NextJS 14. All the Backend routes are in the api folder. 

### Chat route:
This routes contains the main post request to the hugging face ai model and generates the streaming response for the api consumer to be used.

Environment Variables:-

```bash
HUGGINGFACE_API_KEY=
```


## Development Server

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

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!
