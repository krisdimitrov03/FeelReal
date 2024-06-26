# FeelReal

Welcome to **FeelReal** – the app that's more attentive to your wellness than your mother asking if you've eaten yet. If you're ready to dive into a world where your emotional, physical, and dietary health come first, then you're in the right place. **FeelReal** is built using Angular on the frontend, with Spring Boot and Hibernate rocking the backend, all tied together with PostgreSQL for that sweet, sweet data persistence. Oh, and we're shipping the whole thing in Docker because, why not?

## What's This All About?

**FeelReal** is a digital mental health and wellness platform designed to help you manage your daily wellness through personalized plans and interactive tools. Whether you're looking to meditate, exercise, or just make sure you're drinking enough water, we're here to support you every step of the way.

## Documentation `BETA`
- [API Documentation](https://documenter.getpostman.com/view/16524194/2sA3JRZz5k).
- [Database diagram](https://drive.google.com/file/d/1UQEq-mHYjrh8ZtGj-szfi07_cNcH3dAn/view?usp=sharing).

## Features

- **Customizable Wellness Plans** - tailor-made plans to help you sleep better, eat healthier, and exercise right. Like a personal trainer, but less shouty.
- **Mindfulness and Meditation Guides** - because sometimes, you just need someone to tell you to breathe.
- **Dietary Guidance** - ever wonder if you're eating too much banitsa? We'll help you keep track.
- **Exercise Routines** - tailored exercises because not everyone wants to lift weights like they're in a Marvel movie.
- **Sleep Tracking** - we'll help you catch those Z's like they're going out of style.
- **Interactive Tools** - track your mood, set goals, and see your progress. It's like a video game, but what you win is a better you.

## Tech Stack

- **Frontend** - Angular
- **Backend** - Spring Boot, Hibernate
- **Database** - PostgreSQL
- **Deployment** - Docker

## Getting Started

Here's how to get the project up and running on your machine.

### Prerequisites

Make sure you have Docker installed on your machine. That's it! Docker will handle the rest.

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/krisdimitrov03/FeelReal.git
   cd FeelReal
   ```

2. **Run with Docker:**

   Use Docker Compose to build and run both the frontend and backend services:

   ```bash
   docker-compose up --build
   ```

   This command will set up both the Angular frontend and the Spring Boot backend along with the PostgreSQL database. Everything is containerized for simplicity and consistency.

   The services are defined in the `docker-compose.yml` file, which includes Docker configurations for each part of our application.

### Using the Application

After running Docker Compose, visit `http://localhost:4200` in your browser to interact with the **FeelReal** platform. Everything you need is running in containers, seamlessly connecting the Angular frontend with the Spring Boot backend.

## Contributing

Got ideas on how to make **FeelReal** even better? Fork the repo, push your changes to a branch, and hit us up with a Pull Request.

## Support

Run into bugs? Got questions? Worry not - we won't leave you hanging. Create an issue in the repository, or better yet, why not fix it and contribute?

## License

FeelReal is distributed under the MIT License. See `LICENSE` for more information.

## Happy Coding!

Remember, this app is all about feeling good, so have fun with it, stay hydrated, and keep those vibes high! ;)
