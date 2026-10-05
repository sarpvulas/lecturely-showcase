# Lecturely showcase

An overview of Lecturely: Ace AP/SAT Exams, an AI-native exam prep app published by Pixra Studio. The source code is private. This repo holds screenshots and an architecture write-up only.

## TL;DR

Students preparing for the SAT and AP exams get generic practice and little feedback on free-response answers. Lecturely is a mobile app with a Socratic AI tutor, a free-response grader, adaptive mock exams and a math camera. It is built as a TypeScript monorepo and is in active development.

![Home (design mock of the redesign)](docs/screenshots/10-design-mock-home.png)

## Product surfaces

- **Socratic tutor ("Ren").** A chat tutor that retrieves concepts and cites them.
- **Free-response grader.** Rubric-based grading of free-response answers.
- **Adaptive mock exams.** Mock exams that adapt to the student.
- **Math camera.** Take a photo of a problem and get help.
- **Also in the app:** flashcards, a lesson reader, a study plan, streaks, offline study packs, and a desktop authoring app for lessons.

## Screenshots

These ten images are design mocks of the iPad redesign. They are not screenshots of the shipped app. They were rendered from the design canvas and show sample data only.

| | |
|---|---|
| ![Home (design mock)](docs/screenshots/10-design-mock-home.png) | ![Practice (design mock)](docs/screenshots/10-design-mock-practice.png) |
| ![Lesson reader (design mock)](docs/screenshots/10-design-mock-lesson-reader.png) | ![Mock exams (design mock)](docs/screenshots/10-design-mock-mock-exams.png) |
| ![Weak spots (design mock)](docs/screenshots/10-design-mock-weak-spots.png) | ![Study plan (design mock)](docs/screenshots/10-design-mock-study-plan.png) |
| ![Guide my week (design mock)](docs/screenshots/10-design-mock-guide-my-week.png) | ![Focus (design mock)](docs/screenshots/10-design-mock-focus.png) |
| ![Flashcard review (design mock)](docs/screenshots/10-design-mock-flashcard-review.png) | ![Onboarding (design mock)](docs/screenshots/10-design-mock-onboarding-how-ren-teaches.png) |

Design language and architecture (drawn, not screenshots):

![Design language](docs/screenshots/07-design-language-palette.png)

![Architecture diagram](docs/screenshots/08-architecture-diagram.png)

The mascot and the app icon:

<img src="docs/screenshots/06-ren-mascot.png" alt="Ren, the tutor mascot" height="160"> <img src="docs/screenshots/05-app-icon-mascot.png" alt="App icon" height="160">

## Tech stack

Expo and React Native for the client. Next.js and tRPC for the API. Drizzle ORM on Postgres. pnpm workspaces with Turborepo. Electron for the lesson authoring app.

## Architecture

See [docs/architecture.md](docs/architecture.md).

## My role

I founded Lecturely and build the product.

## Limitations

The code is private, so nothing here can be run. The screenshots may lag the current app. No FRQ grader or math camera screens are shown yet.

## Contact

[LinkedIn](https://www.linkedin.com/in/sarpvulas/)

All images and text in this repository are all rights reserved.
