# NextFire Blog App
Link: nextfire-blog-app.vercel.app
\
A React-Next.js-Firebase Social blogging platform

## 😄 Summary 
A Medium like social blogging platform that allows authors to post realtime content that is search engine optimized and bot-friendly. The application features server side rendering standards like SSR and ISR through Next.js, Firestore data modeling, user authentication, custom usernames, hearts and image file uploads. Deployment is done using Vercel and fully protected with security rules specified in Firebase.

## 💻 Tech 
The React in the front end directly connects with Firebase backend services, removing the need for a middle API. User auth is handled by Firebase using OAuth 2.0 and Google sign in. Next.js handles data retrieval, allowing for server side rendering so cliend facing content can be bot and search engine friendly. Vercel allows for easy deployment and CI/CD.

## 📷 Pictures
![](images/image1.png)
![](images/image2.png)


## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
