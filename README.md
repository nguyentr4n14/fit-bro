<h1 align="center">FitBro - AI Fitness Assistant</h1>

![Demo App](/public/screenshot-for-readme.png)

## Demo

🔗 **Live App**: <a href="https://fit-bro-seven.vercel.app/" target="_blank">FitBro</a>

## Technologies Used

- **Next.js**: React framework for building the frontend and API routes
- **Tailwind CSS & Shadcn UI**: For styling and UI components
- **Clerk**: Authentication and user management
- **Vapi**: Voice agent platform for conversational AI
- **Convex**: Real-time database (SQL)
- **Gemini AI**: Large Language Model for generating personalized fitness programs

## Features

- **AI Fitness Assistant**: Engage in conversation with an AI that asks about your fitness goals, physical condition, and preferences
- **Personalized Workout Plans**: Receive custom exercise programs designed around your specific fitness level, existing injuries, and personal goals
- **Diet Recommendations**: Receive personalized meal plans accounting for your allergies and dietary preferences
- **User Authentication**: Sign in with GitHub, Google, or email/password
- **Program Management**: Create and view multiple fitness programs with only the latest one active
- **Responsive Design**: User-friendly design that functions smoothly across desktop and mobile devices

## Setup .env file

```js
# Clerk Authentication
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

# Clerk Redirect URLs
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

# Vapi Voice AI
NEXT_PUBLIC_VAPI_WORKFLOW_ID=
NEXT_PUBLIC_VAPI_API_KEY=

# Convex Database
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
```

## Getting Started

1. Clone the repository
2. Install dependencies:

```shell
npm install
```

3. Set up your environment variables as shown above
4. Run the development server:

```shell
npm run dev
```
