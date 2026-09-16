# Poros

Poros is a team-built mobile application that helps students organize a job search through resume management, application tracking, target-company preparation, and AI-assisted research.

This repository contains the product vision, domain and UI models, deployment design, and usability-testing materials. The application code is maintained in the related client and backend repositories.

## Implemented prototype

- Account registration and sign-in
- Resume upload, listing, and management
- Job-application tracking across companies and stages
- Target-company lists and preparation checklists
- AI-assisted resume tailoring
- Company event and learning-resource research
- PostgreSQL-backed persistence

## Planned beyond the prototype

The original product vision also included automated application submission, intelligent deadline alerts, and a complete personalized career roadmap. These ideas were not completed in the course prototype and are listed here to distinguish the vision from shipped functionality.

## Technology

- React Native, Expo, and TypeScript
- Redux Toolkit and React Navigation
- Node.js, Express, and PostgreSQL
- JWT authentication
- Anthropic and Tavily integrations through authenticated backend routes
- Supabase storage and deployment configurations for common cloud platforms

## Repositories

- [Mobile client](https://github.com/Jojo-Osei-Kofi/Poros-Client)
- [Backend data service](https://github.com/Jojo-Osei-Kofi/Poros_data_service)

## Design and research

- [Domain model](design/POROS%20DOMAIN%20MODEL.jpeg)
- [UI model](design/POROS%20UI%20MODEL.png)
- [Deployment model](Deployment%20model.png)
- [Usability test script](Poros%20Usability%20Test%20Script.pdf)
- [Usability test report](Usability%20Test%20Report_%20Poros.pdf)

## Jojo Osei-Kofi's contributions

- Built React Native and TypeScript authentication flows for account registration and sign-in.
- Implemented resume upload and listing workflows.
- Developed the job-tracker interface for organizing companies and application stages.
- Integrated frontend workflows with the PostgreSQL-backed data service.
- Supported cross-platform testing through Expo.
- Led structured usability sessions with 10 participants, synthesized findings, and documented workflow improvements.

## Team

Poros was created for Calvin University's CS 262 Software Engineering course by:

- [Jojo Osei-Kofi](https://github.com/Jojo-Osei-Kofi)
- [Kofi Baah Nyarko](https://github.com/KofiBaahNyarko)
- [Ose Aisuodionoe-Shadrach](https://github.com/Ose-97)
- [Ruhama Getahun](https://github.com/RuhamaGetahun)
- [Youssef Dalil](https://github.com/YoussefDalil24)

The repository preserves team attribution because Poros was collaborative work.
