# FutureFit AI

FutureFit AI is an AI-powered career guidance application designed to help users navigate their professional journey with personalized insights. By leveraging advanced machine learning models, the platform assists users in discovering suitable career paths, enhancing skills, and making informed career decisions.

## Features

- **Career Path Discovery**: Get AI-driven recommendations for career opportunities based on your skills, interests, and industry trends.
- **Skill Gap Analysis**: Identify skills required for your target job and receive personalized learning suggestions.
- **AI-Powered Resume Insights**: Optimize your resume with AI-generated feedback for better job prospects.
- **Job Market Analysis**: Stay updated with real-time labor market trends and emerging career opportunities.
- **User-Friendly Interface**: Experience an intuitive and engaging UI to seamlessly explore career options.

## Technologies Used

- **Tech Stack**: Next.js, Vite, Tailwind CSS
- **Database**: PostgreSQL
- **AI Integration**: Google Gemini API

## Getting Started

To set up the project locally:

### Clone the repository:
```sh
git clone https://github.com/jaivisal/FutureFit-with-ai.git
cd FutureFit-with-ai
```

### Install dependencies:
```sh
npm install
```

### Set up environment variables:
Create a `.env` file in the root directory and add the following:
```sh
DATABASE_URL=
DIRECT_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/dashboard
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/onboarding

GEMINI_API_KEY=
RESEND_API_KEY=
ARCJET_KEY=
```

### Start the development server:
```sh
npm run dev
```

### Access the application:
Open your browser and navigate to `http://localhost:3000`

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```sh
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```sh
   git commit -m 'Add new feature'
   ```
4. Push to the branch:
   ```sh
   git push origin feature/your-feature-name
   ```
