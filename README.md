## Next.js 14 AI Prompt Sharing Application

## Overview

This repository contains a full-stack web application built with Next.js 14, utilizing serverless architecture for backend operations and MongoDB for data storage. The primary focus of this application is to provide CRUD (Create, Read, Update, Delete) functionalities for managing prompts designed for AI applications.

## Features
  - Modern Design with Glassmorphism Trend Style: A modern and visually appealing design, incorporating the glass morphism trend style for a sleek and contemporary appearance.
  - Discover and Share AI Prompts: Allow users to discover AI prompts shared by the community and create their prompts to share with the world. Discover and Share AI Prompts: Allow users to discover AI prompts shared by the community and create their prompts to share with the world.
  - Edit and Delete Created Prompts: Users can edit their created prompts at any time and delete them when needed.
  - Profile Page: Each user gets a dedicated profile page showcasing all the prompts they've created, providing an overview of their contributions.
  - View Other People's Profiles: Users can explore the profiles of other creators to view the prompts they've shared, fostering a sense of community.
  - Copy to Clipboard: Implement a convenient "Copy to Clipboard" functionality for users to easily copy the AI prompts for their use.
  - Search Prompts by Specific Tag: Allow users to search for prompts based on specific tags, making it easier to find prompts related to specific topics.
  - Google Authentication using NextAuth: Enable secure Google authentication using NextAuth, ensuring a streamlined and trustworthy login experience.
  - Responsive Website: Develop a fully responsive website to ensure optimal user experience across various devices, from desktops to smartphones
  and many more, including code architecture and reusability

## Technologies Used

 - Next.JS 14
 - Mongo DB
 - Tailwind CSS
 - Next Auth

## Setup Instructions

Follow these steps to set up and run the application locally:

## Prerequisites
Make sure you have the following installed on your machine:
- [Git](https://git-scm.com/)
- [Node](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

## Installation
1. Clone the repository
```https://github.com/ravikiranbt1690/crud_promptopia.git```
2. Navigate to the project directory
3. npm install

## Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

```
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_URL_INTERNAL=http://localhost:3000
NEXTAUTH_SECRET=
GOOGLE_ID=
GOOGLE_CLIENT_SECRET=
MONGODB_URI=
```


Replace the placeholder values with your actual credentials. You can obtain these credentials by signing up on these corresponding websites from [Google Cloud Console](https://console.cloud.google.com/), [Cryptpool](https://www.cryptool.org/en/cto/openssl) (for random Auth Secret), and [MongoDB](https://www.mongodb.com/).

## Running the Project
```
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
