![Sitecore logo in red background](public\sitecore.svg)

# Sitecore Developer Portal
Welcome to the Sitecore Developer Portal. This app was created to help you get started with Sitecore. The developer portal aims to bring all the Sitecore developer tools together in one place.

## The Tech
The Sitecore developer portal is built with Next.js, Typescript, Tailwind CSS, and is hosted on Vercel. The app uses static site generation to create all the pages at build time. It also utilizes Incremental Static Regeneration (ISR) to automatically update the app when you make changes to page content are made. Much of the page content is written in Markdown and is converted to HTML at build time.

## Build Prerequisites
#### Environment Variables
The Sitecore developer portal incorperates a number of third party services to bring in content. For full functionality, you must create a **.env.local** file in the root of the project and add in the below environment variables. 

The following variables should exist within the .env.local file: 
- YOUTUBE_API_KEY: An API key with YouTube Data API v3 access enabled
- TWITTER_BEARER_TOKEN: A bearer token from Twitter 

*Note: The site will still function without the above keys. The components that require these environment variables will fail gracefully and not diplay on the page*

## Getting Started

1. Clone the GitHub repository.
2. Run *npm install* from inside the repository to install all dependencies.
3. Ensure pre-requisites above are complete.
4. Run the developement server with *npm run dev*.
5.  Open [http://localhost:3000](http://localhost:3000) with your browser to see the result

## Bugs and Enhancements 
We are actively working on improving the developer portal. If you have any suggestions or issues, please let us know. Opening an issue on GitHub is a great way to get started.