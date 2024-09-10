# 🚀 Deployment Master Commands

This document contains the essential commands to deploy your project using **Netlify** and **Vercel**.

## Netlify Deployment 🌐

Before deploying to Netlify, create a production build of your project using:

```
npm run build
```

Then, deploy your project to Netlify in production mode with:

```
netlify deploy --prod
```

## Vercel Deployment 📦

If you are deploying a Node.js project to Vercel, make sure you have a `.vercel` file in your project directory.

To deploy your project to Vercel in production mode, use this command:

```
vercel --prod
```

If you are not logged in to Vercel, you can log in using:

```
vercel login
```
