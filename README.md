## Getting Started with Next.js and TypeScript on Vercel

Welcome to a straightforward guide designed to take you through creating a Next.js project with TypeScript and deploying it effortlessly on Vercel. Follow these simple steps to get your website up and running.

Step 1: Create Your Next.js Project

Begin by creating a new Next.js project. Open your terminal and run the following command:

```
npx create-next-app@latest
```

This command scaffolds a new Next.js application with all the necessary setup.

Step 2: Sign Up or Log In to Vercel

Visit the Vercel website and either log in to your existing account or sign up for a new one. Vercel offers a seamless experience for deploying websites with zero configuration for Next.js projects.

Step 3: Install Vercel CLI

To interact with Vercel directly from your local environment, you'll need the Vercel CLI. Install it using Homebrew with the following command:

```
brew install vercel
```

This tool allows you to deploy projects, manage your deployments, and more, directly from your terminal.

Step 4: Generate a Vercel Token

Create a token in Vercel for authentication. This token will be used to authorize your deployments and other CLI operations.

Step 5: Configure the Output Folder

By default, Vercel deploys from the "public" directory. If your project uses a different output folder, like "out", update this setting in your Vercel project configuration.

Step 6: Deploy Your Website

Deploy your site by running the vercel command in your project directory. Follow the prompts to set up your Vercel account and specify the project location.

Step 7: Use Vercel CLI for Deployment

For a more streamlined deployment process, especially for continuous integration, utilize the Vercel CLI with the following commands:

1. Pull your project settings with:

   ```
   vercel pull --yes --environment=production --token=YOUR_TOKEN
   ```

2. Build your project for production with:

   ```
   vercel build --prod --token=YOUR_TOKEN
   ```

3. Deploy your prebuilt project with:

   ```
   vercel deploy --prebuilt --prod --token=YOUR_TOKEN
   ```

Replace YOUR_TOKEN with your actual Vercel token.

And there you have it! By following these steps, you'll have your Next.js project running live on Vercel in no time. Enjoy building and deploying your web applications with ease.
